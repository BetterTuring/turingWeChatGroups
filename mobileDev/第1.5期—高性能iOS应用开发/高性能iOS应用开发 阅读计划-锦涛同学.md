#《高性能iOS应用开发》阅读计划

——图灵移动开发群阅读计划（第 1.5 期）

<br>


#####领读人：锦涛同学 —> hejintao@outlook.com  
微信ID：hjt13980073267

#####本书特点

- 为iOS开发者提供常见性能问题的解决方案 

#####适合读者

- 具有一定iOS开发经验的人群、想了解移动应用开发性能优化的人群

##### 总阅读时长：3周

##### 每天阅读时间：2小时

##### 答疑时间安排：每周一次，每周六晚移动开发群 20:00—22:00

##### 图灵社区本书网址：[《高性能iOS应用开发》](http://www.ituring.com.cn/book/1924)   

##### 图灵阅读计划GitHub网址：[图灵阅读计划](https://github.com/BetterTuring/turingWeChatGroups) 

##### 本书阅读打卡小程序

<img src="http://file.ituring.com.cn/Original/17094c3e737332bba5d5" Width="220" style = "margin: 10px 100px" />




> 前言：作为一名iOS开发者，我们该如何开发出一款高性能的iOS应用呢？上图：

<img src="http://upload-images.jianshu.io/upload_images/1389022-fd0be7cef33b5b9e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" width="600" / >



## 阅读计划 

<div style="margin-top:15px"></div>  

### 阅读时间安排

<div style="margin-top:15px"></div>  


| 需要阅读的章节        | 所需时间   |  大致内容  |
| --------   | -----:  | :----:  |
| 移动应用的性能     | 2小时 |   iOS开发中的如何定义高性能和性能指标     |
| 内存管理        |   8小时   |   内存消耗、ARC、僵尸对象、循环引用....  |
| 能耗        |    1小时   |  CPU、网络、定位和GPS  |
| 并发编程        |    8小时    |  线程、GCD、队列、线程安全  |
| 应用的生命周期        |    1小时    |  冷热启动、首次启动、升级后启动、通知、后台拉去...  |
| 用户界面       |   2小时   |  视图加载、视图层级、自动布局、iOS 8 新特性...  |
| 网络        |   4小时   |  指标和测量、应用部署、工具（如Charles）  |
| 数据共享        |   1小时   |  深层链接、剪贴板、共享内容、iOS 8 扩展  |
| 应用安全        |   3小时   |  应用访问、网络安全、本地存储、数据共享、安全和应用性能...  |
| 测试及发布        |   1小时   |  测试类型、单元测试、功能测试...  |
| 工具        |   2小时   |  Accessibility Inspector、Instruments、Xcode视图调试器、PonyDebugger、Charles  |
| 埋点与分析        |   1小时   |  埋点、分析、真实用户监控  |
| iOS 9       |   1小时   |  应用生命周期、用户界面、扩展、应用瘦身  |
| iOS 10       |   1小时   |  Siri扩展、改进的通知、iMessage扩展、VoIP支持  |



<div style="margin-top:25px"></div>  


## 第一部分  开始

<div style="margin-top:15px"></div>  

### 第 1 章  移动应用的性能

##### 建议阅读时长：2小时

#### 内容概要

主要讲解如何定义移动开发的性能指标，以及被定义出来的有哪些性能指标，如内存、电量消耗、初始化时间、响应速度等等。

#### 重点

- 性能指标
- 采样、应用埋点
- 日志


<img src="http://upload-images.jianshu.io/upload_images/1389022-f523f2968e24cc63.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" style = "width:150px; margin: 10px 100px">


<div style="margin-top:25px"></div>  


## 第二部分  核心优化

<div style="margin-top:15px"></div>  

### 第 2 章  内存管理

##### 建议阅读时长：3.5小时

####内容概要

主要讲解 iPhone 和 iPad 上内存管理的相关知识，包括内存消耗、内存管理（自动引用计数、自动释放池...）、僵尸对象等。

#### 重点

- 内存消耗
- 自动释放池、自动引用计数
- 僵尸对象
- 循环引用

#### 补充 

