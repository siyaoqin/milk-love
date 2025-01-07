---
layout: post
title: Sample blog post to learn Jekyll structure
subtitle: Welcome to my blog! This is my first post.
tags: [Jekyll]
comments: true
mathjax: true
author: siyaoqin
---

记录Jekyll前端架构功能

```plaintext
my-jekyll-site/
│
├── _config.yml             # Jekyll 配置文件，包含站点的设置和插件配置
├── _includes/              # 包含可复用的 HTML 片段（如页头、页脚、导航）
│   ├── header.html         # 页头
│   └── footer.html         # 页脚
├── _layouts/               # 存放布局模板，用于渲染不同的页面
│   ├── default.html        # 默认布局模板
│   ├── post.html           # 博客文章布局
│   └── page.html           # 普通页面布局
├── _posts/                 # 存放 Markdown 格式的博客文章
├── _data/                  # 存放数据文件，支持 JSON 或 YAML 格式
│   └── authors.yml         # 作者数据
├── assets/                 # 存放网站静态资源（如图片、字体、图标等）
│   ├── images/             # 网站图片
│   ├── fonts/              # 网站字体
│   └── icons/              # 图标
├── css/                    # 存放样式文件
│   ├── main.css            # 网站主样式
│   └── reset.css           # 重置样式
├── js/                     # 存放 JavaScript 文件
│   └── main.js             # 主要的 JavaScript 文件
├── index.md                # 网站首页内容（Markdown 格式）
├── about.md                # "关于"页面内容（Markdown 格式）
├── 404.html                # 404 页面
├── feed.xml                # RSS 订阅文件（如果启用）
└── sitemap.xml             # 网站的 sitemap 文件
```
