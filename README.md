<div align="center">

# Vminer

### PRL 挖矿 Windows 一站式管理工具，解压即用

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_群-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## Vminer 是什么

Vminer 是一个 PRL 挖矿 Windows 桌面管理器，聚合多款挖矿软件和多个矿池配置。无需 Docker，下载后解压即可使用。

适合想要降低命令行配置成本、快速切换矿池、管理多显卡、查看运行状态和日志的 Windows 用户。

<div align="center">
  <img src="docs/screenshot.png" width="820" alt="Vminer 控制台">
</div>

## 核心功能

**挖矿管理**

- 解压即用，无需安装 Docker。
- 支持多矿池配置切换。
- 支持全部显卡或指定显卡编号运行。
- 支持直连和加密代理两种连接方式。
- 运行时自动锁定关键设置，停止后再修改。

**状态与日志**

- 实时显示在线状态、显卡数量、算力、接受份额、拒绝份额和运行状态。
- 显示矿机列表，包括矿机名、软件、矿池、显卡、算力和最后更新时间。
- 彩色运行日志，便于区分正常连接、错误和程序输出。
- 可测试连通性，不会实际启动挖矿。

**使用体验**

- 设置自动保存。
- 支持开机启动。
- 支持软件启动后自动开始。
- 支持最小化到右下角托盘，默认不勾选。
- 内置软件说明、更新日志和矿池后台入口。

**透明性**

- 客户端不篡改矿池任务包。
- 客户端不替换用户钱包地址。
- 用户可以自行检查设置、运行日志、进程参数和网络连接。

## 下载

<div align="center">

### [下载最新版 v0.1.4](https://github.com/heishiqing/Vminer/releases/latest)

</div>

下载压缩包后解压，双击根目录 `Vminer.exe` 启动。首次启动会显示软件说明。

## 兼容性

| 挖矿软件 | 支持矿池 | 状态 |
|---|---|---|
| lpminer | LuckyPool, BaikalMine | 已接入 |
| AlphaMiner | AlphaPool | 已接入 |
| Pearl Miner | PearlHash | 等待官方 Windows 版本 |

显卡支持：

| 显卡类型 | 状态 |
|---|---|
| NVIDIA RTX 30/40 系列 | 推荐使用 |
| NVIDIA RTX 50 系列 | 已加入兼容性提示，请按软件说明检查驱动和矿工支持 |
| AMD | 暂不支持 |

## 快速上手

1. 填写 PRL 钱包地址。
2. 填写矿机名。
3. 选择挖矿软件、矿池和节点。
4. 选择直连或加密代理。
5. 点击“测试连通性”，通过后点击“开始”。

## 交流与反馈

| 渠道 | 入口 |
|---|---|
| QQ 群 | 245770181 |
| GitHub Issues | [提交 issue](https://github.com/heishiqing/Vminer/issues) |
| 更新日志 | [CHANGELOG.md](CHANGELOG.md) |

## 免责声明

请确认你有权在当前设备上运行挖矿程序。挖矿可能带来电力消耗、硬件温度上升和设备损耗风险。收益、矿池稳定性和网络连通性不做保证。请遵守所在地法律法规和平台规则。

## 支持作者

如果 Vminer 帮你节省了时间，欢迎支持作者。

<img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="爱发电 - heishiqing">

## 作者其他项目

- [Vbot-B](https://github.com/heishiqing/Vbot-B)：B 站私信自动回复机器人。
