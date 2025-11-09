# 📝 Markdown转换工具

一个简单易用的Web工具，将AI生成的Markdown内容转换为TXT、Word等格式，方便分享。

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

🌐 **在线访问**：[https://riverxue.github.io/MdToEvery/](https://riverxue.github.io/MdToEvery/)

## 💡 解决什么问题？

**痛点**：使用ChatGPT、Claude、文心一言等AI工具时，生成的内容都是Markdown格式。直接复制分享到微信、QQ、邮件时，会显示大量Markdown语法（`**粗体**`、`# 标题`等），很不美观。

**解决方案**：一键将Markdown转换为纯文本或Word文档，分享更专业、更美观！

## ✨ 功能特点

- 🔄 **Markdown转TXT**：去除所有Markdown语法，生成纯文本文件
- 📘 **Markdown转Word**：保留格式（标题、粗体、列表等），生成.docx文件
- 🌐 **Markdown转HTML**：转换为HTML格式，便于预览
- 📋 **多种输入方式**：支持粘贴、文件上传
- 📱 **响应式设计**：完美支持手机和电脑端
- ⚡ **纯前端实现**：无需服务器，直接在浏览器使用

## 🚀 使用方法

### 方法一：直接打开（推荐）

1. 下载所有文件到本地
2. 双击打开 `index.html` 文件
3. 在浏览器中使用

### 方法二：部署到服务器

1. 将所有文件上传到Web服务器
2. 通过浏览器访问 `index.html`

### 方法三：GitHub Pages（已部署）

✅ **项目已部署到GitHub Pages**

🌐 **在线访问**：[https://riverxue.github.io/MdToEvery/](https://riverxue.github.io/MdToEvery/)

**部署步骤**：
1. 访问仓库：https://github.com/RiverXue/MdToEvery
2. 进入 Settings → Pages
3. 选择 Source: main branch
4. 保存后等待1-2分钟即可访问

详细部署说明请查看：[GitHub_Pages部署指南.md](./GitHub_Pages部署指南.md)

## 📖 使用步骤

1. **输入内容**
   - 点击"粘贴"按钮自动粘贴剪贴板内容
   - 或点击"上传文件"选择.md文件
   - 或直接在文本框中输入/粘贴Markdown内容

2. **选择转换格式**
   - 点击"转TXT"：生成纯文本文件（去除所有Markdown语法）
   - 点击"转Word"：生成Word文档（保留格式）
   - 点击"转HTML"：生成HTML文件（可在浏览器中查看）

3. **下载文件**
   - 转换完成后，点击"下载文件"按钮
   - 文件会自动下载到本地

## 🎯 适用场景

- ✅ **AI内容分享**：ChatGPT/Claude生成的内容分享到微信、QQ、邮件
- ✅ **文档转换**：将AI生成的报告转换为Word文档，更专业
- ✅ **去除语法**：去除Markdown语法，只保留纯文本，更易读
- ✅ **格式预览**：快速预览Markdown渲染效果
- ✅ **内容整理**：将AI对话内容整理成正式文档

## 📱 使用场景示例

### 场景1：AI对话内容分享
从ChatGPT复制内容 → 粘贴到工具 → 转TXT → 分享到微信（纯文本，无语法）

### 场景2：制作正式文档
AI生成报告 → 转Word → 下载 → 在Word中进一步编辑

### 场景3：内容整理
AI对话记录 → 转HTML → 保存为网页 → 分享给团队

## 💡 技术说明

- **纯前端实现**：使用HTML + CSS + JavaScript
- **核心库**：
  - `marked`：Markdown解析
  - `docx`：Word文档生成
  - `FileSaver.js`：文件下载

## 📝 文件说明

- `index.html` - 主页面
- `style.css` - 样式文件
- `script.js` - 主要功能逻辑
- `README.md` - 使用说明

## 🔧 浏览器兼容性

- Chrome/Edge（推荐）
- Firefox
- Safari
- 移动端浏览器

## 🌟 为什么选择这个工具？

- 🚀 **完全免费**：无需注册，无需付费
- ⚡ **即开即用**：打开网页就能用，无需安装
- 📱 **全平台支持**：手机、电脑都能用
- 🔒 **隐私安全**：纯前端处理，数据不上传服务器
- 🎨 **界面美观**：苹果风格设计，使用体验好

## 📄 许可证

MIT License - 自由使用和修改

## 🤝 贡献

欢迎提交Issue和Pull Request！

## 📢 分享给朋友

如果这个工具对你有帮助，欢迎分享给需要的朋友！

- 🔗 在线地址：https://riverxue.github.io/MdToEvery/
- ⭐ GitHub：https://github.com/RiverXue/MdToEvery

## 🏷️ 相关标签

`markdown` `converter` `ai-tools` `chatgpt` `word-converter` `markdown-to-word` `markdown-to-txt` `web-tool` `frontend` `javascript`

---

**提示**：如果遇到问题，请确保浏览器支持现代JavaScript特性，并检查网络连接（需要加载CDN资源）。

