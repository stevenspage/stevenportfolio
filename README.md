# Steven's Projects - 导航主页

一个优雅、现代的 GitHub 项目导航页面，展示我的三个主要开源项目。

## 🚀 特性

- ✨ **现代设计**：浅色主题，简洁优雅的界面
- 📱 **响应式布局**：完美适配桌面端和移动端
- 🎨 **TailwindCSS**：使用最新的 CSS 框架，确保样式一致性
- 🎭 **流畅动画**：页面加载淡入效果和卡片悬停动效
- 🔗 **项目链接**：直接跳转到各个项目页面

## 🎯 展示项目

1. **English Ebooks** - 英语电子书资源集合
2. **VocabFlow** - 智能词汇学习工具
3. **Latest TV** - 最新影视资讯平台

## 🛠️ 技术栈

- HTML5
- TailwindCSS (CDN)
- 原生 JavaScript
- Inter 字体

## 📦 部署到 GitHub Pages

### 方法 1：直接部署（推荐）

1. 将此仓库推送到您的 GitHub 账户
2. 在仓库设置中启用 GitHub Pages
3. 选择 `main` 分支作为源
4. 访问 `https://yourusername.github.io/repository-name`

### 方法 2：手动部署

1. 将 `index.html` 文件上传到您的 GitHub Pages 仓库
2. 确保文件名是 `index.html`（作为默认页面）
3. 提交并推送更改

## 🎨 自定义

### 修改项目信息

编辑 `index.html` 文件中的项目卡片部分：

```html
<!-- 修改项目标题 -->
<h3 class="text-xl font-semibold text-dark mb-3">您的项目名称</h3>

<!-- 修改项目描述 -->
<p class="text-neutral leading-relaxed mb-6">您的项目描述</p>

<!-- 修改项目链接 -->
<a href="您的项目链接" class="...">
```

### 修改颜色主题

在 `<script>` 标签中的 `tailwind.config` 部分修改颜色：

```javascript
colors: {
    primary: '#您的主题色',
    neutral: '#您的中性色',
    dark: '#您的深色',
    light: '#您的浅色',
}
```

## 🌟 设计特点

- **科技风格背景**：深色渐变背景 + 蓝色网格纹理
- **动态光效**：多层次的发光圆形元素，营造科技感
- **卡片设计**：半透明深色背景，毛玻璃效果，发光边框
- **背景图片**：每个项目都有独特的 SVG 背景图案，增强视觉层次
- **悬停效果**：卡片上浮 + 彩色发光边框
- **图标系统**：每个项目都有独特的 SVG 图标，带发光效果
- **动画效果**：页面加载淡入、扫描线、数据流动效果
- **角落装饰**：几何边框装饰，增强科技感

## 📱 响应式设计

- **桌面端**：三列网格布局
- **平板端**：两列网格布局
- **移动端**：单列堆叠布局

## 🔧 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 许可证

MIT License - 可自由使用和修改

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

---

**Steven's Projects** - 用 ❤️ 和 TailwindCSS 构建
