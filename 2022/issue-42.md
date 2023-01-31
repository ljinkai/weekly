# 独立开发变现周刊（第42期）：将爱好变成一个能赚钱的副业产品

分享独立开发、产品变现相关内容，每周五发布。

**目录**
- `1、Voicl: 网站上的语音交互小组件，提高转化率`
- `2、Jiga: 如何在一个特定的利基市场中盈利?`
- `3、NFT艺术品图片生成开源工具`
- `4、2个有意思的灵感`
- `5、Screenshotapi: 将爱好变成一个能赚钱的副业产品`

## 1、Voicl: 网站上的语音交互小组件，提高转化率

这个是一个可以在网站上使用语音小工具与你的听众交谈并收集语音反馈。

1、可以后台选择预制模板，录制音频，然后将语音显示在网站上

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtncu4hj20za0l4mzo.jpg)

2、用户来到网站，可以语音进行交流

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtre09hj20vc0i6dgx.jpg)

3、一行代码即可嵌入网站

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtr7fk5j20za0l4gnl.jpg)

[Voicl官网](https://www.voicl.com/)

## 2、Jiga: 如何在一个特定的利基市场中盈利?

嘿!我叫Yonatan，创建一家名为Jiga的公司。我们帮助3D打印客户与制造商连接。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtr331fj20b40b40t9.jpg)

我们开发了一个非常酷的定价算法，可以在几秒钟内计算出打印和/或加工3D模型的价格。仅这一点就可以帮助很多消费者获得实时的报价，并比较不同的制造商、技术和材料。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtqxwwuj20u50hu76v.jpg)

现在，我们每个月大约能从10个订单中获得3000美元的MRR。我们有一些回头客，这对我们来说是最重要的指标。

我的联合创始人在一家3D公司，他在做另一个创业点子时，人们不停地给他打电话，问他是否知道他们可以在哪里打印或制造3D模型。他大概打了10到15个这样的电话，才明白这可以扩大成一项业务。

为了验证这一点，我们购买了域名jiga3.com，添加了一个简单的表单，这个表单带有上传3D模型的选项，上面写着:“制造3D模型的即时报价。”当然，这一切都是手动的。我们给上传带有报价的模型的人手动回复邮件。在我看来，这是一个出色的初始产品验证。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtqm3pqj20s60ieab9.jpg)

我们让真正的制造商加入到系统中，他们提供给我们他们的定价模型，这样我们的系统就可以根据制造商的规格快速输出报价。今天，我们的网络应用程序上的每一个报价请求都会触发数十个制造商的查询，为客户找到最合适的(在价格、质量或交货时间方面)。

我们花了1个半月的时间去创造最初的MVP，并且从那时起我们便开始尝试着去验证我们的假设并获得用户的反馈。我们从用户和客户那里得到了许多非常有价值的反馈，这使我们进入了另一个阶段，即专注于修复我们的基础设施并做出新的假设。

我们用React/Next.JS构建了这个应用，服务放在了Vercel上。

我们的后端大部分是用NodeJS编写的，还有一些用Python编写的奇妙的3d相关模块，放在了Render上。

目前，我们主要集中在陌生电话和电子邮件，以验证和完善我们的产品。因为我们每月接的订单很少，所以学习和完善每一个订单的方法是很重要的。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtqfteoj20oj0ieac4.jpg)

我们的下一个重要里程碑是达到2万美元的MRR，这样我们就可以给自己发一份微薄的薪水。我们的长期目标是成为按需制造领域的顶级在线平台。

我们希望世界各地的工程师在制作原型机时，或者在设计大型机器时，都能想到Jiga。他们可以通过一个可信赖的在线平台立即订购定制部件，而不是手动寻找供应商、犯错误、谈判和比较价格。

每隔一天，我就会看到想要创业的人谈论他们的想法，但实际上却什么都不做。如果你不花时间和汗水去做点什么，你的想法就一文不值。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtq7qauj20px0ie0uh.jpg)

