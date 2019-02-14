---
title: 搭建博客笔记
comments: true
date: 2019-02-14 21:13:12
tags: 笔记
categories: 博客
---

<!--more-->

记录本次搭建博客中遇到的坑以及常用命令

非常感谢网上几位大神的教程，文末我会附上链接

### hexo常用命令

博客写作，部署流程

```
hexo new "文章标题"
hexo clean
hexo g
hexo s
hexo d

//详细版
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #将.deploy目录部署到GitHub
hexo help  # 查看帮助
hexo version  #查看Hexo的版本
```

