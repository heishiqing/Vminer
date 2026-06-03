<div align="center">

# Vminer

### One-stop Windows manager for PRL mining. Unzip and run.

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_Group-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## What is Vminer

Vminer is a Windows desktop manager for PRL mining. It bundles miner and pool configuration into a simple desktop app. No Docker is required. Download, unzip, and run.

It is designed for Windows users who want easier pool switching, GPU selection, status monitoring, and readable runtime logs.

<div align="center">
  <img src="docs/screenshot.png" width="820" alt="Vminer dashboard">
</div>

## Features

**Mining management**

- Unzip and run, no Docker required.
- Switch between supported pool configurations.
- Use all GPUs or specify GPU IDs.
- Supports direct connection and encrypted proxy mode.
- Locks key settings while running, then unlocks them after stopping.

**Status and logs**

- Shows online status, GPU count, hashrate, accepted shares, rejected shares, and mining state.
- Shows miner list with worker name, software, pool, GPU, hashrate, shares, and last update.
- Colorized runtime logs for easier troubleshooting.
- Connectivity test checks the setup without starting mining.

**User experience**

- Settings are saved automatically.
- Supports start with Windows.
- Supports auto start after opening the app.
- Supports minimizing to the system tray, disabled by default.
- Includes software notes, changelog, and pool dashboard shortcut.

**Transparency**

- The client does not modify pool task packets.
- The client does not replace the user's wallet address.
- Users can inspect settings, runtime logs, process arguments, and network connections.

## Download

<div align="center">

### [Download latest v0.1.4](https://github.com/heishiqing/Vminer/releases/latest)

</div>

Download the zip, unzip it, and double-click `Vminer.exe` in the root folder. The software notes are shown on first launch.

## Compatibility

| Miner | Supported pools | Status |
|---|---|---|
| lpminer | LuckyPool, BaikalMine | Integrated |
| AlphaMiner | AlphaPool | Integrated |
| Pearl Miner | PearlHash | Waiting for official Windows build |

GPU support:

| GPU type | Status |
|---|---|
| NVIDIA RTX 30/40 series | Recommended |
| NVIDIA RTX 50 series | Compatibility notes added. Check driver and miner support in the app notes. |
| AMD | Not supported yet |

## Quick start

1. Enter your PRL wallet address.
2. Enter a worker name.
3. Select miner, pool, and node.
4. Select direct or encrypted proxy mode.
5. Click "Test connectivity"; if it passes, click "Start".

## Community and feedback

| Channel | Link |
|---|---|
| QQ Group | 245770181 |
| GitHub Issues | [Open an issue](https://github.com/heishiqing/Vminer/issues) |
| Changelog | [CHANGELOG.md](CHANGELOG.md) |

## Disclaimer

Make sure you have the right to run mining software on the current device. Mining may increase power consumption, hardware temperature, and device wear. Earnings, pool stability, and network connectivity are not guaranteed. Follow local laws, regulations, and platform rules.

## Support the author

If Vminer saves you time, consider supporting the author.

<img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="afdian - heishiqing">

## Other projects

- [Vbot-B](https://github.com/heishiqing/Vbot-B): Bilibili private message auto-reply bot.
