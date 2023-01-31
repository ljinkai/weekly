# 独立开发变现周刊（第47期）：Tailwind CSS 从副业产品到2百万美元的故事

分享独立开发、产品变现相关内容，每周五发布。

**目录**
- `1、Posture Pal: 用Airpods来帮你改善颈椎病`
- `2、Undock: 根据你偏好和日程安排行为`
- `3、Tailwind CSS: 从副业产品到2百万美元的故事`

## 1、Posture Pal: 用Airpods来帮你改善颈椎病

这是一个iOS的应用小产品，通过使用苹果AirPods中的运动传感器，Posture Pal可以帮助你改善脖子和肩膀的姿势。

几年前，我买了一个硬件跟踪器来改善我的姿势，这需要我把它贴在我的脖子后面，体验并不好，我停止了使用它。当我接触到运动检测API时，我意识到我可以创建同样的姿势跟踪，很多人整天都把AirPods戴在耳朵里，所以他们不需要调整他们的生活方式。

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajh8l9yj21jc0sm44u.jpg)

通过手机App 启动一个Posture会话，Posture将跟踪你的颈部倾斜，当检测到不良姿势时，就会发出提醒。

**错误的姿势**

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajojxegj210u0kgwi5.jpg)

**正确的姿势**

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajo8yi6j210u0k8wi8.jpg)

[应用iOS访问地址](https://apps.apple.com/us/app/posture-pal-improve-stance/id1590316152)

## 2、Undock: 根据你偏好和日程安排行为

大家好，我是Nash，Undock的创作者。

有一天醒来，我想知道自己为什么要花那么多的时间来和别人相处，如何来提升效率？

收发邮件?显然效率低下。日历链接? 有时是方便的，在有些情况下是完全不合适的。所以我开始使用Undock，为忙碌的人们提供控制、便利、隐私和日历的完美平衡。

**它是如何工作的?**

Undock会根据你的空闲时间、偏好和日程安排行为，为你推荐最佳的会议时间。有很多事情在背后进行，让我们进入重要的事情。

无论您是安排一个1对1或一个大规模的小组会议，Undock都有一个令人难以置信的1点击体验，以找到最佳时间。

![](https://snimg.jamyido.top/large/e6c9d24ely1h0lb7kw2rzj21aq0sigpk.jpg)

**它在哪里起作用?**

任何你输入手机键盘的地方，目前只有iOS。

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajnq6puj20yq0kagnb.jpg)

Apple 在 iOS 8 里就引入了 Keyboard Extension，Custom Keyboard 要实现起来也非常简单，我们只需要在项目里新建一个 Custom Keyboard Extension 的 Target，Xcode 就自动会给我们创建一个 KeyboardViewController，开发者通过这个类就可以做简单的开发了。

**在网页上，**Undock的Chrome扩展允许你在网页上进行快速的操作和管理。

![](https://snimg.jamyido.top/large/e6c9d24ely1h0lb8gntvwj20yo0k4q4i.jpg)

在安排会议的时候，我的脑力负担绝对为零，这是无价的。

[Undock官网](https://undock.com/)

## 3、****Tailwind CSS****: 从副业产品到2百万美元的故事

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajkg89lj20cs0csaak.jpg)

我是 Adam Wathan，Tailwind CSS的发明者。

2020年7月份，Tailwind 的总安装量突破了1千万次，这让我非常惊讶。

我们从Tailwind UI中获得200万美元的收入，这是我们第一个商用的Tailwind CSS产品，是在第一个Tailwind CSS版本发布两年之后。

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajkaj83j21js0n476m.jpg)

下面是故事的开始……

**第一个副业项目**
早在2015年，我就告诉了我的商业伙伴Steve Schoger我有一个小项目的想法，公司可以在这个网站上与他们的团队分享有趣的链接，外部人士也可以订阅，看看他们欣赏的团队在看什么。

我们称之为“Digest”。

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajk3i4vj21dw0sy0ui.jpg)

我们对此非常兴奋，于是我决定休假一周去创造最初的产品原型。但按照常规的开发方式，我花了整整一周的时间来决定技术堆栈，在最后一天才开始实现真正的功能。

其中一个决定是如何处理CSS。我一直是Bootstrap的忠实粉丝，但是第一个Bootstrap 4 alpha刚刚出来，他们放弃了Less，而选择了Sass，我讨厌Sass!

但在我看来Less是更好的语言。它是功能性的和声明性的，而且它有一个Sass没有的特性:mixin类。

如果你在Tailwind中使用过 @apply，这可能看起来很熟悉……

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajjwt5nj213y0nemza.jpg)

不管怎样，回到“Digest”，通常我会用Bootstrap，但是Sass的东西把它给毁了。我想继续使用Less，我唯一的选择就是从头开始创作所有的样式。

我所构建的东西受到bootstrap的启发，有很多组件类，比如btn、card-list和radio-box。

(顺便说一下，这是我们当时最终的结果，我认为即使5年后它仍然看起来很好!)

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajjpe3pj21a40u041x.jpg)

最终，我们忙于其他项目，失去了对这个想法的热情，最终这个副业项目走向了墓地(就像大多数事情一样)。

**除了样式表。**

在每个新项目中，我不断复制和粘贴Digest中的所有Less文件，并把它们作为一个起点，根据需要对它们进行定制，以适应我正在构建的任何新设计。在我们放弃 "Digest" 后，我至少将样式应用4到5个其他项目中。

当我复制样式时，我注意到一些事情:开始只是简单的填充和边距工具，逐渐涵盖越来越多的CSS特性，而组件文件却越来越短。

