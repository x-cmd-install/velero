# velero

[中文版本](./README.cn.md)

Backup and migrate Kubernetes applications and their persistent volumes

![velero](https://repo.x-cmd.io/velero.svg)

## Install

```sh
x install velero
```

## Code insight

Total: **256,874** lines of code across **1214** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 214,014 | 25,351 | 28,905 | 975 |
| Json | 22,340 | 0 | 0 | 12 |
| Yaml | 10,283 | 66 | 37 | 95 |
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
- **Last commit**: 2026-09-10
- **Assets in release**: 9

## Popularity

- **Stars**: 10,288 · **Forks**: 1,621 · **Open issues**: 4,816 · **Contributors**: 345

## Totals (cumulative)

- **Releases**: 177 · **Merged PRs**: 3915 · **Open PRs**: 185 · **Closed issues**: 4163 · **Open issues**: 653 · **Commits**: 6831

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 2 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 2 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 5 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 8 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 17 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 33 | 0 | 0 | 0 | 0 | 0 |

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

## Distribution status

Reported by **53** distros on [repology.org](https://repology.org/project/velero). **13** are ✅ on the latest upstream release, **7** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `1.18.2` | ✅ latest |
| Homebrew | `1.18.2` | ✅ latest |
| Nix unstable | `1.18.2` | ✅ latest |
| openSUSE Tumbleweed | `1.18.2` | ✅ latest |

## Improve this data

Install metadata for velero lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `velero` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/velero.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:46:19Z._
