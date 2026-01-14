# Stationeers Server UI（工位元服务器界面）

> [!IMPORTANT]
> 本项目根据 SSUI [许可证](LICENSE)授权，不允许重新分发。
> 请勿 fork，而是加入 [Discord](https://discord.gg/8n3vN92MyJ) 说明您的意图或[提交问题](https://github.com/SteamServerUI/SteamServerUI/issues)。

> [!TIP]
> **如何使用中文界面：** 在配置文件 `config.json` 中将 `LanguageSetting` 设置为 `"zh-CN"`，或使用环境变量 `LANGUAGE_SETTING=zh-CN`。

![Go](https://img.shields.io/badge/Go-1.25.0-blue?logo=go&logoColor=white)
![Version](https://img.shields.io/github/v/release/jacksonthemaster/StationeersServerUI?logo=github&logoColor=white)
![Issues](https://img.shields.io/github/issues/jacksonthemaster/StationeersServerUI?logo=github&logoColor=white)
![Stars](https://img.shields.io/github/stars/jacksonthemaster/StationeersServerUI?style=social&logo=github)
![Windows](https://img.shields.io/badge/Windows-支持-blue?logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-支持-green?logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-可用-blue?logo=docker&logoColor=white)
![Downloads](https://img.shields.io/github/downloads/jacksonthemaster/StationeersServerUI/total?logo=github&logoColor=white)
![Last Commit](https://img.shields.io/github/last-commit/jacksonthemaster/StationeersServerUI?logo=git&logoColor=white)
![Stationeers](https://img.shields.io/badge/游戏-Stationeers-orange?logo=steam&logoColor=white)

管理 Stationeers 专用服务器不应该需要 Linux 博士学位或花费数小时编辑配置文件和阅读 Wiki。SSUI 为您提供强大的 Web 界面、自动备份、Discord 集成和专业的服务器管理 - 所有这些都来自一个可执行文件。没有麻烦，只有一个正常运行的服务器。几分钟内完成。

## ✨ 功能展示 ✨

| 🚀 简易设置 | 默认安全 | 🔄 自动更新 | 🎮 简易控制 | 💾 智能备份 | 🤖 Discord 机器人 | 🛠️ 命令管理器 | 🧩 模组支持 | 
|:-------------:|:-----------------:|:---------------:|:----------------:|:----------------:|:--------------:|:------------------:|:-------------:|
| 运行即用 | JWT 认证、TLS | 启动时游戏服务器更新 | 一键管理 | 自动化系统 | 远程控制 | 执行服务器命令 | BepInEx 集成 |

<div align="center">

### 🌟 这是一个 Web 界面，您无需图形化操作系统即可运行 🌟

[![下载页面](https://img.shields.io/badge/打开-下载页面-orange?style=for-the-badge)](https://steamserverui.github.io/StationeersServerUI/)

[![下载最新 Windows 版本](https://img.shields.io/badge/直接-Windows%20下载-blue?style=for-the-badge)](https://steamserverui.github.io/StationeersServerUI/?download=windows)
[![下载最新 Linux 版本](https://img.shields.io/badge/直接-Linux%20下载-%23FCC624?style=for-the-badge&logo=linux&logoColor=%23FCC624)](https://steamserverui.github.io/StationeersServerUI/?download=linux)

[![预览网站](https://img.shields.io/badge/访问-在线预览-green?style=for-the-badge)](https://steamserverui.github.io/StationeersServerUI/preview/server.html)
</div>

</div>
<div align="center">
  <img src="media/events-preview.png" width="800" onclick="window.open('https://steamserverui.github.io/StationeersServerUI/server.html')">
  
  <em>优雅地管理您的 Stationeers 服务器 - 复古界面，现代功能。</em>
</div>


## TL;DR - 快速入门

📚 访问 [Wiki](https://github.com/JacksonTheMaster/StationeersServerUI/wiki) 中的[快速入门指南](https://github.com/SteamServerUI/StationeersServerUI/wiki/Quick-Start-Guide)
⛓️‍💥 按照链接页面（页面底部的链接）操作！
📖 完整文档在 [Wiki](https://github.com/JacksonTheMaster/StationeersServerUI/wiki) 中提供。

## 这是什么？

一个时尚的复古主题 Web UI，用于管理您的 Stationeers 专用服务器。不再需要命令行头痛或手动编辑文件！


### 为什么您会喜欢它

- 🚀 **零配置设置** - 放在空文件夹中运行即可
- 🔌 **自动 SteamCMD 设置** - 无需手动安装
- 🔄 **自动更新** - 服务器和管理 UI 在启动时自动更新
- 🎮 **一键控制** - 通过简单的按钮启动/停止服务器或恢复备份
- 💾 **智能备份** - 具有轻松恢复功能的自动备份系统
- 🤖 **Discord 集成** - 通过 Discord 控制您的服务器
- 🔒 **默认安全** - JWT 认证和 TLS
- 🛠️ **命令管理器** - 直接从 UI 或从 Discord 命令执行服务器命令
- 🧩 **模组支持** - 支持 BepInEx 模组
- 📦 **Docker 支持** - 在 Docker 容器中运行
- 🛠️ **Stationeers 服务器命令管理器** - 直接通过 UI、API 或 Discord 命令执行服务器命令
- 🧩 **BepInEx 集成** - 自动设置流行的模组框架

## 详细文档

如需全面的说明、示例和更多详细信息，请访问我们的 [GitHub Wiki](https://github.com/JacksonTheMaster/StationeersServerUI/wiki)。

| 文档部分 | 描述 |
|----------------------|-------------|
| [功能](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Features) | 接近完整的功能和能力列表 |
| [系统要求](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Requirements) | 系统要求和先决条件 |
| [安装](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Installation) | 分步安装指南 |
| [首次设置](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/First-Time-Setup) | 让您的服务器启动并运行 |
| [Discord 集成](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Discord-Integration) | 设置和使用 Discord 功能 |
| [Web 界面](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Web-Interface) | 有效使用 Web UI |
| [Docker 指南](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Docker-Guide) | 在 Docker 容器中运行 |
| [安全注意事项](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Security-Considerations) | 重要的安全最佳实践 |

## Web UI 预览

_点击图片放大。_

| UI 概览 | 配置 | 备份管理 |
|:-----------:|:-------------:|:-----------------:|
| ![UI 概览](media/UI-4.png) | ![配置](media/UI-2.png) | ![备份管理](media/UI-3.png) |

## Discord 预览

_点击图片放大。_

| 连接日志 | 保存日志 | 面板 | Discord 命令 |
|:-----------:|:-------------:|:-----------------:|:-------------:|
| ![连接日志](media/discord-connections.png) | ![保存日志](media/discord-saves.png) | ![面板](media/discord-panel.png) | ![Discord 命令](media/discord-commands.png) |

## 贡献

喜欢这个项目吗？我很乐意您帮助改进它！请参阅[贡献指南](https://github.com/JacksonTheMaster/StationeersServerUI/wiki/Contributing)开始。

- 🐛 **发现错误？**[提交问题](https://github.com/JacksonTheMaster/StationeesServerUI/issues)
- 💡 **有想法？**[建议功能](https://github.com/JacksonTheMaster/StationeesServerUI/issues/new?labels=enhancement)
- 🤔 **有问题？**[查看 Wiki](https://github.com/JacksonTheMaster/StationeesServerUI/wiki) 或[发起讨论](https://github.com/JacksonTheMaster/StationeesServerUI/issues/new?labels=question)。

## 许可证

本项目根据 STATIONEERS SERVER UI LICENSE AGREEMENT 授权 - 有关详细信息，请参阅 [LICENSE](LICENSE) 文件。

---

## 语言版本 / Language Versions

- [English](readme.md) - 英文版本
- [中文](readme_zh-CN.md) - 中文版本（当前）
