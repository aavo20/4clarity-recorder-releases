# 4Clarity Downloads

Official installer downloads and release notes for **4Clarity**.

The application source code is private. This public repository contains only
release metadata and downloadable installers.

## Download 4Clarity 0.2.3

| Platform | Device | Download |
| --- | --- | --- |
| Windows | 64-bit PC | [Windows x64 installer](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.3-win.2) |
| macOS | Apple Silicon Mac | [Apple Silicon DMG](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.3-mac.2) |
| macOS | Intel Mac | [Intel DMG](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.3-mac.3) |

Download the installer listed for your device. The automatically generated
**Source code** archives are not application installers.

All published versions and their release notes are available on the
[Releases page](https://github.com/aavo20/4clarity-recorder-releases/releases).

## Choosing a Mac Download

Open **Apple menu > About This Mac** and check the processor information:

- If it shows **Chip: Apple M-series**, download the Apple Silicon DMG.
- If it shows **Processor: Intel**, download the Intel DMG.

Both macOS builds require macOS 14.2 or later.

## Install on Windows

1. Download `4Clarity_0.2.3_x64-setup.exe` from the Windows release.
2. Open the installer and follow the setup prompts.
3. Launch 4Clarity from the Start menu or desktop shortcut.

The Windows installer is not currently code-signed. Microsoft Defender
SmartScreen may ask for confirmation. Only continue when the installer was
downloaded from this repository.

## Install on macOS

1. Download the DMG that matches your Mac processor.
2. Open the downloaded DMG.
3. Drag **4Clarity** into **Applications**.
4. Launch 4Clarity from **Applications**.

The macOS application and DMG are signed with the SWEETSOFT D.O.O. Developer ID
and notarized by Apple. End users do not need an Apple Developer account.

Download the DMG directly from GitHub rather than transferring it through a
messaging application. Some sandboxed applications can add quarantine metadata
that prevents an otherwise valid application from opening normally.

## Local Models

Transcription, speaker separation, and summary models are not included in the
installer. They can be downloaded when first needed or managed later from
**Settings**.

## About the Source Code Archives

GitHub automatically adds **Source code (zip)** and **Source code (tar.gz)** to
every tagged release. These archives are snapshots of this public downloads
repository, not the private 4Clarity application source code. They cannot be
removed from the GitHub Releases interface and can be ignored by end users.
