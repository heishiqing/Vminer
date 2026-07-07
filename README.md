<div align="center">

<img src="docs/icon.png" width="96" alt="Vminer" />

# Vminer

### PRL 挖矿 Windows 一站式管理工具，解压即用

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_群-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## 📖 Vminer 是什么

Vminer 是一个 PRL 挖矿 Windows 桌面管理器，解压后双击即可使用。专注 **NVIDIA 显卡**挖矿，内置多家矿池和挖矿内核，一键配置、连通性检查、状态监控和矿池余额查询。

适合需要快速配置矿池、切换挖矿内核、查看算力和份额、查询矿池余额的 N 卡用户。

<div align="center">
  <img src="docs/screenshot.png" width="820" alt="Vminer 控制台">
</div>

## 📥 下载

<div align="center">

### [⬇️ 下载最新版 v0.2.6](https://github.com/heishiqing/Vminer/releases/latest)

</div>

下载压缩包后解压，双击根目录 `Vminer.exe` 启动。压缩包内包含 `使用说明.md` 和 `User Guide.md`。

> 🆕 **v0.2.6 更新**：修复服务器线路异常后连接恢复和备用线路切换不及时的问题 · 修复远程热更新证书校验兼容问题 · 修复内核版本列表刷新，服务器上架新内核后客户端可显示新版本 · 优化矿池余额和币价查询的备用线路等待时间。完整记录见 [CHANGELOG](CHANGELOG.md)。

> 🔗 **P 池 MDL 钱包绑定工具**：如果使用 PearlHash / P 池的 MDL 绑定模式，可下载 [MDL 钱包绑定签名助手](https://github.com/heishiqing/pearl-mdl-bind-helper/releases/latest/download/P.MDL.zip)，解压后按中文提示双击运行脚本。

## ✨ 功能

- **一键挖矿**：填钱包、选矿池、点开始，自动下载并启动对应挖矿内核。
- **MDL 双挖**：支持 PRL + MDL 合并挖矿，在支持双挖的矿池中可同时填写 PRL 与 MDL 钱包。
- **多矿池**：内置 8 家矿池，软件内一键切换。
- **状态显示**：在线状态、显卡数量、算力、接受份额、拒绝份额和运行状态一目了然。
- **日志查看**：运行日志、矿池连接和挖矿内核输出。
- **矿池余额查询**：软件内直接查矿池侧余额、已支付、份额、在线矿机数（中国大陆无需梯子）。
- **相关网站**：一键直达官网、钱包、区块浏览器、各大矿池官网。
- **实时币价**：软件内查看实时 PRL 币价（中国大陆无需梯子）。
- **自动运行**：开机启动、软件启动后自动挖矿、后台静默模式。
- **网吧无盘系统**：支持把完整配置随客户端目录复制到母盘；新机器可读取矿池、内核、双挖、钱包和矿工名规则，矿工名留空时自动使用本机电脑名。
- **功耗与风扇**：NVIDIA 显卡功耗百分比设置 + 风扇转速控制（每 5 分钟自动巡查，漂移则按设置重新固化）。
- **起挖自检**：连不上、显卡驱动或杀毒拦截等问题会一键提示并停止，不无脑重试。
- **矿机名**：可加前缀或随机生成，方便区分多台机器。
- **全新界面**：暗色玻璃风格，左侧导航，操作更顺手。

## 🖥️ 显卡兼容

**NVIDIA 专版**，聚焦 N 卡能效与稳定性优化。软件会按显卡自动筛选可用内核和矿池。

## 🔌 支持矿池、软件、币种

**币种：** PRL

**矿池（8 家）：** AlphaPool、LuckyPool、F2Pool、HeroMiners、Kryptex、2Miners、PearlFortune、PearlHash

**挖矿软件：** SRBMiner、AlphaMiner、WildRig、TW（pearl-gpu）—— 按所选矿池自动匹配；内核首次启动按需下载，安装包更精简。

| 矿池 | 支持挖矿软件 | MDL 双挖 / 说明 |
|---|---|---|
| AlphaPool | AlphaMiner | 支持 MDL 双挖 |
| LuckyPool | SRBMiner、TW（pearl-gpu） | 支持 MDL 双挖（SRBMiner） |
| F2Pool（鱼池） | TW（pearl-gpu） | 使用 F2Pool 用户名 / 子账户挖矿；池内统计暂不支持 |
| HeroMiners | SRBMiner、TW（pearl-gpu） | 支持 MDL 双挖（SRBMiner） |
| Kryptex | SRBMiner、TW（pearl-gpu） | PRL 单挖 |
| 2Miners | SRBMiner、TW（pearl-gpu） | PRL 单挖 |
| PearlFortune | TW（pearl-gpu） | P 池绑定模式，使用上方 MDL 绑定工具 |
| PearlHash | WildRig | PRL 单挖 |

**内核版本：** SRBMiner 3.3.9 / 3.4.1 / 3.4.2 / 3.4.3；AlphaMiner 1.7.7 / 1.8.3 / 1.8.6；WildRig 0.48.9 / 0.49.1 / 0.49.2；TW 2.2.1 / 2.2.6 / 2.3.1 / 2.3.2。实际可选版本会随服务器清单更新。

## 🚀 快速上手

1. 填写 PRL 钱包地址。
2. 填写矿机名（可随机生成）。
3. 选择矿池和节点（挖矿内核自动匹配）。
4. 选择直连或加密代理。
5. 点击“测试连通性”，通过后点击“开始”。

## 💬 交流与反馈

| 渠道 | 入口 |
|---|---|
| QQ 群 | **245770181** |
| GitHub Issues | [提交 issue](https://github.com/heishiqing/Vminer/issues) |
| 更新日志 | [CHANGELOG.md](CHANGELOG.md) |

## ⚠️ 免责声明

请确认你有权在当前设备上运行挖矿程序。挖矿可能带来电力消耗、硬件温度上升和设备损耗风险。收益、矿池稳定性和网络连通性不做保证。请遵守所在地法律法规和平台规则。

## ❤️ 支持作者

如果喜欢本软件，请助力作者发电。

<div align="center">
  <img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="爱发电 - heishiqing">
</div>

## 🔗 作者其他项目

- [Vbot-B](https://github.com/heishiqing/Vbot-B)：B 站私信自动回复机器人。
