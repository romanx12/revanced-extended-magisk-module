#### ⚠️ Do not download modules from 3rd party sources like random websites you found on Google. There are many that uses my modules and impersonates ReVanced.

# ReVanced Extended Magisk Module
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rvxc_magisk)
[![Build Modules](https://github.com/MatadorProBr/revanced-extended-magisk-module/actions/workflows/build.yml/badge.svg)](https://github.com/MatadorProBr/revanced-extended-magisk-module/actions/workflows/build.yml)
[![CI](https://github.com/MatadorProBr/revanced-extended-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/MatadorProBr/revanced-extended-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced Extended Builder

Get the [latest CI release](https://github.com/MatadorProBr/revanced-extended-magisk-module/releases).

[**mindetach module**](https://github.com/j-hc/mindetach-magisk) in the releases section detaches YouTube and YouTube Music from Play Store and blocks their forced updates.

## Features
 * Support all present and future [ReVanced Extended](https://github.com/inotia00/revanced-patches) apps
 * Can build Magisk modules and non-root APKs
 * Updated daily with the latest versions of apps and patches
 * Optimize APKs and modules for size
 * Modules
     * recompile invalidated odex for faster usage
     * receive updates from Magisk app
     * do not break safetynet or trigger root detections
     * handle installation of the correct version of the stock app and all that
     * support Magisk and KernelSU

#### **Note that the [CI workflow](../../actions/workflows/ci.yml) is scheduled to build the modules and APKs hourly using GitHub Actions if there is a change in ReVanced Extended patches. You may want to disable it.**

## To include/exclude patches or patch more ReVanced Apps
[**See the list of patches**](https://j-hc.github.io/rvmm-config-gen/)

 * Star the repo :eyes:
 * [Fork the repo](https://github.com/MatadorProBr/revanced-extended-magisk-module/fork) or use it as a template
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

Also see here [`CONFIG.md`](./CONFIG.md).

# Building Locally
## On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/MatadorProBr/revanced-extended-magisk-module/main/build-termux.sh)
```

## On Desktop
```console
$ git clone --recurse https://github.com/MatadorProBr/revanced-extended-magisk-module
$ cd revanced-extended-magisk-module
$ ./build.sh
```
