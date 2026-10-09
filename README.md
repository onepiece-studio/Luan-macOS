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

Luan targets Apple Silicon Macs running macOS 26 or later. Its bundle identifier is `app.fuyo.luan`.

## Test builds

Current releases are development test builds with simulated license activation. Any nonempty email and license input can activate test Pro; this is not a purchase entitlement. Production builds exclude the simulation path. Since Build 35, Luan is signed with an Apple Developer ID and notarized by Apple, so the downloaded app opens after the standard macOS first-launch confirmation.

Each release is a regular (non-prerelease) GitHub Release with a fixed `Luan.dmg` asset for first-time installation and a build-numbered ZIP for in-app updates.

## Updates

Build 15 is the first build distributed from this repository. From Build 15 on, Luan checks this feed and offers updates in the app through Sparkle.

Builds 10–14 were distributed from a previous repository that has since been deleted, so they cannot receive updates from this feed. If you are on one of those builds, download and install the latest `Luan.dmg` once; later updates then arrive in the app.
