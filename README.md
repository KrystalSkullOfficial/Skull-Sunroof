# Sunroof [<img src="./static/icon.png" width="225" align="right" alt="Sunroof">](https://github.com/verticalsync/Sunroof)

[![Suncord](https://img.shields.io/badge/Suncord-yellow?style=flat)](https://github.com/verticalsync/Suncord)
[![Tests](https://github.com/verticalsync/Sunroof/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/verticalsync/Sunroof/actions/workflows/test.yml)
[![Discord](https://img.shields.io/discord/1207691698386501634.svg?color=768AD4&label=Discord&logo=discord&logoColor=white)](https://discord.gg/VasF3Ma4Ab)

Sunroof is a fork of [Vesktop](https://github.com/Vencord/Vesktop).

You can join our [discord server](https://discord.gg/VasF3Ma4Ab) for commits, changes, chat or even support.<br></br>

## Main features

-   Much more lightweight and faster than the official Discord app
-   Linux Screenshare with sound & wayland

**Extra included changes**

-   Suncord preinstalled
-   Custom Splash animations from [this PR](https://github.com/Vencord/Vesktop/pull/355)

**Not yet supported**:

-   Global Keybinds

## Installing

### Windows

If you don't know the difference, pick the Installer.

-   [Installer](https://github.com/verticalsync/Sunroof/releases/latest/download/Sunroof-Setup-1.6.0.exe)
-   [Portable](https://github.com/verticalsync/Sunroof/releases/latest/download/Sunroof-1.6.0-win.zip)

### Mac

If you don't know the difference, pick the Intel build.

-   [Intel build (amd64)](https://github.com/verticalsync/Sunroof/releases/latest/download/Sunroof-1.6.0.dmg)
-   [Apple Silicon (arm64)](https://github.com/verticalsync/Sunroof/releases/latest/download/Sunroof-1.6.0-arm64.dmg)

### Linux

[![Download on Flathub](https://flathub.org/api/badge?svg)](https://flathub.org/apps/io.github.verticalsync.sunroof)

If you don't know the difference, pick amd64.

-   amd64 / x86_64
    -   [AppImage](https://github.com/verticalsync/Sunroof/releases/latest/download/Sunroof-1.6.0.AppImage)
    -   [Ubuntu/Debian (.deb)](https://github.com/verticalsync/Sunroof/releases/latest/download/sunroof_1.6.0_amd64.deb)
    -   [Fedora/RHEL (.rpm)](https://github.com/verticalsync/Sunroof/releases/latest/download/sunroof-1.6.0.x86_64.rpm)
    -   [tarball](https://github.com/verticalsync/Sunroof/releases/latest/download/sunroof-1.6.0.tar.gz)
-   arm64 / aarch64
    -   [AppImage](https://github.com/verticalsync/Sunroof/releases/latest/download/Sunroof-1.6.0-arm64.AppImage)
    -   [Ubuntu/Debian (.deb)](https://github.com/verticalsync/Sunroof/releases/latest/download/sunroof_1.6.0_arm64.deb)
    -   [Fedora/RHEL (.rpm)](https://github.com/verticalsync/Sunroof/releases/latest/download/sunroof-1.6.0.aarch64.rpm)
    -   [tarball](https://github.com/verticalsync/Sunroof/releases/latest/download/sunroof-1.6.0-arm64.tar.gz)

## Building from Source

Packaging will create builds in the dist/ folder

> [!NOTE]
> On Windows, if you run the test script, you will get test errors about venmic, you can ignore these as it's a linux only module.

```sh
git clone https://github.com/verticalsync/Sunroof
cd Sunroof

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman
# Or package to a directory only
pnpm package:dir
```
