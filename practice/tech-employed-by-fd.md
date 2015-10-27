# 前端开发所需的web技术

![](../images/web-tech-employed.jpg "http://www.2n2media.com/compare-front-end-development-and-back-end-development")

<cite> 图片来源：<a href="http://www.2n2media.com/compare-front-end-development-and-back-end-development">http://www.2n2media.com/compare-front-end-development-and-back-end-development</a> </cite>

下列网络技术都是前端开发者所需要掌握的技术：

* 超文本标记语言（Hyper Text Markup Language，也就是HTML）
* 层叠样式表（Cascading Style Sheets，也就是CSS）
* 文档对象模型（Document Object Model，也就是DOM）
* JavaScript程序语言（包括ECMAScript 6, ES6, JavaScript 2015）
* 网络API（也就是 HTML5 和他的小伙伴们，或者浏览器API）
* 超文本传输协议（Hypertext Transfer Protocol，也就是HTTP）
* 统一资源定位符（Uniform Resource Locator's，也就是URL）
* JavaScript对象表示法（JavaScript Object Notation，也就是JSON）
* 网络内容易用性指南（Web Content Accessibility Guidelines，WCAG）和易用富网络应用（Accessible Rich Internet Applications，ARIA）

下面会分别定义这些技术，并附上相关文档和标准。想要查阅更全面的网络相关标准列表，可以访问[platform.html5.org](https://platform.html5.org/).

##### 超文本标记语言（Hyper Text Markup Language，也就是HTML）

> 超文本标记语言，简称HTML，是创建网页所用的标准标记语言。[1]网络浏览器可以读取HTML文件并把它们渲染成可视或可听的网页。HTML沿着网页呈现顺序，从语义上描述页面结构。这使得HTML成为标记语言，而非编程语言。 - wikipedia.org

主要相关标准/文档：

* [W3C的HTML5](http://www.w3.org/TR/html5/) ：全球广域网核心语言的第五个重要修订版
* [HTML元素](https://html.spec.whatwg.org/multipage/semantics.html#semantics)
* [HTML语法](https://html.spec.whatwg.org/multipage/syntax.html#syntax)
* [所有W3C HTML标准](http://www.w3.org/standards/techs/html#w3c_all)
* [HTML元素参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [HTML属性参考](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
* [全局属性](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)

##### 层叠样式表（Cascading Style Sheets，也就是CSS）

> 层叠样式表（CSS）使用样式表语言，描述文档的外观和格式。尽管它经常用于改变网页和使用HTML、XHTML写成的用户界面的外观，但其实这种语言可以用于任何XML文档，包括纯XML、SVG以及XUL。CSS和HTML、JavaScript一道，作为大多数网站的基石，建立具有极强视觉吸引力的页面，互联网应用界面以及大量移动应用界面。 - wikipedia.org

主要相关标准/文档：

* [Cascading Style Sheets Level 2 Revision 2 (CSS 2.2) Specification](https://drafts.csswg.org/css2/)
* [Selectors Level 3](http://www.w3.org/TR/css3-selectors/)
* [All W3C CSS Specifications](http://www.w3.org/Style/CSS/current-work#roadmap)
* [CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

##### 文档对象模型（Document Object Model，也就是DOM）

> 文档对象模型（DOM）是跨平台且与语言无关的公约，用于描述HTML、XHTML和XML文档，并与之中的对象进行交互。每个文档中的节点被组织为树状结构，被称作 DOM 树。DOM 树种的对象可以被寻址，并通过对象上的方法操纵。DOM 的公共接口由其应用程序接口（API）定义。 - wikipedia.org

主要相关标准/文档：

* [W3C DOM4](http://www.w3.org/TR/2014/WD-dom-20140204/)
* [DOM](https://dom.spec.whatwg.org/)
* [Document Object Model (DOM) Level 3 Events Specification](http://www.w3.org/TR/2013/WD-DOM-Level-3-Events-20131105/)

##### JavaScript程序语言（包括ECMAScript 6, ES6, JavaScript 2015）

> JavaScript是高层次、动态、弱类型的解释性编程语言，并通过ECMA脚本语言标准规范化。JavaScript 和 HTML、CSS 一起，成为万维网内容产品的三大基石之一。绝大部分网站都会使用这项技术，而且所有现代浏览器无需插件均可支持。JavaScript是基于原型的，函数第一的多范式语言，支持面向对象、命令式和函数式编程。它具有工作于文字、数组、日期以及正则表达式的 API，但不支持任何像是联网、存储或图像设备 I/O，主要依其宿主环境而定。 - wikipedia.org

主要相关标准/文档：

* [ECMAScript® 2015 Language Specification](http://www.ecma-international.org/ecma-262/6.0/)

##### 网络API（也就是 HTML5 和他的小伙伴们，或者浏览器API）

> 当使用JavaScript书写网络用代码的时候，有很多绝佳API可供使用。下面是当你开发你的app或网站时有可能会用到的所有界面列表。 - Mozilla

主要相关文档：

* [Web API Interfaces](https://developer.mozilla.org/en-US/docs/Web/API)

##### 超文本传输协议（Hypertext Transfer Protocol，也就是HTTP）

> 超文本传输协议（HTTP）是为分布式协作超媒体信息系统建立的应用协议。HTTP是万维网数据通信的基础。 - wikipedia.org

主要相关标准：

* [Hypertext Transfer Protocol -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)
* [Hypertext Transfer Protocol version 2 draft-ietf-httpbis-http2-16](https://tools.ietf.org/html/draft-ietf-httpbis-http2-16)

##### 统一资源定位符（Uniform Resource Locator，也就是URL）

> 统一资源定位符（URL，也被称为网址）[1][2]通过定义网络中的计算机和检索机制定位资源来引用资源。URL是统一资源标示符（Uniform resource identifier, URI）的特殊类型[3]，不过很多人将其混用[4]。URL标示访问指示资源的方法，而URI并不都是如此[4][5]。URL最常用于引用网页（http），但也用于引用文件传输（ftp）、E-mail（mailto），数据库访问（JDBC）以及其他应用。 - wikipedia.org

主要相关标准：

* [Uniform Resource Locators (URL)](http://www.w3.org/Addressing/URL/url-spec.txt)
* [URL Living Standard](https://url.spec.whatwg.org/)

##### JavaScript对象表示法（JavaScript Object Notation，也就是JSON）

> JSON，有时也被称为 JavaScript 对象表示法，是一种开放标准格式，使用属性-值对构成的人类可读文本传输数据对象。这是异步浏览器/服务器通信（AJAT）所使用的基础数据格式，广泛取代了XML（使用AJAX）。尽管JSON来源于JavaScript脚本语言，但它是与语言无关的数据格式。在很多编程语言中都有现成的解析生成JSON数据的代码。JSON格式最早由Douglas Crockford定义，现在有两个竞争标准描述，RFC 7159 和 ECMA-404。EMCA标准是最小化的，只描述了允许的语法，而RFC还提供了一些语义和安全方面的考量。JSON的官方网络媒体类型是 application/json。JSON文件的后缀名是 .json。 - wikipedia.org

主要相关标准：

* [介绍JSON](http://json.org/)
* [JSON数据交换格式](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)
* [JSON API](http://jsonapi.org/)

##### 网络内容易用性指南（Web Content Accessibility Guidelines，WCAG）和无障碍富网络应用（Accessible Rich Internet Applications，ARIA）

> 易用性指为残障人士进行的产品、设备、服务或者环设计。无障碍设计的核心是同时确保“直接访问”和“间接访问”，也就是对辅助设备的兼容（比如屏幕阅读器）。 - wikipedia.org

* [Web Accessibility Initiative (WAI)](http://www.w3.org/WAI/)
* [Web Content Accessibility Guidelines (WCAG) Current Status](http://www.w3.org/standards/techs/wcag#w3c_all)
* [Accessible Rich Internet Applications (WAI-ARIA) Current Status](http://www.w3.org/standards/techs/aria#w3c_all)


