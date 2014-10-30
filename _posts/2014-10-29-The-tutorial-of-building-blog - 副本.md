---
layout: post
category: Jekyll
title: 基于Jekyll和github的个人博客搭建经历
tagline: by zmz
tags: [Jekyll, github]
---

本博客主要是分享小z在搭建个人博客过程中一些的经历。小z是菜鸟一枚，在搭建博客的过程中走了一些弯路，当然也积累了一些经验，就此写在这里，希望本文对那些想搭建基于Jeykll和github个人博客的人们有所帮助，谢谢。

<!--more-->

## 1. [Jekyll](http://jekyllcn.com/)

[Jekyll](http://jekyllcn.com/)是用来生成静态网页的一个工具。我们可以使用[markdown](http://baike.baidu.com/view/2311114.htm)语言来书写博客，但最终我们的博客是要通过浏览器来阅读的，那博客是怎么变为网页的呢？这就是Jekyll完成的任务。但是Jekyll会有自己的目录结构，下边我们会提到。好了，对于Jekyll大家了解这么多足足足以^_^

##2. [Github](https://github.com/)和Git

[Github](https://github.com/)是一个著名的开源代码库和分布式版本控制系统，其作者就是大名鼎鼎的[Linus Torvalds](http://baike.baidu.com/view/117611.htm?fromtitle=Linus+Torvalds&fromid=9336769&type=syn)——Linux操作系统的创始人。大多数人可能不懂“版本控制”，其实大家无需了解这一**程序员世界**的名词，只知道我们的网站存放在Github上就可以了。此外，存放在Github上的东西别人是可以免费下载的，除非你花钱，创建一个私人库，否则就是公共的，这就是开源的理念。

### 2.1 申请Github帐号

Github帐号的申请过程这里就不说了，登陆[Github官网](https://github.com/)申请就可以了。我想大家都能搞得定（什么？？你不会？？好吧，孩子，洗洗睡吧。）

### 2.2 安装Git
虽然可以通过浏览器在Github上进行简单的操作，比如创建和修改文件，但是对于Github的操作远远不止这些，而且，我们在写博客的时候，通常先会在本地书写和调试，等内容和排版都在本地完成后才会提交到网上，所有这些操作都需要使用到一个工具——[Git](http://baike.baidu.com/subview/1531489/12032478.htm?fr=aladdin)。对于Git的简单使用推荐参考[这里](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000),作者对Git进行了简单而又详细地讲解（如果你有钱，而且感觉该Git教程对你有帮助，可以资助作者哦^_^）l。

由于小z平时在windows玩耍，所以Git也是安装的windows版本。下载链接以及安装过程可以参考上述[教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137396287703354d8c6c01c904c7d9ff056ae23da865a000)（什么？你又不会？还能不能愉快的玩耍了:)）。

好了，到这里，小z假定你已经有了Github的帐号，并且成功安装了Git工具。我们离成功进了一小步——只要：进步，就是好的。

小z的Github帐号是：**DutZMZ**，下面会以该帐号讲解。

##安装Ruby
[Ruby](http://baike.baidu.com/subview/45135/5977034.htm?fr=aladdin)是一种面向对象的脚本语言，小z对该语言完全不懂，但不碍事，我们不需要对Ruby了解那么多，只要按步骤把Ruby的开发平台安上就可以了。

（未完，待续。。。）

