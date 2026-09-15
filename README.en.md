<div align="center">

<img src="docs/icon.png" width="96" alt="Vminer" />

# Vminer

### Native Windows multi-coin GPU miner · unzip and run

**PRL (Pearl) · QTC (Quantus)**　｜　also supports XTM (Tari)

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

> 🌙 **Silent Mode** — mines in the background only while the PC is idle, and yields the GPU the instant you touch the mouse or keyboard, so it never gets in your way.
>
> 🖥️ **Diskless (cyber-cafe)** — the full config is baked into the master image, so every client restores its wallet and auto-starts mining on boot; set it up once and the whole room mines.

## ⬇️ Download

**[Download the latest release →](https://github.com/heishiqing/Vminer/releases/latest)**

- Requirements: Windows 10 / 11 64-bit with a dedicated NVIDIA GPU.
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
- 🔎 **Hashrate and earnings lookup** — enter your wallet at [stats.vminers.com](https://stats.vminers.com/) to see every rig's hashrate, online status, and earnings.
- 🌡️ **Power and fans** — set a power limit and fan behavior, re-applied automatically after a restart.
- 🔒 **Encrypted end to end** — all communication between the client and the servers is encrypted.
- ♻️ **Auto update** — on by default; downloads use primary and backup routes with automatic fallback and integrity checks.
- 🩺 **Pre-start checks** — GPU driver, antivirus blocking, and network are checked before mining starts, with clear messages if something is wrong.
- 🖥️ **Runs in the background** — start with Windows, hide to tray on close, and a global `Ctrl+Alt+V` hotkey.

## ⛏️ Supported Pools and Engines

| Coin | Pool | Mining engines |
|---|---|---|
| **PRL** | AlphaPool | AlphaMiner / PeakMiner |
| **PRL** | HeroMiners | SRBMiner / TW-Pearl-Miner / PeakMiner |
| **PRL** | Kryptex | SRBMiner / TW-Pearl-Miner / PeakMiner |
| **PRL** | LuckyPool | SRBMiner / TW-Pearl-Miner / PeakMiner |
| **PRL** | PEARLSKI | PEARLSKI official engine |
| **PRL** | PearlHash | WildRig |
| **QTC** | Kryptex | SRBMiner |
| **QTC** | LuckyPool | SRBMiner |
| **XTM** | Kryptex | lolMiner |

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
| Hashrate lookup | [stats.vminers.com](https://stats.vminers.com/) |
| GitHub Issues | [Open an issue](https://github.com/heishiqing/Vminer/issues) |
| Changelog | [CHANGELOG.md](CHANGELOG.md) |

## ⚠️ Disclaimer

Make sure you have the right to run mining software on the current device. Mining may increase power consumption, hardware temperature, and device wear. Earnings, pool stability, and network connectivity are not guaranteed. Follow local laws, regulations, and platform rules.
