# Luan

Distribution repository for **Luan**, a native macOS menu bar app that provides sound cues for coding workflows.

- Website: [luan.fuyo.app](https://luan.fuyo.app)
- Downloads: [Releases](https://github.com/onepiece-studio/Luan-macOS/releases) · [latest Luan.dmg](https://github.com/onepiece-studio/Luan-macOS/releases/latest/download/Luan.dmg)
- Sparkle feed: [appcast.xml](https://raw.githubusercontent.com/onepiece-studio/Luan-macOS/main/appcast.xml)

## Repository scope

This repository contains release metadata and approved distribution assets. **Application source code is not stored here.** App updates use the public HTTPS feed and release assets; GitHub credentials are never embedded in the app.

Luan targets Apple Silicon Macs running macOS 26 or later. Its bundle identifier is `app.fuyo.luan`.

## Test builds

Current releases are development test builds with simulated license activation. Any nonempty email and license input can activate test Pro; this is not a purchase entitlement. Production builds exclude the simulation path. These ad-hoc signed builds have not been Apple-notarized.

Each release is a regular (non-prerelease) GitHub Release with a fixed `Luan.dmg` asset for first-time installation and a build-numbered ZIP for in-app updates.

Build 15 is the first build distributed from this repository. Builds 10–14 were distributed from a previous repository that has since been deleted and cannot see this feed; install Build 15 once from the DMG, after which updates arrive in the app.
