# Vminer

[中文](README.md) | [English](README.en.md)

Vminer is a Windows management tool for PRL mining. It bundles mining software into a ready-to-use desktop package, so Docker is not required. It helps users start, stop, monitor, and test mining connectivity across supported miners and pools.

> This is an early test release. Please read the in-app notes and compatibility information before mining.

## Download

Download the latest package from [Releases](https://github.com/heishiqing/Vminer/releases).

Extract the archive and run `Vminer.exe` from the root folder. On first launch, the app will ask you to read the software notes.

## Community

QQ group: `245770181`

## Current Support

Coin: PRL

| Miner software | Supported pools | Status |
| --- | --- | --- |
| lpminer | LuckyPool, BaikalMine | Integrated |
| AlphaMiner | AlphaPool | Integrated |
| Pearl Miner | PearlHash | Waiting for the official Windows release and stable protocol support |

GPU compatibility:

- AMD GPUs are not supported in the current version.
- AlphaMiner currently does not support RTX 50-series GPUs. Support depends on the official update.
- RTX 30/40-series NVIDIA GPUs may be used according to verified environments.

## Features

- Bundled mining software, no Docker installation required.
- Start and stop mining processes.
- Display online status, GPU count, GPU model, hashrate, accepted shares, rejected shares, and last update time.
- Support multi-GPU rigs. Use `all` for all GPUs or specify GPU indexes.
- Filter miners and pools by compatibility.
- Support direct pool connection and encrypted proxy mode.
- Connectivity test does not start mining.
- Colorized runtime logs for success, errors, pools, GPUs, and program output.
- Start with Windows.
- Start automatically when the app opens.
- Minimize to system tray.
- Auto-save settings and lock relevant settings while mining is running.
- Open the selected pool dashboard.
- Reserved capability for server announcements, changelog, and background updates.

## Connection Modes

Direct: the miner connects directly to the selected pool. Use this mode first when connectivity is normal.

Encrypted proxy: the miner connects through the software's encrypted channel. Use this mode when direct connectivity fails, pool access is unstable, or you do not want plain mining traffic to be identified by your network provider.

## Client Transparency

The client does not alter pool jobs and does not replace the user's wallet address. Users can inspect settings, logs, process arguments, and network connections to verify the mining address and pool connection.

## Quick Start

1. Enter your PRL wallet address.
2. Enter a worker name.
3. Select miner software, pool, and node.
4. Choose direct or encrypted proxy mode.
5. Run the connectivity test.
6. Click start after the test passes.

## Disclaimer

Make sure you have permission to run mining software on the device. Mining may increase power usage, hardware temperature, and device wear. Earnings, pool stability, and network connectivity are not guaranteed. Follow local laws, regulations, and platform rules.
