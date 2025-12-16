---
layout: post
title: "我的第一篇博客：Jekyll 上线之旅"
date: 2025-12-16 20:30:00 +0800
categories: [技术, 个人]
---

这是我的第一篇博客文章！我成功地在 Windows 上配置了 Ruby 和 Jekyll 环境，并通过 SSH 协议将我的网站部署到了 GitHub Pages 上。

---

## 我学到的关键技巧

1.  **使用 `bundle install` 管理依赖：** 在 Ruby/Jekyll 环境中，所有的主题和插件都是通过 Bundler 来安装和管理的。
2.  **Git 推送流程：** 必须先 `add`，再 `commit`，最后才能 `push`。
3.  **解决网络问题：** 遇到 HTTPS 连接失败（如 403 错误或连接重置）时，可以切换到 **SSH 协议**来解决。

## 如何编辑文章？

只需要在 `_posts` 文件夹中编辑 `.markdown` 文件即可。

* **粗体：** **这是粗体字**
* **链接：** [这是我的 GitHub 仓库](https://github.com/lqx220/lqx220.github.io)