针对内存管理这一块还可以阅读 [《Objective-C高级编程》](http://www.ituring.com.cn/book/1023) 以及这篇文章 [“iOS内存管理”](http://www.jianshu.com/p/8b1ed04b3ba9)

<div style="margin-top:20px"></div> 

### 第 3 章  能耗

##### 建议阅读时长：1小时

#### 内容概要

主要讲解CPU、网络、地图、屏幕等相关知识。

#### 重点

- CPU
- 网络
- 地图
- 其他硬件

<div style="margin-top:20px"></div> 

### 第 4 章  并发编程

#####建议阅读时长：3.5小时

####内容概要

主要讲解开发中的线程、GCD、队列、线程安全这一块的内容。

#### 重点

- 线程、线程安全
- GCD
- 队列

#### 补充

针对线程和GCD（宏中心派发）这一块还可以阅读 [《Objective-C高级编程》](http://www.ituring.com.cn/book/1023)

<img src="http://upload-images.jianshu.io/upload_images/1389022-799ab6bd73ba6e3b.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240"  style = "width:150px; margin: 10px 100px">


<div style="margin-top:25px"></div>  


## 第三部分 iOS性能

<div style="margin-top:15px"></div> 

### 第 5 章  应用的生命周期

##### 建议阅读时长：2小时

##### 内容概要

主要讲解如应用的启动（冷启动、热启动、首次启动、升级后启动）、推送、后台拉取这一块知识。

#### 重点

- 冷启动、热启动、首次启动、升级后启动
- 推送
- 后台拉取

<div style="margin-top:20px"></div> 

### 第 6 章  用户界面

##### 建议阅读时长：1.5小时

##### 内容概要

主要讲解视图控制器的加载、层级、可见性还有 UIView 下的一些组件以及自动布局等内容。

#### 重点

- 视图加载、层级、可见性
- UIView 下的一些重要组件
- 自动布局、屏幕尺寸类型

#### 补充

- 自动布局参考书籍：[《iOS Auto Layout开发秘籍（第2版）》](https://www.amazon.cn/图书/dp/B00R4AG4CW/ref=sr_1_1?ie=UTF8&qid=1503991359&sr=8-1&keywords=autolayout)
- 视图层级：[视图加载、层级、可见性](http://blog.csdn.net/jiisd/article/details/43982663)

<div style="margin-top:20px"></div> 

### 第 7 章  网络

##### 建议阅读时长：1.5小时

#### 内容概要

主要讲解移动开发中网络的相关知识，如 DNS 查找时间、SSL 握手时间、网络延迟、服务器、数据请求以及数据格式等。

#### 重点

- DNS查找时间、SSL握手时间、网络延迟、网络类型
- 服务器、请求、数据格式
- Charles

<div style="margin-top:20px"></div> 

### 第 8 章  数据共享

##### 建议阅读时长：1.5小时

##### 内容概要

主要讲解iOS App 开发中的深层链接、剪贴板、共享内容、iOS 8 扩展。

#### 重点

- 深层链接
- 剪贴板
- 共享内容
- iOS 8 扩展（配置操作扩展、共享扩展）

<div style="margin-top:20px"></div> 

### 第 9 章  安全

##### 建议阅读时长：1小时

####内容概要

主要讲解iOS App 开发中的涉及的安全问题，如应用访问、网络安全、本地存储、数据的共享以及安全和应用的性能问题。

#### 重点

- 应用访问（匿名访问、认证访问）
- 网络安全
- 本地存储
- 数据共享

#### 补充

[本地存储](http://www.jianshu.com/p/cd475693e2f8)


<div style="margin-top:25px"></div>  


## 第四部分  代码之外

<div style="margin-top:15px"></div> 

### 第 10 章  测试和发布

#### 建议阅读时长：1小时

####内容概要

测试一项功能、一个组件或一个应用与实现它同样重要

#### 重点

- 测试类型
- 单元测试
- 功能测试
- 持续集成与自动化

#### 补充

[持续集成与自动化](http://blog.csdn.net/u013602835/article/details/54632843)


<div style="margin-top:20px"></div> 

### 第 11 章  工具

##### 建议阅读时长：1.5小时

####内容概要

介绍iOS开发中一些常用的调试工具，如 Instruments、Charles、Xcode 视图调试器等

#### 重点

- Instruments介绍与使用

  ![](http://upload-images.jianshu.io/upload_images/1389022-4ecef222ba6e6a38.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- Charles使用

  <img src="http://upload-images.jianshu.io/upload_images/1389022-703f3164b55f8b46.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" width="400" />


- Xcode视图调试器  

  <img src="http://upload-images.jianshu.io/upload_images/1389022-24066115b0c0a064.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" width="400" />



#### 补充

- [Instruments使用](http://www.jianshu.com/p/d0e149332380)
- [Charles使用](http://www.jianshu.com/p/fdd7c681929c)

<div style="margin-top:20px"></div> 

### 第 12 章  埋点与分析

##### 建议阅读时长：1.5小时

####内容概要

  <img src="http://upload-images.jianshu.io/upload_images/1389022-877e4d718eeda6e2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" width="400" style = "margin: 10px 40px" />


应用发布后，通过收集多个设备和地理位置的真实数据，帮助明确用户的使用模式和需要调整的各种场景。

#### 重点

- 埋点
- 分析
- 真实用户监控

#### 补充

可以借助的第三方平台：[友盟](https://www.umeng.com/)、[OneAPM](https://www.oneapm.com/)、[Bugly](https://bugly.qq.com/v2/)


<div style="margin-top:25px"></div>  


## 第五部分  iOS 9 和 iOS 10

<div style="margin-top:15px"></div> 


### 第 13 章  iOS 9

##### 建议阅读时长：1小时

####内容概要

主要介绍iOS 9的一些新功能。

#### 重点

- 通用链接
- 扩展
- 应用瘦身


#### 补充

通用链接介绍：[通用链接](https://developer.apple.com/library/content/documentation/General/Conceptual/AppSearch/UniversalLinks.html#//apple_ref/doc/uid/TP40016308-CH12-SW2)

<div style="margin-top:20px"></div> 


### 第 14 章  iOS 10


#####建议阅读时长：1小时

#### 内容概要

主要介绍 iOS 10 的一些新功能。

####重点

- Siri的扩展
- 通知的改进
- iMessage扩展
- VoIP支持

<img src="http://upload-images.jianshu.io/upload_images/1389022-d673d6d92f29075a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" style = "width:150px; margin: 10px 100px"/>
