# 更新日志 / Changelog

[中文](README.md) | [English](README.en.md)

## v0.3.13

- 网吧模式重做:一个总开关,全力 / 规避 / 智能三种让位方式;规避名单内置热门游戏并可自行增删;智能模式看显卡占用,看网页视频照常挖。开机后台静默运行,快捷键呼出;挖矿时可自动调低功耗,让给游戏时恢复 100%。
- 性能调度:功耗、风扇、核心、显存一页调好,支持温度自动联动;同型号显卡一起改,一键恢复默认。
- 群控:在客户端登录账号,即可在 app.vminers.com 用手机、平板、电脑远程批量管理矿机;网页上的操作,客户端界面同步变化。
- 新增「显卡掉驱动后自动重启电脑」(系统设置):确认掉驱动、挖矿停了之后自动重启并接着挖,有次数上限;N 卡 / A 卡通用。
- 支持 A 卡(AMD):SRBMiner 挖 PRL / QTC,lolMiner 挖 XTM。
- 稳定性、兼容性与算力 / 数据显示的若干修复与改进。

English:

- Netbar mode rebuilt: one master switch with Full power / Avoid games / Smart; a built-in, editable list of popular games; Smart watches GPU load so browser video doesn't interrupt mining. Runs silently in the background from startup, shows with a hotkey; can lower power while mining and go back to 100% when a game has the GPU.
- Performance page: power, fan, core and memory on one page, with an auto thermal link; same-model cards change together; one-click restore.
- Fleet Control: sign in inside the client and manage rigs from a phone, tablet or computer at app.vminers.com; changes made on the web show up in the client.
- New "Reboot automatically if a GPU driver crashes" (System Settings): once a driver crash is confirmed and mining has stopped, the PC reboots and resumes mining, with a limit; NVIDIA and AMD.
- AMD GPU support: SRBMiner for PRL / QTC, lolMiner for XTM.
- Stability, compatibility and hashrate / display fixes and improvements.

## v0.3.10

- 使用说明界面重做,排版与阅读更清晰。
- 内核被杀毒软件拦截或删除时,日志会明确指出真实原因,并给出操作指引(含一键功能)。
- 起挖失败时给出更明确的原因提示。
- 稳定性、兼容性与算力 / 数据显示的若干修复与改进。

English:

- Redesigned in-app guide for clearer reading.
- When antivirus blocks or deletes a mining engine, the log names the real cause and gives step-by-step fixes (with one-click actions).
- Clearer reasons when mining fails to start.
- Stability, compatibility and hashrate / display fixes and improvements.

## v0.3.9

- 新增 XTM(Tari)挖矿支持(Kryptex 矿池 + lolMiner 内核)。默认仍是 PRL,出现第二个币种时才显示币种选择器,PRL 用户使用不受影响。
- 币价、矿池后台查询、算力查询站全面支持按币种显示(PRL / XTM),算力单位按币种正确显示。
- 侧栏「算力实时查询」直接带上钱包跳转查询站。
- 主域名迁移到 vminers.com(旧域名继续可用)。
- 修复选择 XTM 时矿池 / 内核联动、界面版本号显示、算力曲线单位等问题。
- 稳定性与显示优化。

English:

- Added XTM (Tari) mining (Kryptex pool + lolMiner engine). PRL remains the default; the coin selector only appears once a second coin is available, so PRL users are unaffected.
- Coin price, pool dashboard lookups, and the hashrate lookup site now display per coin (PRL / XTM), with the correct hashrate unit for each coin.
- The sidebar "Live hashrate lookup" opens the lookup site with your wallet pre-filled.
- Moved the main domain to vminers.com (the old domain still works).
- Fixed pool / engine linkage when selecting XTM, the in-app version display, and hashrate chart units.
- Stability and display improvements.

## v0.3.8

- 侧栏新增「算力 / 收益查询」入口,点击直接带上设置里的钱包跳转查询站。
- 新增 PEARLSKI 矿池(含官方内核、余额查询);移除 2Miners 矿池。
- 矿池下拉按 PRLScan 真实排名排序;钱包直达扩展到 LuckyPool / PearlHash。
- 内核下拉与只读框显示版本号;矿池卡新增「矿池网站」链接。
- 份额统计口径统一:客户端显示、日志与上报口径一致,每张显卡各自计数,相加等于总数。
- 修正内核版本上报与实际内核不一致的问题。
- 修复 PEARLSKI 内核输出解析(此前算力 / 份额显示为空)。
- 在线更新检查改为启动即查,并每 30 分钟检查一次。
- 界面导航图标与对齐优化。

English:

- Added a sidebar "Hashrate / earnings lookup" entry that opens the lookup site with the wallet from your settings.
- Added the PEARLSKI pool (with its official engine and balance lookup); removed the 2Miners pool.
- The pool dropdown is sorted by real PRLScan ranking; direct wallet links now also cover LuckyPool / PearlHash.
- Engine dropdowns and read-only fields show version numbers; pool cards gained a "Pool website" link.
- Unified share accounting: the client display, logs, and reports now use the same counting, with per-GPU counts adding up to the total.
- Fixed engine version reports not matching the engine actually running.
- Fixed PEARLSKI engine output parsing (hashrate / shares previously showed empty).
- Online update checks now run at startup and every 30 minutes.
- Navigation icon and alignment polish.

## v0.3.7

- 修复 WildRig 挖矿时「总算力 / 单卡算力」不显示的问题。
- 大幅优化界面性能,消除点击矿池 / 内核 / 下拉时的卡顿。
- 修复选择内核后左侧矿池列表被过滤消失的问题:矿池列表始终全部显示,选定矿池后自动适配内核。
- 修复「选了某内核却启动了另一个内核」的问题。
- 正式包改为不带内核的精简版,各内核通过签名清单按需下载并校验 SHA-256。
- 本版发布时的内核:AlphaMiner 1.8.6、KRig 1.2.0、PeakMiner 2.11.0、SRBMiner 3.5.9、TW-Pearl-Miner 3.5.1、WildRig 0.50.2。

English:

- Fixed WildRig total / per-GPU hashrate not being displayed.
- Major UI performance improvements, removing lag when clicking pools, engines, and dropdowns.
- Fixed the pool list disappearing after selecting an engine: the full pool list is always shown, and engines adapt once a pool is chosen.
- Fixed choosing one engine but launching another.
- The release package no longer bundles engines; each engine is downloaded on demand from the signed manifest and verified with SHA-256.
- Engines at release time: AlphaMiner 1.8.6, KRig 1.2.0, PeakMiner 2.11.0, SRBMiner 3.5.9, TW-Pearl-Miner 3.5.1, WildRig 0.50.2.

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
