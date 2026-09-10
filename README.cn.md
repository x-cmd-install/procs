# procs

[English version](./README.md)

A modern replacement for ps written in Rust

![procs](https://repo.x-cmd.io/procs.svg?lang=zh)

## 安装

```sh
x install procs
```

## 代码规模

合计: **14,688** 行代码（覆盖前 5 种语言、共 **111** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Rust | 14,216 | 386 | 1,658 | 105 |
| Toml | 367 | 0 | 60 | 3 |
| AsciiDoc | 40 | 0 | 19 | 1 |
| Makefile | 38 | 0 | 12 | 1 |
| Yaml | 27 | 0 | 4 | 1 |

## OpenSSF Scorecard 评分

总评分: **4.6 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Pinned-Dependencies** (0/10) — dependency not pinned by hash detected -- score normalized to 0

## 源代码

- **上游仓库**: <https://github.com/dalance/procs>
- **许可证**: MIT

## 发布

- **最新版本**: `v0.14.12` (2026-06-25)
- **最近提交**: 2026-09-09
- **Release 含资产**: 6 个

## 流行度

- **Star**: 6,165 · **Fork**: 155 · **开放 issue**: 173 · **贡献者**: 55

## 累计统计

- **发布数**: 111 · **已合并 PR**: 706 · **开放 PR**: 9 · **已关闭 issue**: 148 · **开放 issue**: 25 · **提交数**: 2305

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 14 | 3 | 0 | 1 | 33 |
| last60d | 2026-07-12 | 0 | 29 | 4 | 1 | 1 | 47 |
| 90d | 2026-06-12 | 1 | 35 | 5 | 2 | 2 | 60 |
| last180d | 2026-03-14 | 1 | 63 | 7 | 3 | 6 | 87 |
| 360d | 2025-09-15 | 2 | 118 | 7 | 4 | 9 | 152 |
| last720d | 2024-09-20 | 6 | 228 | 7 | 13 | 15 | 551 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [procs-0.14.12-1.x86_64.rpm](https://github.com/dalance/procs/releases/download/v0.14.12/procs-0.14.12-1.x86_64.rpm) | 2.4 MiB | `runtime/rpm/x86_64` |
| [procs-v0.14.12-aarch64-linux.zip](https://github.com/dalance/procs/releases/download/v0.14.12/procs-v0.14.12-aarch64-linux.zip) | 2.3 MiB | `native/linux/arm64` |
| [procs-v0.14.12-aarch64-mac.zip](https://github.com/dalance/procs/releases/download/v0.14.12/procs-v0.14.12-aarch64-mac.zip) | 2.0 MiB | `other` |
| [procs-v0.14.12-x86_64-linux.zip](https://github.com/dalance/procs/releases/download/v0.14.12/procs-v0.14.12-x86_64-linux.zip) | 2.4 MiB | `native/linux/x64` |
| [procs-v0.14.12-x86_64-mac.zip](https://github.com/dalance/procs/releases/download/v0.14.12/procs-v0.14.12-x86_64-mac.zip) | 2.1 MiB | `other` |
| [procs-v0.14.12-x86_64-windows.zip](https://github.com/dalance/procs/releases/download/v0.14.12/procs-v0.14.12-x86_64-windows.zip) | 1.5 MiB | `native/win/x64` |

## 发行版状态

在 [repology.org](https://repology.org/project/procs) 上共有 **137** 个发行版报告此项目。**31** 个 ✅ 已是最新上游版本，**80** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `0.14.11` | ⚠️ outdated |
| Debian 14 | `0.14.11` | ⚠️ outdated |
| Debian 13 | `0.14.10` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `0.14.10` | ⚠️ outdated |
| Arch | `0.14.12` | ✅ latest |
| Homebrew | `0.14.12` | ✅ latest |
| Nix unstable | `0.14.12` | ✅ latest |
| Void | `0.14.10` | ⚠️ outdated |
| Alpine edge | `0.14.12` | ✅ latest |
| openSUSE Tumbleweed | `0.14.12` | ✅ latest |

## 改进这些数据

procs 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `procs` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/procs.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T20:15:50Z._
