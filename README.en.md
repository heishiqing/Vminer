<div align="center">

<img src="docs/icon.png" width="96" alt="Vminer" />

# Vminer

### Mining client for Windows PRL/BTX and macOS BTX. Unzip and run.

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_Group-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## What is Vminer

Vminer is a desktop mining manager. Download the zip, unzip it, and double-click the app to start.

- **Windows edition**: supports PRL and BTX mining, primarily on NVIDIA GPUs, with multiple pools, multiple miner kernels, connection checks, status monitoring, and pool information lookup.
- **macOS edition**: built for BTX mining on Apple Silicon Macs. It uses encrypted proxy mode by default for minebtx. The user wallet is empty in the release package and must be filled in on first run.

<div align="center">
  <img src="docs/screenshot.en.png" width="820" alt="Vminer dashboard" />
</div>

## Download

| Platform | Current version | Download | How to start |
|---|---:|---|---|
| Windows | v0.2.9 | [Download Vminer-v0.2.9.zip](https://github.com/heishiqing/Vminer/releases/download/v0.2.9/Vminer-v0.2.9.zip) | Unzip and double-click `Vminer.exe` |
| macOS Apple Silicon | v0.0.1 | [Download Vminer-mac-v0.0.1.zip](https://github.com/heishiqing/Vminer/releases/download/mac-v0.0.1/Vminer-mac-v0.0.1.zip) | Unzip and double-click `Vminer.app` |

macOS release page: [mac-v0.0.1](https://github.com/heishiqing/Vminer/releases/tag/mac-v0.0.1).

If macOS shows a first-run security prompt, right-click `Vminer.app` in Finder and choose Open once. The release package ships with an empty user wallet, which must be filled in after first launch.

The Windows package includes `使用说明.md` and `User Guide.md`.

## Windows Features

- PRL and BTX: select a coin in Single Settings to see its compatible pools and mining software.
- One-click mining: enter a wallet or pool username, pick a pool, and start.
- Multiple pools: AlphaPool, LuckyPool, F2Pool, HeroMiners, Kryptex, 2Miners, PearlFortune, and PearlHash.
- Multiple miner kernels: SRBMiner, AlphaMiner, WildRig, TW pearl-gpu, and PeakMiner, auto-matched to the selected pool with available versions loaded from a signed server manifest.
- BTX mining: the Windows edition supports LuckyPool BTX with SRBMiner 3.4.6.
- MDL dual mining on supported pools.
- Status display: online state, GPU count, hashrate, accepted shares, rejected shares, and runtime logs.
- Stable recovery: improved recovery from disconnects, prolonged no-job states, and no-valid-share states while reducing false positives on slow-share pools.
- Clear diagnostics: bilingual messages for wallet/username, pool login, miner download, GPU, and network errors.
- Related sites: quick links to the official site, wallet, block explorer, pools, and exchanges.
- Auto run: launch at login and auto mine after app launch.
- Cyber-cafe diskless support: configuration can be saved next to the client folder for master-image deployment.

## Windows Miner Compatibility

| Miner | Current default | Supported PRL pools | Supported BTX pools |
|---|---:|---|---|
| SRBMiner | 3.4.6 | LuckyPool, HeroMiners, Kryptex, 2Miners, F2Pool | LuckyPool BTX |
| AlphaMiner | 1.7.7 | AlphaPool | — |
| WildRig | 0.49.5 | PearlHash | — |
| TW pearl-gpu | 3.2.2 | LuckyPool, HeroMiners, Kryptex, 2Miners, F2Pool, PearlFortune | — |
| PeakMiner | 2.1.1 | LuckyPool, HeroMiners, Kryptex, AlphaPool, F2Pool, 2Miners | — |

Miner versions are provided dynamically through a signed server manifest. Older builds remain selectable when needed for compatibility. AlphaMiner keeps stable version `1.7.7` as the default; `1.8.3` and MDL-capable `1.8.6` remain available for manual selection.

## macOS BTX Edition

- Supports Apple Silicon macOS devices.
- Uses encrypted proxy mode by default.
- Floating window is off by default.
- The user wallet is empty by default and must be filled in by the user.
- Supports Chinese/English UI, launch at login, auto mine after app launch, pool-side hashrate/share sync, and BTX/USDT price display.
- Current miner kernel: `dexbtx-miner 0.4.20`.
- Current pool: `minebtx`. Hashrate and shares are shown according to the pool API response.
- Current macOS release version: `0.0.1`.

## Quick Start

1. Download the package for your system.
2. Unzip it to a local folder.
3. Double-click the app.
4. Fill in your wallet address and worker name.
5. Select a pool and connection mode, then start mining.

## Community and Feedback

| Channel | Link |
|---|---|
| QQ Group | **245770181** |
| GitHub Issues | [Open an issue](https://github.com/heishiqing/Vminer/issues) |
| Changelog | [CHANGELOG.md](CHANGELOG.md) |

## Disclaimer

Make sure you have the right to run mining software on the current device. Mining may increase power consumption, hardware temperature, and device wear. Earnings, pool stability, and network connectivity are not guaranteed. Follow local laws, regulations, and platform rules.

## Support the Author

If you like Vminer, consider supporting the author on Afdian.

<div align="center">
  <img src="https://raw.githubusercontent.com/heishiqing/Vbot-B/main/static/afdian.jpg" width="240" alt="Afdian - heishiqing" />
</div>

## Other Projects

- [Vbot-B](https://github.com/heishiqing/Vbot-B): Bilibili private message auto-reply bot.
- [pearl-proxy](https://github.com/heishiqing/pearl-proxy): encrypted PRL proxy/relay software.
