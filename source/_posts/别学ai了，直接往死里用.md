---
title: 别学AI了，直接往死里用
date: 2026-08-17 03:03:13
categories:
  - AI
tags:
  - AI
---

<font style="color:rgb(23, 43, 77);">（兼论为什么大多数人连“滥用”的资格都没有）  
  
</font>

<font style="color:rgb(23, 43, 77);">AI这玩意儿现在真是烂大街了。你媳妇听到了也很可能问你一句：“AI？就是那个天天帮我P图、写小红书文案的东西？你们不就是用它写写bug吗？”以上虽然是个笑话，也表现出在实际工作中大家对于AI的态度——哪怕到不了顶礼膜拜的程度，起码也觉得这玩意儿无所不能。</font>

<font style="color:rgb(23, 43, 77);">以下有两种使用AI的情况：</font>

<font style="color:rgb(23, 43, 77);">● 每次鼓起勇气想认真学AI，带着“我要系统掌握Prompt Engineering”的雄心壮志，同时选了一堆晦涩难懂的资料去学习，被各种“思维链”“Few-shot”“RAG”名词轰得七荤八素，头昏眼花，学习过程体验还不如刷短视频，只好草草放弃。</font>

<font style="color:rgb(23, 43, 77);">● 另一种情况，平常做crud的时候，AI就是用来生成重复代码的，大部分时间只需要遵从AI的建议直接点Tab黏贴，稍微高级点儿的用法压根就用不上，长此以往，别说深度使用AI了，连判断AI生成的代码对不对都做不到，如果不是为了面试，都懒得了解AI到底还能干啥。</font>

<font style="color:rgb(23, 43, 77);">AI说白了就是解决问题的工具。约会要AA，打游戏要4090，灯泡不能塞嘴里——这些都是日常非常典型的生活模式。用AI也是同样的简单概念。工作中碰到问题后，聪明人会用AI来解决问题，久而久之得到了认可和推广，总结为解决这类问题的使用模式。</font>

<font style="color:rgb(23, 43, 77);">那么，为什么AI这么简单的东西，大部分人还是用不好呢？我总结下来有三个核心观点。</font>

## <font style="color:rgb(23, 43, 77);">一、学会用AI的方法只有一个：滥用AI</font>
<font style="color:rgb(23, 43, 77);">这话听着离谱，但仔细想想就明白了。</font>

<font style="color:rgb(23, 43, 77);">你学骑自行车怎么学会的？摔出来的。你学游泳怎么学会的？呛出来的。你学写代码怎么学会的？bug改出来的。</font>

<font style="color:rgb(23, 43, 77);">同样的道理，你想学会用AI，只有一个办法——</font>**<font style="color:rgb(23, 43, 77);">往死里用</font>**<font style="color:rgb(23, 43, 77);">。</font>

<font style="color:rgb(23, 43, 77);">很多人问我：“我怎么才能学会用AI？”我说你一天用多少次？他说大概一周两三次，问个问题、写个文案啥的。我说你这种用法，学十年也学不会。</font>

<font style="color:rgb(23, 43, 77);">什么叫“滥用”？就是什么事都丢给AI试试，哪怕是明明自己两分钟能做完的事，也要丢给AI看它怎么做。用错了，再试；试错了，再换种问法。久而久之，你就能形成一种“AI语感”——你知道什么样的任务适合AI，什么样的问题该怎么描述，什么样的结果可以接受。</font>

<font style="color:rgb(23, 43, 77);">别小看这种“语感”。这跟你学英语是一样的，语法规则你背得再熟，没有大量“滥用”英语的实践，你开口还是磕磕巴巴。</font>

