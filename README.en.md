<div align="center">

<img src="docs/icon.png" width="96" alt="Vminer" />

# Vminer

### Windows mining client for PRL. Unzip and run.

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![QQ Group](https://img.shields.io/badge/QQ_Group-245770181-12B7F5)](#)

[中文](README.md) | [English](README.en.md)

</div>

---

## What is Vminer

Vminer is a Windows desktop mining manager for PRL (Pearl). Download the zip, unzip it, and double-click the app to start. It is designed primarily for NVIDIA GPUs and includes multiple pools, multiple miner kernels, connection checks, status monitoring, and pool information lookup.

<div align="center">
  <img src="docs/screenshot.en.png" width="820" alt="Vminer dashboard" />
</div>

## Download

| Platform | Current version | Download | How to start |
|---|---:|---|---|
| Windows | v0.3.1 | [Download Vminer-v0.3.1.zip](https://github.com/heishiqing/Vminer/releases/download/v0.3.1/Vminer-v0.3.1.zip) | Unzip and double-click `Vminer.exe` |

The package includes `使用说明.txt` and `User Guide.txt`.

## Windows Features

- One-click mining: enter a wallet or pool username, pick a pool, and start.
- Multiple pools: AlphaPool, LuckyPool, F2Pool, HeroMiners, Kryptex, 2Miners, PearlFortune, and PearlHash.
- Multiple miner kernels: SRBMiner, AlphaMiner, WildRig, TW pearl-gpu, and PeakMiner, auto-matched to the selected pool with available versions loaded from a signed server manifest.
- Status display: online state, GPU count, hashrate, accepted shares, rejected shares, and runtime logs.
- Stable recovery: improved recovery from disconnects, prolonged no-job states, and no-valid-share states while reducing false positives on slow-share pools.
- Clear diagnostics: bilingual messages for wallet/username, pool login, miner download, GPU, and network errors.
- Related sites: quick links to the official site, wallet, block explorer, pools, and exchanges.
- Auto run: launch at login and auto mine after app launch.
- Cyber-cafe diskless support: configuration can be saved next to the client folder for master-image deployment.

## Windows Miner Compatibility

| Miner | Current version | Supported PRL pools |
|---|---:|---|
| SRBMiner | 3.4.6 | LuckyPool, HeroMiners, Kryptex, 2Miners, F2Pool |
| AlphaMiner | 1.7.7 | AlphaPool |
| WildRig | 0.49.6 | PearlHash |
| TW pearl-gpu | 3.2.2 | LuckyPool, HeroMiners, Kryptex, 2Miners, F2Pool, PearlFortune |
| PeakMiner | 2.2.2 | LuckyPool, HeroMiners, Kryptex, AlphaPool, F2Pool, 2Miners |

Miner versions are provided dynamically through a signed server manifest. Open the version dropdown to refresh the available versions; older builds remain selectable when needed for compatibility.

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
