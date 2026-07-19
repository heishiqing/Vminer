<div align="center">

<img src="docs/icon.png" width="96" alt="Vminer" />

# Vminer

### Windows PRL/BTX 与 macOS BTX 挖矿客户端，解压即用

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_群-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## Vminer 是什么

Vminer 是桌面挖矿管理工具。用户下载压缩包、解压、双击程序即可使用。

- **Windows 版**：支持 PRL 与 BTX 挖矿，主要面向 NVIDIA 显卡，提供多矿池、多挖矿内核、连接检测、状态监控和矿池信息查询。
- **macOS 版**：面向 BTX 挖矿，支持 Apple Silicon Mac，默认走加密代理模式连接 minebtx，用户钱包默认留空，首次运行后自行填写。

<div align="center">
  <img src="docs/screenshot.png" width="820" alt="Vminer 控制台" />
</div>

## 下载

| 系统 | 当前版本 | 下载 | 启动方式 |
|---|---:|---|---|
| Windows | v0.2.9 | [下载 Vminer-v0.2.9.zip](https://github.com/heishiqing/Vminer/releases/download/v0.2.9/Vminer-v0.2.9.zip) | 解压后双击根目录 `Vminer.exe` |
| macOS Apple Silicon | v0.0.1 | [下载 Vminer-mac-v0.0.1.zip](https://github.com/heishiqing/Vminer/releases/download/mac-v0.0.1/Vminer-mac-v0.0.1.zip) | 解压后双击 `Vminer.app` |

macOS 独立发布页：[mac-v0.0.1](https://github.com/heishiqing/Vminer/releases/tag/mac-v0.0.1)。

macOS 首次运行如果出现安全提示，请在 Finder 中右键 `Vminer.app`，选择“打开”一次。正式包内用户钱包为空，首次运行后自行填写。

Windows 压缩包内包含 `使用说明.md` 和 `User Guide.md`。

## Windows 版功能

- PRL 与 BTX：在单机设置中选择币种，并自动显示对应的矿池和挖矿软件。
- 一键挖矿：填写钱包或矿池用户名、选择矿池、点击开始。
- 多矿池：支持 AlphaPool、LuckyPool、F2Pool、HeroMiners、Kryptex、2Miners、PearlFortune、PearlHash。
- 多内核：支持 SRBMiner、AlphaMiner、WildRig、TW pearl-gpu、PeakMiner，按所选矿池自动匹配，并从服务器签名列表获取可用版本。
- BTX 挖矿：Windows 版支持 LuckyPool BTX 与 SRBMiner 3.4.6。
- MDL 双挖：在支持的矿池中可同时填写 PRL 与 MDL 钱包。
- 状态显示：在线状态、显卡数量、算力、份额、拒绝份额、运行日志。
- 稳定恢复：优化断线、长时间无任务和无有效份额时的自动恢复，并降低慢份额矿池的误判。
- 明确诊断：钱包/用户名、矿池登录、内核下载、显卡和网络异常提供中英文提示。
- 相关网站：一键打开官网、钱包、区块浏览器、矿池和交易所等链接。
- 自动运行：支持开机启动、软件启动后自动挖矿。
- 网吧无盘：支持配置随客户端目录保存，便于复制到母盘。

## Windows 内核适配列表

| 挖矿内核 | 当前默认版本 | PRL 适配矿池 | BTX 适配矿池 |
|---|---:|---|---|
| SRBMiner | 3.4.6 | LuckyPool、HeroMiners、Kryptex、2Miners、F2Pool | LuckyPool BTX |
| AlphaMiner | 1.7.7 | AlphaPool | — |
| WildRig | 0.49.5 | PearlHash | — |
| TW pearl-gpu | 3.2.2 | LuckyPool、HeroMiners、Kryptex、2Miners、F2Pool、PearlFortune | — |
| PeakMiner | 2.1.1 | LuckyPool、HeroMiners、Kryptex、AlphaPool、F2Pool、2Miners | — |

内核版本由服务器签名列表动态提供。旧版本会按兼容性需要保留在版本下拉框中；AlphaMiner 当前仍以稳定的 `1.7.7` 为默认版本，`1.8.3` 与支持 MDL 的 `1.8.6` 可手动选择。

## macOS BTX 版

- 支持 Apple Silicon macOS 设备。
- 默认连接方式为加密代理模式。
- 默认悬浮窗关闭。
- 用户钱包默认留空，首次运行后由用户自行填写。
- 支持中文/英文界面、开机启动、启动后自动挖矿、矿池算力/份额同步、BTX/USDT 价格显示。
- 当前内核：`dexbtx-miner 0.4.20`。
- 当前矿池：`minebtx`。算力和份额以矿池接口返回为准。
- macOS 版当前发布版本号：`0.0.1`。

## 快速开始

1. 下载对应系统的压缩包。
2. 解压到本地文件夹。
3. 双击启动程序。
4. 填写钱包地址和矿工名。
5. 选择矿池和连接方式，点击开始挖矿。

## 交流与反馈

| 渠道 | 入口 |
|---|---|
| QQ 群 | **245770181** |
| GitHub Issues | [提交 issue](https://github.com/heishiqing/Vminer/issues) |
| 更新日志 | [CHANGELOG.md](CHANGELOG.md) |

## 免责声明

请确认你有权在当前设备上运行挖矿程序。挖矿可能带来电力消耗、硬件温度上升和设备损耗风险。收益、矿池稳定性和网络连通性不做保证。请遵守所在地法律法规和平台规则。

## 支持作者

如果喜欢本软件，可以助力作者发电。

<div align="center">
  <img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="爱发电 - heishiqing" />
</div>

## 作者其他项目

- [Vbot-B](https://github.com/heishiqing/Vbot-B)：B 站私信自动回复机器人。
- [pearl-proxy](https://github.com/heishiqing/pearl-proxy)：PRL 加密转发软件。
