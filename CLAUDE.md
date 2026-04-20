# 个人博客项目

## 技术栈

- **框架**: Astro
- **部署**: GitHub Pages
- **域名**: 个人域名
- **内容形式**: 文字 + 图片 + 视频
- **评论**: Giscus (基于 GitHub Discussions)
- **写作**: Markdown

## 项目结构

```
2026-04-21-个人博客/
├── CLAUDE.md
├── astro.config.mjs
├── package.json
├── public/
│   └── assets/          # 静态资源
├── src/
│   ├── content/
│   │   └── blog/        # 博客文章 (Markdown)
│   ├── layouts/
│   ├── pages/
│   └── styles/
└── .github/
    └── workflows/       # GitHub Actions 自动部署
```

## 部署流程

1. GitHub Pages 构建
2. 自定义域名配置
3. Giscus 评论系统集成