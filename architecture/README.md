#video crawler

有关抓取视频资源的简要说明

##数据库设计

###注册表

确保抓取工具已验证。
包括， 

###规则表

关于xpath / jsonpath的规则 

###过滤表

使用redis或no-sql。
bloomfilter重复网址


### Crawl Urls表

start_urls

##履带式模块设计

这个项目的主要部分。
include，**代理模块，url manager模块，请求模块，
解析模块和下载模块等。**

###代理模块

避免ip禁止

###请求/抓取模块

通过请求队列控制请求优先级

include，**调度程序模块，多线程下载模块，请求队列模块**

### PraseWeb模块

解析web html / json / xml。

如果以下是** True **，请将下一个url返回到** UrlManager模块**

###下载模块

远程下载视频，
细分的方式

### UrlManager模块

管理发送队列

##功能扩展设计

###基本队列插件

### Selenium插件

###下载Pulgin

### CookiesPool插件
