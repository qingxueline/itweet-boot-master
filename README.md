## Itweet-boot
itweet.cn 个人网站系统

![itweet-boot](https://github.com/itweet/itweet-boot/raw/master/images/dribbble.gif)

> Itweet-boot 英文含义推文，博客,我很早就以itweet.cn写博客，使用过hexo等很多优秀的静态博客系统，但是始终
> 找不到一款我自己合心意的博客系统，所以就诞生了itweet-boot项目。

`Itweet-boot`使用高效率Web开发框架spring boot开发，默认支持多主题，可以随便扩展新的主题，后台暂时不支持多主题，如果觉得项
目不错，请献出你的[Star](https://github.com/itweet/itweet-boot/stargazers)以示支持.

整个网站系统，使用非常简洁的设计元素，黑白灰三色构成，艺术感十足。

演示站点：http://www.skynetx.org

## 特性

+ 大道至简,设计感十足
+ Markdown 文章发布
+ 支持多主题，方便扩展
+ 支持图片上传
+ 支持完整的权限管理
+ 支持文章管理
+ 支持教程管理
+ 支持素材管理
+ 支持标签管理
+ 支持类别管理
+ 功能模块化可插拔
+ 简洁高效扩展模块

## 少废话，先看东西

![itweet1.png](https://github.com/itweet/itweet-boot/raw/master/images/itweet1.png)
![itweet2.png](https://github.com/itweet/itweet-boot/raw/master/images/itweet2.png)
![itweet3.png](https://github.com/itweet/itweet-boot/raw/master/images/itweet3.png)
![itweet4.png](https://github.com/itweet/itweet-boot/raw/master/images/itweet4.png)
![itweet5.png](https://github.com/itweet/itweet-boot/raw/master/images/itweet5.png)
![blog1.png](https://github.com/itweet/itweet-boot/raw/master/images/blog1.png)
![blog2.png](https://github.com/itweet/itweet-boot/raw/master/images/blog2.png)

![m1.png](https://github.com/itweet/itweet-boot/raw/master/images/m1.png)
![m2.png](https://github.com/itweet/itweet-boot/raw/master/images/m2.png)


## 感谢

+ [spring-boot](https://projects.spring.io/spring-boot)
+ [itdeer](https://github.com/itdeer)

版权
---
 - 原创文章，转载请注明： 转载自[whoami](http://www.itweet.cn)的博客 
 - `本博客的文章集合:` http://www.itweet.cn/archives/
 
 
快速启动itweet-boot

    通过IDEA导入Maven项目，然后修改application.properties文件中的db连接信息。
    进入ItweetBootApplication，右键Run “ItweetBootApplication”运行,首次运行需要联网下载很多package。
    通过http://localhost:8080/admin/system/main 访问后台 用户名：root 密码：123456
    登录成功之后，新增加至少4篇文章和4篇推文内容，然后访问http://localhost:8080/ 访问前端页面
    前端页面滚动图片，需要在后台素材管理模块上传类型为首页的4张720*320规格的图片。

