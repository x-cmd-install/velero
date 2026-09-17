# velero

[中文版本](./README.cn.md)

Backup and migrate Kubernetes applications and their persistent volumes

![velero](https://repo.x-cmd.io/velero.svg)

## Install

```sh
x install velero
```

## Code insight

Total: **259,691** lines of code across **1219** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 216,802 | 25,559 | 29,156 | 980 |
| Json | 22,340 | 0 | 0 | 12 |
| Yaml | 10,312 | 66 | 37 | 95 |
| Sass | 5,666 | 1,079 | 1,303 | 103 |
| Svg | 2,013 | 15 | 2 | 29 |

## OpenSSF Scorecard

Overall score: **7.1 / 10**

Lowest-scoring checks:

- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## Source

- **Upstream**: <https://github.com/vmware-tanzu/velero>
- **Homepage**: <https://velero.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.18.3-rc.2` (2026-06-26)
- **Last commit**: 2026-09-17
- **Assets in release**: 9

## Popularity

- **Stars**: 10,296 · **Forks**: 1,622 · **Open issues**: 4,818 · **Contributors**: 352

## Totals (cumulative)

- **Releases**: 177 · **Merged PRs**: 3937 · **Open PRs**: 174 · **Closed issues**: 4182 · **Open issues**: 636 · **Commits**: 6884

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-18 | 2 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-19 | 2 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-19 | 4 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-21 | 8 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-22 | 16 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-27 | 33 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [CHECKSUM](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/CHECKSUM) | 804 B | `other` |
| [velero-v1.18.2-darwin-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-darwin-amd64.tar.gz) | 58.4 MiB | `native/darwin/x64` |
| [velero-v1.18.2-darwin-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-darwin-arm64.tar.gz) | 55.3 MiB | `native/darwin/arm64` |
| [velero-v1.18.2-linux-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-amd64.tar.gz) | 55.0 MiB | `native/linux/x64` |
| [velero-v1.18.2-linux-arm.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-arm.tar.gz) | 51.2 MiB | `native/linux/arm` |
| [velero-v1.18.2-linux-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-arm64.tar.gz) | 50.6 MiB | `native/linux/arm64` |
| [velero-v1.18.2-linux-ppc64le.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-ppc64le.tar.gz) | 50.8 MiB | `native/unknown` |
| [velero-v1.18.2-linux-s390x.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-linux-s390x.tar.gz) | 53.1 MiB | `native/unknown` |
| [velero-v1.18.2-windows-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.2/velero-v1.18.2-windows-amd64.tar.gz) | 55.8 MiB | `native/win/x64` |

## Improve this data

Install metadata for velero lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `velero` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/velero.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260917.yml` · 2026-09-17T05:01:13Z._
