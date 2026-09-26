# 4Clarity Downloads

Official installer downloads and release notes for **4Clarity**.

The application source code is private. This public repository contains only
release metadata, downloadable installers, and signed update packages.

## Download 4Clarity 0.2.6

| Platform | Device | Download | Release notes |
| --- | --- | --- | --- |
| Windows | x64 PC (Intel or AMD) | [Windows installer (.exe)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.2.6/4Clarity_0.2.6_x64-setup.exe) | [0.2.6 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.6) |
| macOS | Apple Silicon Mac (M-series) | [Apple Silicon installer (.dmg)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.2.6/4Clarity_0.2.6_aarch64.dmg) | [0.2.6 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.6) |
| macOS | Intel Mac | [Intel installer (.dmg)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.2.6/4Clarity_0.2.6_x86_64.dmg) | [0.2.6 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.6) |

**Choose one installer for your device from the table above.** Not sure which Mac
you have? See [Choosing a Mac Download](#choosing-a-mac-download).

The `.app.tar.gz`, `.sig`, and `latest.json` files in the release assets are used
by in-app updates; you do not need to download them manually. The automatically
generated **Source code** archives are not application installers.

All published versions and their release notes are available on the
[Releases page](https://github.com/aavo20/4clarity-recorder-releases/releases).

## What's New in 0.2.6

- **Optional automatic call recording:** enable it for your selected Zoom,
  Microsoft Teams, Slack, Discord, or Telegram desktop apps. A compact floating
  window lets you continue recording or discard the captured audio. Automatic
  recording stays off until you enable it.
- **Automatic call completion on Windows:** confirmed automatic Telegram and
  Discord recordings can stop and save after 30 seconds without detected call
  activity, then start transcription in the background. Manual recordings stay
  under your control.
- **Automatic transcription and a task queue:** saving a recording starts
  transcription. Queue transcription and summary work for other recordings;
  tasks run one at a time and continue while you browse. Pending tasks are not
  restored after closing the app.
- **Better recording navigation:** combine search with date, contact, duration,
  and project filters, rename recordings from their menu, and browse a simpler
  chronological list.
- **Contact ordering and simpler sidebars:** reorder contacts by dragging or
  using the keyboard, filter by group, and switch between active and archived
  projects when archived projects exist.
- **Updated summaries:** new summaries and automatic titles use the interface
  language (English, Russian, or Ukrainian) and the Qwen3 4B local model. See
  [Local Models](#local-models) for the new component download.
- **Reliability fixes:** reduced false recording starts from Telegram sounds on
  macOS, corrected generated characters, dismissible import errors, translated
  cancellation notices, and processing workers that stop when the app quits.

See the [full release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.2.6)
for all changes.

## Updating an Existing Installation

**Upgrading from 0.2.4 or earlier:** download the 0.2.6 installer for your computer
from the table above and run it to upgrade your existing installation.

**On 0.2.5 or later:** official release builds support signed in-app updates.
Check for updates in **Settings > About**. Download an available update with
progress and cancellation controls, then choose **Install and restart**.
Installation never starts silently. You can also use the installers above.

## Choosing a Mac Download

Open **Apple menu > About This Mac** and check the processor information:

- If it shows **Chip: Apple M-series**, download the Apple Silicon DMG.
- If it shows **Processor: Intel**, download the Intel DMG.

Both macOS builds require macOS 14.2 or later.

## Install on Windows

1. Download `4Clarity_0.2.6_x64-setup.exe` from the table above.
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

**New in 0.2.6:** summaries and automatic recording titles use Qwen3 4B. The new
summary component is about **2.5 GB** and must be downloaded even if you have an
older summary model. Prepare it in Local components before working offline, or
download it when generating your next summary. Automatic title generation does
not start this download on its own.

Existing recordings and summaries remain available. Upgrading does not
regenerate saved summaries or delete older model files; unused models can be
removed through Local components when you choose.

## About the Source Code Archives

GitHub automatically adds **Source code (zip)** and **Source code (tar.gz)** to
every tagged release. These archives are snapshots of this public downloads
repository, not the private 4Clarity application source code. They cannot be
removed from the GitHub Releases interface and can be ignored by end users.
