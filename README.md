# EasyCover - 基于afoim/easy_cover魔改的封面图生成工具
 
<img width="1893" height="1390" alt="a7db63bb841d2b78d604e2662c50365c" src="https://github.com/user-attachments/assets/e8379b3a-2806-4069-ab47-9a7487c1dd82" />

简单、优雅的封面图生成工具。纯客户端运行，保护您的隐私。

## ✨ 特性

*   **纯客户端生成**：所有图片处理均在浏览器完成，无需上传服务器。
*   **多比例支持**：支持 1:1, 16:9, 21:9, 4:3, 2:1 等多种主流封面比例。
*   **丰富的图标库**：集成 Iconify，支持搜索和使用数万个图标。
*   **黑暗模式自适应**：根据系统主题自动切换到黑暗模式。
*   **配置文件导入导出**：支持导入和导出当前配置，方便配置复用。
*   **高度自定义**：
    *   **图标**：大小、旋转、颜色、阴影、容器形状（圆/方/圆角）、毛玻璃效果（高斯模糊 + 透明度）。
    *   **文字**：自定义内容、大小、颜色、描边。
    *   **背景**：纯色背景、图片背景（支持缩放、旋转、平移、模糊）。
*   **智能排版**：自动居中布局，支持“适应”和“铺满”两种图片填充模式。
*   **纯净导出**：一键导出 PNG，自动隐藏辅助线和标尺。

## 🛠️ 技术栈

*   [Next.js](https://nextjs.org/) - React 框架
*   [Tailwind CSS](https://tailwindcss.com/) - 样式引擎
*   [Shadcn/ui](https://ui.shadcn.com/) - UI 组件库
*   [Zustand](https://github.com/pmndrs/zustand) - 状态管理
*   [Iconify](https://iconify.design/) - 图标方案
*   [html-to-image](https://github.com/bubkoo/html-to-image) - 图片生成

## 🚀 快速开始

1.  **克隆仓库**

```bash
git clone https://github.com/Flygeon/easy_cover.git
cd easy_cover
```

2.  **安装依赖**

```bash
npm install
# 或者
yarn install
# 或者
pnpm install
```

3.  **启动开发服务器**

```bash
npm run dev
```

打开浏览器访问 [http://localhost:3000](http://localhost:3000) 即可使用。

## 📖 使用指南

1.  **选择布局**：在左侧面板选择所需的图片比例（如 16:9）。
2.  **设置内容**：输入封面标题，调整文字大小和颜色。
3.  **添加图标**：点击图标选择器搜索并选择合适的图标，调整其样式和容器背景（支持毛玻璃效果）。
4.  **配置背景**：选择纯色背景或上传本地图片。使用“适应”或“铺满”按钮快速调整图片布局。
5.  **导出**：点击底部的“导出封面图”按钮保存图片。

## 📦 部署

本项目已配置为静态导出 (`output: 'export'`)，可轻松部署到任何静态托管服务。

### Vercel 部署

1.  Fork 本仓库。
2.  在 Vercel 中导入项目。
3.  Vercel 会自动识别 Next.js 项目。
4.  **重要**：确保构建命令为 `npm run build` (默认)，输出目录默认为 `out` (Next.js 静态导出默认目录)。
    *   注：本项目已在 `next.config.ts` 中启用了 `output: 'export'`，Vercel 会自动处理，无需额外配置。

### GitHub Pages 部署

1.  构建项目：
    ```bash
    npm run build
    ```
2.  将生成的 `out` 目录内容推送到 `gh-pages` 分支。

## 📄 许可证

本项目采用 [AGPL-3.0](LICENSE) 许可证。

---
❤欢迎访问原项目

[https://github.com/afoim/easy_cover](https://github.com/afoim/easy_cover) 

Made with ❤️ by AcoFork&Flygeon（偷偷挂个自己名应该没人发现吧ovo）
