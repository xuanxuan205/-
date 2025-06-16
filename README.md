# SuperCrackerApp - 密码破解工具

## 简介

SuperCrackerApp 是一个功能强大的密码破解工具，旨在帮助用户恢复各种加密文件的密码。它支持多种文件类型，包括 ZIP、RAR、7z、Office 文档和 PDF 文件，并提供了多种破解模式，包括字典攻击和精确掩码攻击。

**免责声明：本工具仅供学习、研究和合法用途。请勿将此工具用于非法活动。使用者需自行承担所有风险和责任。**

## 特性

- **多文件类型支持**：支持破解 ZIP、RAR、7z、Microsoft Office (Word, Excel, PowerPoint) 和 PDF 文件的密码。
- **多种破解模式**：
  - **字典攻击**：使用预设的密码字典进行尝试。
  - **掩码攻击**：通过指定密码字符集和长度范围进行精确的暴力破解（例如：`?l?l?l` 匹配所有三位小写字母组合）。
- **用户友好界面**：基于 Tkinter 构建的直观图形用户界面，方便文件选择、模式配置和进度监控。
- **进度管理**：支持保存和加载破解进度，避免重复劳动。
- **文件类型检测**：自动识别文件类型并调用相应的破解模块。
- **并发处理**：支持同时处理多个破解任务（待实现或未来增强）。
## 许可证

本项目根据 MIT 许可证发布。有关详细信息，请参阅 `LICENSE` 文件。

---

**MIT 许可证**

```
MIT License

Copyright (c) 2024 [你的名字或组织名称]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
