# 独立开发变现周刊（第 2 期）：挑战100天获取100个付费用户

## 1、Termux：Android终端模拟器

Termux 是一个Android终端模拟器,开源且不需要root，可以在手机上模拟Linux 环境。它提供一个命令行界面，让用户与系统互动。通过Termux可以用手机连接你的远程服务器，如果你的产品服务出现了Bug，这时候电脑不在手边也可以操作服务器了。还可以用手机搭建一个Http Server，实现电脑和手机的互连访问。

![](http://qiniu.gafata.com/2021-05-13-100.png?imageView2/2/w/600)

很早之前看到尤大的微博才知道termux的这个神器，我还写过一篇文章：[发现有趣的人](https://mp.weixin.qq.com/s/zeo2h5S8M6q_zzhpQB7swQ)，介绍过搭配便携键盘可以实现在手机端的编程开发，还是很有意思的。

![](http://qiniu.gafata.com/2021-05-13-1.png?imageView2/2/w/600)

官网：[https://termux.com/](https://termux.com/)

搭配键盘使用：[https://mp.weixin.qq.com/s/zeo2h5S8M6q_zzhpQB7swQ](https://mp.weixin.qq.com/s/zeo2h5S8M6q_zzhpQB7swQ)

Termux架设手机Server: [https://www.ruanyifeng.com/blog/2019/07/termux-tutorial.html](https://www.ruanyifeng.com/blog/2019/07/termux-tutorial.html)

## 2、Lottie动画

Lottie是一个开源动画文件格式，可用于Web、Android，iOS。可以实现非常漂亮的动画，体积小，质量高，现在一些免费的动画效果有很多，可以在网站上搜索，相信用在你自己的产品里，会让产品效果提升一个档次。也有基于不同框架下的实现，像Vue、微信小程序、React等等

![](http://qiniu.gafata.com/2021-05-13-2.png?imageView2/2/w/600)

- lottie-web仓库地址: [https://github.com/airbnb/lottie-web](https://github.com/airbnb/lottie-web)
- lottie-ios仓库地址: [https://github.com/airbnb/lottie-ios](https://github.com/airbnb/lottie-ios)
- lottie-android仓库地址: [https://github.com/airbnb/lottie-android](https://github.com/airbnb/lottie-android)
- 免费在线动画库: [https://lottiefiles.com/](https://lottiefiles.com/)
- Vue集成实现：[https://github.com/chenqingspring/vue-lottie](https://github.com/chenqingspring/vue-lottie)

## 3、ZX: 像JavaScript一样写Bash脚本

一个更方便的写脚本的工具。Bash很好，但不是很好用，zx像写JavaScript的方式实现脚本的书写。下面这个例子看起来有点像JS，实现了github仓库的本地备份。

![](http://qiniu.gafata.com/2021-05-13-3.png?imageView2/2/w/600)

Github仓库地址：[https://github.com/google/zx](https://github.com/google/zx)

## 4、Daily.dev: 获取最新开发消息的开源浏览器插件

是一个浏览器插件，有Chrome、Firefox、Edge 3个版本的插件，展示国外每天新的科技新闻、技术文章，汇集了很多网站的热点信息，像：Hacker News、[dev.to](http://dev.to/)、Hashnode等350+的站点信息，内容非常丰富。还有手机端的PWA版本，daily.dev有开源代码库，包括前端、后端的代码。想实现一个类似的产品可以参考。

![](http://qiniu.gafata.com/2021-05-13-4.png?imageView2/2/w/600)

官网: [https://daily.dev/](https://daily.dev/)

Github仓库地址：[https://github.com/dailydotdev/daily](https://github.com/dailydotdev/daily)

## 5、30 seconds of code: 最常用的JS代码片段

JavaScript的代码片段集合。包括常用的数组、对象等的操作，还有算法，Dom操作，以及Node.js的工具方法。

我们在写代码的时候，经常会用到一些很常用的功能，这些代码比较固定，也不可能都记得住，经常会利用搜索来到处查找这些方法。这个网站就是解决这样的问题，可以很方便快速的找到需要的功能方法，很方便也很实用。

![](http://qiniu.gafata.com/2021-05-13-5.png?imageView2/2/w/600)

快速查找网址：[https://www.30secondsofcode.org/js/p/1](https://www.30secondsofcode.org/js/p/1)

Github仓库：[https://github.com/30-seconds/30-seconds-of-code](https://github.com/30-seconds/30-seconds-of-code)

## 6、100in100: 100天获取100个付费用户挑战

这是一项挑战活动，通过做自己的产品，来获取100个付费用户，在网站上可以看到每个产品的挑战情况。有产品的排名情况，最终排名前7的可以得到$100的礼品卡，前10名还可以获得免费设计的服务。这个活动在Twitter上最近比较流行，很多人参加了这个活动，还吸引了一些赞助商的支持。

通过这些产品可以获得灵感，一些挺有意思的产品还挺好玩的。比如其中一个是为了促进自己养成写作的习惯，可以设定一个目标，如果没有完成，就扣掉自己1美元。已经有付费用户开始用了，说明还是有需求的。其它的还有效率工具、虚拟助理等产品。

![](http://qiniu.gafata.com/2021-05-13-6.png?imageView2/2/w/600)

挑战官网：[https://100in100.co/](https://100in100.co/)

## 7、VuePress: Vue 驱动的静态网站生成器

以Markdown格式内容生成静态页面。这个项目是由Evan You发起并创建的，有很多的开源开发者贡献代码。可以在 Markdown 中使用 Vue 组件，又可以使用 Vue 来开发自定义主题。有非常丰富的插件支持。生成Blog、文档说明类的静态站还是非常棒的。VuePress跟其它静态站生成器相比，比如：Nuxt、Hexo、Gitbook等，最大的优势就是用Vue的语法来开发Blog、文档类的静态站点。

只需要几步就可以创建一个项目，然后就可以放到GitHub Pages、Netlify、Heroku、Vercel等上面。

另外，有一个插件vuepress-plugin-yuque，我们知道语雀的优势在于文档编辑，如果能够将两者结合起来，你将能得到一种从文档编写、管理，到网站发布，都比以前更流畅的体验。

![](http://qiniu.gafata.com/2021-05-13-7.png?imageView2/2/w/600)

官网：[https://vuepress.vuejs.org/zh/](https://vuepress.vuejs.org/zh/)

非常多的资源示例：[https://github.com/vuepress/awesome-vuepress](https://github.com/vuepress/awesome-vuepress)

和语雀的集成：[https://www.yuque.com/vuepress/vuepress-plugin-yuque/intro](https://www.yuque.com/vuepress/vuepress-plugin-yuque/intro)

---
<center>
以上内容会同步更新在：

Indie Maker Start: [http://www.indiemakerstart.com/](http://www.indiemakerstart.com/)

Github: [https://github.com/ljinkai/weekly](https://github.com/ljinkai/weekly)

微信公众号：凯凯而谈


![](http://qiniu.gafata.com/2019-03-17-web-bear.jpg?imageView2/2/w/200)

扫码订阅
</center>