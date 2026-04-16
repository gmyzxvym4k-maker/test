# AI Word Document & Collaboration Platform

一个基于 Web 的 AI 文档编辑与协作平台，支持智能评论、富文本编辑和 Word 文档导入导出功能。

## 功能特性

- 📝 **富文本编辑** - 支持内容可编辑的文档界面
- 💬 **智能评论系统** - 可点击的评论功能，支持协作文档讨论
- 📄 **Word 文档支持** - 支持 OOXML Word 文档的解析和导入
- 🤖 **AI 模型集成** - 集成 AI 模型，支持本地回退模式
- 📤 **导出功能** - 支持导出为 HTML 和 Word 格式

## 技术栈

- HTML5
- CSS3
- JavaScript (jQuery)
- 内容可编辑 (contenteditable) API

## 快速开始

直接在浏览器中打开 `index.html` 文件即可使用：

```bash
# 使用任意静态文件服务器
python -m http.server 8000
```

然后在浏览器中访问 `http://localhost:8000`

## 项目结构

```
.
├── index.html          # 主页面文件
└── README.md           # 项目说明文档
```

## 待实现功能

以下功能已在代码中标注，等待实现：

- [ ] OOXML Word 文档解析和导入功能
- [ ] 富文本编辑功能完善
- [ ] 智能评论系统实现
- [ ] AI 模型集成与本地回退模式
- [ ] HTML 和 Word 导出功能

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

MIT License
