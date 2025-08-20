# 🚀 部署指南

## GitHub Pages 部署步骤

### 1. 创建新仓库

1. 在 GitHub 上创建一个新的仓库
2. 仓库名称建议：`main-page` 或 `portfolio`
3. 设置为 Public 仓库
4. 不要初始化 README（我们将手动添加文件）

### 2. 上传文件

将以下文件上传到您的仓库：

- `index.html` - 主页面文件
- `README.md` - 项目说明文档
- `DEPLOY.md` - 本部署指南

### 3. 启用 GitHub Pages

1. 进入仓库的 **Settings** 标签页
2. 在左侧菜单中找到 **Pages**
3. 在 **Source** 部分选择 **Deploy from a branch**
4. 选择 **main** 分支
5. 点击 **Save**

### 4. 访问您的页面

部署完成后，您的页面将在以下地址可用：
```
https://yourusername.github.io/repository-name
```

## 🔧 自定义配置

### 修改项目信息

编辑 `index.html` 文件中的项目卡片：

```html
<!-- 修改项目标题 -->
<h3 class="text-xl font-semibold text-dark mb-3">新项目名称</h3>

<!-- 修改项目描述 -->
<p class="text-neutral leading-relaxed mb-6">新项目描述</p>

<!-- 修改项目链接 -->
<a href="https://your-new-project-url.com" class="...">
```

### 修改页面标题

```html
<title>您的页面标题</title>
<h1 class="text-4xl md:text-5xl font-bold text-dark mb-4">您的页面标题</h1>
```

### 修改颜色主题

在 `<script>` 标签中修改颜色配置：

```javascript
colors: {
    primary: '#3B82F6',    // 主色调
    neutral: '#6B7280',    // 中性色
    dark: '#111827',       // 深色
    light: '#F9FAFB',      // 浅色背景
}
```

## 📱 测试响应式设计

### 本地测试

1. 在浏览器中打开 `index.html`
2. 按 `F12` 打开开发者工具
3. 点击设备模拟器图标
4. 测试不同屏幕尺寸的显示效果

### 断点测试

- **移动端**: 375px - 768px
- **平板端**: 768px - 1024px  
- **桌面端**: 1024px+

## 🎨 添加新项目

### 复制现有卡片

1. 复制一个完整的项目卡片 `<div class="group">...</div>`
2. 粘贴到网格容器中
3. 修改项目信息、链接和图标

### 自定义图标

替换 SVG 图标：

```html
<svg class="w-8 h-8 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
    <!-- 在这里放置您的 SVG 路径 -->
</svg>
```

## ⚡ 性能优化建议

### 图片优化

- 使用 WebP 格式图片
- 压缩图片文件大小
- 考虑使用懒加载

### 代码优化

- 压缩 HTML 和 CSS
- 使用 CDN 加载外部资源
- 启用 Gzip 压缩

## 🐛 常见问题

### 页面不显示

1. 检查文件名是否为 `index.html`
2. 确认 GitHub Pages 已启用
3. 等待几分钟让部署完成

### 样式不加载

1. 检查网络连接
2. 确认 TailwindCSS CDN 链接有效
3. 清除浏览器缓存

### 响应式问题

1. 检查 viewport meta 标签
2. 测试不同设备尺寸
3. 验证 CSS 媒体查询

## 📞 获取帮助

如果遇到问题：

1. 检查 GitHub Pages 状态页面
2. 查看浏览器控制台错误信息
3. 在 GitHub Issues 中搜索类似问题
4. 提交新的 Issue 描述您的问题

---

**祝您部署顺利！** 🎉

