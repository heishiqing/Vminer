<div align="center">

<img src="docs/icon.png" width="96" alt="Vminer" />

# Vminer

### One-stop Windows manager for PRL mining. Unzip and run.

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_Group-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## 📖 What is Vminer

Vminer is a Windows desktop manager for PRL mining. Unzip the package and double-click to run. It supports single-machine mining and LAN group control, including start, stop, status monitoring, connectivity checks, and pool dashboard shortcuts.

It is designed for users who want quick pool setup, miner switching, hashrate and share display, or centralized management for multiple Windows machines on the same LAN.

<div align="center">
  <img src="docs/screenshot.en.png" width="820" alt="Vminer dashboard">
</div>

## 📥 Download

<div align="center">

### [⬇️ Download latest v0.2.1](https://github.com/heishiqing/Vminer/releases/latest)

</div>

Download the zip, unzip it, and double-click `Vminer.exe` in the root folder. The package includes `使用说明.md` and `User Guide.md`.

> 🆕 **What's new in v0.2.1**: added PearlFortune / PearlHash / 2Miners pools · mining kernels fully upgraded (on-demand download, slimmer package) · NVIDIA-only build · new GPU fan control · new "Related Sites" page · pool dashboard upgraded to "Pool Balance" lookup. Full log in [CHANGELOG](CHANGELOG.md).

## ✨ Features

- **Single Mode**: run mining on the current Windows machine.
- **Group Control**: manage multiple Vminer machines on the same LAN.
- **Status display**: online state, GPU count, hashrate, accepted shares, rejected shares, and mining state at a glance.
- **Runtime logs**: miner output, pool connection state, and program messages.
- **Pool balance lookup**: view pool-side balance, paid, shares, and online rigs inside the app (no VPN needed in mainland China); pool dashboard shortcuts also available.
- **Related Sites**: one-click access to the official site, wallet, block explorer, and pool websites.
- **Live price in-app**: view the real-time PRL price inside the app (no VPN needed in mainland China).
- **Auto run**: start with Windows, auto mine after launch, and background silent mode.
- **Power & fan**: NVIDIA power-limit percentage setting (re-checked every 5 minutes and re-applied if it drifts), plus fan-speed control.
- **Worker name prefix**: add an optional prefix to worker names to tell machines apart.

## 🖥️ GPU compatibility

Vminer filters available miners and pools by detected GPU.

**NVIDIA:** fully supported — all current mining software and pools are available.

> This build is NVIDIA-only, focused on N-card efficiency and stability.

For Group Control, group workers by GPU model before applying settings.

## 🔌 Supported software, pools, and coin

**Coin:** PRL

**Pools:** AlphaPool, LuckyPool, Kryptex, HeroMiners, PearlFortune, PearlHash, 2Miners

**Mining kernels:** several mainstream PRL kernels built in (SRBMiner, AlphaMiner, WildRig, etc., all latest versions), auto-matched to the selected pool; kernels are downloaded on demand at first launch to keep the package slim.

## 🚀 Quick start

1. Enter your PRL wallet address.
2. Enter a worker name.
3. Select miner, pool, and node.
4. Select direct or encrypted proxy mode.
5. Click "Test connectivity"; if it passes, click "Start".

## 🌐 Group Control

Group Control manages multiple Vminer machines on the same LAN. Keep only one controller machine in a LAN. Workers connect to the controller and report online state, GPU, software, pool, hashrate, shares, and error state.

For mixed-GPU environments, group workers by compatibility first, then apply settings and start in batches.

## 💬 Community and feedback

| Channel | Link |
|---|---|
| QQ Group | **245770181** |
| GitHub Issues | [Open an issue](https://github.com/heishiqing/Vminer/issues) |
| Changelog | [CHANGELOG.md](CHANGELOG.md) |

## ⚠️ Disclaimer

Make sure you have the right to run mining software on the current device. Mining may increase power consumption, hardware temperature, and device wear. Earnings, pool stability, and network connectivity are not guaranteed. Follow local laws, regulations, and platform rules.

## ❤️ Support the author

If you like Vminer, consider supporting the author on Afdian.

<div align="center">
  <img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="Afdian - heishiqing">
</div>

## 🔗 Other projects

- [Vbot-B](https://github.com/heishiqing/Vbot-B): Bilibili private message auto-reply bot.
