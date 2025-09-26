# NannaU-CS Wiki

Welcome to NannaU CS Wiki!

欢迎来到 NannaU CS Wiki！

## Contribution Guide 如何贡献

条件: 拥有github帐号.

1. 在线编辑
    
    要编辑现有文章的内容，可以点击标题右侧的"编辑"图标，浏览器会跳转到github的编辑页面，github 会自动创建一份本 repo 的 fork，进行编辑后，点击最下方的 Propose changes, 再点击新页面中的 Create pull request, 便可完成编辑。

    (编辑不会立刻生效，需要等待管理员手动 merge) 
    
2. 本地编辑

    将 fork 的仓库 clone 到本地, commit 你的修改， push 到你的 fork 仓库， 再提交 Pull request.
    如果要新建文档，需要在根目录下 mkdocs.yml 文件中 nav: 下添加对应的文档目录

如果依然对如何编辑有疑问，可以参照 [OI-Wiki 上相关页面](https://oi-wiki.org/intro/htc) 来进行编辑

## Build Guide 如何构建

We recommend using [uv](https://docs.astral.sh/uv/) to build the site.

建议使用 [uv](https://docs.astral.sh/uv/) 来构建网站。

```bash
uv sync
```

然后可以使用 `mkdocs serve` 来预览网站.
