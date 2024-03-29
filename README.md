# mpv-macos-git-builds

[![CI](https://github.com/NextFire/mpv-macos-git-builds/actions/workflows/ci.yml/badge.svg)](https://github.com/NextFire/mpv-macos-git-builds/actions/workflows/ci.yml)

**The latest build is available [here](https://github.com/NextFire/mpv-macos-git-builds/releases/latest).**

This repository provides unofficial git desktop builds of [mpv-player/mpv](https://github.com/mpv-player/mpv) for macOS.

Build dependencies:

- `ffmpeg` (git)
- `libplacebo` (git) for gpu-next
- `luajit` (stable) for Lua scripts
- `mujs` (stable) for JS scripts

## Homebrew

You can `brew tap nextfire/tap` ([repo](https://github.com/NextFire/homebrew-tap)) then install the git build with `brew install --cask mpv-git`.

The tap is automatically updated at each release so you can use `brew upgrade` to update mpv.
