# Spring官方Guides

随着微服务的流行，Spring Boot/Cloud的崛起，Spring Source几乎再一次要成为Java的代名词。那么我们如何才能快速的学习和入门Spring呢？除了很多国内高手编写的一些教程之外，有没有更为官方的指导呢？实际上，在Spring官方网站中是有非常优秀的教程页面的：[https://spring.io/guides。](https://spring.io/guides)

但是由于该教程内容均是英文的，所以只有少部分人会关注这里。所以，我们[SpringForAll社区](http://spring4all.com)计划开始组织对这部分高质量内容的翻译工作，以促进Spring这样优秀的框架在国内的发展！由衷的希望Spring大生态变得越来越强大！

我们的成果：http://www.spring4all.com/article/558

## 如何开始

详情请参考：[WIKI 如何开始](https://github.com/SpringForAll/spring-guides-translation/wiki)

## 协作参与

* 交流社区：[SpringForAll社区](http://spring4all.com)
* Github：[https://github.com/SpringForAll/spring-guides-translation](https://github.com/SpringForAll/spring-guides-translation)
* 组织人：[程序猿DD](https://github.com/dyc87112/)
* 管理组成员：[maskwang520](https://github.com/maskwang520)、[strongant](https://github.com/strongant)、[chenzhijun](https://github.com/chenzhijun)、[lexburner](https://github.com/lexburner)、[Jitianyu](https://github.com/Jitianyu)
* 校对组头目：[maskwang520](https://github.com/maskwang520)

### 协作流程

* [翻译和校对的流程](https://github.com/SpringForAll/spring-guides-translation/blob/master/translate-readme.md)
* [待校对的翻译](https://github.com/SpringForAll/spring-guides-translation/pulls)
* [翻译操作指南](https://github.com/SpringForAll/spring-guides-translation/blob/master/translate-step.md) 
* [校对流程指南](https://github.com/SpringForAll/spring-guides-translation/blob/master/proofread.md)

### 翻译内容

* [待翻译内容](https://github.com/SpringForAll/spring-guides-translation/tree/master/source)
* [已完成内容](https://github.com/SpringForAll/spring-guides-translation/tree/master/translated)

<!-- ### 文章状态目录

| 编号   | 标题                                       | 状态   | 译者                                       | 校对                                       |
| ---- | ---------------------------------------- | ---- | ---------------------------------------- | ---------------------------------------- |
| 1001 | [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/) | 校对完成 | [Jitianyu](https://github.com/Jitianyu)  |                                          |
| 1002 | [Scheduling Tasks](https://spring.io/guides/gs/scheduling-tasks/) | 校对完成 | [happyxiaofan](https://github.com/happyxiaofan) | [carlzhangweiwen](https://github.com/carlzhangweiwen) |
| 1003 | [Consuming a RESTful Web Service](https://spring.io/guides/gs/consuming-rest/) | 校对完成 | [hapihapidoge](https://github.com/hapihapidoge) | [maskwang](https://github.com/maskwang520) |
| 1004 | [Building Java Projects with Maven](https://spring.io/guides/gs/maven/) | 校对完成 | [liqiangatongoingdotme](https://github.com/liqiangatongoingdotme) | [william-hyx](https://github.com/william-hyx) |
| 1005 | [Accessing Relational Data using JDBC with Spring](https://spring.io/guides/gs/relational-data-access/) | 寻找校对 | [codedrinker](https://github.com/codedrinker) |                                          |
| 1006 | [Uploading Files](https://spring.io/guides/gs/uploading-files/) |      | [JustDoNow](https://github.com/JustDoNow) |                                          |
| 1007 | [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/) |      | [512013674](https://github.com/512013674) |                                          |
| 1008 | [Registering an Application with Facebook](https://spring.io/guides/gs/register-facebook-app/) |      |                                          |                                          |
| 1009 | [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/) | 校对完成 | [linzx2015](https://github.com/linzx2015) |                                          |
| 1010 | [Registering an Application with Twitter](https://spring.io/guides/gs/register-twitter-app/) |      |                                          |                                          |
| 1011 | [Messaging with RabbitMQ](https://spring.io/guides/gs/messaging-rabbitmq/) | 校对完成 | [chenzhijun](https://github.com/chenzhijun) | [程序猿DD](https://github.com/dyc87112)     |
| 1012 | [Accessing Twitter Data](https://spring.io/guides/gs/accessing-twitter/) |      |                                          |                                          |
| 1013 | [Accessing Facebook Data](https://spring.io/guides/gs/accessing-facebook/) | 校对调整 | [wangzhidong](https://github.com/wangzhidong) |                                          |
| 1014 | [Accessing Data with Neo4j](https://spring.io/guides/gs/accessing-data-neo4j/) |      |                                          |                                          |
| 1015 | [Validating Form Input](https://spring.io/guides/gs/validating-form-input/) |      | [carl-zhao](https://github.com/carl-zhao) |                                          |
| 1016 | [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/) | 正在校对 | [xyq000](https://github.com/xyq000)      | [strongant](https://github.com/strongant) |
| 1017 | [Messaging with JMS](https://spring.io/guides/gs/messaging-jms/) |      | [zivyu](https://github.com/zivyu)        |                                          |
| 1018 | [Creating a Batch Service](https://spring.io/guides/gs/batch-processing/) | 校对完成 | [cleverlzc](https://github.com/cleverlzc) | [lexburner](https://github.com/lexburner) |
| 1019 | [Securing a Web Application](https://spring.io/guides/gs/securing-web/) | 校对完成 | [徐靖峰](https://github.com/lexburner)      | [程序猿DD](https://github.com/dyc87112)     |
| 1020 | [Building a Hypermedia-Driven RESTful Web Service](https://spring.io/guides/gs/rest-hateoas/) |      |                                          |                                          |
| 1021 | [Accessing Data with GemFire](https://spring.io/guides/gs/accessing-data-gemfire/) |      |                                          |                                          |
| 1022 | [Integrating Data](https://spring.io/guides/gs/integration/) | 翻译完成 | [xuxiaoxie](https://github.com/xuxiaoxie) | [xuxiaoxie](https://github.com/xuxiaoxie)[feilangrenM](https://github.com/feilangrenM) |
| 1023 | [Caching Data with GemFire](https://spring.io/guides/gs/caching-gemfire/) |      | [liweijian199011](https://github.com/liweijian199011) |                                          |
| 1024 | [Managing Transactions](https://spring.io/guides/gs/managing-transactions/) |      |                                          |                                          |
| 1025 | [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/) |      | [lovedboy2012](https://github.com/lovedboy2012) |                                          |
| 1026 | [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/) | 校对完成 | [cholf](https://github.com/cholf)        | [cleverlzc](https://github.com/cleverlzc) |
| 1027 | [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/) |      | [dejunyu](https://github.com/dejunyu)    |                                          |
| 1028 | [Converting a Spring Boot JAR Application to a WAR](https://spring.io/guides/gs/convert-jar-to-war/) | 校对完成 | [JohnHello](https://github.com/JohnHello) |                                          |
| 1029 | [Creating Asynchronous Methods](https://spring.io/guides/gs/async-method/) | 校对完成 | [shaoshao721](https://github.com/shaoshao721) | [mrdear](https://github.com/mrdear)      |
| 1030 | [Handling Form Submission](https://spring.io/guides/gs/handling-form-submission/) |      | [zzzvvvxxxd](https://github.com/zzzvvvxxxd) |                                          |
| 1031 | [Building an Application with Spring Boot](https://spring.io/guides/gs/spring-boot/) | 校对完成 | [nycgym](https://github.com/nycgym)      | [cleverlzc](https://github.com/cleverlzc) |
| 1032 | [Using WebSocket to build an interactive web application](https://spring.io/guides/gs/messaging-stomp-websocket/) | 校对完成 | [maskwang520](https://github.com/maskwang520) | [strongant](https://github.com/strongant) |
| 1033 | [Working a Getting Started guide with STS](https://spring.io/guides/gs/sts/) | 校对完成 | [hanbin](https://github.com/hanbin)      | [cleverlzc](https://github.com/cleverlzc) |
| 1034 | [Consuming a RESTful Web Service with AngularJS](https://spring.io/guides/gs/consuming-rest-angularjs/) | 校对完成 | [yunlzheng](https://github.com/yunlzheng) | [rhwayfun](https://github.com/rhwayfun)  |
| 1035 | [Consuming a RESTful Web Service with rest.js](https://spring.io/guides/gs/consuming-rest-restjs/) |      |                                          |                                          |
| 1036 | [Consuming a RESTful Web Service with jQuery](https://spring.io/guides/gs/consuming-rest-jquery/) |      | [william-hyx](https://github.com/william-hyx) |                                          |
| 1037 | [Enabling Cross Origin Requests for a RESTful Web Service](https://spring.io/guides/gs/rest-service-cors/) |      | [yunlzheng](https://github.com/yunlzheng) |                                          |
| 1038 | [Building Spring YARN Projects with Gradle](https://spring.io/guides/gs/gradle-yarn/) | 正在校对 | [UniKrau](https://github.com/UniKrau)    | [程序猿DD](https://github.com/dyc87112)     |
| 1039 | [Building Spring YARN Projects with Maven](https://spring.io/guides/gs/maven-yarn/) | 正在校对 | [UniKrau](https://github.com/UniKrau)    | [程序猿DD](https://github.com/dyc87112)     |
| 1040 | [Simple YARN Application](https://spring.io/guides/gs/yarn-basic/) | 正在校对 | [UniKrau](https://github.com/UniKrau)    | [程序猿DD](https://github.com/dyc87112)     |
| 1041 | [Testing YARN Application](https://spring.io/guides/gs/yarn-testing/) | 正在校对 | [UniKrau](https://github.com/UniKrau)    | [程序猿DD](https://github.com/dyc87112)     |
| 1042 | [Batch YARN Application](https://spring.io/guides/gs/yarn-batch-processing/) | 正在校对 | [UniKrau](https://github.com/UniKrau)    | [程序猿DD](https://github.com/dyc87112)     |
| 1043 | [Restartable Batch YARN Application](https://spring.io/guides/gs/yarn-batch-restart/) |      | [UniKrau](https://github.com/UniKrau)    |                                          |
| 1044 | [Consuming a SOAP web service](https://spring.io/guides/gs/consuming-web-service/) | 校对完成 |                                          |                                          |
| 1045 | [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/) | 校对完成 | [strongant](https://github.com/strongant) | [maskwang](https://github.com/maskwang520) |
| 1046 | [Accessing Neo4j Data with REST](https://spring.io/guides/gs/accessing-neo4j-data-rest/) |      |                                          |                                          |
| 1047 | [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/) | 正在翻译 | [qiushile](https://github.com/qiushile)  |                                          |
| 1048 | [Accessing GemFire Data with REST](https://spring.io/guides/gs/accessing-gemfire-data-rest/) |      |                                          |                                          |
| 1049 | [Producing a SOAP web service](https://spring.io/guides/gs/producing-web-service/) | 校对完成 | [feilangrenM](https://github.com/feilangrenM) | [王嘉龙](https://github.com/zaixiandemiao)  |
| 1050 | [Simple Single Project YARN Application](https://spring.io/guides/gs/yarn-basic-single/) |      |                                          |                                          |
| 1051 | [Caching Data with Spring](https://spring.io/guides/gs/caching/) |      | [zzzvvvxxxd](https://github.com/zzzvvvxxxd) |                                          |
| 1052 | [Deploying to Cloud Foundry from STS](https://spring.io/guides/gs/sts-cloud-foundry-deployment/) |      |                                          |                                          |
| 1053 | [Spring Boot with Docker](https://spring.io/guides/gs/spring-boot-docker/) | 校对完成 | [StormMaybin](https://github.com/StormMaybin) | [carlzhangweiwen](https://github.com/carlzhangweiwen) |
| 1054 | [Working a Getting Started guide with IntelliJ IDEA](https://spring.io/guides/gs/intellij-idea/) | 校对完成 | [xiudongxu](https://github.com/xiudongxu) | [cleverlzc](https://github.com/cleverlzc) |
| 1055 | [Creating CRUD UI with Vaadin](https://spring.io/guides/gs/crud-with-vaadin/) |      |                                          |                                          |
| 1056 | [Service Registration and Discovery](https://spring.io/guides/gs/service-registration-and-discovery/) | 正在翻译 | [lovedboy2012](https://github.com/lovedboy2012) |                                          |
| 1057 | [Centralized Configuration](https://spring.io/guides/gs/centralized-configuration/) | 校对完成 | [zaixiandemiao](https://github.com/zaixiandemiao) | [胡明昊](https://github.com/hh23485)        |
| 1058 | [Routing and Filtering](https://spring.io/guides/gs/routing-and-filtering/) | 校对完成 | [hh23485](https://github.com/hh23485)    | [oshare](https://github.com/oshare)      |
| 1059 | [Circuit Breaker](https://spring.io/guides/gs/circuit-breaker/) | 校对完成 | [ligang](http://github.com/holy12345/)   | [Mr.lzc](http://github.com/cleverlzc)    |
| 1060 | [Client Side Load Balancing with Ribbon and Spring Cloud](https://spring.io/guides/gs/client-side-load-balancing/) | 寻找校对 | [holy12345](https://github.com/holy12345) |                                          |
| 1061 | [Testing the Web Layer](https://spring.io/guides/gs/testing-web/) |      |                                          |                                          |
| 1062 | [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/) |      | [pzzls](https://github.com/pzzls)        |                                          |
| 1063 | [Creating a Multi Module Project](https://spring.io/guides/gs/multi-module/) | 正在翻译 | [panhoucheng](https://github.com/panhoucheng) |                                          |
| 1064 | [Creating API Documentation with Restdocs](https://spring.io/guides/gs/testing-restdocs/) | 校对完成 | [HoldDie](https://github.com/HoldDie)    | [Jitianyu](https://github.com/Jitianyu)  |
| 2001 | [Spring Security Architecture](https://spring.io/guides/topicals/spring-security-architecture/) | 正在翻译 | [徐靖峰](https://github.com/lexburner)      | 马超君                                      |
| 3001 | [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/) | 正在校对 | [silentbalanceyh](https://github.com/silentbalanceyh) | [cleverlzc](https://github.com/cleverlzc) |
| 3002 | [Spring Security and Angular JS](https://spring.io/guides/tutorials/spring-security-and-angular-js/) |      |                                          |                                          |
| 3003 | [React.js and Spring Data REST](https://spring.io/guides/tutorials/react-and-spring-data-rest/) |      |                                          |                                          |
| 3004 | [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/) |      |                                          |                                          | -->

| 编号   | 标题                                       | 状态   | 译者                                       | 校对                                       |
| ---- | ---------------------------------------- | ---- | ---------------------------------------- | ---------------------------------------- |
| 1001 | [AngularJS+Spring Security using Basic Authentication](http://websystique.com/spring-security/angularjs-basic-authentication-using-spring-security/) |  |   |                                          |
| 1002 | [Secure Spring REST API using Basic Authentication](http://websystique.com/spring-security/secure-spring-rest-api-using-basic-authentication/) |已认领  | [新乐](https://github.com/qiushile)  |                                          |
| 1003 | [Secure Spring REST API using OAuth2](http://websystique.com/spring-security/secure-spring-rest-api-using-oauth2/) |  |   |                                          |
| 1004 | [Spring MVC 4 + Spring Security 4 + Hibernate Example](http://websystique.com/springmvc/spring-mvc-4-and-spring-security-4-integration-example/) |已认领  | [anonymous](https://github.com/wjtBird)   |                                          |
| 1005 | [spring-security-4-custom-login-form-annotation-example](http://websystique.com/spring-security/spring-security-4-custom-login-form-annotation-example/) |  |   |                                          |
| 1006 | [Spring Security 4 Hello World Annotation+XML Example](http://websystique.com/spring-security/spring-security-4-hello-world-annotation-xml-example/) |  |   |                                          |
| 1007 | [Spring Security 4 Hibernate Integration Annotation+XML Example](http://websystique.com/spring-security/spring-security-4-hibernate-annotation-example/) |  |   |                                          |
| 1008 | [Spring Security 4 Hibernate Role Based Login Example](http://websystique.com/spring-security/spring-security-4-hibernate-role-based-login-example/) |  |   |                                          |
| 1009 | [Spring Security 4 Logout Example](http://websystique.com/spring-security/spring-security-4-logout-example/) | 已认领  | [FraserYu](https://github.com/FraserYu)  |                                          |
| 1010 | [Spring Security 4 Method security using @PreAuthorize,@PostAuthorize, @Secured, EL](http://websystique.com/spring-security/spring-security-4-method-security-using-preauthorize-postauthorize-secured-el/) |  |   |                                          |
| 1011 | [Spring Security 4 Hibernate Password Encoder Bcrypt Example](http://websystique.com/spring-security/spring-security-4-password-encoder-bcrypt-example-with-hibernate/) |  |   |                                          |
| 1012 | [Spring Security 4 Remember Me Example with Hibernate](http://websystique.com/spring-security/spring-security-4-remember-me-example-with-hibernate/) |  |   |                                          |
| 1013 | [Spring Security 4 Role Based Login Example](http://websystique.com/spring-security/spring-security-4-role-based-login-example/) |  |   |                                          |
| 1014 | [Spring Security 4 Secure View Fragments using taglibs](http://websystique.com/spring-security/spring-security-4-secure-view-layer-using-taglibs/) |  |   |                                          |

## 翻译规范

关于翻译的一些规范如下：

* 翻前必看：**一些专业名词列表：[Term List](https://github.com/SpringForAll/spring-guides-translation/blob/master/term-list.md)**

* 翻译文件格式：markdown

* 文件名格式：原文标题.md （文件已经预创建，直接编辑即可）

* 文章摘要部分采用如下的固定格式：（已经预创建，请勿删除该部分）

  > 原文：\[Securing a Web Application\]\([https://spring.io/guides/gs/securing-web/\](https://spring.io/guides/gs/securing-web/%29\)
  >
  > 译者：\[xxx\]\(\)
  >
  > 校对：\[yyy\]\(\)

* 文章末尾使用统一的版权声明：（已经预创建，请勿删除该部分）
  > 本文由spring4all.com翻译小分队创作，采用\[知识共享-署名-非商业性使用-相同方式共享 4.0 国际 许可\]\([http://creativecommons.org/licenses/by-nc-sa/4.0/\)协议进行许可。](http://creativecommons.org/licenses/by-nc-sa/4.0/%29协议进行许可。)

* 正文标题按层次结构 从 \#\# 开始

* 代码片段\`\`\`之后需要写明语言类型

* 如有图片更静态资源保存在static目录下，每篇文章建立自己的目录存储（目录名使用文章编号，文章编号见README）

* 文章锚点的跳转处理，不要跳转到英文原文，而应该采用文章内部锚点的跳转，在Markdown中的实现示例：假设有一个链接`xxx`是跳转到标题`Gradle`的，那么链接和标题需要下面这样写：
  * 链接这样写 ：`[xxx](#maodian)`
  * 要跳转到的标题这样写：`<h2 id="maodian">Gradle</h2>` ， 不能用传统的写法：`## Gradle`

* 标题、正文、段落、代码段、摘要等大块内容之间都应该空一行。比如：标题与正文之间空一行，段落与段落之间空一行，代码段前后空一行等。

* 文中出现的链接直接以Markdown的链接形式处理，不要采用论文的标注形式

* 对于一些常规段落，比如：`What you’ll need`部分，可以参考已翻译完的文章内容，有差异部分做一些小修改即可

* 正文中的短代码片段使用\`\` 标注，比如：\`@Controller\`

* 尊重原作、不修改、不删减内容

* 每篇文章翻译完成之后提交PR，并在翻译交流群中找校对人员完成review，最后由管理员完成Merge

* 若译者与校对有不同建议，可以将争议部分发到交流群中一起讨论确定结果

## 致谢

将最诚挚的谢意给SpringForAll社区每一位翻译小队成员，他们都是Spring的忠实爱好者，这里的所有内容都是他们牺牲了业余时间所创造出来的。

下面是所有参与翻译与校对的小伙伴名单（排名不分先后）：

* 待补充

## License

本站作品由SpringForAll翻译小分队创作，采用[知识共享-署名-非商业性使用-相同方式共享 4.0 国际 许可](http://creativecommons.org/licenses/by-nc-sa/4.0/)协议进行许可。