人们常犯的一个错误是，在没有得到验证的情况下，从一开始就创建一个大的东西。你知道最好的验证是什么吗?利润和回头客。

如果你能赚到哪怕一点点钱，让人们足够开心，他们就会再次光顾，即使是非常简单的交易。做大事，但要循序渐进，并始终确认你所做的每一步。

[Jira产品过程](https://www.indiehackers.com/interview/how-we-found-profitability-in-an-ultra-specific-niche-d10b0dd604)

## 3、NFT艺术品图片生成开源工具

如何你想生成自己的NFT，那么可以考虑使用这样的开源工具，它是通过设定不同的特征图片，然后通过合成图层，生成最终的成千上万的艺术图片。

它的目的是让生成艺术领域更容易被任何人接触。有了这个工具，你不需要成为一个程序员来创建生成艺术NFT图片。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtpssa2j20zk0k0n1k.jpg)

[NFT艺术品图片生成开源代码](https://github.com/NotLuksus/nft-art-generator)

## 4、2个有意思的灵感

1、每天的工作 vs 有热情的工作

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtp74cbj20u10u0dhk.jpg)

2、问题 && 解决方案 = 最小化原型

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtoh64hj20u10u00tv.jpg)

## 5、Screenshotapi: 将爱好变成一个能赚钱的副业产品

我叫Dirk Hoekstra。我在阿姆斯特丹做软件开发。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqto6wz5j20b40b4mxu.jpg)

在过去的几个月里，我一直在利用业余时间开发screenshotapi.net。Screenshotapi是一个允许开发者通过一个简单的API调用来截屏网站的工具。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqto119hj20sp0l40u7.jpg)

这个工具目前拥有20个活跃的付费用户，每个月的收益约为400美元。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtnuupwj20og0iet9m.jpg)

这一切都始于我的个人爱好项目。我当时想创建一个新闻文章目录，显示所有编入索引的新闻文章的截图。这意味着我需要将网站截屏。

我开始在谷歌上搜索，发现了截图Api的工具。我测试了一个，它成功了。然而，它每月向我收取35美元。我不喜欢支付这么多钱，所以我想自己开发一个。当我在做的时候，我想也可以把这个工具变成一个截图SaaS应用。

因为我是全职工作，下班回家后，强迫自己挤出一两个小时的编程时间。但几个月后，screenenshotapi开始运行了。

我用Laravel创建这个项目。前端，使用Javascript和Vue。屏幕截图是通过运行一个真正的Chrome浏览器(使用Selenium)创建的。通过这种方式，网站呈现的效果与在普通电脑上完全相同。

我也遇到了其他开发者所面临的问题。我创造了一个产品，但不知道如何吸引用户。

我做的第一件事就是看看我的竞争对手在做什么。我使用Ahrefs工具来查看他们是如何产生流量的，以及他们从哪里得到反向链接的。

然后我只是做了同样的事情，似乎对他们有用。大多数反向链接没有产生流量，但我认为它们对搜索引擎优化有一定的价值。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtnqcjbj21bu0gwq4r.jpg)

真正对我有用的是谷歌广告。我现在每个月花100美元在谷歌的“截图API”关键字上。到目前为止，20个付费用户中有13个来自付费谷歌广告。

![](https://snimg.jamyido.top/large/e6c9d24ely1gzgqtniz8nj21400rmtal.jpg)

我还在想办法解决这些问题。但我的策略仍然是观察竞争对手在做什么，并进行试验，看看这是否也适用于我。

我还计划构建更多简单的SaaS应用产品。我相信把一件小事解决得极好，总比把五件大事搞砸要好。

但目前，我最大的障碍是时间，因为我也是全职工作。如果截图API达到$ 1000的MRR，那么我将考虑全职开发，但在那之前，这只是个副业。

[Dirk采访原文](https://www.indiehackers.com/interview/building-a-hobby-project-that-pays-for-itself-c43f9efdc8)

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