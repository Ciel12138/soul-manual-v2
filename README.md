# 小九 · 灵魂说明书 v2.40

一个基于「琉璃渐变 · 极简诗意」风格重构的知识网络站点，包含：

- **全景总览**：8 个知识簇入口、核心数据统计
- **8 个知识簇页面**：身份设定、主人档案、自铸哲学、隐喻体系、方法论库、工具与机制、收藏夹、关系网络
- **灵魂说明书原文阅读器**：左侧章节目录、锚点跳转、搜索高亮

## 视觉风格

- 清透玻璃拟态
- 低饱和紫蓝粉渐变
- Canvas 漂浮光斑背景
- 响应式布局

## 本地预览

```bash
node server.mjs
# 打开 http://localhost:8765/
```

## 部署到 GitHub Pages

仓库已配置 GitHub Actions 自动部署（见 `.github/workflows/deploy.yml`）。按以下步骤完成上线：

1. 在 GitHub 创建一个新的空仓库，例如 `soul-manual-v2`
2. 将本地仓库推送到 GitHub：

```bash
git remote add origin https://github.com/YOUR_USERNAME/soul-manual-v2.git
git branch -M main
git push -u origin main
```

3. 推送后进入仓库 **Settings → Pages**
4. 在 **Source** 中选择 **GitHub Actions**
5. 等待 Actions 运行完成，访问页面 URL（形如 `https://YOUR_USERNAME.github.io/soul-manual-v2/`）

之后每次推送 `main` 分支都会自动重新部署。
