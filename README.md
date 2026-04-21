# Astro 起始项目：Minimal

```sh
npm create astro@latest -- --template minimal
```

> 🧑‍🚀 **已经是 Astro 老手？** 删除此文件，开始愉快编码吧！

## 🚀 项目结构

在 Astro 项目中，你会看到以下文件夹和文件：

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro 会在 `src/pages/` 目录中查找 `.astro` 或 `.md` 文件。每个页面根据文件名生成对应的路由。

`src/components/` 目录没有特殊含义，但我们习惯将 Astro/React/Vue/Svelte/Preact 组件放在这里。

静态资源（如图片）可以放置在 `public/` 目录中。

## 🧞 命令

所有命令需在项目根目录的终端中执行：

| 命令                      | 操作                                           |
| :------------------------ | :-------------------------------------------- |
| `npm install`             | 安装依赖                                       |
| `npm run dev`             | 启动本地开发服务器，地址为 `localhost:4321`    |
| `npm run build`           | 构建生产环境站点，输出到 `./dist/`             |
| `npm run preview`         | 本地预览构建结果，部署前使用                   |
| `npm run astro ...`       | 运行 Astro CLI 命令，如 `astro add`、`astro check` |
| `npm run astro -- --help` | 获取 Astro CLI 帮助信息                       |

## 👀 想了解更多？

欢迎查阅 [官方文档](https://docs.astro.build) 或加入我们的 [Discord 服务器](https://astro.build/chat)。
