<div align="center">

<img src="docs/icon.png" width="96" alt="Vminer" />

# Vminer

### Native Windows multi-coin GPU miner · unzip and run

**PRL (Pearl) · QTC (Quantus)**　｜　also supports XTM (Tari)

**NVIDIA and AMD GPUs**

[![Release](https://img.shields.io/github/v/release/heishiqing/Vminer?color=0E7490&label=latest)](https://github.com/heishiqing/Vminer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/heishiqing/Vminer/total?color=F59E0B)](https://github.com/heishiqing/Vminer/releases)
[![Discord](https://img.shields.io/badge/Discord-Join_us-5865F2?logo=discord&logoColor=white)](https://discord.gg/XYwrTWjHGE)
[![QQ Group](https://img.shields.io/badge/QQ_Group-245770181-12B7F5)](#-community-and-feedback)

[中文](README.md)　｜　[English](README.en.md)　·　Website [www.vminers.com](https://www.vminers.com/)

</div>

---

## ✨ What is Vminer

Vminer is a native Windows multi-coin GPU mining client — primarily **PRL (Pearl)** and **QTC (Quantus)**, and also **XTM (Tari)**, with more coins on the way. Download the zip, unzip it, and double-click to start — no WSL2, Docker, or command line needed. Once you pick a pool, the client automatically matches the compatible mining engines and downloads and verifies them on first use.

<div align="center">
  <img src="docs/screenshot.en.png" width="820" alt="Vminer dashboard" />
</div>

> 🎮 **Netbar mode** — one master switch, three ways to share the GPU: Full power (always mining), Avoid games (steps aside the moment a game on the list starts) and Smart (watches GPU load — games get the GPU, browser video doesn't interrupt mining). Runs silently in the background from startup and shows with a hotkey; can lower power while mining and go back to 100% when a game has the GPU.
>
> 🖥️ **Diskless (cyber-cafe)** — the full config is baked into the master image, so every client restores its wallet and auto-starts mining on boot; set it up once and the whole room mines.
>
> 📱 **Fleet Control** — sign in inside the client, then manage every rig from a phone, tablet or computer at [app.vminers.com](https://app.vminers.com/).

<div align="center">
  <img src="docs/fleet.png" width="640" alt="Fleet Control web (demo data)" />　<img src="docs/fleet-phone.png" width="170" alt="Fleet Control on a phone (demo data)" />
  <br><sub>Fleet Control · desktop and phone (demo data)</sub>
</div>

## ⬇️ Download

**[Download the latest release →](https://github.com/heishiqing/Vminer/releases/latest)**

- Requirements: Windows 10 / 11 64-bit with a dedicated GPU — NVIDIA or AMD. AMD cards currently mine PRL / QTC with SRBMiner (Kryptex, HeroMiners, LuckyPool) and XTM with lolMiner.
- Unzip and double-click `Vminer.exe` in the root folder.
- The package includes `使用说明.txt` and `User Guide.txt`.
- The package ships without mining engines; each engine is downloaded and hash-verified the first time you select it, which keeps the download small.
- Only download from this repository's Releases or the official site [www.vminers.com](https://www.vminers.com/), and verify the file with the SHA-256 on the release page.

## 🚀 Quick Start

1. Download, unzip, and double-click `Vminer.exe`.
2. Pick a coin and a pool — the client filters the engines that work with that pool.
3. Enter your own wallet address for that coin (Kryptex also accepts a username).
4. Click Start. The dashboard shows your hashrate, shares, and earnings.

## 🎛️ Features

- 🪙 **Multi-coin** — primarily PRL and QTC, plus XTM, switchable from a dropdown.
- 🔀 **Pools and engines matched automatically** — choose a pool and the client lists only the engines that work with it; pools that require their own official engine are locked to it.
- 🔄 **Engine versions updated online** — engine versions come from a signed server manifest, and the dropdown shows each engine's current version — no manual files.
- 📊 **Live monitoring** — total hashrate, shares, pool balance, and coin price, plus per-GPU hashrate, temperature, and power.
- 📱 **Fleet Control** — at [app.vminers.com](https://app.vminers.com/), see every rig grouped by coin or pool (hashrate, temperature, power, online status); start / stop, switch pool / engine / coin / wallet, set power and fans, reboot or shut down — for one rig or many. The client's own screen follows the changes.
- 🎛️ **Overclocking** — power, fan, core and memory on one page; an auto thermal link eases power and raises the fan when a card runs hot and steps back when it cools; same-model cards change together; one-click restore. Tuning is for NVIDIA cards; AMD cards show live status.
- 🛟 **Reboot on driver crash** — optional: once a GPU driver crash is confirmed and mining has stopped, the PC reboots and resumes mining automatically, with a limit so it never loops. NVIDIA and AMD.
- 🔒 **Encrypted end to end** — all communication between the client and the servers is encrypted.
- ♻️ **Auto update** — on by default; downloads use primary and backup routes with automatic fallback and integrity checks.
- 🩺 **Pre-start checks** — GPU driver, antivirus blocking, and network are checked before mining starts, with clear messages if something is wrong.
- 🖥️ **Runs in the background** — start with Windows, start mining on launch, hide to tray on close, and a hotkey to show the window.

## ⛏️ Supported Pools and Engines

| Coin | Pool | Mining engines | AMD |
|---|---|---|:---:|
| **PRL** | AlphaPool | AlphaMiner / PeakMiner | — |
| **PRL** | HeroMiners | SRBMiner / TW-Pearl-Miner / PeakMiner | ✓ |
| **PRL** | Kryptex | SRBMiner / TW-Pearl-Miner / PeakMiner | ✓ |
| **PRL** | LuckyPool | SRBMiner / TW-Pearl-Miner / PeakMiner | ✓ |
| **PRL** | PEARLSKI | PEARLSKI official engine | — |
| **PRL** | PearlHash | WildRig | — |
| **QTC** | Kryptex | SRBMiner | ✓ |
| **QTC** | LuckyPool | SRBMiner | ✓ |
| **XTM** | Kryptex | lolMiner | ✓ |

The client is the source of truth for pools and engines. The servers update them online through a signed manifest, so new pools or engine versions usually don't require a new client download.

## 💵 Fees

Vminer is free to download. **No extra fees — Vminer only takes the kernel's 2%.** Earnings go straight to your own wallet.

## ❓ FAQ

- **Will antivirus flag it?** Mining software is sometimes flagged by antivirus heuristics. If that happens, add Vminer to your trusted list.
- **Why don't the client's share counts match the pool dashboard?** The two count differently (dynamic difficulty, reporting windows, delays). **The pool's dashboard is the one that counts.**
- **Do I need to give my private key?** No. Mining only needs your wallet **address**. Anyone asking for your private key, seed phrase, or a coin transfer is a scammer.

## 💬 Community and Feedback

| Channel | Link |
|---|---|
| Discord | [Join the Vminer community](https://discord.gg/XYwrTWjHGE) |
| QQ Group | **245770181** |
| Website | [www.vminers.com](https://www.vminers.com/) |
| Fleet Control | [app.vminers.com](https://app.vminers.com/) |
| GitHub Issues | [Open an issue](https://github.com/heishiqing/Vminer/issues) |
| Changelog | [CHANGELOG.md](CHANGELOG.md) |

## ⚠️ Disclaimer

Make sure you have the right to run mining software on the current device. Mining may increase power consumption, hardware temperature, and device wear. Earnings, pool stability, and network connectivity are not guaranteed. Follow local laws, regulations, and platform rules.
