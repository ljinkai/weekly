# 独立开发变现周刊（第75期）：我的SaaS模板代码库每月赚4千美元

分享独立开发、产品变现相关内容，每周五发布。

**目录**
- `1、html2canvas: 使用JavaScript网页截图`
- `2、Ezindie: 明星产品的开源替代项目`
- `3、Sidekick: 一个让你变的专注的生产力浏览器桌面应用`
- `4、我的SaaS模板开发套件每月赚4千美元`

## 1、html2canvas: 使用JavaScript网页截图

这是一个开源JS库，Github上有26K的Star，允许你直接在用户浏览器上对网页或部分网页进行“截屏”。截图是基于DOM的，因此可能不是100%准确的真实表示，因为它不制作实际的截图，而是基于页面上可用的信息构建截图。

它不需要来自服务器的任何渲染，因为整个图像是在客户机的浏览器上创建的。但是，由于它严重依赖浏览器，这个库不适合在nodejs中使用。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzteb4xj31t00u0dla.jpg)

[html2canvas开源地址](https://github.com/niklasvh/html2canvas)

## 2、Ezindie: 明星产品的开源替代项目

市场上有很多优秀的产品，同时开源代码里也有类似产品的开源替代，这些开源项目能帮我们快速的实现产品。所以我整理了一些知名产品的开源替代项目，放到的ezindie网站上，今后如果有类似产品的需求，可以及时参考。这个集合页面会不断更新迭代。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzwcs5hj30u01bdtd5.jpg)

[Ezindie的开源项目替代](https://www.ezindie.com/open-source-alternative)

## 3、Sidekick: 一个让你变的专注的生产力浏览器桌面应用

Sidekick是一款面向知识工作者的生产力浏览器。是Mac上的一款桌面端应用，它集成了所有的web应用程序，以帮助保持组织和高效，同时加快你的工作流程。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzw4xxwj31sm0rsn1i.jpg)

消除标签混乱：会话帮助你分组，保存和打开标签，而不混乱。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzvy21dj31320ogwhr.jpg)

多账户帮助您在Gmail、Slack、concept和messenger中的不同账户之间跳转，而无需注销。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzvr0ymj313i0pmacx.jpg)

[Sikekick官网](https://www.meetsidekick.com/)

## 4、我的SaaS模板开发套件每月赚4千美元

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzvnhz8j309y09y74n.jpg)

Hi, 我是Alexandro，墨西哥人，我正在开发SaasRock，具有开箱即用的功能，如认证、订阅、验证、事件和Webhooks、定价计划构建器、博客、权限等。使用Remix、Tailwind CSS和Prisma构建，并与Stripe的支付功能、Postmark的邮件功能和Zapier的Webhooks功能进行了很好的集成。托管在Vercel上，使用Supabase作为数据库。

我的目标用户是全栈开发人员和低代码工程师，他们希望用强大的初始代码库快速构建SaaS应用。

SaasRock目前的月收入为4380美元。我在今年3月19日开始开发，并在6月1日进行了预发布。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzvk96oj30nm0fijsm.jpg)

### 你是怎么想到这个想法的?

我是C#的开发人员，工作了8年，但我想开始构建web应用程序，所以我学习了Vue2，为我的客户建立了两个网站。

我喜欢前端的Vue和后端的 .NET，所以我建立了一个叫做NetcoreSaas的样板，一个基于 .NET、Vue和Tailwind CSS的SaaS代码库。我在AppSumo上发布了这款模板，总共获得了大约50名用户。

但我觉得我的开发可以更快，于是将Vue2应用迁移到Vue3，然后是React，然后是slvelte。结果是相同的样板，但有不同的前端，我称之为saasfrontend。过了一段时间，我从中赚到了765美元。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzvh99mj30nm06yt9b.jpg)

然后我发现了Remix，一个专注于web标准的全栈JavaScript框架。我立刻意识到这是一个完美的解决方案，所以我在7天内构建了“the Remix SaaS kit”(现在的SaasRock)的v0.0.1版本，并在24小时内免费提供。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzvd764j30nm0xi41q.jpg)

这条推文很受欢迎，因为Remix团队转发了它，我获得了超过1000次的下载:

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzv8qbdj30nm0egwgl.jpg)

在这一点上，我决定开源其他SaaS套件，并专注于SaasRock。

### 描述下启动业务的过程

所有这些都是我自己启动的。我为saasrock的域名支付了大约300美元，为logo支付了250美元(我没有使用)，为托管+数据库支付了70美元/月。

这是网站第一次发布时的样子:

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzv4aj2j30nm0cbab2.jpg)

这是它现在的样子:

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzv16prj30nm0djjsk.jpg)

对于每个网站我发布我需要:

