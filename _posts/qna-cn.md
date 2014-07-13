title: Questions and Answers（中文）
date: 2014-03-16 18:10:16
categories: Docs
---

{% label Q danger %} `Wixo` 这名字有何含义？

{% label A success %} `Wixo` 意思是 A **wi**ki theme for he**xo** .

{% label Q danger %} 如何指定某些页面生成 ToC(Table of Contents) ？

{% label A success %} 在[文章头部](https://github.com/wzpan/hexo-theme-freemind#front-matter)添加 `toc: true` 。

{% label Q danger %} 从哪里可以找到你的这几篇文档的 Markdown 源码？

{% label A success %} 在项目的 [source](https://github.com/wzpan/hexo-theme-wixo/tree/source) 分支。

{% label Q danger %} 为啥我在插入 bootstrap 插件后总是自动折行？

{% label A success %} 这个问题是你的 Markdown 设置引起的。解决办法是在你的 Hexo 的 _config.yml 文件中禁用 Markdown 的 `breaks` 选项：

<script src="https://gist.github.com/wzpan/9967986.js"></script>
