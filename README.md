<div align="center">

# ⛏️ Vminer

### PRL 挖矿 Windows 一站式管理工具 · 打开即用

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![License](https://img.shields.io/badge/license-MIT-F59E0B.svg)](#)
[![QQ Group](https://img.shields.io/badge/QQ_群-245770181-12B7F5)](https://qm.qq.com/q/245770181)

[中文](README.md) · [English](README.en.md)

</div>

---

## 🎯 Vminer 是什么

聚合 **PRL 挖矿软件 + 矿池** 的 Windows 桌面端管理器. **无需 Docker, 解压即用**.

适用场景: 想挖 PRL 但不想折腾命令行 / 多矿池切换 / 显卡分配 / 加密代理.

## ✨ 核心特性

**挖矿管理**
- 🚀 **打开即用** — 不依赖 Docker, 不依赖运行时, 解压 .exe 直接跑
- 🔀 **多矿池一键切换** — LuckyPool / BaikalMine / AlphaPool 配置好之间切换
- 🎛️ **多显卡分配** — `all` 全显卡或指定显卡编号 (例如 0,2,5)
- 🛡️ **加密代理** — 直连不稳时走加密通道, 不让明文挖矿流量被运营商识别

**监控 & 运维**
- 📊 **实时状态卡** — 在线/算力/接受份额/拒绝份额/最后更新
- 🌈 **彩色日志** — 成功/错误/矿池/显卡/程序输出 分色显示
- 🧪 **连通性测试** — 测网络不启动挖矿, 验配置先
- 🛎️ **开机自启 + 自动开始 + 最小化托盘** — 适合长期挂机
- 💾 **设置自动保存** — 运行中关键设置自动锁定防误改

**透明性**
- 🔍 **不篡改任务包, 不替换钱包地址** — 用户可自查日志/进程参数/网络连接
- 📰 **服务器公告 + 更新日志** — 矿池/兼容性变化即时推送

## 📥 下载

<div align="center">

### [⬇ 下载最新版 v0.1.1](https://github.com/heishiqing/Vminer/releases/latest)

</div>

解压后双击根目录 `Vminer.exe`. 首次启动会弹软件说明.

## 🪙 兼容性

| 挖矿软件 | 支持矿池 | 状态 |
|---|---|---|
| **lpminer** | LuckyPool, BaikalMine | ✅ 已接入 |
| **AlphaMiner** | AlphaPool | ✅ 已接入 |
| Pearl Miner | PearlHash | 🟡 等待官方 Windows 版本 |

显卡:

| 类型 | 状态 |
|---|---|
| RTX 30/40 NVIDIA | ✅ 主力支持 |
| RTX 50 NVIDIA | 🟡 lpminer ✅ / AlphaMiner 等官方 |
| AMD | ❌ 暂不支持 |

## 🚦 五步上手

1. 填 PRL 钱包地址
2. 填矿机名
3. 选挖矿软件 / 矿池 / 节点
4. 选直连 or 加密代理
5. 点 **测试连通性** → 通了点 **开始**

## 💬 交流 / 反馈

| 渠道 | 入口 |
|---|---|
| QQ 群 | **245770181** |
| GitHub Issues | [提 issue](https://github.com/heishiqing/Vminer/issues) |
| 更新日志 | [CHANGELOG.md](CHANGELOG.md) |

## ⚠️ 免责声明

请确认你**有权在当前设备上运行挖矿程序**. 挖矿带来电力消耗 / 硬件温度上升 / 设备损耗风险. 收益、矿池稳定性、网络连通性**不做保证**. 请遵守所在地法律法规和平台规则.

## ❤ 支持作者

如果 Vminer 帮你省了时间, 欢迎请作者一杯咖啡 ☕

<img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="爱发电 - heishiqing">

## 🌟 作者其他项目

- [**Vbot-B**](https://github.com/heishiqing/Vbot-B) — B 站私信自动回复机器人
