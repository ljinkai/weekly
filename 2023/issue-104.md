# 独立开发变现周刊（第104期）：开发月收入1000美金的Kindle小工具

分享独立开发、产品变现相关内容，每周五发布。

**目录**
- `1、Headshot AI: 生成专业头像的开源项目`
- `2、Pallyy: 一站式社交媒体发布管理平台`
- `3、Builder: Headless 内容管理系统`
- `4、开发一个月收入1000美金的Kindle生产力工具`

## 1、Headshot AI: 生成专业头像的开源项目

Headshot AI是完全免费且开源的项目，可以在几分钟内生成专业的AI头像。

用到的技术栈有：

- 🚀 Leap AI - 用于AI模型训练
- 🚀 Leap AI - 生成头像
- ▲  Next.js - 用于应用程序和登陆页面
- 🔋 Supabase - DB和Auth的
- 📩 Resend - 用于发送邮件
- ⭐️ Shadcn - Tailwindcss样式
- 🔥 Replit - 一键运行应用

![](https://qiniu.gafata.com/ezindie/202391422126764.png?imageslim)

[Headshot AI开源项目地址](https://github.com/leap-ai/headshots-starter)

## 2、Pallyy: 一站式社交媒体发布管理平台

为成长中的品牌提供社交媒体管理平台，简单，pally提供功能丰富的社交媒体管理和日程安排，有可以试用的版本，高级版需要付费解锁。
包括常用社交媒体的管理：Instagram、Facebook、Twitter、LinkedIn、Google My Business、Pinterest、Tiktok。
提前几个月开始计划你的内容，使用多个视图来帮助你看到你的内容完成后的样子。
在一个收件箱里管理你所有的社交媒体对话。
不错过任何评论，DM。你可以轻松地组织、回复和管理所有对话，它就像你社交的gmail。

![](https://qiniu.gafata.com/ezindie/202391422126804.png?imageslim)

作者在这个一个项目上一直保持专注了几年时间，收入一直在增加，目前月收入达到了6万美金。

![](https://qiniu.gafata.com/ezindie/202391422123751.png?imageslim)

作者最近通过2千美金收购了一个图片生成标题的在线工具，将其流量引导到Pally，能带来每天5K的自然流量。

![](https://qiniu.gafata.com/ezindie/202391422123752.png?imageslim)

[pallyy官网](https://pallyy.com/)

## 3、Builder: Headless 内容管理系统

Builder是一个带有可视化编辑器的CMS，可以让你直接在当前站点或应用程序中拖放组件。完全由api驱动，代码更干净，工作流程更简单。

可以在项目里方便的集成，安装依赖包

![](https://qiniu.gafata.com/ezindie/202391422125643.png?imageslim)

引入代码，通过拖动，一些配置，点击即可发布。

![](https://qiniu.gafata.com/ezindie/202391422123753.png?imageslim)

[builder官网](https://www.builder.io/)

## 4、开发一个月收入1000美金的Kindle生产力工具

![](https://qiniu.gafata.com/ezindie/202391422122365.png?imageslim)

大家好，我是Daniel Nguyen，KTool的创始人，这是一个为Kindle用户提供的生产力工具。KTool允许你发送新闻文章、时事通讯和RSS源到你的Kindle。

![](https://qiniu.gafata.com/ezindie/2023914221223259.png?imageslim)

我们最喜欢的功能是能够将来自多个来源的内容捆绑到一本每日杂志中。

我理想的客户是那些花大量时间在显示器前工作的忙碌的专业人士。在漫长的一天工作之后，你可以在Kindle上阅读所有有趣的文章，而不是花更多的时间浏览社交媒体或新闻网站。

KTool最近的月经常性收入(MRR)达到了1000美元。

### 你是如何想到这个主意的?

我从互联网上赚到的第一美元大约是在15年前，当时我在卖一个名为Invision Power Board的开源论坛软件的插件。从那以后，我主要从事软件咨询和建立业余项目以获得乐趣。

![](https://qiniu.gafata.com/ezindie/2023914221223295.png?imageslim)

我第一次想到KTool的想法是在HackerNews上读到“我是一个快要失明的软件工程师，我应该做些什么?”

我从5岁起就戴眼镜了。我的右眼瞎了。医生说没有治愈的机会。

我真的很害怕。天哪，如果我的左眼不工作了，我的生活就完了。从那以后，我对花在电脑屏幕上的时间非常在意。

从那时起，我开始使用Kindle相关产品:把尽可能多的阅读材料下载到Kindle上。然后我遇到了很多限制，这让我创建了KTool，一个可以将你喜欢的在线内容发送到Kindle的工具:博客文章、Twitter帖子、黑客新闻讨论、RSS订阅、新闻简报……

![](https://qiniu.gafata.com/ezindie/2023914221223171.png?imageslim)

我没有立即开始。一开始，我试图通过在Reddit上提问来验证这个想法。最初的想法是一个macOS应用程序，可以将PDF和EPUB发送到Kindle。但在Twitter上公开发布之后，我很清楚人们不会为它付费。所以我开始把文章和推特帖子发送到Kindle上，并获得了更好的吸引力。

### 介绍下构建产品的第一个版本的过程

![](https://qiniu.gafata.com/ezindie/2023914221223325.png?imageslim)

我在构建MVP时的原则是，针对一个用例，使用一个配置来解决一个问题。

对于KTool，我希望用户尽可能快地获得价值。所以我决定不马上构建整个应用程序。相反，它是一个超级简单的表单，用户可以输入一个链接，然后将其发送到他们的Kindle。

我花了59美元买了一个登陆页面模板，稍微调整了一下，然后把它免费托管在Cloudflare Pages上。在最初的几个月里，我只专注于核心解析器——它可以获取文章链接并将其转换为原生Kindle格式。

尽管UI非常基础，有些不方便，但早期用户经常使用它，并提供了很多很好的反馈。我就知道我找到了继续下去的方向。

后来，当我对核心功能有信心时，我决定构建一个浏览器扩展，它现在是KTool的主要产品。

### 描述下开始的过程

我于2022年1月开始公开构建KTool，并于2月在Twitter上发布了测试版。我不断改进产品，直到有一天我超级幸运。有人在Hacker News上提到了KTool。那天我得到了几个订单，完全是网上的陌生人。

我在早期销售终身会员(LTDs)，几个月后，我在LTDs的销售额达到了3000美元，这是相当不错的成绩。比我想象的好多了。

![](https://qiniu.gafata.com/ezindie/2023914221233457.png?imageslim)

今年7月，我决定停止销售终身会员，转而销售订阅制。一开始是很有挑战性的。直到我在Hacker News上发布了KTool，它才获得了很大的关注。这对我来说是一个巨大的成功，KTool登上了头版，并在第2位呆了将近2天。

在这段时间里，我学到的最大的东西就是这段很容易受到人们议论的时候，告诉别人我为什么要做这个产品。我担心这会让人觉得太私人，但令我惊讶的是，它受到了很好的欢迎。

### 是什么吸引并留住了客户?

在早期，我唯一的增长策略是在Twitter上公开建立KTool。这既是为了建立个人品牌，也是为了从早期用户那里获得快速反馈。

当我去年开始更认真地使用Twitter时，我立即得到了创始人和独立开发者社区的大力支持。我可能不是谈论在Twitter上增加用户的最佳人选。

![](https://qiniu.gafata.com/ezindie/2023914221233514.png?imageslim)

对我来说有效的“策略”是分享我在推广KTool和Bolt AI方面的经验。我偶尔会创作一些创业中有意思的对比图片，人们似乎很喜欢。有些像病毒一样传播，获得了超过100万的展现。我把我的产品放在病毒式推特下面，就是这么简单。

Twitter仍然是KTool的第二大流量来源。

![](https://qiniu.gafata.com/ezindie/2023914221233102.png?imageslim)

但是在Twitter上花费太多时间是不可扩展的。在某种程度上，我感到筋疲力尽。所以我开始探索其他渠道。我尝试了一些不同的方法:

- AppStore优化(ASO):我为KTool开发了Safari扩展，并将其提交给苹果AppStore。我对ASO有了更多了解，并在Mac AppStore的“Send to Kindle”一词中获得了第一名的位置。
- 开发更多的免费工具:我已经构建了多个免费工具来驱动KTool的流量并捕获他们的电子邮件地址
- 电子邮件营销:我每月发送产品更新和偶尔的促销。
- 时事通讯赞助:我在Twitter上联系了一些时事通讯作者
- 我试着运行一些谷歌广告活动
- 最近我在SEO上投入了更多的精力，并开始看到有希望的结果。

ASO是目前KTool表现最好的渠道。它不需要我做任何事情就能不断带来流量。我认为它之所以有效，是因为人们积极地寻找一种减少在电脑上花费时间的解决方案。

与iOS应用商店不同，Mac应用商店的竞争并不激烈。在Mac应用商店中，我的一些重要关键词能够排到第一名，但在手机应用商店中却只能排到70名左右。

“工程即营销”很有效，但这就像推出另一种产品。作为一名独立创业者，我发现很难维护这些免费工具并不断开发新的工具。

![](https://qiniu.gafata.com/ezindie/2023914221233410.png?imageslim)

付费广告似乎不起作用。对于像KTool这样每月5美元的产品来说，CAC太高了。

我从时事通讯赞助中得到了不同的结果。与付费广告类似，CAC太高，难以持续。所以最后，我决定不再继续投入它了。

我现在的策略很简单，在有效的事情上加倍下注。这意味着在ASO和SEO上投入更多时间。

我开始与一位自由职业者合作，帮助我构建更多的免费工具。如果做得好，我相信从长远来看，工程营销可以成为KTool发展的一个伟大策略。

![](https://qiniu.gafata.com/ezindie/2023914221233237.png?imageslim)

最近，我推出了两款不同的AI产品:Bolt AI和PDFPals。两者现在都产生了收益，我用它来投资KTool。

### 你的业务使用什么平台/工具?

* 域名和主机: Render，Cloudflare
* 邮箱: Bento, GSuite
* 付款: Paddle
* SEO: KeySearch, Astro
* 登陆页面&模板: TailwindUI
* 营销图像和视频: Xnapper, Screen Studio
* Affiliates: Rewardful
* 设计:Figma

### 对其他想要创业者有什么建议吗?

![](https://qiniu.gafata.com/ezindie/2023914221233769.png?imageslim)

开始总是最难的，对失败的恐惧是强烈的。

1、我的建议是尽快度过“第一个可怕的时刻”。开始吧，然后边走边想之后的。快速发布，不要等到产品完美(提示:它永远不会完美)

2、你的大多数决定都是可以调整的，所以最好现在就做一个决定，这样你以后可以从中学习和调整，而不是根本不做决定。

3、如果你像我一样有技术背景，不要犯把所有时间都花在产品和开发上的错误。至少花50%的时间在销售和市场营销上。

4、创业是令人兴奋的，但它可能是你职业生涯中最具挑战性的事情。加入一个支持性社区，如Indie Hacker或Twitter创客社区。

“不要把所有的时间都花在产品和开发上，至少花50%的时间在销售和市场营销上。”