# 独立开发变现周刊（第110期）：一个副业产品24小时内获得12万美元投资

分享独立开发、产品变现相关内容，每周五发布。

**目录**
- `1、Newslater: 个人newsletter生成器`
- `2、Pagy: 简单的方法来建立一个网站`
- `3、wereadx: 开源的微信读书辅助工具`
- `4、OpenSign: DocuSign的免费和开源替代`
- `5、一个副业产品在24小时内获得12万美金的投资`

## 1、Newslater: 个人newsletter生成器

根据保存到阅读列表的文章，自动为你生成每日newsletter。每天，你都会在适合的时间收到阅读列表中五篇文章的摘要。无论您想要在早上通勤时、午休期间还是晚上轻松阅读时事通讯，可以选择何时接收时事通讯。

![](https://qiniu.gafata.com/ezindie/2023112225235402.png?imageslim)

[newslater官网](https://newslater.co/)

## 2、Pagy: 简单的方法来建立一个网站

像写字一样简单，不需要设计或编码技能。像写Notion Page一样来创建你的网站。pagy的工作就像一个文本编辑器。只需点击并书写，然后拖放以制作任何想要的布局。作者在市场营销方面还做得不多，所以很高兴看到增长率保持稳定，即使它很低。

pagy目前10月份的统计数据:

- 343美元月收入 (+18%)
- 56个网站创建(+8)
- 164项新试验
- 1k访客
- 8.6%流失率

![](https://qiniu.gafata.com/ezindie/2023112225241772.png?imageslim)

![](https://qiniu.gafata.com/ezindie/2023112225242265.png?imageslim)

[Pagy官网](https://pagy.co/)

## 3、wereadx: 开源的微信读书辅助工具

可用于书籍下载及自动阅读、自动兑换体验卡等。一个开源代码库，微信读书辅助工具，数据来自于微信读书网页版。也可以自己部署。

功能列表：

- 下载书架上的书到本地，目前仅支持下载 html 和 epub 格式(后续会支持azw3)
- 自动更新阅读时长，可用于刷“读书排行榜”或者“阅读挑战赛”
- 每周日晚 23:30 自动领取“时长兑福利”中的免费体验卡(暂未对外开放)
- 支持下载用户自己上传的 pdf 格式的书

![](https://qiniu.gafata.com/ezindie/2023112225231228.png?imageslim)

[wereadx开源代码地址](https://github.com/champkeh/wereadx)

## 4、OpenSign: DocuSign的免费和开源替代

OpenSign是一个开源文档电子签名解决方案，为DocuSign, PandaDoc, SignNow等产品的免费替代方案。

特性：

- 安全签名:利用最先进的加密算法，以确保您的文件的安全性和完整性。
- 用户友好界面:设计时考虑到可用性，使技术和非技术用户都能轻松使用。
- 多平台支持:兼容各种浏览器和设备。
- 审计跟踪:保留与文档签名过程相关的所有活动的详细日志，包括IP地址和访问时间。
- API支持:为集成到其他软件和服务提供健壮的API。

![](https://qiniu.gafata.com/ezindie/2023112225237409.png?imageslim)

[OpenSign开源代码地址](https://github.com/OpenSignLabs/OpenSign)

## 5、一个副业产品在24小时内获得12万美金的投资

大家好，我是Paul, Recall的开发者，这是一款基于AI的浏览器扩展，可以根据你在网上浏览的内容建立你的个人知识库。

![](https://qiniu.gafata.com/ezindie/2023112225221582.png?imageslim)

我之所以开发 Recall，是因为我们正处于一个由前所未有的内容创造时代。平台专注于授权创作者生成内容，从而导致信息的大量涌入。我开发Recall的目标是帮助人们充分利用这些丰富的内容。

现有的工具允许用户保存和分类内容，但问题是用户很少重新访问它，这首先违背了保存它的目的。Recall解决了这个问题，它将你的内容存储在一个知识图中，并自动找到你添加的内容之间的联系。这样，当相关的内容出现时，过去的内容就会重新出现。

![](https://qiniu.gafata.com/ezindie/2023112225331424.png?imageslim)

在开发 Recall 的过程中，我也经历了不少起起落落，但随着我们越来越接近市场。今天，我们的月收入刚刚达到9000美元，月增长率为10%，但这才刚刚开始。

### 你是如何想到这个主意的?

![](https://qiniu.gafata.com/ezindie/2023112225330623.png?imageslim)

我是Maltego的早期员工，这是一家链接分析公司，生产用于绘制信息关系的软件。在Maltego工作时，我有了一个想法，用同样的技术来绘制我在网上收藏的内容之间的联系。我的问题是，我会从YouTube或博客上保存很多内容，但很快就忘记了，也不会再回头看了。

我的想法是将内容存储在一个知识图中，当新的相关内容出现时，它会重新出现过去的内容。我尝试用现有的工具(如Notion和Evernote)手动实现这个功能，但结果并不满意，因为它非常繁琐。这就是为什么我决定开始创建Recall。

我在2022年初开始尝试一些与Recall相关的想法。在这个阶段，它只是一个副业项目，我仍然在做全职的工作。

经过几个月的编码，我准备向世界展示一个MVP。与我对产品的设想相比，这相当简单，但这是一个开始。基本上，它可以让你建立你的数据库，包括你遇到的任何你觉得有趣并想要记住的东西。这些东西可以是人、地方、书、电影等等。

Recall将为添加的每个内容创建一张卡片，自动对其进行分类，并查找与你过去保存的其他卡片的联系。这样做的目的是帮助你在遇到相关的事情时重新显示你过去保存过的卡片。它解决了一个我认为很多人都有的问题:他们保存了大量的笔记、内容和书签，以为他们会重新访问它们，但很少这样做。我的解决方案确保你有机会触达到过去相关的内容。

第一个版本的样子

![](https://qiniu.gafata.com/ezindie/2023112225330747.png?imageslim)

在发布到Product Hunt之前，我阅读了所有能找到的成功发布策略。我花了几个小时准备一份清单，上面写着我可以在哪里发布的文章，以及我可以向谁和哪里寻求“支持”。

当发行后，我对产品产生了一些最初的吸引力和兴趣，但留存率非常低。人们喜欢这个想法并愿意尝试，但很少有人会继续成为活跃用户。我花了更多的时间来改进产品，但我并没有找到我所希望的曲棍球杆式的增长。我从Product Hunt获得了几千个注册用户，但不管我怎么尝试，留存率都没有提高。

我发现自己陷入了许多创业者都会遇到的困境，是转向还是坚持。似乎有很多人认为，如果你的MVP没有太大的吸引力，你可能应该尽快转向。然而，这说起来容易做起来难，因为我已经在这个项目上投入了好几个月的时间。

我决定把这个项目搁置几个月，把更多的精力放在我的其它软件开发工作上，同时决定下一步要做什么。我还不能彻底放弃它。

在此期间，有一名用户一直在烦我为Recall添加黑暗模式。他们说他们喜欢这个产品，但他们不能使用它，除非它有暗模式。一开始，我忽略了他们，但在他们坚持给我发了几封邮件后，我决定在一个周末实现它。

在发行了 Dark Mode 之后，我决定在HackerNews上发布我的困境。我之前在HN上的文章并没有引起多大的关注，但我想:为什么不写一篇诚实的文章，询问社区对产品的看法，以及是否值得继续下去?当时，我并没有多想，也不知道它会改变一切。

### 改变一切的帖子

![](https://qiniu.gafata.com/ezindie/2023112225329660.png?imageslim)

当我发布HN帖子时已经很晚了，我第一次查看它是在我准备睡觉的时候。我很惊讶地看到我已经有大约30个赞和一些评论了。我很快就回复了评论，但每次刷新页面都会有另一条评论和更多的赞。

我看到了Recall网站的访问量和注册人数激增，我也继续收到了很多评论。人们的评论褒贬不一，有些人说他们喜欢这个想法，觉得它很棒，有些人则抨击这个想法，说它很愚蠢，我是在浪费时间。

然后，我收到了一封电子邮件，有人表示有兴趣投资Recall。这似乎好得令人难以置信，尤其是考虑到当时是2022年11月，而风险投资市场自2021年的高点以来已经大幅崩溃。我以怀疑的态度回复了他们的邮件，但在快速回复之后，我意识到他们是认真的。

经过几封来回的电子邮件，以及40分钟的电话交谈，我们签署了一份SAFE(未来股权的简单协议)，他们电汇给我12万美元的投资。

我很震惊，在24小时内，我从考虑放弃我热爱的业余项目变成了有风投支持的创业公司。

所以这篇文章让这一切发生了。它在HackerNews上获得了近500个赞，并在大约13个小时的时间里成为排名第一的帖子。

我认为这篇文章的成功之处在于它琅琅上口并带有脏话的标题，以及我对处境的诚实。

### 描述下创业的过程

在获得Recall的资金后，我发现自己处于关键时刻。现在我有了自己的发展方向，可以全职开发Recall，甚至可以雇佣一些人来帮忙，但这仍然无法解决用户留存问题。

我的第一步是找个人帮忙开发，这样我就可以腾出时间来专注于其他与创业有关的事情。我做了很多面试，因为我知道找到合适的人对产品的成功至关重要。在与UpWork上的开发人员进行了几次不成功的试验项目后，我被介绍给了来自塞尔维亚的自由软件开发人员Igor Gligorevic。在我和他打了第一个电话之后，我就知道他就是我要找的那个人。在和他一起工作了一个月之后，我想让他成为我的合伙人。我邀请他作为联合创始人全职加入Recall，他同意了。

随着Igor的加入，我们的发展速度加快了10倍，我可以专注于与用户交流。我的任务是更好地了解我的用户，找出导致他们流失的原因。我的第一次尝试是发送电子邮件，询问流失的用户是否可以填写一份反馈表格，说明他们不再继续使用该产品的原因。我很快发现没有人填这些表格。我向更活跃的用户发送了另一个表单，但我仍然没有获得可以作为决策基础的具体数据。

![](https://qiniu.gafata.com/ezindie/2023112225347894.png?imageslim)

接下来，我让一些朋友在我面前第一次使用这个工具。诀窍是，他们不允许问任何问题，我也不允许说任何话。这真是一次大开眼界的经历。我认为显而易见的东西对用户来说没有意义。和我一起做这件事的人中，几乎没有人通过了入门流程并看到了产品的真正价值。

如果坐在我前面的人不知道如何使用我的产品，难怪留存率会这么低。我一直专注于构建产品，却没有意识到它开始变得很复杂。在我看来，这是显而易见的，但那是因为我几个月来每天都盯着它看。

我知道我需要极大地简化产品并改善体验。我开始了一个迭代的过程，观察人们使用产品，找到他们遇到的问题，解决问题，然后和新的人一起再做一次。我一遍又一遍地重复这个过程，直到我观察的每个用户都可以登录并创建他们的第一个摘要，而不会出现任何问题。

最大的收获是，让用户提供反馈远不如坐下来看着他们使用产品有价值。在书面反馈中，人们通常只是告诉你他们认为你想听到的，或者他们给你不同的解决方案的想法。如果你想了解用户是如何使用你的产品的，我推荐使用这个策略。

### 是什么吸引并留住了客户?

![](https://qiniu.gafata.com/ezindie/2023112225347901.png?imageslim)

我一直试图尽可能降低营销成本，并专注于以产品为导向的增长。我的目标是要有一个好产品，让人们推荐给他们的朋友。在现实中，这是相当具有挑战性的，并且需要一些营销努力。

在Product Hunt上发布是我们获得首批付费用户的好方法，Recall是当天排名第二的产品，为我们带来了20名左右的付费用户。要想做得好，有一个大的社区是很有帮助的。

Recall吸引大量付费用户的另一种方式是在所有流行的AI工具目录上发布内容。去年，围绕AI的炒作和关注让Recall受益匪浅。我们甚至在一些AI工具目录上做了一些付费广告。

在我努力寻找低成本营销渠道的过程中，我尝试了很多增长技巧，试图尽可能地自动化营销。一个成功的增长Hack是，我建立了一个机器人来监控Twitter上有文章链接的热门推文。然后，我的机器人会自动为这篇文章创建一个摘要，并在评论中发布摘要的图片和链接。

当人们点击我的链接时，它会在Recall中打开摘要，并鼓励他们注册以将摘要保存在他们的知识库中。这一策略在几天内发挥了很好的作用，带来的流量几乎与我们在Product Hunt发布时一样多。

不幸的是，在 Elon Musk 接管Twitter之后，导致Twitter API的定价大幅上涨，这使得该策略无利可图。

撰写有用的内容是另一种吸引用户的低成本方式。它不仅有助于你的搜索引擎优化，而且还允许你详细了解你的产品的不同使用场景。我刚刚开始写“Recall”博客，但我希望我能早点开始写。

### 你的业务使用什么工具?

我最初并没有太注意SEO优化，我认为这是一个噱头，SEO会随着时间的推移而有机增长。我的联合创始人建议我尝试一下SemRush的关键词研究。

这次经历改变了我对它价值的看法。现在，我不仅用它进行SEO优化，而且发现它对研究用户搜索行为和分析各种关键词的搜索流量非常有用，以辨别人们感兴趣的内容。

另一个为我节省了大量时间的工具是Stripe Atlas。它使在美国注册公司的过程变得非常简单和轻松，它与我们已经在使用的支付工具Stripe紧密集成。

### 通过创业，你学到了什么特别有用或有利的东西吗?

![](https://qiniu.gafata.com/ezindie/2023112225346773.png?imageslim)

1、从中学到的一个教训是，让你的产品尽快出现在用户面前很重要。

工程师们通常认为，如果他们开发出一款优秀的产品，人们就会发现它，它自然会像病毒一样传播开来。这种思维方式让你永远不想发布你的产品，因为你希望它是完美的，你会不断找到不发布的理由。实际上，当你向真正的用户发布产品时，你会了解到用户想要什么，这有助于塑造你的产品。

你肯定不希望自己陷入一种司空见惯的境地:花了8个月的时间努力打造一个没人想要的产品。

一个更好的方法是建立一个简单的MVP，说明你的想法，然后向潜在客户展示它，并从那里迭代。

2、我希望早点学到的教训是尽快开始向用户收费。

这可能并不适用于所有企业，但对于SaaS产品，这是验证你正在构建的东西是否可以成为业务的最佳方式。在很长一段时间里，我都没有对Recall收费。

一旦我有了用户基础，我就会引入定价。但当我最终拥有了相当规模的用户基础(约3000名用户)时，我却一直推迟收费，因为我害怕惹恼现有用户，他们会停止使用我的产品。但这正是我需要弄清楚的: 有多少人愿意为我的产品付费。这是找到适合市场的产品的唯一途径。

### 对其他想要创业或刚刚起步的创业者有什么建议吗?

1、在创业初期，专注于解决一个具体问题是至关重要的。许多创始人陷入了试图在短时间内做太多事情的陷阱，这可能会稀释他们的主要使命，分散他们的资源。通过将注意力集中在一个特定的问题上，你不仅可以为你的潜在客户建立一个清晰的价值主张，还可以为你的商业决策创建一个指导原则。

2、随着业务的增长和核心问题的有效解决，你可以考虑扩展和多样化你的产品。但请记住，坚实的基础是长期成功的关键。

---
<center>
本内容开源，欢迎推荐或自荐：

往期内容合集: [https://www.ezindie.com/weekly](https://www.ezindie.com/weekly)

订阅Telegram频道：[https://t.me/ezindie](https://www.ezindie.com/weekly)

B站视频频道: [https://space.bilibili.com/395127673](https://space.bilibili.com/395127673)

微信公众号：凯凯而谈

![](http://qiniu.gafata.com/2019-03-17-web-bear.jpg?imageView2/2/w/200)

扫码订阅
</center>