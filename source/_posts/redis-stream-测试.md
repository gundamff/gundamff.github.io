---
title: redis stream 测试
date: 2026-08-17 03:03:13
categories:
  - 技术
tags:
  - 技术
---

添加消息, teststream 是key

```plain
xadd teststream * id 1
xadd teststream * id 2
xadd teststream * id 3
xadd teststream * id 4
xadd teststream * id 5
```

查询消息, - + 表示 最小和最大,可以是stream中任意两个id

```plain
xrange teststream - +
```



创建消费组,

0 ,表示消费组将会消费teststream 下面所有的消息

$, 表示消费组将会消费创建时间之后的所有消息

[id], 表示消费组将会消费指定ID之后的所有消息

```plain
xgroup create teststream group1 0
xgroup create teststream group1 $
xgroup create teststream group1 1595400021271-0
```



创建消费者并开始读取消息,返回指定组内从未被其他消费者消费(接收)的消息,也就是最新的消息 相当于 (消费=fasle)

0, 返回指定组内被当前消费者消费(接收)了但是未处理的消息(没标记ACK的), 这里注意消费和处理(ACK)两个概念的不同,这里不会返回当前消费者没有消费过的消息 相当于 (消费=true && ack = true); 举个例子: xadd N条消息之后 立刻xreadgroup 0 返回的会是 null,先 xreadgroup > 再执行xreadgroup 0 就是所有没有ack的消息了

[id], 同上,只是返回的范围变成了指定ID之后的数据



```plain
xreadgroup GROUP group1 consumer-1 count 10 BLOCK 0 streams teststream 0
xreadgroup GROUP group1 consumer-1 count 10 BLOCK 0 streams teststream >
xreadgroup GROUP group1 consumer-1 count 10 BLOCK 0 streams teststream 1595400021271-0
```

标记处理, 一看就明白没有什么好说的

```plain
XACK teststream group1 1595400021271-0
```



测试一轮后的结论

这东西出来还是太新了,spring-data-redis的支持也并不完善,玩玩就算了,大规模上生产估计是个坑



//update 20200907

记几个查询命令

```plain
Xinfo stream teststream
Xinfo groups teststream
XINFO CONSUMERS groups teststream
```



参考文章:

[https://lolico.me/2020/06/28/Using-stream-to-implement-message-queue-in-springboot/](https://lolico.me/2020/06/28/Using-stream-to-implement-message-queue-in-springboot/)

[https://juejin.im/post/5d044fe1f265da1b9253d80b](https://juejin.im/post/5d044fe1f265da1b9253d80b)

[https://my.oschina.net/pass/blog/3145295](https://my.oschina.net/pass/blog/3145295)

[http://xiaorui.cc/archives/5285](http://xiaorui.cc/archives/5285)

[https://cloud.tencent.com/developer/article/1529507](https://cloud.tencent.com/developer/article/1529507)

