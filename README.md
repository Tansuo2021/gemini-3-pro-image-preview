# Gemini 3 Pro Image Preview

<div align="center">

![Gemini 3 Pro](https://img.shields.io/badge/Gemini-3%20Pro-blue?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**🎨 强大的 Gemini 3 Pro 图像生成工作台**

[在线演示](#) | [快速开始](#快速开始) | [功能特性](#功能特性) | [贡献指南](#贡献指南)

</div>

---

## 📖 项目简介

Gemini 3 Pro Image Preview 是一个基于 Google Gemini 3 Pro 模型的现代化图像生成工作台。它提供了直观的用户界面、强大的功能和出色的用户体验，支持多种图像生成场景和创作工具。

### ✨ 核心亮点

- 🚀 **并发生成** - 支持批量并发生成图片，提高创作效率
- 🎯 **4K 渲染** - 支持高达 4K 分辨率的图像生成
- 💾 **本地存储** - 使用 IndexedDB 本地存储对话历史
- 📱 **响应式设计** - 完美适配桌面端和移动端
- 🌓 **暗黑模式** - 内置优雅的暗黑主题
- 🔄 **对话上下文** - AI 可记住历史对话，实现连续创作

---

## 🎯 功能特性

### 核心功能

#### 🖼️ 图像生成
- **多分辨率支持**：1K / 2K / 4K 可选
- **多种长宽比**：支持 1:1、16:9、9:16、3:4、4:3 等 11 种比例
- **参考图上传**：支持上传参考图进行图像生成
- **批量生成**：一次性生成多张图片

#### 💬 对话管理
- **会话持久化**：使用 IndexedDB 存储对话历史
- **上下文记忆**：可配置保留 3/5/10/20 条历史对话
- **会话切换**：快速切换不同的对话会话
- **历史记录**：完整的对话历史记录

#### 🎨 创作工具

##### 📝 XHS 灵感实验室
- 小红书风格内容创作
- AI 生成文案和配图
- 支持图片分析和文案生成
- 批量生成分镜图片

##### 🍌 提示词快查
- 集成 [Banana Prompt](https://github.com/glidea/banana-prompt-quicker) 提示词库
- 快速搜索和使用优质提示词
- 支持分类筛选（绘图/生活/学习/工作等）

##### 📚 我的提示词
- 管理个人提示词库
- 添加、编辑、删除自定义提示词
- 快速应用到对话中

##### 😊 表情包制作
- 一键进入表情包生成模式
- 预设表情包生成参数
- 支持 LINE 风格表情包

##### ✂️ 图片切片工具
- 九宫格切图功能
- 支持横线/竖线切割
- 1:1 补全功能
- 一键打包下载

### 高级功能

#### ⚙️ API 渠道管理
- **多渠道支持**：支持配置多个 API 渠道
- **随机轮询**：自动在多个渠道间轮询
- **双接口支持**：
  - Gemini 原生接口
  - OpenAI 兼容接口
- **渠道管理**：添加、编辑、删除 API 渠道

#### 💾 自动保存
- **File System Access API**：使用浏览器原生 API
- **本地保存**：生成的图片自动保存到本地目录
- **不占空间**：不占用浏览器存储空间
- **浏览器要求**：Chrome 86+ / Edge 86+

#### 🌐 流式传输
- **OpenAI 流式接收**：支持流式接收 API 响应
- **实时显示**：实时显示生成进度
- **整体解析**：完整解析后显示图片

---

## 🚀 快速开始

### 前置要求

- 现代浏览器（Chrome 86+ / Edge 86+ / Firefox / Safari）
- Gemini API Key 或兼容的 OpenAI API

### 安装步骤

1. **克隆仓库**
```bash
git clone https://github.com/Tansuo2021/gemini-3-pro-image-preview.git
cd gemini-3-pro-image-preview
```

2. **启动本地服务器**
```bash
# 使用 Python
python -m http.server 8000

# 或使用 Node.js
npx serve

# 或使用 PHP
php -S localhost:8000
```

3. **打开浏览器**
```
http://localhost:8000
```

### 配置 API

1. 点击右上角的 **设置** 图标
2. 展开 **API 渠道管理**
3. 填写以下信息：
   - **渠道名称**：自定义名称（如：官方API）
   - **接口类型**：选择 Gemini 原生接口 或 OpenAI 兼容接口
   - **API Base URL**：API 地址
   - **API Key**：你的 API 密钥
   - **Model**：模型名称（如：gemini-3-pro-image-preview）
4. 点击 **保存渠道**

---

## 📦 技术栈

- **前端框架**：原生 JavaScript（无框架依赖）
- **样式**：CSS3 + CSS Variables
- **存储**：IndexedDB
- **文件系统**：File System Access API
- **Markdown 解析**：marked.js
- **文件压缩**：JSZip

---

## 📱 浏览器兼容性

| 浏览器 | 版本要求 | 核心功能 | 自动保存 |
|--------|---------|---------|---------|
| Chrome | 86+ | ✅ | ✅ |
| Edge | 86+ | ✅ | ✅ |
| Firefox | 最新版 | ✅ | ❌ |
| Safari | iOS 14+ | ✅ | ❌ |

**注意**：自动保存功能需要 File System Access API 支持（Chrome/Edge 86+）

---

## 🎨 界面预览

### 桌面端
- 三栏布局：侧边栏 + 主内容区 + 设置面板
- 响应式设计，自动适配不同屏幕尺寸

### 移动端
- 优化的移动端布局
- 侧边栏滑出设计
- 触摸友好的交互

### 暗黑模式
- 一键切换暗黑/明亮主题
- 自动保存主题偏好
- 完整的暗黑模式适配

---

## 🔧 配置说明

### 分辨率设置
- **1K**：1024x1024
- **2K**：2048x2048
- **4K**：4096x4096（默认）

### 长宽比选项
- Auto（自动）
- 21:9（超宽屏）
- 16:9（宽屏）
- 3:2、4:3、5:4（横向）
- 1:1（正方形）
- 4:5、3:4、2:3、9:16（竖向）

### 对话上下文
- **保留条数**：3 / 5（默认）/ 10 / 20 条
- **功能**：AI 可基于历史对话和图片继续创作
- **注意**：保留条数越多，消耗的 Token 越多

---

## 🤝 贡献指南

欢迎贡献代码、报告问题或提出建议！

### 贡献流程

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 开发建议

- 遵循现有代码风格
- 添加必要的注释
- 测试你的更改
- 更新相关文档

---

## 📝 更新日志

### v1.0.0 (2026-01-04)
- ✨ 初始版本发布
- 🎨 完整的图像生成功能
- 💬 对话上下文支持
- 🛠️ XHS 灵感实验室
- 🍌 提示词快查工具
- ✂️ 图片切片工具
- 📱 移动端适配
- 🌓 暗黑模式支持

---

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

---

## 🙏 致谢

- [Google Gemini](https://deepmind.google/technologies/gemini/) - 强大的 AI 模型
- [Banana Prompt](https://github.com/glidea/banana-prompt-quicker) - 优质提示词库
- [marked.js](https://marked.js.org/) - Markdown 解析
- [JSZip](https://stuk.github.io/jszip/) - 文件压缩

---

## 📮 联系方式

- **GitHub Issues**: [提交问题](https://github.com/Tansuo2021/gemini-3-pro-image-preview/issues)
- **Pull Requests**: [贡献代码](https://github.com/Tansuo2021/gemini-3-pro-image-preview/pulls)

---

<div align="center">

**⭐ 如果这个项目对你有帮助，请给一个 Star！**

Made with ❤️ by [Tansuo2021](https://github.com/Tansuo2021)

</div>
