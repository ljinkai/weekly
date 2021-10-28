# 独立开发变现周刊（第26期）：短链浏览器插件，从1个想法到35万活跃用户

分享独立开发产品变现相关有价值的内容，每周五发布。

**目录**
- `1、Csaba Kissi：赚了300万美金后，背后那些取胜的诀窍`
- `2、Http Server Online：网页版HTTP服务`
- `3、Playwright: 一款微软开源的小白自动化神器`
- `4、AutoForward SMS：买的一个700美金/月收入的Android APP, 6个月后5000美金/月`
- `5、Link Shortener Extension：浏览器插件从1个想法到35万活跃用户`
- `6、leonardoenglish：通过Podcast来学习有趣的英语`

分享独立开发产品变现相关有价值的内容，每周五发布。

## 1、Csaba Kissi：赚了300万美金后，背后那些取胜的诀窍

Csaba Kissi 12年前离职了，之前在美国做程序员。为高层管理人员创建报告。同时也做了两个副业项目。

当决定离职时，我的储蓄是我收入的10倍。但当时我对自己作为一个企业家的能力也不是100%的自信。但有趣的是，在我离开后，我把利润扩大到了薪水的三倍。

1、Download3000产品的增长技巧

我的主要产品是Download3000。我有一些其他的网站，但这个为我净赚了超过90%的总收入。Download3000理念的第一次迭代是我为Delphi组件创建的下载目录。我创建它主要是因为我想要一个免费的渠道来销售我自己的软件。后来我决定在每天有2万访问者的网站上投放广告。

当我开始使用谷歌AdSense时，我意识到它可以带来比在我的网站上处理其他应用程序的广告多得多的收入。所以我决定把我所有的精力放在发展网站本身，而不是做免费软件和共享软件应用程序。三年后，该网站的访问量增至每天20万人次。

当你第一次创建一个网站时，你不会得到任何流量。所以我最初营销网站的想法是获得反向链接，改善我们的主页SEO。**对我来说，第一步是去竞争对手的网站，逆向工程他们正在做的事情**。我花了大约一周的时间在这上面——有像Soft32.com和Brothersoft.com这样的网站可以帮助我——查看他们的meta标签。

我注意到的最重要的事情是: 产品名称的位置，产品描述，下载按钮的位置，以及用户点击下载按钮时的流程。

后来，为了获取更多的流量，我决定为一些不同的内容管理系统创建插件，这些系统能够通过API将我的内容带到这些站点。对于WordPress, Joomla和PHPU，一旦你安装了插件，你的站点就变成了一个下载目录。

这里的技巧是，你可以浏览目录，但如果你想看到关于软件的细节，你被重定向到我的网站。所以这对双方都是双赢的局面。

他们得到了免费的内容，我也得到了大量的反向链接。我还可以跟踪安装我插件的网站。每次有一个API请求，主机的域名就会发送给我。我将这些信息保存到数据库中，这样我就能追踪使用这些插件的网站的数量。大约有2000个网站在使用它。这对我来说是一个重大的改变。

2、Twitter的增长技巧

我刚开始的时候从 Danny Thompson 那里买了一门课。**他教我的是选择四到五个大账户，并为这些账户设置通知。一旦他们发布了一些内容，成为第一个回复有意义内容的人。**

如果你能开始一段对话也很好。如果你连续几周这样做，你就会被账户所有者注意到，他们就会开始与你接触，并注意到你。这就是我如何与Twitter上所有的大账户联系的方法。

如果你想在Twitter上增长长，需要时间。如果你想成为一名优秀的开发者，这需要时间。如果你想成为一名优秀的营销人员，这需要时间。所以你不可能在一周或一个月内实现你的目标。这是不可能的。

做好失败的准备也很重要。有些人在第一个项目失败时感到失望，但这是正常的。在你实现目标之前，你必须经历很多次失败。无论你是企业家、演员、音乐家还是学生，每段旅程都是这样的。

