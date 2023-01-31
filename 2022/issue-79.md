# 独立开发变现周刊（第79期）：一个产品页面流灵感网站，每月4.5K美元

**目录**
- `1、Microverse World Builder: 一个开源的元宇宙的开发环境`
- `2、Pake: Rust 打包网页生成很小的 Mac App`
- `3、Crisp Widget: 一个网页对话交互小部件`
- `4、一个产品页面流灵感网站，每月4.5K美元`

分享独立开发、产品变现相关内容，每周五发布。

## 1、Microverse World Builder: 一个开源的元宇宙的开发环境

Microverse World Builder是一个开放元宇宙的开发环境，允许web和web3开发人员快速创建多用户3D元宇宙世界，可以发布到任何web服务器上，完全独立。

平台包括示例世界、一个灵活的化身系统、与大多数3D对象的兼容性以及与外部数据系统的连接器。此外，JavaScript开发人员可以在世界内扩展功能，以创建与其他封闭平台不可能实现的交互。Microverse World Builder 已经开源，期待着合作构建一个支持开放元宇宙的生态系统。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55lzxr3j31c00u0gu0.jpg)

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55pkillj31e60u0agf.jpg)

[Microverse World Builder 官网](https://croquet.io/index.html)

## 2、Pake: Rust 打包网页生成很小的 Mac App

Pake使用Rust写的一个开源项目，底层使用 Tauri，支持微信读书、Twitter、Youtube、Reference、RunCode、Google Translate、Witeboard、Flomo、语雀、Vercel、V2EX、工具箱等

Pake 比较特别的是，相比传统的 Electron 套壳打包，大小要小将近 40 倍，一般 2M 左右，此外由于底层使用的，Rust Tauri 框架，性能体验较 JS 框架要轻快不少，内存小很多；此外实现了通用快捷键的透传、容器通信、样式改写注入、沉浸式的窗口、拖动、简化使用流程优化等功能，有一点点可玩性，你可以 Fork 自己打包喜欢的。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55p59dsj314p0u0jyw.jpg)

[Pake开源项目地址](https://github.com/tw93/Pake)

## 3、Crisp Widget: 一个网页对话交互小部件

Crisp Widget是一个完全的重新设计，是新一代的网站小部件，具有响应性，重量轻，支持多渠道。

由VueJS提供动力，允许前所未有的网站性能和轻量级。

支持文本、Gif&视频预览、用户评分、交互式问答、文件分享、在线视频通话等功能。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55ov96uj31pc0s4grf.jpg)

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55op9dkj31vy0nojx6.jpg)

[Crisp官网](https://crisp.chat/en/)

## 4、一个产品页面流灵感网站，每月4.5K美元

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55ojof8j30b40b40ta.jpg)

我是Ramy Khuffash，我经营着一家名为Page Flows的小公司，这是一个为在线产品设计者提供灵感视频的仓库。客户为访问付费。我经营这个生意已经有几年了，每个月的收入大约是4500美元。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55ofzqbj30nm0f440k.jpg)

### 你是怎么想到这个想法的?

我在大学里学的是会计和信息系统，但当我毕业的时候，我意识到我不想成为一名会计或在信息系统工作。几年来，我做过各种各样的工作，尝试使用WordPress，并与人合伙创建了一家失败的消费者初创公司，之后我开始了自己的网页开发之路。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55nzwo5j31x20u0n3r.jpg)

在我的整个职业生涯中，我建立了一些业余项目来提高我的技能，并朝着开创自己的事业前进。其中一个项目是名为UI Movement的通讯，这是一个设计灵感通讯。这是我迄今为止最成功的业余项目，在Product Hunt上发布后迅速获得了数千名订阅者。

如果你是一个独立的创始人，我也强烈建议你加入一个社群小组。我和另外两位创始人每周一都要参加电话会议。有一群志同道合的人一起交流，这对我帮助很大。

大约一年之后，我准备开始做一些新的事情。我想创造一种可以直接向顾客收费的产品或服务。我与一些UI Movement的订阅用户建立了电话联系，以了解他们注册的原因，他们从通讯中获得了什么价值，以及我是否能够创造出他们愿意为之付费的内容。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55ncnyhj30nm0cl74y.jpg)

谢天谢地，从中还是得出了一些有用的见解。不断出现的一个主题是，人们喜欢渴望的UI设计灵感，但更直观的设计灵感会更有帮助。

这就是 Page Flows 想法诞生的时刻。它将成为一个流行产品的视频库。当设计师陷入设计问题时，他们会使用 Page Flows 来查看其他公司是如何解决这些问题的。

除了最初与UI Movement 订阅者的对话之外，我没有进行任何验证。我的方法是快速发布，然后观察市场的反应。如果人们不感兴趣，我就放弃。

### 介绍下第一个产品的设计、原型和制造过程