<font style="color:rgb(23, 43, 77);">但这里有个陷阱：很多人把“滥用”理解成了“无脑用”。这是两码事。无脑用是“扔给AI，全盘接受，从不思考”——这不是滥用，这叫</font>**<font style="color:rgb(23, 43, 77);">大脑托管</font>**<font style="color:rgb(23, 43, 77);">。Anthropic今年那篇论文已经把话说得很明白了：那些把AI当外包、全盘接受AI代码的人，认知能力直接掉了17%，从阿里P7跌回校招实习生</font><font style="color:rgb(23, 43, 77);">。而且他们完成任务的速度优势，只有区区2分钟，在统计学上都不算显著</font><font style="color:rgb(23, 43, 77);">。</font>

<font style="color:rgb(23, 43, 77);">所以“滥用”不是让你放弃思考，而是让你</font>**<font style="color:rgb(23, 43, 77);">高频次、多场景、有意识地</font>**<font style="color:rgb(23, 43, 77);">去用。每一次用都是在训练你的AI直觉。</font>

## <font style="color:rgb(23, 43, 77);">二、如何判断一个任务是否适合AI？问自己三个问题</font>
<font style="color:rgb(23, 43, 77);">滥用归滥用，你不能指望AI帮你生孩子。在“滥用”的过程中，你得学会判断什么样的任务适合AI。</font>

<font style="color:rgb(23, 43, 77);">我总结了一个“灵魂三问”：</font>

### <font style="color:rgb(23, 43, 77);">第一问：我能精确描述我想要达成什么结果吗？</font>
<font style="color:rgb(23, 43, 77);">这一问直接筛掉了80%的人。</font>

<font style="color:rgb(23, 43, 77);">很多人用AI的姿势是这样的：“帮我写个好一点的文案。”然后AI输出一堆东西，他们说：“不行，不够好。”再让AI改，还是不行。最后得出结论：“AI真垃圾。”</font>

<font style="color:rgb(23, 43, 77);">问题出在哪？出在你根本不知道自己要什么。“好一点”是什么意思？是更有趣？更专业？更短？更煽情？你自己都说不清楚，凭什么让AI猜？</font>

<font style="color:rgb(23, 43, 77);">苹果那篇翻车的AI论文就是个活教材。他们用AI自动生成benchmark的GT（Ground Truth，标注数据），结果错误率高达30%，论文都被喷撤稿了</font><font style="color:rgb(23, 43, 77);">。问题出在哪？不是AI的问题，是研究团队根本没有精确定义“什么样的GT是正确的”，也没认真检验AI生成的GT是否正确。最终导致北京一个程序员熬夜适配他们的benchmark，跑出来的结果一塌糊涂，才发现了这个荒谬的错误</font><font style="color:rgb(23, 43, 77);">。</font>

<font style="color:rgb(23, 43, 77);">这一问的核心是：</font>**<font style="color:rgb(23, 43, 77);">如果你自己都不知道什么样的结果是好的，AI一定不知道。</font>**

### <font style="color:rgb(23, 43, 77);">第二问：我能把这个任务拆分成AI能理解的子任务吗？</font>
<font style="color:rgb(23, 43, 77);">这一问考验的是你的“任务拆解”能力。</font>

<font style="color:rgb(23, 43, 77);">AI不是万能的，你不能指望一句“帮我做个电商网站”就完事了。但如果你能把“做个电商网站”拆成“设计数据库表结构”“写商品列表API”“写用户登录接口”……那AI就能一个一个帮你搞定。</font>

<font style="color:rgb(23, 43, 77);">CodeRabbit 2025年分析了470个GitHub Pull Request，发现AI生成的代码平均每个PR有10.83个问题，而人类代码只有6.45个，缺陷率高1.7倍</font><font style="color:rgb(23, 43, 77);">。但问题是，为什么还有那么多人用AI写代码写得飞起？</font>

<font style="color:rgb(23, 43, 77);">区别就在于：</font>**<font style="color:rgb(23, 43, 77);">会拆任务的人，AI就是神助攻；不会拆的人，AI就是屎山制造机。</font>**

