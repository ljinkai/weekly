# 独立开发变现周刊（第84期）：一个地理位置API服务，月收入1.5万美元

分享独立开发、产品变现相关内容，每周五发布。

**目录**
- `1、tiny.host: 简单部署你的web项目`
- `2、Verif Tools: 一个在线虚拟身份信息生成器`
- `3、screen.studio: 一个桌面端的录屏编辑工具`
- `4、一个地理位置API服务，月收入1.5万美元`

## 1、tiny.host: 简单部署你的web项目

1、拖放你的个人文件或包含内容的zip文件
2、输入一个链接名称点击上传
3、就是这样，大功告成!

这个小产品，作者的年入收入可以达到10万美金级别。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdho8ldj31k50u0q6e.jpg)

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdjflmsj30uc0nmjt5.jpg)

[tiny.host官网](https://tiiny.host/)

## 2、Verif Tools: 一个在线虚拟身份信息生成器

Verif Tools，一个在线虚拟身份信息生成器，能够在线生成全球各国的护照、驾驶证照、身份证、账单、信用卡、社会保障SSN、居留证、军人证等等，信息支持定制填写，填写完成即可一键生成，支持下载，无水印下载需要付费。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdj9xrzj31rn0u0gqp.jpg)

[Verif Tools](https://verif.tools/)

## 3、screen.studio: 一个桌面端的录屏编辑工具

这是一个Mac端的录屏编辑工具。不需要复杂的操作就可以编辑出效果很好的演示视频。作者Adam Pietrasiak 在2022年9月13日写了第一行Screen Studio代码。到12月15日已经收入了1万多美金。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdj0eukj30tg0nqq59.jpg)

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdiw6jqj30uw0tmmzx.jpg)

[screen.studio官网](https://www.screen.studio/)

## 4、一个地理位置API服务，月收入1.5万美元

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdipxbpj30m20ku3zh.jpg)

我是欧文·鲁奇，我的创业项目是geocode.xyz，一个地理位置分析，geocoding API的服务。

它于2016年推出，目前每天有数千名用户，每月API调用超过1亿次，每月收入超过1.5万美元。这一数字比一年前增长了1000%以上，而且仍在快速增长——当月的数据总是高于前一个月。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdikaobj30nm0f2dgh.jpg)

### 你是怎么想到这个想法的?

建立地理定位API的想法始于我在研究生院的时候，因为当时缺乏这样的API(谷歌Maps还没有发布)。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdifos7j31sh0u00wz.jpg)

我没有验证这个想法，这是我自己在其他一些项目中所需要的产品。

### 带我们了解下你第一个产品的过程。

地理解析/地理编码 软件是一个复杂的技术过程。它将NLP技术与 Computational Geometry 算法和快速内存数据库相结合。

在2004年，我们花了大约一个月的时间构建了第一个地理代码api。它只适用于加拿大，而且仅限于地理编码。后来，它扩大到包括美国。

这个过程通常是这样的 —— 编写脚本来清理和导入来自不同来源的数据。验证和测试。评估各种性能和准确性指标，并进一步微调，以实现100%覆盖率和准确性的目标。

在性能和准确性之间总是有一个反向的权衡。已经花了14年的时间来建造，我仍然不时地调整它。

2016年，我开始重写现在的 geocode.xyz

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdib0oij31qj0u0jwp.jpg)

由于OpenStreetMap项目和各种政府开放数据倡议的成功，全球有足够多的开放地理数据可用，使努力变得值得。

该软件的重写使用reinforcement技术从任何长度的文本中进行地理定位和消除歧义，然后通过将它们与完全基于开放数据的现有地理编码数据集进行匹配来进行地理编码。

一开始，启动成本接近于零(我geocode.xyz的域名花了1美金。对于服务器，我在AWS上使用了一个免费的云实例)

大约两年过去了，经营成本随着收入的增加而有所增加。

软件是按小时租用的。它的成本在0.10美元/小时到6.00美元/小时之间，具体取决于硬件上的CPU数量。AWS处理所有客户关系，因此部分业务处于自动化状态。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdi61v0j31nc0tc42a.jpg)

我还通过直接出售API访问来赚钱，那个定价页面是最近才发布的，在一段时间内API是免费的，大多数业务模式是基于AWS的。

尽管免费版本现在通过节流受到了更多的限制，但与最接近的竞争对手相比，我选择了一个非常便宜的API访问定价模型。

### 描述下创业的过程

geocode.xyz在那里发布了大约6个月后才受到注意，并开始获得第一批客户。

我的第一个客户是一名记者，他想分析2016年左右当地对欧洲移民危机的态度。他们使用geocode构建了一些整洁的实时数据可视化。我花了一些时间使它更好地工作在特定的用例。(我是免费做的，所以严格来说这不是客户)

另一方面，第一个付费客户是在2017年12月左右。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdhyygaj31ua0s2gs2.jpg)

然后在2018年1月又增加了3个客户。2月份还有5个，以此类推。其中一些使用geoparsing API，另一些使用 geocoding 或反向 geocoding。批处理地理编码端口也非常受欢迎，特别是对于那些正在寻找一种快速简便的方法在地图上可视化数据的小型客户端。

与此同时，AWS市场实例在2016年发布后不久就有了销售。

2018年初，geocode.xyz开始获得很多客户，所以从这一点开始，我可以称它为“业务”。我不知道为什么。我的营销努力仅限于在会议上发表演讲。也许有些人觉得这个API很有用，会链接到它，并在某些论坛上写了积极的评论。

### 自推出以来，是什么吸引和留住了客户?

自发布以来，我的主要关注点一直是改进API。自两年前以来，它已经走了很长一段路。

我想，一旦一个产品被注意到，它就会迅速发展，2018年的 geocode.xyz就是这样。我的猜测是，如果我能继续添加所需的功能，并改进现有的功能，这种增长将会持续下去，直到这种类型的API的市场规模有限，以及其他竞争对手的潜在进入/增长。

![](https://snimg.jamyido.top/large/008vxvgGly1h94sdhth3fj31sr0u0gsd.jpg)

我仍然不知道2018年发生了什么导致了 geocode.xyz 获得关注，以及为什么在2017年没有发生。2017年，我确实在这方面付出了很多努力，但结果却很少。

geocode.xyz非常有利可图，运营成本保持在总收入的10%以下。从长远来看，我打算进一步与AWS合作，因为这是目前增长最快的收入领域。

### 通过创业，你学到了什么特别有用的东西吗?

经营企业是一项艰巨的工作。从想法到产品，尤其是在开始阶段，需要付出很多努力。产品永远不会完美，所以努力还在继续，因为我是个完美主义者。

我也可以少工作，但我仍然努力工作，因为我喜欢这样，这样我更有使命感。

在过去的13年里，我每年都比之前7年作为全职软件开发人员更加努力。我也赚了更多。

### 对其他想要起步或刚刚起步的企业家的建议?

认清自己的长处，做自己喜欢做的事。有目标感很重要，尤其是当这个目标是要解决一个你有能力解决的问题时。这一点，再加上经济独立的目标，可以把你的时间转化为成功的事业。

```
认清自己的长处，做自己喜欢做的事。有目标感很重要，尤其是当这个目标是要解决一个你有能力解决的问题时。
```

本次周刊结束，欢迎大家推荐自己的产品，我们下周见！

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