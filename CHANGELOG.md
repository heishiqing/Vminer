# 更新日志 / Changelog

[中文](README.md) | [English](README.en.md)

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
