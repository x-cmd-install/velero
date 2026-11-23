# velero

[English version](./README.md)

Backup and migrate Kubernetes applications and their persistent volumes

[![x-cmd/install — velero Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/velero.svg?lang=zh)](https://x-cmd.com/install/velero)

## 安装

```sh
x install velero
```

## 代码洞察

合计: **267,819** 行代码（覆盖前 5 种语言、共 **1235** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 224,351 | 26,457 | 29,962 | 993 |
| Json | 22,339 | 0 | 0 | 12 |
| Yaml | 10,533 | 71 | 37 | 98 |
| Sass | 5,666 | 1,079 | 1,303 | 103 |
| Svg | 2,013 | 15 | 2 | 29 |

## OpenSSF Scorecard 评分

总评分: **6.8 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## 源代码

- **上游仓库**: <https://github.com/vmware-tanzu/velero>
- **官网**: <https://velero.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.19.0` (2026-11-23)
- **最近提交**: 2026-11-23
- **Release 含资产**: 9 个

## 流行度

- **Star**: 10,381 · **Fork**: 1,651 · **开放 issue**: 4,914 · **贡献者**: 369

## 累计统计

- **发布数**: 183 · **已合并 PR**: 4111 · **开放 PR**: 185 · **已关闭 issue**: 4280 · **开放 issue**: 634 · **提交数**: 7102

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-24 | 3 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-09-24 | 5 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-08-25 | 8 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-27 | 11 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-11-28 | 20 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-12-03 | 36 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [CHECKSUM](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/CHECKSUM) | 804 B | `other` |
| [velero-v1.19.0-darwin-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-darwin-amd64.tar.gz) | 62.0 MiB | `native/darwin/x64` |
| [velero-v1.19.0-darwin-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-darwin-arm64.tar.gz) | 58.5 MiB | `native/darwin/arm64` |
| [velero-v1.19.0-linux-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-amd64.tar.gz) | 58.8 MiB | `native/linux/x64` |
| [velero-v1.19.0-linux-arm.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-arm.tar.gz) | 54.8 MiB | `native/linux/arm` |
| [velero-v1.19.0-linux-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-arm64.tar.gz) | 53.9 MiB | `native/linux/arm64` |
| [velero-v1.19.0-linux-ppc64le.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-ppc64le.tar.gz) | 54.2 MiB | `native/unknown` |
| [velero-v1.19.0-linux-s390x.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-s390x.tar.gz) | 57.2 MiB | `native/unknown` |
| [velero-v1.19.0-windows-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-windows-amd64.tar.gz) | 59.5 MiB | `native/win/x64` |

## 发行版状态

在 [repology.org](https://repology.org/project/velero) 上共有 **55** 个发行版报告此项目。**13** 个 ✅ 已是最新上游版本，**7** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `1.18.4` | ✅ latest |
| Homebrew | `1.18.4` | ✅ latest |
| Nix unstable | `1.18.4` | ✅ latest |
| openSUSE Tumbleweed | `1.18.4` | ✅ latest |

## 改进这些数据

velero 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `velero` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/velero.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261123.yml` · 2026-11-23T07:35:08Z._
