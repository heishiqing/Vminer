# 更新日志 / Changelog

[中文](README.md) | [English](README.en.md)

## v0.2.5

- 修复部分环境启动/界面异常问题，提升客户端稳定性。
- 优化网吧无盘系统和批量部署场景下的配置保存与读取，矿池、内核、双挖等配置可完整保留。
- 矿工名留空时自动使用本机电脑名，方便同一配置复制到多台机器。
- 优化显卡状态读取，减少运行中的额外查询开销。
- 继续支持 PRL 挖矿与 MDL 双挖。

English:

- Fixed startup/UI issues seen in some environments and improved client stability.
- Improved config saving and loading for cyber-cafe diskless systems and bulk deployments, preserving pool, kernel, dual-mining and related settings.
- Empty worker names now use the local computer name automatically, making shared configs easier to deploy across many machines.
- Optimized GPU status polling to reduce extra runtime queries.
- PRL mining and MDL dual mining remain supported.

## v0.2.4

- 修复 AlphaPool 双挖启动与稳定性问题，重点覆盖 A 池无法双挖/启动失败场景。
- 新增客户端内核版本动态拉取：服务器上架新内核后，客户端可刷新并显示新版本号。
- 上架 WildRig 0.49.1 与 TW 2.3.1 可选内核；SRBMiner / AlphaMiner 维持当前稳定版本。
- 修复性能总开关关闭时仍可能覆盖外部风扇设置的问题；关闭性能调度后不再接管外部超频/风扇配置。
- 优化异常退出后的自动恢复保护，减少循环闪退后反复恢复挖矿的风险。

English:

- Fixed AlphaPool dual-mining startup and stability issues, especially the A-pool dual-mining launch path.
- Added dynamic kernel-version refresh: newly published server-side kernels can appear in the client without hardcoding every future version.
- Added WildRig 0.49.1 and TW 2.3.1 as selectable kernels while keeping SRBMiner / AlphaMiner on the current stable versions.
- Fixed fan settings being overwritten when the performance master switch is off; external overclock/fan settings are no longer touched in that mode.
- Improved recovery protection after abnormal exits to reduce repeated crash/restart loops.

## v0.2.3

- 新增 MDL 合并挖矿支持：在支持合并挖矿的矿池中，可同时填写 PRL 与 MDL 钱包进行挖矿。
- 优化 HeroMiners、LuckyPool、AlphaPool、PearlHash 等矿池的兼容性与稳定性。
- 优化断线重连、运行日志和后台清理体验。
- 优化新版显卡与多矿工内核的启动稳定性。

English:

- Added MDL merge-mining support for pools that support PRL + MDL mining.
- Improved compatibility and stability for HeroMiners, LuckyPool, AlphaPool, PearlHash, and more.
- Improved reconnect behavior, runtime logs, and background cleanup.
- Improved startup stability for newer GPUs and multiple mining kernels.

## v0.2.2

- 修复部分多卡 / Windows 10 环境中挖矿启动后闪退的问题。
- AlphaMiner 内核新增 1.8.3 可选版，默认仍保留稳定版。
- 优化安装包体积与更新器体验。

English:

- Fixed a startup crash seen on some multi-GPU / Windows 10 environments.
- Added AlphaMiner 1.8.3 as an optional kernel while keeping the stable default.
- Reduced package size and improved the updater experience.
