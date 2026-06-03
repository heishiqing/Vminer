<div align="center">

# ⛏️ Vminer

### One-stop Windows manager for PRL mining · Unzip and run

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![License](https://img.shields.io/badge/license-MIT-F59E0B.svg)](#)

[中文](README.md) · [English](README.en.md)

</div>

---

## 🎯 What is Vminer

A Windows desktop manager that bundles **PRL miners + pools**. **No Docker, just unzip and run**.

For users who want to mine PRL without fighting CLI / switch pools easily / assign GPUs / use encrypted proxy.

## ✨ Features

**Mining management**
- 🚀 **Run out of the box** — No Docker, no runtime, just unzip the .exe
- 🔀 **One-click pool switching** — LuckyPool / BaikalMine / AlphaPool, all preconfigured
- 🎛️ **Multi-GPU allocation** — `all` for all cards, or specify card IDs (e.g. 0,2,5)
- 🛡️ **Encrypted proxy** — Falls back when direct connect is unstable; hides cleartext mining traffic from ISP

**Monitoring & ops**
- 📊 **Real-time status cards** — Online / hashrate / accepted / rejected shares / last update
- 🌈 **Colorized logs** — Success / error / pool / GPU / program output color-coded
- 🧪 **Connectivity test** — Verify config without starting mining
- 🛎️ **Start with Windows + auto start + minimize to tray** — Set & forget
- 💾 **Auto-save settings** — Critical settings lock while running

**Transparency**
- 🔍 **Does not modify task packets or replace wallet address** — Users can inspect logs / process args / network connections
- 📰 **Server announcements + changelog** — Pool/compatibility changes pushed in-app

## 📥 Download

<div align="center">

### [⬇ Download latest v0.1.1](https://github.com/heishiqing/Vminer/releases/latest)

</div>

Unzip and double-click `Vminer.exe` in the root. First launch shows the user notes.

## 🪙 Compatibility

| Miner | Supported pools | Status |
|---|---|---|
| **lpminer** | LuckyPool, BaikalMine | ✅ Integrated |
| **AlphaMiner** | AlphaPool | ✅ Integrated |
| Pearl Miner | PearlHash | 🟡 Waiting for official Windows build |

GPU:

| Type | Status |
|---|---|
| RTX 30/40 NVIDIA | ✅ Primary support |
| RTX 50 NVIDIA | 🟡 lpminer ✅ / AlphaMiner pending official |
| AMD | ❌ Not supported yet |

## 🚦 Five-step quickstart

1. Enter PRL wallet address
2. Enter worker name
3. Pick miner / pool / node
4. Pick direct or encrypted proxy
5. Click **Test connectivity** → pass → click **Start**

## 💬 Community / feedback

| Channel | Link |
|---|---|
| QQ Group | **245770181** |
| GitHub Issues | [Open an issue](https://github.com/heishiqing/Vminer/issues) |
| Changelog | [CHANGELOG.md](CHANGELOG.md) |

## ⚠️ Disclaimer

Make sure you **have the right to run mining on this device**. Mining brings power consumption / heat / hardware wear. No guarantees on earnings, pool stability, or network connectivity. Comply with local laws and platform rules.

## ❤ Support the author

If Vminer saves you time, consider buying me a coffee ☕

<img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="afdian - heishiqing">

## 🌟 Other projects

- [**Vbot-B**](https://github.com/heishiqing/Vbot-B) — Bilibili private message auto-reply bot
