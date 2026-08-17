---
title: obs相关资料
date: 2026-08-17 03:03:13
categories:
  - 技术
tags:
  - 技术
---

## 常见流媒体协议
RTMP: 既可以用来推送又可以用来直播，其核心理念是将大块的视频帧和音频帧拆分，然后以小数据包的形式在互联网上进行传输，而且支持加密, 基于<font style="color:#333333;">TCP</font>。

HLS: 苹果公司提出的基于HTTP的流媒体网络传输协议。其工作原理是切片式传输，把直播流切成无数片，用户在观看视频时，每次客户端可以只下载一部分。适合移动端使用

FLV: <font style="color:#333333;">Adobe推出的私有协议,走HTTP,原本只能用flash播,但是B站的 </font>[<font style="color:#333333;">flv.js</font>](https://github.com/bilibili/flv.js)<font style="color:#333333;"> 弥补了这个缺陷</font>



<font style="color:#333333;">以上三种协议:  </font>[<font style="color:#333333;">腾讯云</font>](https://cloud.tencent.com/document/product/267/7968#.E6.94.AF.E6.8C.81.E5.93.AA.E4.BA.9B.E6.8E.A8.E6.B5.81.E5.8D.8F.E8.AE.AE.EF.BC.9F)<font style="color:#333333;">,</font>[<font style="color:#333333;">阿里云</font>](https://help.aliyun.com/knowledge_detail/42262.html?spm=a2c4g.11186631.2.1.167c6f39VsGRvp)<font style="color:#333333;">都是三种协议的</font><font style="color:#333333;">播放 但只支持RTMP协议推流</font>

[<font style="color:#333333;"> 腾讯云直播流播放SDK(支持IOS,ANDROID,IOS,H5播放器)</font>](https://cloud.tencent.com/document/product/454/34920)

[<font style="color:#333333;"> 阿里云直播流播放SDK</font>](https://help.aliyun.com/knowledge_detail/49785.html?spm=a2c4g.11186631.2.2.167c6f39VsGRvp)

<font style="color:#333333;">开源 rtmp库其实有不少 参见 </font>[https://github.com/topics/rtmp](https://github.com/topics/rtmp)<font style="color:#333333;"> 哪怕把上面的条件限定到java依然还是有很多的(其中不少是大厂或者收费的了...)</font>

<font style="color:#333333;">支持以上三种的播放器就更多了,常见的有 </font>[<font style="color:#333333;">谷歌的shaka-player</font>](https://github.com/google/shaka-player)<font style="color:#333333;">, </font>[<font style="color:#333333;">videojs</font>](https://github.com/videojs/http-streaming)<font style="color:#333333;">, </font>[<font style="color:#333333;">flv.js</font>](https://github.com/bilibili/flv.js)

<font style="color:#333333;"></font>

## OBS(Open Broadcaster Software)
[https://github.com/obsproject/obs-studio](https://github.com/obsproject/obs-studio) 目前使用最广的推流客户端 全平台 完全开源 完整生态 支持大量插件

[同类软件的比较英文版](https://en.wikipedia.org/wiki/Comparison_of_screencasting_software)



## 国内改版的obs
[https://github.com/bilibili/biliobs](https://github.com/bilibili/biliobs)

[https://github.com/alibaba/tblive](https://github.com/alibaba/tblive)



---

## streamlabs-obs
基于ts,vue的开源osb客户端 [github地址](https://github.com/stream-labs/streamlabs-obs) 项目主要使用的技术 vue, node, typescript, electron, [官网](https://streamlabs.com/) [API地址](https://stream-labs.github.io/streamlabs-obs-api-docs/docs/index.html)

[<font style="color:#2c3e50;">obs-studio-node</font>](https://github.com/stream-labs/obs-studio-node)<font style="color:#2c3e50;"> 用于封装底层OBS的相关接口</font>

[<font style="color:#2c3e50;">streamlabs-beaker</font>](https://github.com/stream-labs/beaker)<font style="color:#2c3e50;"> 封装的UI组件</font>

<font style="color:#2c3e50;"></font>

---

根据上面obs-node库用原生JS做的例子

[https://github.com/qlteacher/obs-example](https://github.com/qlteacher/obs-example)

---

## 直播平台架构
[爆炸式增长的斗鱼架构平台的演进](https://segmentfault.com/a/1190000011650413)

[快手直播平台演进之路](https://segmentfault.com/a/1190000020910241)

[斗鱼：如何打造一个高性能、高可用直播系统架构](https://www.infoq.cn/article/we4dDaWLO7ZsHLij6AZ9)

[熊猫直播技术架构演进](https://cpp.la/328.html)

[AWS 案例研究：虎牙直播](https://aws.amazon.com/cn/solutions/case-studies/huya/)

[我们为什么使用DASH](https://www.bilibili.com/read/cv855111/)

[OBS源码解读](https://blog.csdn.net/jbl5501328/category_6393550.html)



---

[系统架构脑图](http://naotu.baidu.com/file/f0267f53b03dbd2c375499e6eb28268c?token=8e125e2fdcaee42c)



