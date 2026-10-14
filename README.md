# Luan

Distribution repository for **Luan**, a native macOS menu bar app that provides sound cues for coding workflows.

- Website: [luan.fuyo.app](https://luan.fuyo.app)
- Download: [luan.fuyo.app/download](https://luan.fuyo.app/download) · [latest Luan.dmg](https://github.com/onepiece-studio/Luan-macOS/releases/latest/download/Luan.dmg) · [all releases](https://github.com/onepiece-studio/Luan-macOS/releases)
- Sparkle feed: [appcast.xml](https://raw.githubusercontent.com/onepiece-studio/Luan-macOS/main/appcast.xml)

## Install with Homebrew

As an alternative to the DMG, install Luan with [Homebrew](https://brew.sh):

```sh
brew install --cask onepiece-studio/tap/luan
```

Homebrew adds the `onepiece-studio/tap` tap automatically. Luan installed this way still updates itself in the app through Sparkle. To uninstall, run `brew uninstall --cask luan`.

## Repository scope

This repository contains release metadata and approved distribution assets. **Application source code is not stored here.** App updates use the public HTTPS feed and release assets; GitHub credentials are never embedded in the app.

Luan targets Apple Silicon Macs running macOS 15 Sequoia or later. Its bundle identifier is `app.fuyo.luan`.

## Test builds

Current releases are public test builds connected to a staging license service. Pro requires a valid test license key; test keys are not purchase entitlements. Luan is signed with an Apple Developer ID and notarized by Apple, so the downloaded app opens after the standard macOS first-launch confirmation.

Each release is a regular (non-prerelease) GitHub Release with a fixed `Luan.dmg` asset for first-time installation and a build-numbered ZIP for in-app updates.

## Updates

Luan checks this feed and offers updates in the app through Sparkle.

## License

Luan is proprietary software. © 2026 Fuyo Studio. All rights reserved. Use of the app is subject to the [Terms](https://luan.fuyo.app/terms).
