# 🚀 nothinkblog.github.io - 博客部署仓库

这是一个专门用于 GitHub Pages 服务的部署仓库，用于展示我的个人博客。

---

## 🛑 注意事项

1.  **代码来源：** 本仓库内的所有文件（HTML, CSS, JavaScript 等）均由 GitHub Actions 自动生成并推送。
2.  **内容修改：** **请不要直接修改** 本仓库中的任何文件。
3.  **源码位置：** 博客的**源码**、配置以及构建脚本位于 [您的博客源码仓库链接]。

## 🛠️ 部署流程

本仓库的内容由 GitHub Actions 自动化管理。每当源码仓库的主分支发生推送时，Actions 会：

1.  构建博客项目 (`pnpm run build`)。
2.  将生成的 `./dist` 目录内容推送到本仓库的 `main` 分支。

---

**访问博客：** [https://nothinkblog.github.io](https://nothinkblog.github.io)
