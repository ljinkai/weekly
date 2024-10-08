# 独立开发变现周刊（第143期）：一个每年收入30万美元的AI业务，成本不到50美元

分享独立开发、产品变现相关内容，每周五发布。

**目录**
- `1、MinerU: 一站式开源数据提取工具`
- `2、DrawDB: 免费，简单，直观的在线数据库设计工具和SQL生成器`
- `3、将副业发展成每月1万美元的SaaS模版业务`
- `4、我建了一个每年收入30万美元的AI业务，成本不到50美元`

## 1、MinerU: 一站式开源数据提取工具

MinerU 是一款一站式、开源、高质量的数据提取工具，主要包含以下功能:

1、Magic-PDF PDF文档提取
是一款将 PDF 转化为 markdown 格式的工具。支持转换本地文档或者位于支持S3协议对象存储上的文件。

![](https://qiniu.gafata.com/ezindie/20248203347353.png?imageslim)

2、Magic-Doc 网页与电子书提取
是一款支持将网页或多格式电子书转换为 markdown 格式的工具。

![](https://qiniu.gafata.com/ezindie/20248203347112.png?imageslim)

[MinerU官网](https://github.com/opendatalab/MinerU)

## 2、DrawDB: 免费，简单，直观的在线数据库设计工具和SQL生成器

DrawDB是开源项目，一个健壮且用户友好的数据库实体关系(DBER)编辑器，可以在浏览器中使用。只需点击几下就可以构建图表，导出sql脚本，定制编辑器等等，而无需创建帐户。

![](https://qiniu.gafata.com/ezindie/20248203346205.png?imageslim)

[DrawDB官网](https://www.drawdb.app/)

## 3、将副业发展成每月1万美元的SaaS模版业务

![](https://qiniu.gafata.com/ezindie/20248203341628.png?imageslim)

27岁的乔纳森·威尔克(Jonathan Wilke)认为，如果他的SaaS样板能赚到1000美元，那就太幸运了。
三年后，他的副业每周只工作几个小时，每月就能赚到1万美元。现在，它在为他的特斯拉买单。

![](https://qiniu.gafata.com/ezindie/20248203349872.png?imageslim)

我和一个朋友共同经营一家小型的网页开发公司。supastarter的想法就是从那里来的。

我们发现自己一遍又一遍地为客户构建一些基本功能。我们想到一个模板可能对新项目有用，很快意识到其他开发者也可能需要这个。

于是，我开始制作一个SaaS的样板代码。我在2021年8月发布了第一个版本。当时我对自己说，如果这东西能赚到1000美元，那对我来说就是巨大的成功。

三个月后，我赚到了1000美元。这对我来说是一个重要的里程碑。

### 完整重写

![](https://qiniu.gafata.com/ezindie/202482033465.png?imageslim)

软件本身最初是用Next.js和Supabase构建的，核心功能包括身份验证和国际化。

从那时起，我们一直在根据客户反馈不断优化这个样板代码。

人们希望使用其他数据库，如Postgres或MongoDB，所以我们对整个项目进行了重构，使其更加模块化和灵活。

大约在第一个版本发布一年后，我们做了一次完全重写。

我们使用Prisma作为ORM，tRPC作为API层。前端样式框架使用Radix UI和Tailwind，并且我们兼容shadcn UI。

两个月后，我们发布了一个Nuxt版本，现在它可能和Next.js版本一样受欢迎。

对销售影响最大的一件事是，我按照客户的要求，构建了一个Tailwind CSS版本的supastarter。这对销量有很大影响，基本上使销量翻了一倍。

现在，我们正在为Sveltekit制作一个新版本，希望在下个月supastarter三周年时发布。

### 营销挑战

对我来说，最大的挑战是营销。我以前从未自己销售过产品。

我的第一次尝试是创建一个X账号。我用这个账号和我的个人账号发布关于supastarter的信息，分享网站链接和一些功能介绍。

然后我把链接放到Reddit上，大概三四天后就有了第一次销售。这可能是我到目前为止最有成就感的时刻。

但我从未真正做过大规模的营销活动。我赞助了一些newsletter和一个提供免费HTML模板的页面。

业务通过口口相传非常缓慢地增长。前三个月可能只有20-25笔销售，但这对我的预期来说已经很大了。

从那以后，我们基本上一直在添加新功能，以使产品对尽可能多的开发者有吸引力。

我们现在的销售额相当稳定，所以我正在寻找新的增长方式。

### 为我的Tesla买单

每当有人用supastarter启动一个应用程序时，我感觉非常好。看到甚至使用一个基于你样板代码的产品，真的很酷。

更好的感觉是，当一个开发者向其他开发者推荐你的产品。

最终，我希望靠我的独立开发工作生活。但不一定是靠这个特定产品。这感觉并不完全正确，因为它并不是百分百可持续的。

保持supastarter作为副业有很多好处。

现在，我每周大概只花4到6小时在上面。如果我开发更多功能或在营销上投入更多努力，可能会增长得更快。

我也非常喜欢我现在的全职工作。团队非常小，非常年轻。我们使用的技术和supastarter类似。

我刚买了一辆Tesla，supastarter基本上为它买单了。这对我来说就很好了。

### 你是掌控者

我更愿意以适合我生活方式的方式来发展一个产品，而不是在它感觉不成熟的时候全职投入。

这是独立开发总体上的一个好处。你是掌控者，而不是那些想要尽可能多收入的风险投资公司。你可以专注于为客户打造最好的产品。

话虽如此，不要把你的产品定价太低。

我最初把supastarter定价在49美元左右，然后逐渐提高价格。现在它的价格是299美元。

我发现，产品定价越高，销售得越好，人们越能认识到它的价值。

## 4、我建了一个每年收入30万美元的AI业务，成本不到50美元

![](https://qiniu.gafata.com/ezindie/20248203357503.png?imageslim)

我是My AskAI的联合创始人之一。我们向SaaS企业销售AI客户支持服务，帮助他们减少和降低支持工单的数量。

你可以添加你的帮助文档（Zendesk、Intercom等），连接其他知识源（如Drive、Notion、Confluence），然后我们会根据你的文档创建一个专为回答用户问题而训练的AI代理。

如果AI不能回答，它会将对话转交给你的人工代理！

你可以在你的网站上使用我们的插件，或者通过我们与Zendesk、Intercom或HubSpot的集成来为客户提供AI答案。企业选择我们而不是这些公司的内部产品主要是因为我们的价格（大约便宜5倍）和我们的响应质量。

目前，我们每月收入2.5万美元，正在与一些最大的客户支持平台竞争。

![](https://qiniu.gafata.com/ezindie/20248203356976.png?imageslim)

### 你是如何想到这个点子的？

小时候我就知道我想创业。

我会宗教般地观看《Dragons' Den》和《The (UK) Apprentice》，尽可能吸收我所能吸收的东西（回想起来可能有很多不好的建议……）。

我不是那种在学校里开柠檬水摊的孩子（不过在某些新法规出台时，我确实通过在eBay上卖儿童汽车座椅赚了一笔）。

我走的是普通中产阶级孩子的路线：上大学，在财务公司找了一份工作（会计师事务所），然后准备长期工作。

但我无法摆脱创业的冲动。我在工作中组建团队和发起项目，试图利用新技术，进军金融科技以及其他许多领域。

我甚至花了一些时间和朋友一起开发自己的运动应用程序，帮助寻找其他人一起运动，但没有成功。

![](https://qiniu.gafata.com/ezindie/20248203355377.png?imageslim)

在工作了9年后，我意识到了一点。

我问自己：

*“如果一切都按计划进行，我在职业生涯中达到了我想要的一切，我会开心吗？”*

当我意识到答案是一个响亮的“否”时，我开始起草辞职信。

所以就这样，我有3个月的通知期和3个月的现金来重新塑造自己，创业或者找别的事情做。

事实证明，从会计师转行到科技产品经理比你想象的要难（或比我想象的要难）。谁能想到呢？

所以我开始在科技公司做合同工，先是一个可再生能源初创公司，然后是一个保险科技公司。

我会工作6个月，存钱，然后尝试自己的点子6个月，或者直到我用完现金，再回去做合同工。

听起来挺低效的，但我知道当我全身心投入做某件事时，我的表现最好，而不是分散注意力。这也给了我一些健康的压力，并给了我一个期限来想出点子。

在此期间，我开始在Twitter（X）上关注更多的“创作者”。每天看到那些从零开始创办企业，并与风险投资支持的公司竞争的人，对我来说是巨大的激励。我从这个社区中学到的东西比我上过的任何一本书或课程都要多。

在自由职业了几年后，我在一家我工作的公司里的一位朋友问我是否愿意见他的一位朋友，给他一些关于如何作为产品经理工作的建议。

他创办并运营了一家获得风险投资支持的旅游保险科技初创公司，该公司因COVID-19的影响而倒闭，所以他在寻找下一个角色。

我们见面了，一拍即合，谈论着刚刚推出的新技术“GPT-3”。

首先，我们制作了一款使用微调AI模型编写大学个人陈述的工具。我们卖出了几份，但那时OpenAI正在手动审批用例，他们不喜欢我们的用例，所以我们从未正式推出。

从那之后，我们转向制作一个叫做“无代码AI模型构建器”的工具。我们的想法是你可以上传一堆训练数据，然后输出一个微调的模型，完全不需要编写代码。

![](https://qiniu.gafata.com/ezindie/20248203357240.png?imageslim)

我们在Ben’s Bites黑客马拉松期间花了几天时间制作了这个工具，并将其发布在Product Hunt上，看看人们的反应。

24小时内，我们有了2笔销售和2000个网站访问者。一周内，我们在一个巨大的德国科技博客上被推荐。

我们开始进一步开发它，但很快发现制作微调模型的阻力太大。

人们实际上想做的是将数据倒入某个东西中，然后得出神奇的结果。这得到了进一步验证，因为开发者们在Twitter上开始推出各种“与播客/书籍聊天”的项目。

我们知道必须为他们提供一个平台。

于是，在两周内（其中一半是在泰国度假期间），Alex利用无代码平台Bubble制作了一个MVP。

它允许用户上传文件，然后开始用自然语言提问。

![](https://qiniu.gafata.com/ezindie/20248203357210.png?imageslim)

我们都有专业服务的背景，我们的思维开始飞速运转，想到了各种应用场景。能够查询大量文档和网站获取答案，而无需消化所有内容。

我们对这款产品的直觉非常有信心，但我们仍然想验证需求。

所以我们在我们的无代码AI模型构建器产品中添加了一个预发布页面，询问用户他们想用这个产品做什么。如果符合条件，我们会将他们引导到My AskAI的预发布注册页面。

在这两周内，我们获得了5000美元的预发布注册（50个用户，每个99美元）。

![](https://qiniu.gafata.com/ezindie/2024820335417.png?imageslim)

这比我们现有（功能性）产品的总收入还要多。

![](https://qiniu.gafata.com/ezindie/20248203357558.png?imageslim)

### 带我们了解一下你构建第一版产品的过程

当我们从头构建新产品时，我们不喜欢过度计划。

我通常会在Figma上草拟一些低到中保真的线框图（我绝对不是设计师），展示产品的流程、按钮位置等。

![](https://qiniu.gafata.com/ezindie/20248203412945.png?imageslim)

这大约需要一天的时间，包括反馈和来回讨论。

我们俩都有产品管理的背景，所以我们对“MVP”思维方式相当擅长，确保我们不会在功能上过于沉重。我们也做得很好，互相监督。

一旦我们设计并规划好了基本功能，Alex会立即开始使用Bubble构建。

这是使用像Bubble这样的无代码工具的一个优点——你可以非常快速地构建和更改东西，就像一个功能性线框图。

我认为这是一个很大的收获，无论你是否打算长期使用代码，使用无代码构建你的第一个版本是一个很大的优势。它允许你快速响应用户反馈并保持他们的参与。

一旦一个粗略的第一个版本准备好，我会开始测试。

我们在一个基本的Notion板上记录所有的bug和功能，以保持整洁并确保范围不会失控。

![](https://qiniu.gafata.com/ezindie/20248203412354.png?imageslim)

然后我们会找到5-10个潜在用户（来自现有用户群、邮件列表、在Twitter上问人或使用用户反馈平台），进行一些用户测试。

我们会注意看他们是否理解产品的作用、如何操作以及如何在没有我们输入的情况下使用它。

总的来说，My AskAI的第一个版本大约花费了50美元的软件和2周的构建时间。

> 目前我们是盈利的，毛利率在85-90%，净利润率在50-55%。我们每月有大约35k的访问者，转化率约为3%。
> 

### 描述一下启动业务的过程

在我们正式上线之前，我们已经从预发布销售中获得了5000美元的收入。

所以上线的问题在于如何将这些一次性收入转化为经常性收入（因为我们有持续的OpenAI账单需要支付）。

为了上线我们：

- 在Twitter上发帖，在那里我们试图“公开构建”
- 在LinkedIn和其他几个平台上分享
- 在Product Hunt上发布
- 发布到我们能找到的尽可能多的AI目录

![](https://qiniu.gafata.com/ezindie/20248203412746.png?imageslim)

![](https://qiniu.gafata.com/ezindie/20248203413153.png?imageslim)

（在这里，为了提供背景信息，这是2023年2月，可能是AI热潮的高峰期，所以我们已经有了顺风）。

我们上线后几乎立即看到了销售额，在两个月内我们的月经常性收入（MRR）达到了约7000美元。

![](https://qiniu.gafata.com/ezindie/2024820341143.png?imageslim)

此时，我们仍然依靠储蓄生活，并认为我们需要达到大约1万美元的MRR才能生活。

幸运的是，我们还成功地在MicroAcquire上卖掉了我们的前几个产品（无代码AI模型构建器和大学陈述生成器，总共25k美元）。

双倍幸运的是，我们的业务成本相当低，只有几个SaaS订阅约100美元/月和OpenAI成本（随我们的收入而增加）。

如果我们回头再做一次，有一件事我们会做得不同的，那就是在发布时制作更高质量的视频内容。

其他同时发布的产品获得了更多的宣传部分原因是他们分享了更好的发布视频，展示了他们的产品，而那时AI的病毒性更容易到来。

### 自发布以来，吸引和留住客户的有效方法是什么？

自15个月前发布以来，我们尝试了多种增长渠道，寻找可重复的渠道。

说实话，我们还在寻找中。

我们在AI领域注意到的一件事是，很多渠道都是暂时性的。

我的意思是它们在一段时间内有效，但很快就会被耗尽。

例如，几乎所有这些方法在一段时间内都有效，但很快就饱和了，或者我们意识到它们不适合B2B SaaS业务：

- 网红帖子（LinkedIn/Twitter/TikTok）——我们还没有看到这些对B2B业务有效的好例子，很多“AI网红”从我们的经验来看，往往会导致虚荣的观看量和参与量（我们做了不少测试！）
- 时事通讯赞助——我们会看到一个初始的提升，但很快就会消失，它们可能更适合长期的品牌知名度而不是转化。
- Reddit广告——这些广告很难做得真实，Reddit是一个残酷的地方。
- AI目录——当热潮达到顶峰时，这些目录是人们了解新AI工具的好方法，但现在只有高度策划的目录能带来任何流量。
- 在Twitter上回复大账号——这在一段时间内是个增长黑客，回复大网红账号，但现在热潮已经大大减弱了，所以你不会得到同样的覆盖率。

![](https://qiniu.gafata.com/ezindie/20248203413288.png?imageslim)

相反，我们现在专注于：

- SEO：我们与一家机构合作撰写博客内容，并试图创建更多的副产品工具和目录来驱动流量。
- 社交媒体：我们发现我们最好的客户往往来自LinkedIn，所以我们将花更多时间在那里使用Breakcold等社交销售工具。
- Google广告：我们进行了不少实验，但从未破解过，像Intercom和Zendesk这样的竞争对手价格高得离谱，但我们认为在长尾关键词上可能仍有一些价值。
- 产品市场营销：我们努力确保通过电子邮件流程、时事通讯、变更日志更新来销售我们自己的产品。
- Reddit：我们设置了一些f5bot的警报，告诉我们有人在谈论与我们相关的话题，这样我们可以及时加入，只要你在任何互动中提供价值，这通常效果不错。

![](https://qiniu.gafata.com/ezindie/2024820341353.png?imageslim)

大多数人不谈论这一点，但AI产品的流失率相当高。

很多人还在试图弄清楚他们能用这些产品做什么，或者只是测试它们的输出质量。

我们还非常快速地发布新功能和修复（感谢我们的无代码技术栈）。

有两件大事大大降低了我们的流失率：

1. 资格审查并专注于更紧密的用户群。这意味着我们可以围绕他们的用例构建产品，使用户更有可能留下来。合格的用户也不太可能只是“尝试”，更有可能是寻找长期解决方案。
2. 向上市场发展。我们现在有更多的企业客户，与他们紧密合作，并签订了长期合同。

### 你现在的情况如何，未来的前景如何？

目前我们是盈利的，毛利率在85-90%，净利润率在50-55%。我们每月有大约35k的访问者，转化率约为3%。

我们专注于B2B SaaS企业，但未来的巨大目标是面向电商企业。

大多数主要的聊天提供商都是从（电商）开始他们的AI产品的，但数量要多得多，AI需要更好地集成到其他工具中才能有用。我们认为今天的产品更适合SaaS企业。

我们刚刚发布了一项本地化功能，现在你可以在多种语言中使用My AskAI。

今天，Alex和我都在家工作。工作时间大约是工作日的早上8点到下午6点半，只有在我们想要或有紧急问题需要处理时才会在这些时间之外工作。

![](https://qiniu.gafata.com/ezindie/20248203412864.png?imageslim)

我们所有的交流都在Slack上进行，那里是做出大多数决定的地方。

新功能和修复几乎是每天发布。这确保了我们能紧跟客户的需求，并保持产品的“活跃开发”状态（在AI领域这是很罕见的）。

另外两个大幅降低我们的流失率的关键点是：

1. **筛选并专注于更小的用户群体。** 这意味着我们可以围绕他们的使用场景构建产品，使用户更有可能留下来。被筛选出来的用户也更不可能只是在“试验”，而更可能是寻找长期解决方案。
2. **进军高端市场。** 现在我们有很多大企业客户，我们与他们紧密合作，并签订了长期合同。

### 在创业过程中，你学到了哪些特别有帮助或有利的经验？

这是我第一次真正有重大进展的业务，所以不可避免地学到了很多教训，以下是其中的一些：

- 不要低估“跟进”的重要性。我们在第七封未回复的邮件后签下了合同。人们很忙，如果你不合适，他们通常会告诉你。
- 专注，说“不”，但不要如此僵化以至于错过随机的机会。虽然保持紧密的产品焦点很重要，但如果我们过于严格，可能会错过通过一个LinkedIn私信引来的大约10万美元的收入机会。
- 如果你没有明确的产品定位，一切都会变得更加困难。决定使用的文案或语言、营销渠道和策略、设计以及功能优先级都会变得非常困难。
- 不要让自己的自负影响决策。我们可能在交付某些功能上迟到了，因为我们自己不太喜欢它们，尽管有几个人在要求。

但我们也做出了一些好的决定。

主要是因为我们尽可能地使用数据来做决策。我们经常对我们的登陆页面进行A/B测试（我们使用VWO），甚至在去年十月将我们的产品核心转向客户支持，都是值得一提的。

我们在时机上也确实很幸运。AI蓬勃发展。

但我们也通过暴露自己在这项新技术中并采取行动来让自己变得幸运。

我们都是相当有纪律、专注的人，并且养成了一些好的习惯：

1. 我们总是将产品或功能简化为最多一天内可以完成的东西。如果它有吸引力，我们再从那里开始。
2. 即使只有我们两个人，我们对产品路线图和修复bug也非常严格。
3. 我们还养成了在构建新功能时通知用户的习惯。我们更新文档，添加到变更日志中，并在我们的新闻通讯中分享。这是利用已有的东西的一个很容易实现的胜利。

![](https://qiniu.gafata.com/ezindie/20248203412566.png?imageslim)

### 对其他想创业或刚开始创业的人的建议？

这些是我会告诉“过去的自己”的一些事情：

1. 创业很难，如果你身边没有人会更难。让自己周围充满可以向他们学习和激励你的人。参加聚会，活跃在Twitter和Reddit上，每天从那些比你稍微领先一步的人身上获得灵感。
2. 不要纠结于客户永远不会看到的事情。忘掉技术栈，如果你可以用Zapier构建某些东西就用它，如果你会编程就编程。不要学习新东西，如果你已经能用现有知识解决问题。
3. 如果可以，和你选择的市场中有影响力的人合作。某个已经有联系和网络的人。分销是最困难的事情之一，拥有已经有分销渠道的人是非常有价值的。
4. 视频越来越重要，所以接受尴尬，开始尝试把你的脸放在镜头前，并习惯通过屏幕录制与人交流。
5. 每员工收入将在未来5-10年内只会增加，我们可以用更少的人构建更多的东西，所以不要纠结于雇佣，寻找工具帮助你解决问题。
6. 不要过度研究一个想法，有时直接构建并发布会更快，而不是纠结于采访潜在用户。

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