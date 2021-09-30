---
title: My First Article
date: 2021-09-26 22:56:04
categories: 
  - 编程
  - hexo 配置手册
tags: 
  - A bored begining
---

# 前言

既然是我博客里的第一篇文章，那我就来摸索一下这里的各种功能好了。

首先list一下，我的根目录里的npm清单：

```
exo-site@0.0.0 /Users/jasmine/jasmines_blog
├── @upupming/hexo-renderer-markdown-it-plus@2.0.2
├── hexo-browsersync@0.3.0
├── hexo-deployer-git@3.0.0
├── hexo-generator-archive@1.0.0
├── hexo-generator-category@1.0.0
├── hexo-generator-feed@3.0.0
├── hexo-generator-index@2.0.0
├── hexo-generator-sitemap@2.1.0
├── hexo-generator-tag@1.0.0
├── hexo-math@4.0.0
├── hexo-renderer-ejs@1.0.0
├── hexo-renderer-jade@0.5.0
├── hexo-renderer-stylus@2.0.1
├── hexo-server@2.0.0
└── hexo@5.4.0
```

1. `hexo-renderer-markdown-it-plus` 为了写latex重新更换的渲染引擎。之所以要更换，是因为在网上hexo原先的 `hexo-renderer-marked` 引擎，有许多符号会和latex里的符号重复，哪怕下载了支持mathjex的插件写tex 的时候也需要加上许多转义符，故放弃。
2. `hexo-browsersync` 这个应该是 hexo 自带的一个插件。如同字面意思，这个插件会在你的`hexo server`启动后，当你进行了任何文件上的更改时，实时地在浏览器端口，重新加载新的内容，帮助你实时编辑并查看效果。
3. `hexo-deployer-git` 这是一个需要手动安装的插件，可以通过 `hexo deploy --git` 命令帮助将hexo生成的静态文件上传至 github page。
4. 