<font style="color:rgb(23, 43, 77);">Veracode的测试更狠——他们测试了100多个大模型，45%的AI生成代码没有通过安全测试，Java的安全失败率高达72%</font><font style="color:rgb(23, 43, 77);">。AI生成的代码在跨站脚本漏洞上几乎全灭，86%的相关样本都挂了</font><font style="color:rgb(23, 43, 77);">。这意味着如果你直接把AI生成的代码扔到生产环境，后果可想而知。</font>

<font style="color:rgb(23, 43, 77);">但那些能用好AI的程序员是怎么做的？他们把任务拆成：先让AI生成骨架代码，然后自己审查安全逻辑，再让AI补充测试用例，最后人工整合。每一步AI都在做它擅长的事——写重复代码；每一步人类都在做自己擅长的事——把控方向、审查安全。</font>

### <font style="color:rgb(23, 43, 77);">第三问：AI最终生成的东西，我能判断对错吗？</font>
<font style="color:rgb(23, 43, 77);">这一问是最要命的。</font>

<font style="color:rgb(23, 43, 77);">很多人用AI是这样的：让AI写个旅游攻略，然后拿着攻略就出门了。结果到了目的地发现网红咖啡馆根本不存在——厦门罗女士就中过这个招</font><font style="color:rgb(23, 43, 77);">。AI旅游攻略会虚构景点、不考虑路程、闭馆信息不更新，这些事早就被网友吐槽烂了</font><font style="color:rgb(23, 43, 77);">。</font>

<font style="color:rgb(23, 43, 77);">谷歌用AI改写新闻标题，把“Valve明确表示明年才会公布价格”改成了“Steam Machine价格公布”，活脱脱一个标题党制造机</font><font style="color:rgb(23, 43, 77);">。GPT-5.2号称“人类专家水平”，结果连26个英文字母都数不全，生成的字母挂图遗漏了U和Z，插图里的动物长得跟生化危机似的</font><font style="color:rgb(23, 43, 77);">。</font>

<font style="color:rgb(23, 43, 77);">这些问题的本质是什么？</font>**<font style="color:rgb(23, 43, 77);">你没有办法判断AI输出的是真还是假。</font>**

<font style="color:rgb(23, 43, 77);">所以这一问的关键在于：在你交给AI的任务领域里，你得有</font>**<font style="color:rgb(23, 43, 77);">基本的判断力</font>**<font style="color:rgb(23, 43, 77);">。你是设计师，你能看出AI生成的图比例对不对、风格合不合适；你是程序员，你能判断AI写的代码逻辑有没有问题、安全有没有漏洞；你是写作者，你能分辨AI写的句子通不通、有没有跑题。</font>

<font style="color:rgb(23, 43, 77);">如果没有这个判断力，AI就是一台精致的信息污染机。</font>

## <font style="color:rgb(23, 43, 77);">三、AI是放大器：能力越强，效果越好；能力越差，反噬越狠</font>
<font style="color:rgb(23, 43, 77);">这是我第三个观点，也是最重要的一个。</font>

<font style="color:rgb(23, 43, 77);">AI不是什么“替代人类”的东西，AI是</font>**<font style="color:rgb(23, 43, 77);">能力的乘法运算</font>**<font style="color:rgb(23, 43, 77);">。</font>

<font style="color:rgb(23, 43, 77);">怎么理解？假设你本身的能力是100分：</font>

+ <font style="color:rgb(23, 43, 77);">能力100 × AI（用得好的话）= 可能是1000，甚至是10000。</font>
+ <font style="color:rgb(23, 43, 77);">但如果你本身的能力是10分：能力10 × AI = 可能还是10，甚至是1。</font>

<font style="color:rgb(23, 43, 77);">更可怕的是，如果你能力差还乱用AI，AI会变成一个</font>**<font style="color:rgb(23, 43, 77);">负向放大器</font>**<font style="color:rgb(23, 43, 77);">，把你的错误和缺陷放大到极致。</font>

