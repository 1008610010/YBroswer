# YBroswer
YBrower是基于腾讯X5内核实现的浏览器DEMO

本产品基于[Ericsongyl/S-Browser: Android：S-Browser（S浏览器，S的意义：sensitive-灵敏、灵活，super-超级，simple-简单、简洁），V2.0改用TBS X5的内核，app体积大大减小，只有1.4M左右，用户体验大大提升，页面加载很快；而原来V1.0使用Chromium_WebView内核，基于TintBrowser框架实现的，app有34M左右。 ](https://github.com/Ericsongyl/S-Browser)

### V1.0
源码下载地址：[YBroswer-v1.0](https://github.com/simplebam/YBroswer/archive/v1.0.zip)  <br/>
App体验链接:[app-release.apk](https://github.com/simplebam/YBroswer/releases/download/v1.0/app-release.apk)

<a href="./art/jietu1.jpg"><img src="./art/jietu1.jpg" width="50%"/></a><img height="0" width="8px"/><a href="./art/jietu2.jpg"><img src="./art/jietu2.jpg" width="50%"/></a>

### V2.0项目截图
源码下载地址：[YBroswer-v2.0](https://github.com/simplebam/YBroswer/archive/v2.0.zip)            <br/>
App体验链接:[app-release.apk](https://github.com/simplebam/YBroswer/releases/download/v2.0/app-release.apk)

<a href="./art/jietu22.jpg"><img src="./art/jietu22.jpg" width="50%"/></a>





## 前言
* 最近由于 “红芯浏览器内嵌Chrome内核都可以融资2.5亿元” 事件引起了巨大的轰动，不少
  朋友想起了我们芯片事件，其实做一个浏览器内核跟做操作系统的难度是差不多的，国内
  互联网公司比如奇虎360的安全/极速浏览器、腾讯的QQ浏览器、百度的百度浏览器等都是基于
  Blink 引擎进行二次优化，其中最好用的就是阿里的UC内核以及腾讯的X5内核。
* 身为阿里粉丝的我，在2017年中听 UC宣称向开发者开放了UC内核的时候便想去尝试，但截
  至到 2018.08.29都没有找到相关文档。
* 腾讯的 X5内核虽然很多坑，但相较于CrossWalk还是很轻，是一个差强人意的产品。X5文档写的
  比较差，希望腾讯以后可以优化一下。

## 官方工具
* X5内核检查工具：[[TBS] X5内核加载问题自动检测工具发布啦 - QQ浏览器移动产品论坛 ](http://bbs.mb.qq.com/thread-1944983-1-1.html)
* X5静态打包:[App想要静态集成X5内核该怎么做 - 腾讯浏览服务 ](https://x5.tencent.com/tbs/technical.html#/detail/sdk/1/8a591c85-337e-4c60-a45a-cf0839819f63)

## X5其他优秀的开源库
* [X5 浏览器内核调研报告 - 简书 ](https://www.jianshu.com/p/2a14d303308d)
  * [baishixian/X5WebEngineDemo: X5 webview demo ](https://github.com/baishixian/X5WebEngineDemo)
* [Ericsongyl/S-Browser: Android：S-Browser（S浏览器，S的意义：sensitive-灵敏、灵活，super-超级，simple-简单、简洁），V2.0改用TBS X5的内核，app体积大大减小，只有1.4M左右，用户体验大大提升，页面加载很快；而原来V1.0使用Chromium_WebView内核，基于TintBrowser框架实现的，app有34M左右。 ](https://github.com/Ericsongyl/S-Browser)
* [Android-X5WebView（Cookie管理、进度监听、适配8.1系统等策略） - 简书 ](https://www.jianshu.com/p/88084a66c256) ,
  这个库特别优秀
  * [zuowutan/ShareX5WebViewDemo: Android-X5WebView基本封装 ](https://github.com/zuowutan/ShareX5WebViewDemo)
* [FangWW/lightning-browser-gsy: 借鉴闪电浏览器+腾讯x5内核 包裹出web-app ](https://github.com/FangWW/lightning-browser-gsy)
* [Android Webview H5 秒开方案实现 - 任玉刚](http://mp.weixin.qq.com/s?__biz=MzIwMTAzMTMxMg==&mid=2649493130&idx=1&sn=f8c9fe91de36c736c2dd863140baefa9&chksm=8eec8575b99b0c637652f5d59e31b032992c0547cefb700ad9c6b5a3d47853ae9fab89fc0394&mpshare=1&scene=24&srcid=0910DzaHfsuamrrXjHgUOatS#rd)
