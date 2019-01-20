---
layout:		post
title:		The sources of ruby gem
subtitle:	源
date:		2019-1-20
author:		LaiJM
head-img:	img/spider.jpg
catalog:	true
tag:		
    -Tips
---

##Linux安装Jekyll

首先是

`sudo apt-get install ruby ruby-dev`

安装完后输入`gem -v`,如果有以下报错

`var/lib/gems/1.9.1/gems/execjs-2.5.2/lib/execjs/runtimes.rb:48:in autodetect: Could not find a JavaScript runtime. See https://github.com/rails/execjs for a list of available runtimes. (ExecJS::RuntimeUnavailable) `

则需安装nodejs

`sudo apt-get install nodejs`

输入`gem -v`出现版本号时即安装成功

安装完后可以更改为国内源以获得更快的速度。

一开始找到的网站是[淘宝源](https://ruby.taobao.org/ "https://ruby.taobao.org").

发现其已经废弃

后查找得[另一个国内源](https://gems.ruby-china.org/ "https://gems.ruby-china.org/")也报错。

打开此域名发现其[更换后地址](https:gems.ruby-china.com/ "https:gems.ruby-china.com/")
