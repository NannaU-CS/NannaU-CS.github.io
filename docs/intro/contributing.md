# 贡献指南

本贡献指南提供了如何为 NannaU CS 生存指南贡献内容的详细步骤和说明。

## 贡献流程

要贡献内容，请按照以下步骤操作：

1. 在 GitHub 上 Fork 本仓库。假设 Fork 后的仓库地址为 `https://github.com/username/NannaU-CS.github.io`；
2. 克隆 Fork 后的仓库到本地，进行本地的修改，并在本地构建和预览（见[本地构建](#_3)）；
3. Add 并 Commit 你的修改，push 到你的 Fork 仓库后，进行 Pull Request。


## 本地构建

推荐使用 python 包管理器 [`uv`](https://docs.astral.sh/uv) 来进行本地环境配置。在安装了 `uv` 后，克隆仓库并进入项目目录，一键配置环境。命令如下：

```bash
git clone https://github.com/username/NannaU-CS.github.io.git
cd NannaU-CS.github.io
uv sync
```

然后，即可使用 `uv run mkdocs serve` 命令来启动本地预览服务器。默认的网址为 <http://127.0.0.1:8000>，使用浏览器打开即可。