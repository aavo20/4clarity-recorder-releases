# 4Clarity Downloads

Official installer downloads and release notes for **4Clarity**.

The application source code is private. This public repository contains only
release metadata, downloadable installers, and signed update packages.

## Download 4Clarity 0.2.5

| Platform | Device | Download | Release notes |
| --- | --- | --- | --- |
| Windows | x64 PC (Intel or AMD) | [Windows installer (.exe)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.2.5/4Clarity_0.2.5_x64-setup.exe) | [0.2.5 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.5) |
| macOS | Apple Silicon Mac (M-series) | [Apple Silicon installer (.dmg)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.2.5/4Clarity_0.2.5_aarch64.dmg) | [0.2.5 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.5) |
| macOS | Intel Mac | [Intel installer (.dmg)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.2.5/4Clarity_0.2.5_x86_64.dmg) | [0.2.5 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.5) |

**Choose one installer for your device from the table above.** Not sure which Mac
you have? See [Choosing a Mac Download](#choosing-a-mac-download).

The `.app.tar.gz`, `.sig`, and `latest.json` files in the release assets are used
by in-app updates; you do not need to download them manually. The automatically
generated **Source code** archives are not application installers.

All published versions and their release notes are available on the
[Releases page](https://github.com/aavo20/4clarity-recorder-releases/releases).

## What's New in 0.2.5

- **Email sharing:** verify your sender address, then send transcripts and
  summaries with an optional message. Replies go to your verified address, and
  your email session is stored in Windows Credential Manager or macOS Keychain.
- **ZIP export and a compact Share screen:** choose selected audio, transcript,
  and summary files for an archive. Email sharing includes text files only.
- **Optional call reminders:** enable reminders for Zoom, Microsoft Teams, Slack,
  Discord, and Telegram desktop apps. Recording starts only when you choose it.
- **Startup and background options:** launch at login and keep the app available
  from the Windows tray or macOS menu bar.
- **Offline preparation:** download and manage local components in advance from
  Settings, with progress, cancellation, and resume.
- **Updated Home and Settings:** a recording overview, clearer settings tabs,
  managed local-processing defaults, and more configurable keyboard shortcuts.
- **Signed in-app updates:** download future updates in the app, then choose
  **Install and restart** when ready.
- **Reliability fixes:** improved settings-save recovery, microphone handling,
  macOS permission feedback, and Windows call-reminder filtering.

See the [full release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.5)
for all changes.

## Updating an Existing Installation

**Upgrading from 0.2.4 or earlier:** download the 0.2.5 installer for your computer
from the table above and run it to upgrade your existing installation.

**On 0.2.5:** official release builds support signed in-app updates. Check for
updates in **Settings > About**. When a newer release is available, download it
with progress and cancellation controls, then choose **Install and restart**.
Installation never starts silently. You can also use the installers above.

## Choosing a Mac Download

Open **Apple menu > About This Mac** and check the processor information:

- If it shows **Chip: Apple M-series**, download the Apple Silicon DMG.
- If it shows **Processor: Intel**, download the Intel DMG.

Both macOS builds require macOS 14.2 or later.

## Install on Windows

1. Download `4Clarity_0.2.5_x64-setup.exe` from the table above.
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
installer. Required components are downloaded when first needed. To prepare for
offline work or manage existing downloads, open
**Settings > General > Local components**.

## About the Source Code Archives

GitHub automatically adds **Source code (zip)** and **Source code (tar.gz)** to
every tagged release. These archives are snapshots of this public downloads
repository, not the private 4Clarity application source code. They cannot be
removed from the GitHub Releases interface and can be ignored by end users.