- 购买一个域名
- 创建Stripe帐户
- 创建一个邮戳服务器
- 创建一个Gmail帐户谷歌工作区与我的域
- 创建一个Twitter账户
- 创建一个Instagram账号
- 创建一个自定义标志和插图Canva
- 使用Cloudflare设置域
- 将我的代码提交到私有的GitHub存储库
- 创建Supabase数据库服务器
- 部署到Vercel
- 在IH、Medium、Dev.to、HN、hashnode和LinkedIn上发表博文
- 在twitter上发布博文
- 使用ConvertKit发送我的通讯订阅博客文章

主要有3个阶段:

**第一阶段:免费24小时 - 3月28日**

对于v0.0.1，我获得了大约1000个gumroad“客户”(每人0美元)，我的手机通知一直响个不停。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzuxkk2j30nm0f0di2.jpg)

最终结果:1066人下载了Remix SaaS套件v0.0.1。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzurkn1j30nm1cdgqs.jpg)

**第二阶段:Remix SaaS套件 — 3月29日 — 299美元**

第二天，我将口gumroad的价格从0美元调整到299美元。第一天，我得到了2个客户，第二天又有一个客户，到4月底，我得到了19个客户，总计3063美元(我给几乎所有要求的人都提供了折扣)。

April Remix SaaS套件客户:

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzuibo9j30nm19djuj.jpg)

Remix SaaS套件的整体分析:

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzucc86j30nm0qp408.jpg)

在这个阶段，我遇到了我的产品/营销导师和朋友Chris Kluis。他主动提出帮助我编写样板，因为他对SaaS应用程序很感兴趣。他指出了两件事:

- 找到一个与Remix脱钩的域名，并新域名做发布
- 每月从299美元改为99美元。
- 于是我把它命名为saasrock.com。

**第三阶段：SaasRock发布前 — 6月1日 — 99美元/月**

在发布前，Chris和我决定推出一个核心版和一个企业版。

$99/m:构建SaaS所需的一切。
$149/m:核心+企业功能:单点登录，附属+推荐，HelpDesk…

在推出saasrock.com两天之后，我获得了第一个99美元的订阅者。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzu8xhkj30nm0jw75c.jpg)

截至9月15日，也就是发行前的3个月，我已经拥有69名用户，并获得了8000美元的收益。虽然还不足以让你全职工作，但足以让你知道Remix SaaS样板的市场是有潜力的。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uzu36yvj30nm0hwjsl.jpg)

### 自推出以来，是什么有效地吸引和留住了客户?

启动Discord是关键。通过这种方式，围绕SaasRock的社区正在成长，每个人都在分享他们对SaasRock应该往何处发展的想法。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uztzkx4j30nm0nmabd.jpg)

另外，得到关于我和产品的反馈和好评会让我有动力去回馈!

排名前三的话题是:

#general - 我会让每个人都知道我现在在做什么，以及我接下来要做什么。

#反馈 - 成员们会通知我他们遇到的错误并反馈他们的问题，有时他们互相帮助是如此的高兴。

#enterprise - 我们谈论即将到来的企业功能。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uztuwuwj30nm0futa9.jpg)

总的来说，我认为discord服务可以让我在建立社区的同时与终端用户保持联系，这对SaasRock的前景来说是一个很好的证明。

### 通过创业，你学到了什么特别有用的东西吗?

优秀的编码是不够的。我认为最好的营销策略是“打造高质量的产品，顾客就会来”。我意识到我需要尝试所有我能想到的策略: 每隔一天推特、YouTube视频和博客帖子。

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uztqndmj30nm0ebabd.jpg)

我的营销策略的关键是一切都是相互联系的。我创建了一个功能，我把它添加到更新日志中，我创建了一篇关于它的博客文章，我把我的想法发在推特上，我发布一个YouTube视频解释如何使用它。所以现在，对于我创建的每个功能，我都有一个:

- Blog:IH, Dev.to, Medium, Hashnode, LinkedIn和我的博客。
- YouTube视频
- 推特

重点是开始写你喜欢做的事情，**这样你就可以围绕它建立一个系统。**

![](https://tva1.sinaimg.cn/large/008vxvgGly1h72uztko5rj30nm0b0q47.jpg)

### 对其他想要起步的开发者有什么建议?

开始行动，经验比天赋更重要。

我害怕开设一个youtube频道，因为我需要频繁地发布内容:

1)我担心会失去质量，

2)我担心不会说英语。

我一开始没有发布长视频，而是在Twitter上分享了Loom的短视频。

慢慢的，我开始获得信心，在两个月后，我开始了SaasRock的youtube频道，这最终成为我在这个项目中做出的最好的决定之一，因为它使我保持进度和动力。

本次周刊结束，欢迎大家投稿，我们下周见！

---
<center>
本内容开源，欢迎推荐或自荐：

Github: [https://github.com/ljinkai/weekly](https://github.com/ljinkai/weekly)

往期内容合集: [https://www.ezindie.com/weekly](https://www.ezindie.com/weekly)

B站视频频道: [https://space.bilibili.com/395127673](https://space.bilibili.com/395127673)

微信公众号：凯凯而谈

![](http://qiniu.gafata.com/2019-03-17-web-bear.jpg?imageView2/2/w/200)

扫码订阅
</center>