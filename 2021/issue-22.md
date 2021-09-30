# 独立开发变现周刊（第22期）：回复消息来辨别鞋子真假，年收入20万美金？

分享独立开发产品变现相关有价值的内容，每周五发布。

**目录**
- `1、Notion-avatar：一个生成 Notion 风格头像的在线工具`
- `2、WxPusher：微信消息实时推送服务`
- `3、Ch Daniel: 回复消息来辨别鞋子真假，年收入20万美金？`
- `4、Anne-Laure Le Cunff: 100天发布100篇文章挑战，年收入10万美金`
- `5、AI拟声: 5秒内克隆您的声音并生成任意语音内容`

## 1、Notion-avatar：一个生成 Notion 风格头像的在线工具

这是一个开源项目，可以在线生成Notion风格的头像，网站搭建用：Nextjs、Tailwind、Vercel。这个小工具虽然功能简单，但是很受欢迎。其实实现这个小产品更重要的是头像的素材。作者找到一位设计师，并获得了他的授权，而这些头像可以从gumroad上花$10买到，购买后可以用于任何用途。

![](http://qiniu.gafata.com/2021-09-30-Untitled.png?imageView2/2/w/600)

[Notion-avatar开源代码地址](https://github.com/Mayandev/notion-avatar)

## 2、WxPusher：微信消息实时推送服务

先说下我为什么会找到这个产品？发现这个产品是因为我个人做产品的过程中，有一个需求痛点，就是想收到用户付款的通知提醒。我想找到一个可以在用户给我的产品付款后，能及时的收到付款通知，这样我就会感觉很爽~。

WxPusher (微信推送服务)是一个使用微信公众号作为通道的，实时信息推送平台，你可以通过调用API的方式，把信息推送到微信上，无需安装额外的软件，即可做到信息实时通知。 你可以使用WxPusher来做服务器报警通知、抢课通知、抢票通知，信息更新提示等。

这些功能基本满足我的需求，而且是免费的，只需要在它的后台配置好Key，然后通过http请求就可以了。而且有其它语言Java、Go、Phyton、PHP的SDK。如果你也有类似我这样的需求，可以加入自己的收藏夹，以备后用。

![](http://qiniu.gafata.com/2021-09-30-Untitled%201.png?imageView2/2/w/600)

**One more thing...**

基于好奇心理，我又搜了搜相关资料，也有人有我类似的痛点，发现了一个帖子，感觉讨论还是挺有价值的，如何实现在手机通知Push上实现个人即时的消息通知呢？现有的解决方案貌似没有一个令人满意的。

1. 邮箱：拉取有延迟，发送不便

2. Server 酱的 APP，基本残废，无法使用

3. PushOver 收费

4. Slark，钉钉：太重，我只想要一个消息栏通知

5. 短信接口，不想上传各种身份证户口本

下面评论给出的解决方案也有很多：

1、ifttt+telegram

2、mipush 自己写个空壳 app

3、Chrome webpush 做的一个

4、Pushover or Bark

不过这些解决方案都不是很好，要么鸡肋，要么国内使用不够友好。

[WxPusher微信推送服务](https://wxpusher.zjiecode.com/docs/#/)

[手机Push个人通知讨论实现](https://www.v2ex.com/t/529852)

## 3、Ch Daniel: 回复消息来辨别鞋子真假，年收入20万美金？

我叫Ch Deniel，简单来说，用户付费，我通过回复一些消息告诉用户购买的商品是真品还是假的，类似下面这样的，一年收入了20万美金。

![](http://qiniu.gafata.com/2021-09-30-Untitled%202.png?imageView2/2/w/600)

这样一条消息$20，最高的时候一条$100，取决于商品的价格高低。

**那我们是怎么做到的呢？**

2017年的时候，我19岁，我想做个App，这个App很简单，用户只是选择品牌，然后引导用户到我的个人网站上去查看辨别真假指导手册。

这样的App+website组合，然后将这个产品发布在了Reddit上，不断的有新用户来浏览，用户数不断的增长5,000、10,000、40,000、300,000

![](http://qiniu.gafata.com/2021-09-30-Untitled%203.png?imageView2/2/w/600)

到350,000用户的用户的时候，每天都会收到3~10封邮件，让我帮他们鉴定产品真假，一开始我还是免费回复，后来觉得我需要通过向用户收取一定的费用，来安排用户优先级，并验证这样模式是否可持续的。并叫了我15岁的弟弟过来帮忙。

后来就在指导手册上加上了Stripe的付款链接，就不断的有收到付款。

![](http://qiniu.gafata.com/2021-09-30-Untitled%204.png?imageView2/2/w/600)

为的看起来更像一个产品，做了现在的网站 legitcheck.app

![](http://qiniu.gafata.com/2021-09-30-Untitled%205.png?imageView2/2/w/600)

**我们是如何获取流量并保持增长的呢？**

我们每个月有30 -40万独立用户。

我很幸运做了下面的事情。

1、当我什么都没做的时候，流量一直在增长。我甚至在不知道SEO的情况下就找到了一个SEO金矿

2、我学习了SEO，在“假vs真(物品名称)”搜索中保持排名第一的位置
3、用户对物品认证的需求不断增长

4、我们用它打造了一个品牌，并尽最大努力让它变得更加可信和专业

5、高利润率、低批量、基于时间的服务(如果需要，利润率为95%)

6、提供出色的客户支持，在必要的时候做正确的事情(退款)，为客户超额交付服务等等。

[Ch Deniel和弟弟的故事](https://www.simple.ink/blog/200-000-year-writing-order-messages)

## 4、Anne-Laure Le Cunff: 100天发布100篇文章挑战，年收入10万美金

Anne-Laure Le Cunff是一个移民的孩子，在Google工作让她觉得眼前的工作一眼就能看到底，这不是她想要的，于是辞职做开始做自己的事，那一年压力很大，因为不想让自己的妈妈失望，但还是失败了。那时Anne-Laure可以继续回大公司上班，但是内心深处知道那不是自己想要的，于是决定继续往前走。

Ness Labs最初在2019年9月份开始的一个订阅服务，社区功能上线是在2020年的3月份。希望能提供一个大家互相连接，共同学习提高，有共同话题的空间。

![](http://qiniu.gafata.com/2021-09-30-Untitled%206.png?imageView2/2/w/600)

在2019年的时候，Anne-Laure想做一个挑战，100天写100篇文章，练习用英语写作，并将过程公开。这样既是对自己的促进，同时也吸引了很多人的关注。后来有很多的媒体、播客也开始采访Anne-Laure。

一开始需要调整自己的心态，觉得有压力，后面逐渐就变成了一种习惯，再后来就逐渐享受这个过程了。虽然感到害怕，但仍然追求你相信的东西。

Anne-Laure说：”我妈妈没有接受过正规教育，但每当她看到有人在做有趣的事情，她就会想，如果他们能做，为什么我不能?“

[100天发布100篇文章挑战故事](https://www.indiehackers.com/post/on-publishing-100-articles-in-100-days-and-crossing-100k-arr-anne-laure-le-cunffs-story-f99d8130c9)

## 5、AI拟声: 5秒内克隆您的声音并生成任意语音内容

借助深度学习算法，通过个人输入的语音，然后通过算法生成完全模拟某个人的声音，而且由机器合成的语音连情绪都能够完美表达出来，基本可以以假乱真。

MockingBird已经登上Github热榜，收获3.5K的Star.

MockingBird具有如下特性：

- 支持普通话并使用多种中文数据集进行测试
- 适用于 pytorch，已在 1.9.0 版本(最新于 2021 年 8 月)中测试，GPU Tesla T4 和 GTX 2060
- 支持 Windows + Linux
- 仅使用新训练的合成器(synthesizer)就有良好效果，复用预训练的编码器/声码器

![](http://qiniu.gafata.com/2021-09-30-Untitled%207.png?imageView2/2/w/600)

[MockingBird开源项目地址](https://github.com/babysor/MockingBird)

---
<center>
本内容开源，欢迎推荐或自荐：

Github: [https://github.com/ljinkai/weekly](https://github.com/ljinkai/weekly)


Indie Maker Start: [https://www.ezindie.com/](https://www.ezindie.com/)

微信公众号：凯凯而谈


![](http://qiniu.gafata.com/2019-03-17-web-bear.jpg?imageView2/2/w/200)

扫码订阅
</center>