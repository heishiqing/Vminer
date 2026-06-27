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

Vminer is a Windows desktop manager for PRL mining. Unzip the package and double-click to run. It focuses on **NVIDIA GPU** mining, with multiple pools and mining kernels built in — one-click setup, connectivity checks, status monitoring, and pool balance lookup.

It is designed for NVIDIA users who want quick pool setup, kernel switching, hashrate and share display, and pool balance lookups.

<div align="center">
  <img src="docs/screenshot.en.png" width="820" alt="Vminer dashboard">
</div>

## 📥 Download

<div align="center">

### [⬇️ Download latest v0.2.1](https://github.com/heishiqing/Vminer/releases/latest)

</div>

Download the zip, unzip it, and double-click `Vminer.exe` in the root folder. The package includes `使用说明.md` and `User Guide.md`.

> 🆕 **What's new in v0.2.1**: added PearlFortune / PearlHash / 2Miners pools · mining kernels fully upgraded (on-demand download, slimmer package) · NVIDIA-only build · new GPU fan control · new "Related Sites" page · pool balance lookup · refreshed dark UI. Full log in [CHANGELOG](CHANGELOG.md).

## ✨ Features

- **One-click mining**: enter a wallet, pick a pool, hit start — the matching kernel is downloaded and launched automatically.
- **Multiple pools**: 7 pools built in, switch inside the app.
- **Status display**: online state, GPU count, hashrate, accepted shares, rejected shares, and mining state at a glance.
- **Runtime logs**: miner output, pool connection state, and program messages.
- **Pool balance lookup**: view pool-side balance, paid, shares, and online rigs inside the app (no VPN needed in mainland China).
- **Related Sites**: one-click access to the official site, wallet, block explorer, and pool websites.
- **Live price in-app**: view the real-time PRL price inside the app (no VPN needed in mainland China).
- **Auto run**: start with Windows, auto mine after launch, and background silent mode.
- **Power & fan**: NVIDIA power-limit percentage plus fan-speed control (re-checked every 5 minutes and re-applied if it drifts).
- **Startup self-check**: connectivity, GPU driver, or antivirus issues raise a clear prompt and stop — no blind retry loop.
- **Worker name**: add a prefix or generate randomly to tell machines apart.
- **Refreshed UI**: dark-glass style with a left sidebar, smoother to use.

## 🖥️ GPU compatibility

**NVIDIA-only**, focused on N-card efficiency and stability. Vminer filters available kernels and pools by detected GPU.

## 🔌 Supported pools, kernels, and coin

**Coin:** PRL

**Pools (7):** AlphaPool, HeroMiners, Kryptex, LuckyPool, 2Miners, PearlFortune, PearlHash

**Mining kernels:** SRBMiner, AlphaMiner, WildRig, TW (pearl-gpu) — all latest versions, auto-matched to the selected pool; downloaded on demand at first launch to keep the package slim.

## 🚀 Quick start

1. Enter your PRL wallet address.
2. Enter a worker name (can be random).
3. Select a pool and node (the kernel is matched automatically).
4. Select direct or encrypted proxy mode.
5. Click "Test connectivity"; if it passes, click "Start".

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
