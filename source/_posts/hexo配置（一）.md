---
title: hexo配置（一）
date: 2017-01-20 10:28:02
categories: hexo
tags: [hexo, 配置, blog]
---

一、指令
hexo init [folder]  新建一个网站。
hexo new [layout] title 新建一篇文章。
hexo generate 生成静态文件。
选项：
   -d 文件生成后立即部署网站
   -w 监视文件变动
hexo publish [layout] <filename> 发表草稿。
hexo server 启动服务器，默认访问：http://localhost:4000/.
选项：
   -p 重设端口
   -s 只使用静态文件
   -l 启动日志记录
hexo deploy 部署网站。
hexo clean 清除缓存文件(db.json)和已生成的静态文件（public）。
hexo list <type> 列出网站资料。
hexo --cwd /path/to/cwd 自定义当前工作目录的路径。