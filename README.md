# AI 简历生成器 | AI Resume Builder

一个纯前端的 AI 简历生成器，用户填写基本信息后，AI 自动优化描述，生成专业简历。

## ✨ 功能特性

- **表单填写** — 个人信息、工作经历、教育背景、技能特长
- **AI 优化** — 调用 DeepSeek API 自动润色工作经历描述（STAR 法则）
- **3 种模板** — 简约 / 专业 / 创意，切换即时预览
- **实时预览** — 左侧编辑，右侧实时渲染简历
- **PDF 导出** — 基于浏览器打印，A4 尺寸完美适配
- **中英双语** — 界面一键切换中文/英文
- **数据持久化** — 自动保存到 localStorage，刷新不丢失
- **示例数据** — 首次打开自动填充示例，快速体验

## 🚀 使用方式

直接用浏览器打开 `index.html` 即可：

```bash
open index.html
# 或
# python3 -m http.server 8080  然后访问 http://localhost:8080
```

## 🤖 AI 优化功能

1. 点击右上角 **🤖 API** 按钮
2. 输入你的 [DeepSeek API Key](https://platform.deepseek.com/)
3. 在工作经历描述旁点击 **✨ AI 优化**
4. AI 会自动用 STAR 法则润色你的工作描述

## 📄 PDF 导出

- 点击右上角 **导出 PDF** 按钮（或 `Ctrl/Cmd + P`）
- 在打印对话框中选择「保存为 PDF」
- 建议设置：A4 纸张、无边距、启用背景图形

## 📐 简历模板

| 模板 | 风格 | 适用场景 |
|------|------|----------|
| 简约 | 干净留白，单栏布局 | 技术岗、外企 |
| 专业 | 双栏深色侧边栏 | 传统行业、管理岗 |
| 创意 | 渐变头部，时间线 | 设计、创意岗位 |

## 🛠 技术方案

- 纯前端：HTML + CSS + JavaScript，单个 `index.html`
- 无需构建工具，无需 Node.js
- DeepSeek Chat API 优化文案
- CSS `@media print` 实现 PDF 导出
- `localStorage` 数据持久化
- Google Fonts (Inter) 优化排版

## 💰 变现思路

- 免费基础版引流（3 个模板）
- 付费解锁高级模板（更多设计风格）
- 付费 AI 优化次数包
- 广告收入

## License

MIT
