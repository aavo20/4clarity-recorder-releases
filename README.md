# 4Clarity Recorder Releases

This public repository contains release downloads for **4Clarity Recorder**.

The application source code is private. This repository is only used to distribute signed and notarized installer builds.

## macOS Apple Silicon

Download the latest macOS Apple Silicon DMG from the GitHub Releases page:

https://github.com/aavo20/4clarity-recorder-releases/releases

Supported devices:

- Apple Silicon Macs: M1, M2, M3, M4, M5, and newer

## Installation

1. Download the `.dmg` file from GitHub Releases using Safari, Chrome, or another browser.
2. Open the downloaded `.dmg`.
3. Drag `4Clarity Recorder.app` into `Applications`.
4. Launch the app from `Applications`.

Do not transfer the `.dmg` through Telegram or other messengers. macOS can hard-quarantine files created by sandboxed apps, which may prevent the app from opening even when the build is correctly signed and notarized.

## Signing and Notarization

Current macOS builds are signed and notarized with Apple Developer ID:

- Developer ID Application: `SWEETSOFT D.O.O. (SJ2MUG2GFP)`
- Apple notarization: accepted
- Gatekeeper: accepted as `Notarized Developer ID`

End users do not need an Apple Developer account.
