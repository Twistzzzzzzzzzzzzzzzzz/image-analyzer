# Image Analyzer

Claude Code Skill — 让 Claude 结构化分析图片内容。支持五大场景：截图分析、UI 审查、图表解读、OCR 文字提取、照片描述。

## 安装

```bash
npx skills add https://github.com/Twistzzzzzzzzzzzzzzzzz/image-analyzer.git
```

或手动克隆：

```bash
git clone https://github.com/Twistzzzzzzzzzzzzzzzzz/image-analyzer.git ~/.claude/skills/image-analyzer
```

## 功能

| 场景 | 说明 | 触发示例 |
|------|------|----------|
| **截图分析** | 识别界面布局、元素、文字和交互状态 | "看看这个截图有什么问题" |
| **UI 审查** | 设计稿可用性评估、排版分析和改进建议 | "review 这个页面设计" |
| **图表解读** | 数据图表、流程图、架构图的结构化解读 | "这个架构图什么意思" |
| **OCR 提取** | 从图片中提取文字，保留原文格式 | "提取这张图里的文字" |
| **照片描述** | 场景、主体、环境、氛围的全面描述 | "这张照片里有什么" |

## 特性

- 5 种结构化分析模板，输出专业一致
- 支持单张和批量图片处理
- 输出格式可选：详细报告 / 简短描述 / 纯文字
- 中文输出，文字原文保留
- 隐私提醒：自动提示注意人脸、证件号等敏感信息

## 使用

在 Claude Code 中，直接提及图片文件路径或粘贴截图路径即可：

```
分析这张截图：/path/to/screenshot.png
```

也可以说：

```
帮我看看这张照片里有什么
review 这个 UI 设计稿
提取这三张图片里的文字
```

## License

MIT
