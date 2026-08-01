# 更新日志 / Changelog

[中文](README.md) | [English](README.en.md)

## v0.3.2

- 修复部分长时间运行场景下连接恢复不完整的问题。
- 修复在线更新准备阶段的文件占用问题，并改进更新下载源切换。
- 优化挖矿内核按需下载、备用源切换和下载日志提示。
- 更新动态内核列表，支持 PeakMiner 2.4.2 与 SRBMiner 3.4.7。
- 优化钱包/用户名模式诊断与中英文错误提示。

English:

- Fixed incomplete connection recovery in some long-running scenarios.
- Fixed file-lock handling during update preparation and improved update-source fallback.
- Improved on-demand miner downloads, fallback switching, and download diagnostics.
- Updated the dynamic miner list with PeakMiner 2.4.2 and SRBMiner 3.4.7.
- Improved wallet/username diagnostics and bilingual error messages.

## v0.3.1

- 客户端调整为 PRL 专用版本，精简已下线功能与旧资源。
- 更新动态内核列表，支持 PeakMiner 2.2.2 与 WildRig 0.49.6。
- 恢复并更新压缩包内的中英文 TXT 使用说明。
- 优化内核版本列表在线刷新、连接恢复和后台进程清理。
- 优化静默模式、配置保存及中英文提示。

English:

- Focused the client on PRL and removed retired features and resources.
- Updated the dynamic miner list with PeakMiner 2.2.2 and WildRig 0.49.6.
- Restored and refreshed the Chinese and English TXT user guides in the package.
- Improved online miner-list refresh, reconnect behavior, and background-process cleanup.
- Improved silent mode, configuration persistence, and bilingual messages.

## v0.3.0

- 优化 F2Pool 用户名模式下的份额处理和连接恢复。
- 优化长时间无任务、无有效份额和网络波动时的自动恢复策略。
- 更新 Windows 内核适配列表，支持 PeakMiner 2.1.1、SRBMiner 3.4.6、WildRig 0.49.5、TW pearl-gpu 3.2.2。
- 优化按需下载与备用下载源，提升矿机内核获取稳定性。
- 优化矿池、钱包/用户名和网络异常的中英文提示。
- 优化 Windows 安全相关入口文案与配置保存体验。

English:

- Improved share handling and reconnect behavior for F2Pool username mode.
- Improved automatic recovery during no-job, no-valid-share, and network fluctuation states.
- Updated Windows miner compatibility: PeakMiner 2.1.1, SRBMiner 3.4.6, WildRig 0.49.5, and TW pearl-gpu 3.2.2.
- Improved on-demand miner downloads and backup download sources.
- Improved bilingual diagnostics for pool, wallet/username, and network errors.
- Improved Windows security-entry wording and configuration persistence.
## v0.2.9

- 新增 PeakMiner 2.0.0，并按矿池兼容性自动筛选可用内核。
- 优化断线、长时间无任务和无有效份额时的自动恢复，降低慢份额矿池误判。
- 完善钱包/用户名、矿池登录、内核下载、显卡与网络异常的中英文诊断提示。
- 修复部分 Windows 图形渲染异常导致客户端退出的问题。
- 优化配置保存与网吧无盘环境使用。
- 优化币价缓存和矿池信息显示。

English:

- Added PeakMiner 2.0.0 with pool-aware compatibility filtering.
- Improved recovery from disconnects, prolonged no-job states, and no-valid-share states while reducing false positives on slow-share pools.
- Added clearer bilingual diagnostics for wallet/username, pool login, miner download, GPU, and network errors.
- Fixed client exits caused by certain Windows graphics rendering failures.
- Improved configuration persistence and cyber-cafe diskless deployment.
- Improved price caching and pool information display.

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
