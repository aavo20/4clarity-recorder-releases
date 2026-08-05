# 4Clarity Recorder Releases

This public repository contains installer downloads for **4Clarity Recorder** on **Windows** and **macOS**.

The application source code is private. This repository is used only to distribute installer builds and release notes.

## Windows

Download the latest Windows installer from the GitHub Releases page:

https://github.com/aavo20/4clarity-recorder-releases/releases/latest

Recommended asset:

- `4Clarity.Recorder.Setup.0.1.0.exe`

Installation steps:

1. Download the `.exe` installer from the latest Windows release.
2. Open the installer.
3. Follow the setup prompts.
4. Launch `4Clarity Recorder` from the Start menu or desktop shortcut.

The Windows build includes the bundled local runtime. Transcript and summary models can be downloaded on first run or later from Settings.

## macOS Apple Silicon

Download the latest macOS Apple Silicon DMG from the macOS release page:

https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.1.0-beta.1-mac

Supported devices:

- Apple Silicon Macs: M1, M2, M3, M4, M5, and newer

Installation steps:

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