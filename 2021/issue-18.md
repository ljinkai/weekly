# 独立开发变现周刊（第 18 期）：一个通过短信进行购物的网站平台

分享独立开发产品变现相关有价值的内容，每周五发布。

**目录**
- `1、Text Retailer：一个通过短信进行购物的网站平台`
- `2、Fabric.js: 让H5的Canvas交互更简单`
- `3、3个实用 UX/UI 的优化技巧`
- `4、Trends.vc: 帮助创造者发现新的市场和想法`
- `5、Github仓库主页点击(.)一键打开VS Code的云编辑器`
- `6、Color Thief: 从图片里提取色盘的JS开源库`

## 1、Text Retailer：一个通过短信进行购物的网站平台

Text Retailer是一个小众市场的SaaS产品，它的理念很有趣。Text Retailer的创始人Sam Schrup 觉得缓慢的页面加载和复杂的结账会导致销售损失。而便捷的购物体验是增加收入的关键。短信很吸引用户注意力，很少被忽视，能排除杂音，为你的客户提供直接的联系。回复购买结账只需要回复一个“Yes”。为短信增加一点点魔法，就可以让购物体验很有趣。这个平台使用收费是按照客户订阅数量来收费的。

![](http://qiniu.gafata.com/2021-09-02-Untitled.png?imageView2/2/w/600)

[Text Retailer的官网](https://textretailer.com/)

## 2、Fabric.js: 让H5的Canvas交互更简单

Fabric.js是一个开源项目，Github上有19K的Star，可以轻松处理HTML5 canvas元素的框架。它是canvas元素之上的一个交互对象模型。它也是 SVG-to-canvas 的解析器。
使用Fabric.js，你可以在画布上创建和填充对象;像简单的几何形状-矩形，圆，椭圆，多边形，或更复杂的形状组成的数百或数千条简单路径。然后你可以用鼠标缩放、移动和旋转这些对象;修改它们的属性 —— 颜色、透明度、z-index等。您还可以一起操作这些对象-用简单的鼠标选择将它们分组。有在线Demo可以体验。

![](http://qiniu.gafata.com/2021-09-02-Untitled%201.png?imageView2/2/w/600)

[Fabric.js开源地址](https://github.com/fabricjs/fabric.js)

## 3、3个实用 UX/UI 的优化技巧

**1、不要强调像删除这样的危险操作**

必须优先考虑默认的行动，而不是危险的/不可逆转的行动。

同时，使用多种方法让它看起来像一个次要动作(颜色，大小，类型，位置等)。

![](http://qiniu.gafata.com/2021-09-02-Untitled%202.png?imageView2/2/w/600)

**2、不均匀的元素会感觉很奇怪**

即使它们之间的间距是一样的，视觉效果似乎是不一致的……

一个超级快速的解决方法是为所有元素设置相同的宽度。选择最大元素的宽度，并将其应用到所有其他元素。

![](http://qiniu.gafata.com/2021-09-02-Untitled%203.png?imageView2/2/w/600)

**3、图标经常会让用户感到困惑或被用户误解**

解决这个可访问性问题是通过添加一个文本标签来描述它的用法。

![](http://qiniu.gafata.com/2021-09-02-Untitled%204.png?imageView2/2/w/600)

## 4、Trends.vc: 帮助创造者发现新的市场和想法

一个订阅制的网站，会发布免费的报告，也有付费的社群。模式非常的简单，仅仅是通过订阅机制，打开网站就只有一个订阅入口，目前是月收入2万美金。创始人Dru Riley, 长的有点像克里斯.保罗，在2017年辞去了大数据工程师的职位，接下来的3年里去旅行、练习柔道。在2020年开始做Trends.vc。Dru分享了他的经验。

1、使用磁性吸引

用有吸引力的内容方式来和用户建立联系。内容是磁铁，社区就是护城河。

2、专注在定期更新上

固定时间的发布内容是有仪式感的，随着时间的增加，用户会越来越建立固定习惯。比如：Q&A、Demo日、定期会议等

3、自我调节

在做Trend.vc内容报告的时候，每星期会花费60+小时来搜集内容和资料。

4、亲自行动

用户反馈要认真对待

5、策略上设置一点点门槛

低门槛是能带来很多用户，但是也会让社区增加很多的“噪音”

6、分散式领导

让更多人的人帮助社区运行起来，防止把自己精力耗干

![](http://qiniu.gafata.com/2021-09-02-Untitled%205.png?imageView2/2/w/600)

![](http://qiniu.gafata.com/2021-09-02-Untitled%206.png?imageView2/2/w/600)

[Trends.vs官网](https://join.trends.vc/)

[Dru Riley的经验分享](https://twitter.com/DruRly/status/1430222481579671561?s=20/)

[Dru Riley的Podcast采访](https://www.indiehackers.com/podcast/173-dru-riley-of-trends-vc)

## 5、Github仓库主页点击(.)一键打开VS Code的云编辑器

只要你在任何 GitHub Repo 页面上按下`.`键会自动跳转到`github.dev`的网站，打开的是一个网页版的 VSCode ，并且会自动克隆下这个 Repo 的代码。在这个网页版的 VSCode 里你甚至可以安装一些特定的插件（无法安装需要外部依赖的插件），能更方便的阅读代码。因为这个网站是官方出品，这个 VSCode 已自动绑定了你的 GitHub 账户，开发者可以在里面阅读、编辑及提交代码，整个过程行云流水，甚至全程不需要打开本地的 IDE。在浏览器写代码还能拥有桌面 IDE 的开发体验。

![](http://qiniu.gafata.com/2021-09-02-Untitled%207.png?imageView2/2/w/600)

## 6、Color Thief: 从图片里提取色盘的JS开源库

Color Thief是一个开源库，有JS端和Node端的模块可用。可以将图片中的颜色进行提取，这样可以快速的将一张图片中使用的颜色进行分析。也可以将网站以图片的方式进行提取，或者网站的色彩搭配。有在线的Demo演示可以体验其效果。

![](http://qiniu.gafata.com/2021-09-02-Untitled%208.png?imageView2/2/w/600)

[Color Thief的Demo演示地址](https://github.com/lokesh/color-thief)

---
<center>
本内容开源，欢迎推荐或自荐：

Github: [https://github.com/ljinkai/weekly](https://github.com/ljinkai/weekly)


Indie Maker Start: [https://www.ezindie.com/](https://www.ezindie.com/)

微信公众号：凯凯而谈


![](http://qiniu.gafata.com/2019-03-17-web-bear.jpg?imageView2/2/w/200)

扫码订阅
</center>