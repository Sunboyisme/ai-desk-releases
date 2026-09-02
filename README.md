# AI个人效率助手（AI Desk）

AI个人效率助手是一款面向 Windows 的桌面 AI 问答与效率工具，集成日常问答、解释、总结、翻译、专注计时和常用文本，减少在多个工具之间切换。

## 下载最新版

[下载 AI Desk v4.0.3 Windows x64 安装包](https://github.com/Sunboyisme/ai-desk-releases/releases/latest/download/AI-Desk-v4.0.3-Windows-x64-Setup.exe)

也可以进入 [Releases 页面](https://github.com/Sunboyisme/ai-desk-releases/releases/latest) 查看版本说明和校验文件。

## 使用前说明

- 支持 Windows x64。
- AI 问答和翻译需要用户自行配置兼容 OpenAI 接口格式的服务、模型与 API Key。
- 当前安装包尚未进行商业代码签名，Windows 可能显示“未知发布者”。请确认下载地址及 SHA-256 后再运行。
- 本产品不宣称提供内置联网搜索或实时网页检索。

## 文件校验

v4.0.3 安装包 SHA-256：

```text
88003A613BCFB1E80D01CFB40C62203CB80D504D473E52DD8B357577DC05A568
```

PowerShell 校验命令：

```powershell
Get-FileHash -Algorithm SHA256 .\AI-Desk-v4.0.3-Windows-x64-Setup.exe
```

输出应与上方 SHA-256 完全一致。

## 安全下载

请只从本仓库的 Releases 页面下载安装包。不要运行来源不明、文件名相似但校验值不一致的文件。
