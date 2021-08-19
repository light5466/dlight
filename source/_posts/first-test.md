---
title: first-test
date: 2021-08-17 14:22:41
tags:
	- 导航
	- 分享
categories: 前端
---

# 第一篇文章
## hexo的安装
	一个博客肯定要单独的放在一个文件下，所以我们可以新建一个空的文件夹，以后用来单独存放博客的内容
在新建的文件夹下，需要安装一下hexo，安装hexo前需要提前安装git以及node
	检查是否安装了git和node ，可以在电脑终端执行以下命令查看(cmd)
<!-- more -->

``` bash
$ node --version
```
如果出现版本号，说明安装成功，没有则去官网：https://nodejs.org/zh-cn/
``` bash
$ git --version
```
同理，出现版本号则为安装成功，没有则去官网：https://git-scm.com/download/win(会自动下载好)
安装好上面的node和git之后，就可以安装hexo了
## npm安装hexo
``` bash
$ npm install -g hexo-cli
$ hexo init
```
等待安装完成之后，当前目录下就会出现安装好的hexo的文件，
``` bash
.
├── _config.yml 网站配置文件
├── package.json 包说明文件
├── scaffolds 文章模板目录
├── source 源码目录
| ├── _drafts 草稿文章目录
| └── _posts 发布文章目录
└── themes 主题目录
```