<font style="color:rgb(23, 43, 77);">最近有个新闻特别能说明问题：德国莱比锡一个哥们用AI聊天机器人帮自己在法庭上辩护，居然赢了</font><font style="color:rgb(23, 43, 77);">。你以为是AI厉害？错了。新闻里明确说，他的法律论据里有“重大错误”。但为什么还是赢了？因为这哥们本身懂法，他知道怎么用AI辅助自己，而不是把整个辩护扔给AI。如果是一个完全不懂法的人用AI辩护，结果大概率是输得一塌糊涂。</font>

<font style="color:rgb(23, 43, 77);">反过来看反面案例。2025年AI技术滥用事件有近120起</font><font style="color:rgb(23, 43, 77);">。安徽铜陵一女子用AI生成“流浪汉卧坐家中”的逼真图像，丈夫收到后吓到报警</font><font style="color:rgb(23, 43, 77);">。12岁小孩用AI做整蛊图发业主群，整个小区被吓坏</font><font style="color:rgb(23, 43, 77);">。AI谣言批量生产，从“江苏干部买方便面被通报”到“华山医院前院长客死他乡”，一条比一条逼真，一条比一条离谱</font><font style="color:rgb(23, 43, 77);">。</font>

<font style="color:rgb(23, 43, 77);">这些是什么？这些是“能力差 × AI = 灾难”的完美案例。造谣的人本来就会编故事，AI只是让他们的“产能”暴涨了100倍。AI没有创造恶意，AI只是放大了恶意。</font>

<font style="color:rgb(23, 43, 77);">企业级AI更是这样。某保险公司AI理赔系统上线准确率仅60%，某制造企业AI质检误判率15%而人工仅3%，某超市AI补货系统上线后缺货率飙升40%</font><font style="color:rgb(23, 43, 77);">。这些项目的问题出在哪？不是AI不行，是数据不行、流程不行、人的判断不行。AI只是忠实地把这些“不行”放大成了“灾难”。</font>

<font style="color:rgb(23, 43, 77);">CodeRabbit的报告里有一句话说得特别好：</font>**<font style="color:rgb(23, 43, 77);">AI加速了输出，但它也放大了特定类型的错误</font>**<font style="color:rgb(23, 43, 77);">。逻辑错误率暴涨75%，安全漏洞翻倍增长——AI不是制造了这些错误，它只是让一个能力不足的程序员更快地写出更多错误代码。</font>

<font style="color:rgb(23, 43, 77);">所以结论是什么？</font>

**<font style="color:rgb(23, 43, 77);">AI不会让你从菜鸟变大神。AI只会让大神变得更高产，让菜鸟暴露得更彻底。</font>**

---

<font style="color:rgb(23, 43, 77);">最后说句掏心窝子的话。</font>

<font style="color:rgb(23, 43, 77);">很多人焦虑AI会取代自己。但真正该焦虑的不是“AI会不会取代我”，而是“我会不会用AI”。</font>

<font style="color:rgb(23, 43, 77);">你不会用AI，但你的竞争对手会用AI——那你就被取代了。</font>

<font style="color:rgb(23, 43, 77);">怎么学会用？就一句话：</font>**<font style="color:rgb(23, 43, 77);">滥用它，往死里用，但用的时候带上脑子。</font>**

<font style="color:rgb(23, 43, 77);">每次用AI的时候，问自己那三个问题：我能说清楚我要什么吗？我能拆成AI能懂的子任务吗？我能判断AI生成的东西对不对吗？</font>

<font style="color:rgb(23, 43, 77);">三个问题答不上来，就先别用AI——先把自己的能力修炼上去。因为AI是放大器，在你能力还不行的时候用AI，AI只会把你的“不行”放大成“灾难”。</font>

<font style="color:rgb(23, 43, 77);">反之，如果你已经是个狠人，AI会让你变成超级赛亚人。</font>

<font style="color:rgb(23, 43, 77);">这不是选择题。这是乘法题。</font>

