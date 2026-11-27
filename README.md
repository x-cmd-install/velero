# velero

[中文版本](./README.cn.md)

Backup and migrate Kubernetes applications and their persistent volumes

[![x-cmd/install — velero Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/velero.svg)](https://x-cmd.com/install/velero)

## Install

```sh
x install velero
```

## Code insight

Total: **268,661** lines of code across **1235** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 225,193 | 26,478 | 30,024 | 993 |
| Json | 22,339 | 0 | 0 | 12 |
| Yaml | 10,533 | 71 | 37 | 98 |
| Sass | 5,666 | 1,079 | 1,303 | 103 |
| Svg | 2,013 | 15 | 2 | 29 |

## OpenSSF Scorecard

Overall score: **6.8 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/vmware-tanzu/velero>
- **Homepage**: <https://velero.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.18.5-rc.1` (2026-11-23)
- **Last commit**: 2026-11-26
- **Assets in release**: 9

## Popularity

- **Stars**: 10,385 · **Forks**: 1,656 · **Open issues**: 4,921 · **Contributors**: 369

## Totals (cumulative)

- **Releases**: 184 · **Merged PRs**: 4131 · **Open PRs**: 198 · **Closed issues**: 4292 · **Open issues**: 629 · **Commits**: 7115

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-28 | 4 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-09-28 | 5 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-08-29 | 9 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-05-31 | 12 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-12-02 | 21 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-12-07 | 37 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [CHECKSUM](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/CHECKSUM) | 804 B | `other` |
| [velero-v1.19.0-darwin-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-darwin-amd64.tar.gz) | 62.0 MiB | `native/darwin/x64` |
| [velero-v1.19.0-darwin-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-darwin-arm64.tar.gz) | 58.5 MiB | `native/darwin/arm64` |
| [velero-v1.19.0-linux-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-amd64.tar.gz) | 58.8 MiB | `native/linux/x64` |
| [velero-v1.19.0-linux-arm.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-arm.tar.gz) | 54.8 MiB | `native/linux/arm` |
| [velero-v1.19.0-linux-arm64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-arm64.tar.gz) | 53.9 MiB | `native/linux/arm64` |
| [velero-v1.19.0-linux-ppc64le.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-ppc64le.tar.gz) | 54.2 MiB | `native/unknown` |
| [velero-v1.19.0-linux-s390x.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-linux-s390x.tar.gz) | 57.2 MiB | `native/unknown` |
| [velero-v1.19.0-windows-amd64.tar.gz](https://github.com/vmware-tanzu/velero/releases/download/v1.19.0/velero-v1.19.0-windows-amd64.tar.gz) | 59.5 MiB | `native/win/x64` |

## Distribution status

Reported by **55** distros on [repology.org](https://repology.org/project/velero). **2** are ✅ on the latest upstream release, **18** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `1.18.4` | ⚠️ outdated |
| Homebrew | `1.19.0` | ✅ latest |
| Nix unstable | `1.18.4` | ⚠️ outdated |
| openSUSE Tumbleweed | `1.18.4` | ⚠️ outdated |

## Improve this data

Install metadata for velero lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `velero` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/velero.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261127.yml` · 2026-11-27T08:40:48Z._
