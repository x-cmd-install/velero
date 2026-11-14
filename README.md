# velero

[中文版本](./README.cn.md)

Backup and migrate Kubernetes applications and their persistent volumes

[![x-cmd/install — velero Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/velero.svg)](https://x-cmd.com/install/velero)

## Install

```sh
x install velero
```

## Code insight

Total: **266,821** lines of code across **1235** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 223,355 | 26,369 | 29,812 | 993 |
| Json | 22,339 | 0 | 0 | 12 |
| Yaml | 10,533 | 71 | 37 | 98 |
| Sass | 5,666 | 1,079 | 1,303 | 103 |
| Svg | 2,013 | 15 | 2 | 29 |

## OpenSSF Scorecard

Overall score: **6.7 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## Source

- **Upstream**: <https://github.com/vmware-tanzu/velero>
- **Homepage**: <https://velero.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.19.0-rc.1` (2026-09-28)
- **Last commit**: 2026-11-14
- **Assets in release**: 9

## Popularity

- **Stars**: 10,377 · **Forks**: 1,649 · **Open issues**: 4,897 · **Contributors**: 366

## Totals (cumulative)

- **Releases**: 181 · **Merged PRs**: 4086 · **Open PRs**: 182 · **Closed issues**: 4268 · **Open issues**: 629 · **Commits**: 7080

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-15 | 1 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-09-15 | 4 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-08-16 | 6 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-18 | 10 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-11-19 | 18 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-11-24 | 34 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [CHECKSUM](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/CHECKSUM) | 804 B | `other` |
| [velero-v1.18.4-darwin-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-darwin-amd64.tar.gz) | 61.1 MiB | `native/darwin/x64` |
| [velero-v1.18.4-darwin-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-darwin-arm64.tar.gz) | 57.8 MiB | `native/darwin/arm64` |
| [velero-v1.18.4-linux-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-linux-amd64.tar.gz) | 57.4 MiB | `native/linux/x64` |
| [velero-v1.18.4-linux-arm.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-linux-arm.tar.gz) | 53.6 MiB | `native/linux/arm` |
| [velero-v1.18.4-linux-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-linux-arm64.tar.gz) | 52.8 MiB | `native/linux/arm64` |
| [velero-v1.18.4-linux-ppc64le.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-linux-ppc64le.tar.gz) | 53.0 MiB | `native/unknown` |
| [velero-v1.18.4-linux-s390x.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-linux-s390x.tar.gz) | 56.3 MiB | `native/unknown` |
| [velero-v1.18.4-windows-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.18.4/velero-v1.18.4-windows-amd64.tar.gz) | 58.3 MiB | `native/win/x64` |

## Distribution status

Reported by **55** distros on [repology.org](https://repology.org/project/velero). **12** are ✅ on the latest upstream release, **8** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `1.18.4` | ✅ latest |
| Homebrew | `1.18.4` | ✅ latest |
| Nix unstable | `1.18.3` | ⚠️ outdated |
| openSUSE Tumbleweed | `1.18.4` | ✅ latest |

## Improve this data

Install metadata for velero lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `velero` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/velero.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261114.yml` · 2026-11-14T06:32:13Z._
