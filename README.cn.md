# velero

[English version](./README.md)

Backup and migrate Kubernetes applications and their persistent volumes

[![x-cmd/install — velero Code Quality Monitoring Repo Card](https://repo.x-cmd.io/velero.svg?lang=zh)](https://x-cmd.com/install/velero)

## 安装

```sh
x install velero
```

## 代码洞察

合计: **259,801** 行代码（覆盖前 5 种语言、共 **1219** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 216,907 | 25,562 | 29,164 | 980 |
| Json | 22,340 | 0 | 0 | 12 |
| Yaml | 10,317 | 66 | 37 | 95 |
| Sass | 5,666 | 1,079 | 1,303 | 103 |
| Svg | 2,013 | 15 | 2 | 29 |

## OpenSSF Scorecard 评分

总评分: **7.1 / 10**

评分最低的几项:

- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## 源代码

- **上游仓库**: <https://github.com/vmware-tanzu/velero>
- **官网**: <https://velero.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.18.3-rc.2` (2026-06-26)
- **最近提交**: 2026-09-20
- **Release 含资产**: 9 个

## 流行度

- **Star**: 10,303 · **Fork**: 1,622 · **开放 issue**: 4,824 · **贡献者**: 352

## 累计统计

- **发布数**: 177 · **已合并 PR**: 3943 · **开放 PR**: 171 · **已关闭 issue**: 4197 · **开放 issue**: 627 · **提交数**: 6893

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-22 | 2 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-23 | 2 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-23 | 4 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-25 | 8 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-26 | 16 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-10-01 | 33 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [CHECKSUM](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/CHECKSUM) | 804 B | `other` |
| [velero-v1.18.2-darwin-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-darwin-amd64.tar.gz) | 58.4 MiB | `native/darwin/x64` |
| [velero-v1.18.2-darwin-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-darwin-arm64.tar.gz) | 55.3 MiB | `native/darwin/arm64` |
| [velero-v1.18.2-linux-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-amd64.tar.gz) | 55.0 MiB | `native/linux/x64` |
| [velero-v1.18.2-linux-arm.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-arm.tar.gz) | 51.2 MiB | `native/linux/arm` |
| [velero-v1.18.2-linux-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-arm64.tar.gz) | 50.6 MiB | `native/linux/arm64` |
| [velero-v1.18.2-linux-ppc64le.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-ppc64le.tar.gz) | 50.8 MiB | `native/unknown` |
| [velero-v1.18.2-linux-s390x.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-s390x.tar.gz) | 53.1 MiB | `native/unknown` |
| [velero-v1.18.2-windows-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-windows-amd64.tar.gz) | 55.8 MiB | `native/win/x64` |

## 改进这些数据

velero 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `velero` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/velero.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260921.yml` · 2026-09-21T04:57:44Z._
