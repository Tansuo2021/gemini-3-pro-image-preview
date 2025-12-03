## 版本更新
- 新增iOS应用端存储到相册功能，点击下载 到新页面长按保存图片
<img width="664" height="1036" alt="image" src="https://github.com/user-attachments/assets/b56df154-c3d1-4e99-a043-c986c0b74d1a" />

- 优化小红书提示词，出图更好看
<img width="3154" height="1684" alt="image" src="https://github.com/user-attachments/assets/cf67cbbb-3dd7-4ea8-9a43-b06658510383" />

- 增加流式接收
<img width="650" height="406" alt="image" src="https://github.com/user-attachments/assets/b4164844-6183-4202-a55a-7784ee9a42a3" />

- 细节优化 可以单纯文字输出 文字图片一同输出

<div align="center">

# 🎨 Gemini 3 Pro - 绘图工作台全能版

**一站式 AI 绘图解决方案 | 小红书创作神器 | 开箱即用**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/yourusername/gemini-pro-workbench/pulls)

[功能特性](#-核心特性) • [快速开始](#-快速开始) • [使用指南](#-使用指南) • [技术架构](#️-技术架构)

---

</div>

## 📖 项目简介

基于 **Gemini 3 Pro** 的多功能 AI 绘图工作台，集成小红书创作、提示词库、图片切割等实用工具。

**🌟 核心亮点：**
- 🚀 **零配置启动** - 单 HTML 文件，双击即用
- 🎯 **多 API 支持** - Gemini + OpenAI 兼容接口
- 📱 **小红书专属** - 从文案到配图一站式解决
- 🍌 **海量提示词** - 集成社区精选词库
- ✂️ **图片工具** - 切片、九宫格、表情包制作
- 🌓 **明暗主题** - 护眼模式，随心切换
- 💾 **本地存储** - 隐私安全，数据不上传

## ✨ 核心特性

### 🖼️ AI 绘图引擎
- ✅ **多渠道管理** - 支持 Gemini 原生接口和 OpenAI 兼容接口
- ✅ **智能轮询** - 随机优选模式，自动切换 API 渠道
- ✅ **高清渲染** - 支持 1K/2K/4K 分辨率输出
- ✅ **灵活比例** - 11 种长宽比预设（1:1, 16:9, 9:16, 3:4 等）
- ✅ **参考图上传** - 支持多图上传（最多 14 张），智能压缩优化
- ✅ **并发生成** - 多图同时生成，实时进度显示
- ✅ **流式传输** - OpenAI 接口支持流式接收，实时查看生成过程
- ✅ **拖拽上传** - 支持图片拖拽、粘贴上传，操作更便捷

### 📱 XHS 灵感实验室
> 专为小红书内容创作者打造的 AI 助手

- ✅ **智能策划** - 输入主题或上传图片，AI 自动生成小红书笔记方案
- ✅ **分镜生成** - 自动规划多张配图的画面描述和提示词
- ✅ **垫图功能** - 为每个分镜单独设置参考图，精准控制风格
- ✅ **批量绘制** - 一键生成所有分镜图片，带进度条反馈
- ✅ **历史记录** - IndexedDB 本地存储，随时查看和复用历史方案
- ✅ **文案导出** - 支持复制标题、正文，快速发布到小红书
- ✅ **自定义模型** - 支持添加自定义 AI 模型到快速选择列表
- ✅ **三栏布局** - 配置、编辑、预览一目了然

### 🍌 提示词快查工具
> 集成社区精选提示词库，告别提示词荒

- ✅ **海量词库** - 集成 [Banana Prompt](https://github.com/glidea/banana-prompt-quicker) 社区精选提示词
- ✅ **分类筛选** - 绘图/生活/学习/工作/NSFW 多分类，快速定位需求
- ✅ **实时搜索** - 支持标题、提示词、分类关键词搜索
- ✅ **一键复制** - 点击即可复制提示词到剪贴板
- ✅ **多源加载** - 自动尝试多个 CDN 源，确保数据可用
- ✅ **卡片展示** - 预览图 + 标题 + 描述，直观易用

### ✂️ 图片切割工厂
> 专业的图片分割工具，支持九宫格和自由切割

- ✅ **自由切割** - 横线/竖线模式，拖拽调整切割位置
- ✅ **九宫格** - 快速生成社交媒体九宫格图片
- ✅ **1:1 补全** - 自动填充背景色，生成正方形切片
- ✅ **批量下载** - 一键打包所有切片为 ZIP 文件
- ✅ **表情包制作** - 配合 AI 生成，快速制作表情包矩阵
- ✅ **实时预览** - 切割线可视化，所见即所得

### 🎭 表情包模式
> 一键生成 LINE 风格表情包矩阵

- ✅ **一键启动** - 自动配置 4K 分辨率 + 16:9 比例
- ✅ **预设提示词** - 内置 LINE 风格 Q 版表情包生成模板
- ✅ **4x6 布局** - 生成 24 个常用表情，覆盖日常聊天场景
- ✅ **智能识别** - 自动识别角色特征，保持风格一致

### 🌓 界面体验
> 精心打磨的用户体验

- ✅ **明暗主题** - 支持明亮/暗黑模式切换，保护视力
- ✅ **响应式设计** - 完美适配桌面端、平板、手机
- ✅ **会话管理** - 本地存储对话历史，支持多会话切换
- ✅ **实时反馈** - Toast 提示、进度条、加载动画
- ✅ **错误处理** - 友好的错误提示和重试机制
- ✅ **快捷操作** - 编辑、重新生成、复制等快捷按钮

## 🚀 快速开始

### 方式一：直接使用（推荐）

1. **下载文件**
   ```bash
   # 克隆仓库
   git clone https://github.com/yourusername/gemini-pro-workbench.git
   
   # 或直接下载 HTML 文件
   wget https://github.com/yourusername/gemini-pro-workbench/raw/main/Gemini-3-Pro-绘图工作台全能修复版-XHS-BananaPrompt.html
   ```

2. **打开文件**
   - 双击 HTML 文件
   - 或右键选择"使用浏览器打开"
   - 推荐使用 Chrome/Edge/Firefox 最新版

3. **开始使用**
   - 无需安装任何依赖
   - 无需配置服务器
   - 开箱即用！

### 方式二：本地服务器（可选）

```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server -p 8000

# 访问 http://localhost:8000
```

---

## ⚙️ API 配置

### 方法一：Gemini 原生接口

1. **获取 API Key**
   - 访问 [Google AI Studio](https://makersuite.google.com/app/apikey)
   - 创建 API Key

2. **配置渠道**
   ```
   渠道名称: Gemini 官方
   接口类型: Gemini 原生接口
   API Base URL: https://generativelanguage.googleapis.com
   API Key: 你的 Gemini API Key
   Model: gemini-3-pro-image-preview
   ```

3. **保存配置**
   - 点击右上角设置图标 ⚙️
   - 展开「API 渠道管理」
   - 填写上述信息
   - 点击「保存渠道」

### 方法二：OpenAI 兼容接口

支持任何 OpenAI 兼容的 API 服务：

```
渠道名称: OpenAI / 其他服务
接口类型: OpenAI 兼容接口
API Base URL: https://api.openai.com (或其他兼容服务)
API Key: 你的 API Key
Model: gpt-4o (或其他支持图像生成的模型)
```

**支持的服务：**
- OpenAI 官方
- OpenRouter
- Together AI
- 各类中转服务

### 多渠道管理

**添加多个渠道作为备用：**

1. 重复上述步骤添加多个渠道
2. 在「当前使用渠道」下拉框选择：
   - **🎲 随机优选** - 自动轮询所有渠道
   - **指定渠道** - 使用特定渠道

**优势：**
- ✅ 单个渠道失败自动切换
- ✅ 提高生成成功率
- ✅ 负载均衡，避免频率限制

## 📖 使用指南

### 基础绘图
1. 在底部输入框输入画面描述
2. （可选）点击上传图标添加参考图
3. 右侧设置分辨率和长宽比
4. 点击发送按钮生成图片
5. 生成后可下载、设为参考图或进行切割

### XHS 创作流程
1. 点击左侧「XHS 灵感实验室」
2. 输入创作主题或上传参考图
3. 设置需要生成的图片数量（1-9 张）
4. 点击「生成方案」，AI 自动策划文案和分镜
5. 查看右侧分镜列表，可编辑提示词或添加垫图
6. 点击「批量生成」一键生成所有配图
7. 复制文案，下载图片，发布到小红书

### 图片切割
1. 点击左侧「图片切片/九宫格」
2. 上传需要切割的图片
3. 选择横线或竖线模式
4. 点击画布添加切割线，拖拽调整位置
5. （可选）勾选「1:1 补全」生成正方形
6. 点击「生成切片」
7. 点击单个切片下载，或「一键打包下载」全部

### 提示词查询
1. 点击左侧「提示词快查」
2. 使用搜索框或分类标签筛选
3. 点击卡片复制提示词
4. 返回主界面粘贴使用

## 🛠️ 技术架构

### 前端技术
- **纯 HTML5** - 单文件应用，无需构建工具
- **原生 JavaScript** - 无框架依赖，轻量高效
- **CSS3 动画** - 流畅的交互体验
- **响应式设计** - 完美适配桌面端和移动端

### 数据存储
- **LocalStorage** - API 配置、用户设置持久化
- **IndexedDB** - XHS 历史记录、会话消息存储
- **Blob URL** - 图片临时缓存，自动清理

### 核心库
- **Marked.js** - Markdown 渲染（XHS 文案预览）
- **JSZip** - ZIP 打包（批量下载切片）

### API 支持
- **Gemini API** - 原生 `generateContent` 接口
- **OpenAI Compatible API** - `/v1/chat/completions` 标准接口

## 📱 响应式适配

### 桌面端（≥1600px）
- 三栏布局：侧边栏 + 主区域 + 设置栏
- XHS 分镜 3 列网格展示
- 完整功能面板

### 平板端（768px - 1600px）
- 两栏布局：主区域 + 可折叠侧边栏
- XHS 分镜自适应列数
- 触摸优化交互

### 移动端（<768px）
- 单栏布局：全屏主区域
- 抽屉式侧边栏
- XHS 分镜单列垂直排列
- 大号触摸按钮

## 🎨 界面特色

### 设计语言
- **Google Material Design** - 简洁现代的视觉风格
- **渐变色彩** - 小红书红、香蕉黄等品牌色
- **毛玻璃效果** - 半透明背景 + backdrop-filter
- **微动画** - hover、active 状态的细腻反馈

### 用户体验
- **实时反馈** - Toast 提示、进度条、加载动画
- **错误处理** - 友好的错误提示和重试机制
- **快捷操作** - 编辑、重新生成、复制等快捷按钮
- **无缝切换** - 会话历史、工具模式快速切换

## 🔒 隐私安全

- ✅ **本地优先** - 所有数据存储在浏览器本地
- ✅ **无服务器** - 不依赖任何后端服务
- ✅ **API 加密** - API Key 仅存储在 LocalStorage
- ✅ **跨域安全** - 图片处理遵循 CORS 策略
- ✅ **开源透明** - 代码完全开放，可自行审计

## 🐛 已知问题

- 部分浏览器可能不支持 `backdrop-filter`（毛玻璃效果）
- 跨域图片无法直接切割（需下载后重新上传）
- IndexedDB 在隐私模式下可能不可用

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 开发建议
1. 使用现代浏览器（Chrome/Edge/Firefox 最新版）
2. 开启开发者工具查看控制台日志
3. 修改代码后直接刷新页面测试
4. 提交前确保代码格式统一

### 功能建议
- [ ] 支持更多 AI 模型（DALL-E, Midjourney 等）
- [ ] 批量导出会话记录
- [ ] 自定义提示词模板库
- [ ] 图片编辑功能（裁剪、滤镜等）
- [ ] 多语言支持

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

## 🙏 致谢

- [Gemini API](https://ai.google.dev/) - 强大的多模态 AI 能力
- [Banana Prompt](https://github.com/glidea/banana-prompt-quicker) - 优质提示词社区
- [Marked.js](https://marked.js.org/) - Markdown 解析库
- [JSZip](https://stuk.github.io/jszip/) - JavaScript ZIP 库

## 📮 联系方式

- **Issues**: [GitHub Issues](https://github.com/Tansuo2021//gemini-pro-workbench/issues)
- **Discussions**: [GitHub Discussions](https://github.com/Tansuo2021//gemini-pro-workbench/discussions)

---

**⭐ 如果这个项目对你有帮助，请给个 Star 支持一下！**

*Made with ❤️ by AI Enthusiasts*