我用Django、HTML、CSS和jQuery构建了页面流。这是一个超级简单的设置。记录用户流视频是耗时和乏味的部分。我用一款名为Monosnap的应用程序在我的MacBook上录制基于网页的产品。对于iOS应用程序，我把iPhone连接到MacBook上，用QuickTime录制屏幕。录制完视频后，我把它们上传到网站上，然后用自己制作的一个简单工具对它们进行注释并截屏。该网站一开始只有大约100个视频，现在已经超过1000个。

我的录制和添加视频的过程没有改变，除了一些小的调整。我短暂地将视频录制和注释外包了出去，但很快就发现，如果没有良好的流程记录，这是行不通的。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55n98a3j30nm0dzwgs.jpg)

我使用Stripe处理支付，并设定了每月14美元的价格。

我想没有人会付那么多钱，但当时的普遍建议是，要比你认为的产品价值稍高一些。总的来说，网站上线大约花了一个月的时间。

### 描述启动业务的过程

最初，我开始通过在UI Movement 订阅上推广网站，让潜在客户看到它。除此之外，我的发行计划便是让Page Flows在Product Hunt上获得推荐。

就好评和流量而言，Product Hunt的帖子相当不错，但这些都没有转化为顾客。这是一次失败。

几周后，当只有一个付费客户时，我决定是时候离开了。我退款给客户，并使所有的用户流程视频免费供任何人访问。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55n08gmj31sq0u0gug.jpg)

大约一年后，我注意到谷歌Analytics的视频获得了相当大的流量。没什么特别的，但足以表明人们对此感兴趣。我想试试我的运气，重新引入付费。这一次，我将收取少量一次性费用，而不是每月订阅。我用一个伪造的支付表单快速创建了一个登陆页面，然后等着看人们是否会尝试付费。令我惊讶的是，有几个人这样做了。这就是我所需要的证明。

我用Stripe创建了一个合适的支付表单，重新开始在网站上添加用户流视频。如果我没有如此迅速地放弃页面流，我可能会更快地实现盈利。

### 是什么有效地吸引和留住了客户?

UI Movement 从一开始就是流量的关键驱动因素。对于如此相似的用户，在那里推广页面流是有意义的。

多次发布也很有帮助。Product Hunt推出了各种迭代版本的Page Flows，每一次都带来了良好的流量提升，并在设计社区和博客中被更多提及。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55mo412j30nm0ez0ur.jpg)

除此之外，SEO也逐渐变得更加重要。人们通过搜索非常特定的来发现Page Flows，但更知名的品牌(特别是设计良好的品牌)往往会带来更多的流量。例如Slack, Dropbox, Spotify等。所有这些长尾关键字搜索加在一起。一开始我并没有过多地考虑SEO，但现在我在决定下一步，会先研究哪些产品可能会带来流量。

### 你未来的计划是什么样的?

增长缓慢而稳定，这可能会让人失去动力，但我总体上对事情的进展感到满意，因为我没有预料到公司能走这么远。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55mknedj30nm08a74u.jpg)

Page Flows多数月的收益介于4000美元至5500美元之间，利润率相当可观。我未来的主要关注点是继续向库中添加视频。这既能确保现有客户满意，又能通过SEO带来新客户。

虽然Page Flows是我的主要收入来源，但我还是会花相当多的时间寻找下一个机会。

### 通过创业，你学到了什么特别有用的东西吗?

在谷歌的长尾关键词排名对于页面流来说非常有价值。这是一个需要时间的策略，但如果你的业务涉及创建内容，那么完全值得研究哪些长尾关键词是相关的，高意图的，容易排名的。

在定价模式方面，我还了解到一次性定价比订阅定价更容易销售。相比每月5美元的产品，人们更愿意在29美元的产品上冒险。即使你想建立一个长期的订阅业务，从一次性的价格开始是更容易的。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55mg4czj314h0u0n0k.jpg)

### 对其他刚刚起步的创业者有什么建议?

我最近最大的认识是，仔细考虑应该遵循哪些建议是很重要的。我们都有不同的目标，所以只关注与你的目标一致的建议是很重要的。举个例子，如果你想建立一个生活方式的公司，遵循风投支持的创业公司创始人的建议可能会让你误入歧途。

![](https://snimg.jamyido.top/large/008vxvgGly1h7z55m82tyj31f20u0jy3.jpg)

话虽如此，我始终需要提醒自己的建议是，从小处着手，快速完成。但是我们中太多的人犯了一个错误，花了几个月的时间在一个产品上，然后才把它呈现在用户面前。

如果你是一个独立的创始人，我也强烈建议你加入一个小组。我和另外两位创始人每周一都会打电话，讨论我们在做什么，计划做什么，以及我们需要什么帮助。有一群志同道合的人一起，这对我帮助很大。

**“我始终需要提醒自己的建议是，从小处着手，快速完成。”**

本次周刊结束，欢迎大家投稿，我们下周见！

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