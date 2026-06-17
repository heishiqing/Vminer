<div align="center">

# ⛏️ Vminer

### PRL 挖矿 Windows 一站式管理工具，解压即用

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_群-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## 📖 Vminer 是什么

Vminer 是一个 PRL 挖矿 Windows 桌面管理器，解压后双击即可使用。软件支持单机挖矿和局域网群控，可管理启动、停止、状态监控、连通性检查和矿池后台跳转。

适合需要快速配置矿池、切换挖矿软件、查看算力和份额，或在局域网内统一管理多台 Windows 机器的用户。

<div align="center">
  <img src="docs/screenshot.png" width="820" alt="Vminer 控制台">
</div>

## 📥 下载

<div align="center">

### [⬇️ 下载最新版 v0.2.0](https://github.com/heishiqing/Vminer/releases/latest)

</div>

下载压缩包后解压，双击根目录 `Vminer.exe` 启动。压缩包内包含 `使用说明.md` 和 `User Guide.md`。

> 🆕 **v0.2.0 更新**：修复自动更新闪退 · SRBMiner 升级 3.3.9（GPU 算力提升）· 新增 Kryptex（K）矿池 · 节点按 港 → 新 → 美 → 欧 智能优选 · 界面焕新。完整记录见 [CHANGELOG](CHANGELOG.md)。

## ✨ 功能

- **单机模式**：在当前 Windows 机器上运行挖矿。
- **群控模式**：管理同一局域网内的多台 Vminer 机器。
- **状态显示**：在线状态、显卡数量、算力、接受份额、拒绝份额和运行状态一目了然。
- **日志查看**：显示运行日志、矿池连接和挖矿程序输出。
- **矿池后台**：软件内直接查看矿池侧余额、已支付、份额、在线矿机数（中国大陆无需梯子），也可打开矿池后台网页。
- **实时币价**：软件内查看实时 PRL 币价（中国大陆无需梯子）。
- **自动运行**：支持开机启动、软件启动后自动挖矿、后台静默模式。
- **功耗设置**：支持 NVIDIA 显卡功耗百分比设置，每 5 分钟自动巡查、漂移则按设置重新固化。
- **矿机名前缀**：可给矿机名加可选前缀，方便区分多台机器。

## 🖥️ 显卡兼容

软件会按显卡自动筛选可用软件和矿池。

**NVIDIA：** 当前可选挖矿软件均支持。

**AMD：** 暂不兼容，等待挖矿软件更新。

群控下建议按显卡型号分组下发。

## 🔌 支持软件、矿池、币种

**币种：** PRL

**lpminer：** LuckyPool

**SRBMiner（3.3.9）：** LuckyPool、HeroMiners、Kryptex

**AlphaMiner：** AlphaPool

**AMD：** 等待软件更新

## 🚀 快速上手

1. 填写 PRL 钱包地址。
2. 填写矿机名。
3. 选择挖矿软件、矿池和节点。
4. 选择直连或加密代理。
5. 点击“测试连通性”，通过后点击“开始”。

## 🌐 群控模式

群控模式用于管理同一局域网内的多台 Vminer 机器。一个局域网建议只保留一台主控机，被控机连接主控后会上报在线状态、显卡、软件、矿池、算力、份额和错误状态。

不同型号显卡建议先按兼容性分组，再分批下发配置和启动。

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
