# LPython
## 什么是LPython
> LPython是用于汇总与Python有关的热点资讯，技术博客，经典案例，学习视频在技术上的实现，在实现上，会包括，分布式爬虫,Android，微信小程序，一同来实现构建这样一个多端实时同步的系统，但是目前，不包括IOS，和WEB端。
## LPython会如何实现
* lPython目前实现的
  * [LPython-Distributed-Spider分布式数据采集实现](https://github.com/BruceJu/LPython_Spider)
  * [LPython-LeanCloud-server后端实现](http://example.com)
  * [LPython-MiniPrgram-小程序实现](https://github.com/BruceJu/LPython_MinProgram)
  * [LPython-Android端实现](https://github.com/BruceJu/LPython_Android)
##  LPython不足
* LPython目前不包括
  * 目前不包括Web端
  * 也不包括IOS端
  * 不是专业的设计可能在页面设计上无法做到统一  
### 为什么没有Web端
> 虽然Web端可以用 'Django' 来实现，但是目前，搭建网站前端的技术我还没有完全掌握，特别是JS，所以对于我来说，还不能实现这样的一个综合的Web站，所以很抱歉，LPython目前还不包括Web端
### 为什么没有IOS端
> 没有IOS端，是因为，个人没有接触郭IOS的开发，所以，不具备IOS端的能力，也不准备去学习，嘻嘻，所以对于我个人来讲LPython不会实现IOS端。

  
## LPython数据源


> 模块定义
 * 文章：包含Python的文章列表
 * 视频: 包含Python的视频
 * 招聘信息:包含Python的招聘信息
 

### 模块数据集

> 文章模块


* 数据来源
  * [伯乐在线](http://python.jobbole.com/all-posts/)
  * [CSDN](http://blog.csdn.net/)
  * [简书](https://www.jianshu.com/search?q=Python)
  * [头条](https://www.toutiao.com/search/?keyword=Python)

> 视频模块

  * [头条Python视频](https://www.toutiao.com/search_content/?offset=0&format=json&keyword=Python&autoload=true&count=20&cur_tab=2&from=video)

> 招聘信息
 
* [拉钩Python招聘](https://www.lagou.com/jobs/list_python?labelWords=sug&fromSearch=true&suginput=py)
* [智联招聘信息](http://sou.zhaopin.com/jobs/searchresult.ashx?jl=%E5%8C%97%E4%BA%AC&kw=Python&sm=0&p=1)

>数据获取方式

  * 单机爬虫(200条以内的数据)
  * 分布式爬虫(20000条一下的数据) 
  *  抓取API进行访问
 


