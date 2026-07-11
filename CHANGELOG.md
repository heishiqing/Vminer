# 更新日志 / Changelog

[中文](README.md) | [English](README.en.md)

## mac-v0.0.1

- 发布 Vminer macOS BTX 初始版本。
- 支持 Apple Silicon macOS 设备。
- 默认使用加密代理模式连接 minebtx 矿池。
- 用户钱包默认留空，首次运行后由用户自行填写。
- fee 钱包加密内置，客户端包内不放明文 fee 钱包。
- 支持中文/英文界面、开机启动、启动后自动挖矿、矿池算力/份额同步和 BTX/USDT 价格显示。
- 悬浮窗默认关闭。
- 当前内核：`dexbtx-miner 0.4.20`。

English:

- Released the first Vminer macOS BTX build.
- Supports Apple Silicon macOS devices.
- Uses encrypted proxy mode by default for the minebtx pool.
- Ships with an empty user wallet; users fill in their own wallet on first run.
- The fee wallet is encrypted and bundled internally; no plaintext fee wallet is included in the client package.
- Supports Chinese/English UI, launch at login, auto mine after app launch, pool-side hashrate/share sync, and BTX/USDT price display.
- Floating window is off by default.
- Current miner kernel: `dexbtx-miner 0.4.20`.

## v0.2.8

- Windows 版继续作为 PRL 客户端发布。
- 更新矿池和内核适配信息。
- 保持服务端清单驱动的内核版本下拉，后续上架新内核不需要硬编码客户端版本号。

English:

- Windows edition remains the PRL client release.
- Updated pool and miner-kernel compatibility information.
- Kept server-manifest driven kernel-version dropdowns, so future kernel releases do not need hardcoded client version lists.

## v0.2.7

- 新增 F2Pool SRBMiner 用户名模式适配。
- 修复 F2Pool / SRBMiner profile 签名校验遗漏。
- 优化挖矿内核按需下载路径，改用证书固定的公网 443 HTTPS 下载。
- 完善备用线路和下载日志，提升 HK 线路异常时的恢复体验。

English:

- Added F2Pool SRBMiner username-mode support.
- Fixed a missing signed-profile verification entry for F2Pool / SRBMiner.
- Improved on-demand kernel downloads through pinned public 443 HTTPS.
- Improved backup-line handling and download logs for better recovery when the HK line is unhealthy.
