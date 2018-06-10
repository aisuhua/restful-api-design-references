之所以创建这个 [repository](https://github.com/aisuhua/restful-api-design-references)，是因为我希望收集一些比较好的有关于 RESTful API 设计的参考文献。偶尔回顾，偶尔改进，大家一起来吧~ 

如果你有更好的私藏文章，不凡分享出来，独乐乐不如众乐乐，**(⊙o⊙)**

#### RESTful 介绍及设计思路 ####

 1. [Principles of good RESTful API Design][1]（译：[好 RESTful API 的设计原则][2] ）简单易懂，条理清晰，推荐
 2. [Best Practices for Designing a Pragmatic RESTful API][3]（译：[RESTful 最佳实践][4] [译文2][5]）有实际的案例 [Enchant][6]
 3. [HTTP API Design Guide][7]（译：[HTTP API 设计指南][8]）
 4. [Some REST best practices][9] 
 5. [理解 RESTful 架构][10] - 阮一峰 简单了解什么是 RESTFul 
 6. [RESTful API 设计指南][11] - 阮一峰 
 7. [Restful API 的设计规范][12] 实战经验的总结，具有较强的启发意义
 8. [撰写安全合格的REST API][13] 利用好 HTTP 协议所具备的特征
 9. [Web 服务编程，REST 与 SOAP][14] REST 与传统的面向服务的接口设计的区别，启发性强
 10. [最佳实践：更好的设计你的 REST API][15] 了解 REST 实现缓存的过程
 11. [Thoughts on RESTful API Design][16]
 12. [REST API Tutorial][17] 全方位介绍 REST
 13. [HTTP 接口设计指北][18]
 14. [Web API Design][19] 接口就是开发人员提供的“界面”，用户体验在接口设计上同样重要，在线查看 [2012 版][20]、[2013 版][21]
 15. [架构风格与基于网络应用软件的架构设计][49] 原汁原味的博士论文，由李锟翻译，有经验的同学可以挑战一下
 16. [Microsoft REST API Guidelines][50] 微软官方的 REST API 设计指南，值得参考

#### 知识碎片 ####

 1. [理解 HTTP 幂等性][23] 讲得很清楚，推荐
 2. [浅析远程过程调用 RPC][24] 告诉你什么是 RPC
 3. [httpstatuses][25] 一眼看完所有常用的 HTTP 状态码，还可以看详细含义
 3. [List of HTTP status codes](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes) From Wikipedia
 3. [HTTP Status Codes](https://msdn.microsoft.com/en-us/library/windows/desktop/aa384325(v=vs.85).aspx) From MSDN Microsoft
 3. [List of HTTP header fields](https://en.wikipedia.org/wiki/List_of_HTTP_header_fields)
 4. [json-api][26] 对 API 应该如何利用好 JSON 的一些建议
 5. [介绍 JSON][27] 无论如何都应该读一遍
 6. [decision-graph.svg][28] 一张大图展示整个 REST API 的验证过程，及各种状态码出现的时机

#### 书籍 ####

 1. [RESTful Web APIs][29] 较新的一本书，对 REST 做了很多系统性的总结，尤其对“超媒体”作了详细的介绍
 2. [Jersey-2.x-User-Guide][30]（译：Jersey 2.x 用户指南）译者也提供了入门简易教程 [REST 实战][31]以及综合实例 [RestDemo][32]*（注：读者需要 Java 基础）*
 3. [REST CookBook][33] 基础介绍构建 RESTful API

#### 例子 ####

 1. [Github API v3][34] 被很多人参考和引用，比如对分页的处理方法、接口版本的设计等等
 2. [Mailgun Documentation][35] 邮件服务 REST API 
 3. [Enchant REST API][36]
 4. [Coinbase][37] API 设计的挺好的，包括官网提供的接口客户端，都是具有参考意义的
 5. [OpenNMS Wiki ReST API][38]
 6. [REST API 使用详解][51] Lean Cloud 中讲解 REST API 的使用，还集成 [Swagger UI](https://swagger.io/swagger-ui/) 在线调试工具，[点击查看](https://leancloud.cn/dashboard/apionline/index.html)。

关于例子，实在是太多了，在有时间的时候，多观察别人的设计，有利于写出好的 API。

#### 调试工具 ####

 1. [DHC (aka Dev HTTP Client)][39] Chrome 插件，简单易用，可分类管理，界面友好。也很多人推荐 [Postman][40]
 2. [Fiddler2][41] 抓包，捕捉每一次 REST 请求和响应的详细内容

#### 文档制作 ####

 1. [slate][42] 创建的 API 文档很好看，也很实用，三列式，目录、调用说明和代码示例同屏滚动显示。
 2. [i5ting_ztree_toc API][43] 把 Markdown 文档生成简单的 HTML API

#### 代码高亮 ####

1. [highlight.js][44] 无需指定代码是什么语言，直接按 TAB 键搞掂，它会自动检测高亮
2. [PrismJS][45] 高亮效果挺好看的

这方面的工具很多，可以自己在网上找找，找一款适合自己的就可以，毕竟只是工具，能达到目的就好。

#### 社区 ####

 1. [API Craft Google Group][46] 有梯子才行
 2. [RESTful - 知乎][47] 我也有作答~~

#### 其他 ####
 1. [MarkdownPad2][48] Windows 下使用 Markdown 语法编写文档。等习惯了它的语法，可以直接使用任何一款文本编辑器直接写了


  [1]: http://codeplanet.io/principles-good-restful-api-design/
  [2]: http://www.cnblogs.com/moonz-wu/p/4211626.html
  [3]: http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api
  [4]: http://blog.jobbole.com/41233
  [5]: http://www.oschina.net/translate/best-practices-for-a-pragmatic-restful-api
  [6]: http://dev.enchant.com/api/v1
  [7]: https://github.com/interagent/http-api-design
  [8]: https://github.com/cocoajin/http-api-design-ZH_CN
  [9]: https://bourgeois.me/rest/
  [10]: http://www.ruanyifeng.com/blog/2011/09/restful.html
  [11]: http://www.ruanyifeng.com/blog/2014/05/restful_api.html
  [12]: http://novoland.github.io/%E8%AE%BE%E8%AE%A1/2015/08/17/Restful%20API%20%E7%9A%84%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83.html
  [13]: https://zhuanlan.zhihu.com/p/20034107
  [14]: https://www.ibm.com/developerworks/cn/webservices/0907_rest_soap/
  [15]: http://www.ibm.com/developerworks/cn/web/1103_chenyan_restapi/
  [16]: https://restful-api-design.readthedocs.org/en/latest/
  [17]: http://www.restapitutorial.com/
  [18]: https://github.com/bolasblack/http-api-guide
  [19]: https://pages.apigee.com/web-api-design-website-h-ebook-registration.html
  [20]: https://pages.apigee.com/rs/apigee/images/api-design-ebook-2012-03.pdf
  [21]: https://pages.apigee.com/rs/351-WXY-166/images/ebook-2013-03-wad.pdf
  [22]: http://apigee.com/
  [23]: http://www.cnblogs.com/weidagang2046/archive/2011/06/04/2063696.html
  [24]: http://www.cppblog.com/jb8164/archive/2008/08/15/58949.html
  [25]: https://httpstatuses.com/
  [26]: http://jsonapi.org/
  [27]: http://www.json.org/json-zh.html
  [28]: http://clojure-liberator.github.io/liberator/doc/decisions.html
  [29]: http://www.amazon.cn/RESTful-Web-APIs%E4%B8%AD%E6%96%87%E7%89%88-%E4%BC%A6%E7%BA%B3%E5%BE%B7%C2%B7%E7%90%86%E6%9F%A5%E5%BE%B7%E6%A3%AE/dp/B00KWGEI64/
  [30]: https://jersey.java.net/documentation/latest/user-guide.html
  [31]: https://waylau.gitbooks.io/rest-in-action/content/
  [32]: https://github.com/waylau/RestDemo
  [33]: http://restcookbook.com/
  [34]: https://developer.github.com/v3/
  [35]: https://documentation.mailgun.com/
  [36]: http://dev.enchant.com/api/v1
  [37]: https://developers.coinbase.com/api/v2
  [38]: http://www.opennms.org/wiki/
  [39]: https://www.sprintapi.com/dhcs.html
  [40]: https://www.getpostman.com/
  [41]: http://www.telerik.com/fiddler
  [42]: https://github.com/tripit/slate
  [43]: https://github.com/i5ting/i5ting_ztree_toc
  [44]: https://highlightjs.org/
  [45]: https://github.com/PrismJS/prism
  [46]: https://groups.google.com/forum/?fromgroups#!forum/api-craft
  [47]: http://www.zhihu.com/topic/19579308/top-answers
  [48]: http://markdownpad.com/
  [49]: http://yuedu.baidu.com/ebook/780324fbf121dd36a32d8269
  [50]: https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md
  [51]: https://leancloud.cn/docs/rest_api.html
