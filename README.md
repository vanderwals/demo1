---
description: GitBook的简介
---

# GitBook

GitBook的内容

GitBook 是一款现代化的文档平台，支持团队协作，可以在上面写产品文档、内部知识分享、接口文档等。GitBook 有网页版和本地版两种，网页版地址如下：[https://www.gitbook.com/](https://link.zhihu.com/?target=https%3A//www.gitbook.com/)，本地版地址如下：[https://github.com/GitbookIO/gitbook](https://link.zhihu.com/?target=https%3A//github.com/GitbookIO/gitbook)。

本地版是基于 [Node.js](https://zhida.zhihu.com/search?content_id=164398827\&content_type=Article\&match_order=1\&q=Node.js\&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3NTM5MjgyNjgsInEiOiJOb2RlLmpzIiwiemhpZGFfc291cmNlIjoiZW50aXR5IiwiY29udGVudF9pZCI6MTY0Mzk4ODI3LCJjb250ZW50X3R5cGUiOiJBcnRpY2xlIiwibWF0Y2hfb3JkZXIiOjEsInpkX3Rva2VuIjpudWxsfQ.dJgHnZgalS6wWKLUzMGBr-VafgCBq2OJ5sfS5AwtF1M\&zhida_source=entity) 开发的，所以需要本地安装 Node.js 环境，本地版现已停止维护了，而且本地版的大部分功能网页版都支持，所以本教程主要是介绍网页版的使用方式。

GitBook 和 [GitHub](https://zhida.zhihu.com/search?content_id=164398827\&content_type=Article\&match_order=1\&q=GitHub\&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3NTM5MjgyNjgsInEiOiJHaXRIdWIiLCJ6aGlkYV9zb3VyY2UiOiJlbnRpdHkiLCJjb250ZW50X2lkIjoxNjQzOTg4MjcsImNvbnRlbnRfdHlwZSI6IkFydGljbGUiLCJtYXRjaF9vcmRlciI6MSwiemRfdG9rZW4iOm51bGx9.YYqNYZwhxroOT2qxvyBeRWE0m119itWgUdntufYMc1U\&zhida_source=entity) 是什么关系呢？这是两个相互独立的网站，但是你在 GitBook 上创建的文档可以同步到 GitHub 仓库，每次对文档的修改都会生成一个 commit，GitBook 会自动帮你提交到 GitHub，这样有助于追溯历史版本。而你往 GitHub 提交的内容也会自动同步到 GitBook。（具体怎么在 GitBook 和 GitHub 之间建立关联一会儿会讲到，但是在这之前，我假设你已经会使用 GitHub 了，如果你没有，可以关注文末的公众号，回复「GitHub」获取相关教程。）
