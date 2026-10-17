# 4Clarity Downloads

Official installer downloads and release notes for **4Clarity**.

The application source code is private. This public repository contains only
release metadata, downloadable installers, and signed update packages.

## Download 4Clarity 0.3.1

**Rebuilt on October 17, 2026.** These installers include the fix for macOS
recordings failing to play when the player uses a combined audio cache.
The application version remains **0.3.1**. If you already have 0.3.1 installed,
download the installer for your device and reinstall it over the existing app;
an in-app update is not offered for the same version.

| Platform | Device | Download | Release notes |
| --- | --- | --- | --- |
| Windows | x64 PC (Intel or AMD) | [Windows installer (.exe)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.3.1/4Clarity_0.3.1_x64-setup.exe) | [0.3.1 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.3.1) |
| macOS | Apple Silicon Mac (M-series) | [Apple Silicon installer (.dmg)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.3.1/4Clarity_0.3.1_aarch64.dmg) | [0.3.1 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.3.1) |
| macOS | Intel Mac | [Intel installer (.dmg)](https://github.com/aavo20/4clarity-recorder-releases/releases/download/v0.3.1/4Clarity_0.3.1_x86_64.dmg) | [0.3.1 release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.3.1) |

**Choose one installer for your device from the table above.** Not sure which Mac
you have? See [Choosing a Mac Download](#choosing-a-mac-download).

The `.app.tar.gz`, `.sig`, and `latest.json` files in the release assets are used
by in-app updates; you do not need to download them manually. The automatically
generated **Source code** archives are not application installers.

All published versions and their release notes are available on the
[Releases page](https://github.com/aavo20/4clarity-recorder-releases/releases).

## What's New in 0.3.1

- **Summary templates:** choose from seven built-in formats for general
  summaries, decisions and actions, team status, client or product meetings,
  interviews, and learning. Preview templates in Settings, choose a default,
  or select a template on a recording to generate its summary.
- **Custom templates:** edit a template's instructions and save your own copy
  for future summaries. Queued summaries keep the template and settings selected
  when they were queued.
- **Contact projects and groups:** link a contact to several projects and
  groups from searchable header pickers, or create and assign a project or
  group without leaving the contact.
- **Formatted summaries and project ordering:** read, copy, and share Markdown
  summaries, and reorder projects by dragging or with the keyboard. Existing
  summaries remain readable, and project order is kept after restart.
- **Playback and processing fixes:** improved macOS Now Playing and system
  playback controls, synchronized microphone and system audio playback, and
  clearer title-generation progress after transcription.
- **More reliable everyday editing:** dialogs and navigation protect unsaved
  edits, failed loads offer Retry, and failed saves preserve entered values.
  Contact membership menus and keyboard focus work more consistently.
- **Fewer short false recording starts in Telegram on macOS:** call detection
  waits for about five to six seconds of sustained activity.

See the [full release notes](https://github.com/aavo20/4clarity-recorder-releases/releases/tag/v0.3.1)
for all changes.

## Updating an Existing Installation

**Upgrading from 0.2.4 or earlier:** download the 0.3.1 installer for your computer
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

1. Download `4Clarity_0.3.1_x64-setup.exe` from the table above.
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

**Since 0.2.6:** summaries and automatic recording titles use Qwen3 4B. The new
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