![](http://qiniu.gafata.com/2021-10-28-Untitled.png?imageView2/2/w/600)

[Csaba经验分享](https://www.indiehackers.com/post/csaba-kissi-on-earning-3m-his-trick-to-outsmarting-the-competition-and-growing-on-twitter-ea73e81870)

## 2、Http Server Online：网页版HTTP服务

今天看到一个思路很奇特的开源小项目，网页版实现加载http服务。一般我们会启动一个http server来实现http的项目启动加载，有Node.js、Java、Python等等。通过网页是怎么实现的呢？
实现思路是通过 File System Access API + Service Worker。Service Worker来实现请求的监听和        Response, File System Access则负责访问本地文件的实现。
现代Web不断发展，出现了一个新的API，叫做 File System Access API，可以实现点击任意元素触发文件选择。因为是新API, Safari目前还不支持。有想了解具体实现，可以看下源代码，也有在线体验的Demo。

![](http://qiniu.gafata.com/2021-10-28-Untitled%201.png?imageView2/2/w/600)

[Http Server Online开源代码](https://github.com/EtherDream/http-server-online)

## 3、Playwright: 一款微软开源的小白自动化神器

Playwright仅用一个API即可自动执行Chromium、Firefox、WebKit等主流浏览器自动化操作，并同时支持以无头模式、有头模式运行。

更厉害的是，Playwright还可支持移动端的浏览器模拟。

Playwright API 支持 JavaScript & TypeScript、Python 和 Java 编程语言。

在本地和 CI 环境中使用一条命令就能完成 Playwright 和浏览器的安装。然后利用 API 启动浏览器、创建页面并自动进行页面交互。

基于Playwright，既可以做自动化测试，也可以做一些自动化功能，比如：爬取、监听网页数据变化、自动完成任务等有趣的操作。

![](http://qiniu.gafata.com/2021-10-28-Untitled%202.png?imageView2/2/w/600)

[Playwright开源地址](https://github.com/microsoft/playwright)

## 4、AutoForward SMS：买的一个700美金/月收入的Android APP, 6个月后5000美金/月

Norbert是 AutoForward SMS的持有者，这个产品是一个Android应用，主要功能是将手机短信转发到邮箱或通过链接可以访问。

这个产品是Norbert在交易网站Flippa上购买的，Norbert首先做的是保证应用的可用性，然后才是想办法优化。这个产品最早的技术栈实现是Kotlin、PHP，后来做了改版用的技术栈是Flutter 2、Firebase、Vue 3、Tailwind 2。

营销工作的第一个里程碑是发布了一个全新的网站。到目前为止，SEO已经驱动了所有的流量到网站(这是唯一的销售点)。真正帮助增长的是定价模式的改变，更早地收取费用，删除免费功能，添加很多可选付费计划。

从那以后，Norbert成功地将订阅数量从500 / 700美元的MRR增加到5000美元的MRR，并在6个月内增加了900名订阅者。

![](http://qiniu.gafata.com/2021-10-28-Untitled%203.png?imageView2/2/w/600)

[AutoForward SMS官网](https://autoforwardsms.com/)

[Norbert采访介绍](https://www.indiehackers.com/post/how-i-acquired-a-mobile-app-on-flippa-and-grew-it-from-700-mrr-to-5-4k-mrr-d50b9a8e82)

## 5、Link Shortener Extension：浏览器插件从1个想法到35万活跃用户

我的名字是Tim Leland，我是Link Shortener Extension浏览器插件的创造者，它有超过35万的活跃用户。

我的目标是让创建短链接成为一键式的过程。这促使我创建了一个浏览器扩展，使创建、共享和跟踪短url变得超级容易。这个扩展的想法是当我读到谷歌在2019年3月关闭它的URL缩短服务时产生的，我认为一个浏览器插件方式的短链服务是有很大的需求。

![](http://qiniu.gafata.com/2021-10-28-Untitled%204.png?imageView2/2/w/600)

我很快意识到，我需要自己的URL短链服务，这促使我创建了TLY。T.LY有超过800万个短url，跟踪了超过7000万次点击。提供诸如自定义域、统计、智能URL等功能

当你在寻找浏览器扩展的想法时，看看前100名的扩展，看看哪些可以改进。在我的案例中，我看到谷歌正在扼杀他们的URL短链接服务，而最流行的URL缩短器扩展是使用谷歌的缩短器，并且有超过100万用户。我知道当它不再起作用时，人们就会去寻找替代方案。这让我的扩展迅速发展，达到35万以上的活跃用户。

![](http://qiniu.gafata.com/2021-10-28-Untitled%205.png?imageView2/2/w/600)

[从1个想法到35万活跃用户](https://www.indiehackers.com/post/from-idea-to-350k-users-link-shortener-extension-d83ec69fef)

## 6、leonardoenglish：通过Podcast来学习有趣的英语

上周分享关于Podcast练英语听力的内容，这周偶然发现了这个产品，可以把Podcast和英语结合起来做成一个产品，并且收费盈利。

leonardoenglish的创作者叫Alastair，通过带有字幕、文本和关键词汇的英语播客来学习英语。有免费和付费订阅。

听每一集，意味着你在提高英语技能的同时也能学到一些有趣的东西。

每一集都配有字幕和交互式文本，所以可以学习新单词和短语，而不会错过一个单词。

![](http://qiniu.gafata.com/2021-10-28-Untitled%206.png?imageView2/2/w/600)

[leonardoenglish官网](https://www.leonardoenglish.com/)

---
<center>
本内容开源，欢迎推荐或自荐：

Github: [https://github.com/ljinkai/weekly](https://github.com/ljinkai/weekly)


Easy Indie: [https://www.ezindie.com/](https://www.ezindie.com/)

微信公众号：凯凯而谈


![](http://qiniu.gafata.com/2019-03-17-web-bear.jpg?imageView2/2/w/200)

扫码订阅
</center>