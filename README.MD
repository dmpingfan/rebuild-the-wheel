﻿# Rebuild the wheel

创建这个仓库主要是打算看一些经典的开源项目，然后根据自己的理解重新造一个相似的 but 是自己写的轮子.

看的思路是先看一下源码，基本上了解源码的框架和思路之后，根据理解的思路自己去重写。

<br/>

***

### 已经做了的项目有：

#### 1. WebBench

    Webbench是一个在linux下使用的网站压测工具。
    
    它使用fork()模拟多个客户端同时访问我们设定的URL，测试网站在压力下工作的性能。
    
    最多可以模拟3万个并发连接去测试网站的负载能力,个人感觉要比Apache自带的ab压力测试工具好。

#### 2. tinyhttp

    tinyhttp是一个简单的web服务器，实现了web服务器的基本原理。
    
    代码全部使用C语言开发，阅读代码，可以了解web服务器的基本原理。

#### 3. cjson

    cjson的源码大约1000行左右，用C语言实现了一个json的解析器。
    
    c语言没有字典或key-value这样的数据结构，
    
    所以如果用c来处理json，必须需要自己定义数据结构来处理

    这就需要设计一个合理的数据结构来干这个事情了，想想都是一个很激动的事情。

### 3. muduo 

    一个非常优秀的c++网络库，很值得学习。

    https://github.com/zhaozhengcoder/muduo



### To-Do：

### 1. stl

    sgi-stl

    侯捷《stl源码剖析》

    参考1 ： https://zcheng.ren/
    
    参考2 ： http://www.cnblogs.com/lfsblack/archive/2012/11/10/2764334.html


### 2. libevent


