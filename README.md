# 个人网站（静态模版）

这是一个简单的个人网站静态模板，适合部署到 GitHub Pages。

部署方式（任选其一）：

1) 使用 GitHub Pages（推荐）
- 将文件放到仓库根目录或 docs/ 目录。
- 进入仓库 Settings → Pages，选择分支（main 或 gh-pages）及目录（/ 或 /docs），保存。
- 页面通常会在几分钟内通过 https://<你的用户名>.github.io/<仓库名>/ 访问。

2) 使用 GitHub Actions 自动部署到 gh-pages（见 .github/workflows/gh-pages.yml）
- 该 workflow 会把构建内容推到 gh-pages 分支。启用后，Pages 指向 gh-pages 分支即可。

自定义
- 修改 index.html 中的文本、链接、图片与样式。
- 如果想要多页面或使用 SSG（如 Jekyll、Hugo、Eleventy），把当前文件迁移到对应框架下。

联系
- 如果你想让我把这些文件直接提交到仓库（创建分支 + 提交），告诉我分支名和是否需要我替换现有文件，我可以生成提交内容说明。