从那时起，我真正开始将“实用至上”的概念定义为一种体系结构哲学，可以在需要的时候随时添加到我的HTML中。

**放弃了第2个副业项目**
几年后，Steve和我开始致力于KiteTail，这将是一个专注于开发者，基于webhook的付款平台:

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajjh7nij21010u0tb0.jpg)

我们当时非常认真地对待这个问题，并且以那些旧的Digest样式为起点——我开始构建这个东西，非常努力地使这些样式，并尽可能地“与项目无关”。

在这一点上，我没有维护任何开源CSS框架的想法。我甚至没有想过我所创造的东西会引起任何人的兴趣。但是在一个接一个的信息流中，人们总是在问是否可以开源打包使用CSS:

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajj7r7bj210o09ujrw.jpg)

这就是公开的好处——如果我没有在另一个被抛弃的项目上直播我的工作，Steve和我永远也不会建立Tailwind Labs的业务(现在在不到2年的时间里已经创造了超过400万美元的收入)。

最终我想“也许可以开源这个小的Less框架?”

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajj2e0bj20nu0vw76g.jpg)

**走向开源**

大约在这个时候，一些人联系我，希望他们能以任何方式与我合作。Stefan Bauer就是其中之一，如果我没记错的话，他是建议使用像sm:font-bold这样的前缀来代替sm-font-bold的人。

我的好朋友Jonathan Reinink也在这个时候给我发了关于这个框架的消息，说他打算对他的SaaS项目进行一次大的重新设计，并想尝试一下我一直在唠叨的这个疯狂的样式框架。

这是使框架真正优秀的关键，因为我们的项目有完全不同的设计，而“Tailwind”需要支持这两个项目。这是一个强大的强迫功能，使其与项目无关。

回到这个故事 —— 这是在2017年6月/ 7月左右，在接下来的2-3个月里，Jonathan和我狂热地工作，努力做的足够好，然后可以开源的东西。

在这一过程中我所面临的一个挑战是，为了让 Tailwind 能够按照我的想法进行配置，我必须真正突破 Less 的极限，并编写一些真正创新的内容:

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajix1ezj21jj0u042w.jpg)

就我所能想到的，为这种东西编写测试套件是不实际的，我只能希望并祈祷解决一个问题不会引入另一个问题。

那是在8月中旬，我的朋友David Hemphill建议我尝试一下PostCSS，看看我是否可以用JS编写框架。

我开始尝试使用它，并惊讶于对代码的信心有了很大的提升。

不管怎样，在2017年的万圣节之夜，我们完成了第一次发行的最后润色，并开始着手编写最初的文档:

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajinqi5j20vc0qy40p.jpg)

我们发布了它，并获得了大量的积极关注，即使是v0.1.0:

![](https://snimg.jamyido.top/large/e6c9d24egy1h0laji92tnj20ut0u0n03.jpg)

经过大约一年的新 v0.x 版本，我发布了许多很酷的新功能和一个不断增长的社区时，我宣布我将全职开发Tailwind CSS。

**全职工作在Tailwind**

我本打算和一个朋友开始一个新的SaaS项目，但在《UI重构》(Refactoring UI, Steve和我在2018年12月出版的一本书)的成功和 Tailwind 的发展之后，我知道如果不把它进一步推进，我会后悔的。

Tailwind CSS是迄今为止我所做过的影响最大的项目——感觉它就像我“在世界上留下的足跡”，不投入工作去推动它的想法让我感到罪恶感。

我很幸运能够从Refactoring UI中获得一大笔资金，并且我知道有很多方法可以围绕框架本身构建商业产品(主题、UI套件、课程等等)，所以我决定尝试一下。

我竭尽全力地整理了这些东西，并将我们所学到的知识应用到一起，组成了一个合适的v1.0版本，于2019年5月13日发布:

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajhyopcj20u00udadn.jpg)

在那之后，史蒂夫和我在那一年剩下的时间里都在埋头苦干，试图弄清楚到底什么才是“Tailwind 赚钱业务”。我们创建了原型并抛弃了许多不同的理念，但最终还是决定采用现在的Tailwind UI。

以下是2019年3月对这个想法的第一次一瞥:

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajhpfbqj20p80wm780.jpg)

我们不知疲倦地为”Tailwind UI“ 工作了好几个月，最终在2020年2月发布了我们的早期版本，在我们设定的截止日期之前连续工作了36个小时。

![](https://snimg.jamyido.top/large/e6c9d24egy1h0lajhhekaj20sk0xs0vg.jpg)

它的成功超出了我们的想象(另:下周收益将突破200万美元)，因此我们能够开始组建一支出色的团队继续推动 ”Tailwind“ 的未来发展。

事情从这里变得更加不可思议，我迫不及待地把我们头脑中的一些想法转变成新的功能，产品和工具，使Tailwind的体验在未来几年更好。

感谢您的支持❤️

[Tailwind CSS的故事](https://adamwathan.me/tailwindcss-from-side-project-byproduct-to-multi-mullion-dollar-business/)

本次周刊结束，欢迎大家投稿，我们下周见！

---
<center>
本内容开源，欢迎推荐或自荐：

Github: [https://github.com/ljinkai/weekly](https://github.com/ljinkai/weekly)

往期内容合集: [https://www.ezindie.com/weekly](https://www.ezindie.com/weekly)

微信公众号：凯凯而谈

![](http://qiniu.gafata.com/2019-03-17-web-bear.jpg?imageView2/2/w/200)

扫码订阅
</center>