# Louie Cartoon Apps

Official downloads and update files for my Windows apps.
Follow me on TikTok: [@LouieCartoon](https://www.tiktok.com/@louiecartoon)

## Apps

| App | What it does | Latest | Download |
|---|---|---|---|
| **AutoLocalLLM** | Scans your PC, recommends AI language models that will actually run on your hardware, downloads and installs them, and lets you chat with them. Everything runs on your own PC. | 1.5.2 | [Installer](https://github.com/louiecartoon/app-releases/releases/download/autolocalllm-v1.5.2/AutoLocalLLMSetup.exe) · [Portable](https://github.com/louiecartoon/app-releases/releases/download/autolocalllm-v1.5.2/AutoLocalLLMPortable.exe) |
| **956 Radio Scanner** | A local radio scanner and player. Finds internet radio stations for your region (default: the Rio Grande Valley, 956), shows them on a radar, and plays and/or records them. | 1.4.5 | [Installer](https://github.com/louiecartoon/app-releases/releases/download/956-radio-scanner-v1.4.5/956RadioScannerSetup.exe) · [Portable](https://github.com/louiecartoon/app-releases/releases/download/956-radio-scanner-v1.4.5/956RadioScannerPortable.exe) |
| **956 News Wire** | A local news scanner. Gathers recent headlines for your keywords (default: the Rio Grande Valley) from news feeds and local news sites onto one screen. | 2.6.4 | [Installer](https://github.com/louiecartoon/app-releases/releases/download/956-news-wire-v2.6.4/956NewsWireSetup.exe) · [Portable](https://github.com/louiecartoon/app-releases/releases/download/956-news-wire-v2.6.4/956NewsWirePortable.exe) |
| **606 Radio Scanner** | The radio scanner set up for Eastern Kentucky (area code 606), with its own purple theme. | 1.1.8 | [Installer](https://github.com/louiecartoon/app-releases/releases/download/606-radio-scanner-v1.1.8/606RadioScannerSetup.exe) · [Portable](https://github.com/louiecartoon/app-releases/releases/download/606-radio-scanner-v1.1.8/606RadioScannerPortable.exe) |

Release notes and older versions are on the [Releases](https://github.com/louiecartoon/app-releases/releases) page.

## Installing

- **Installer**: installs the app for your Windows user, with a Start menu entry and an uninstaller. Recommended.
- **Portable**: a single `.exe` that runs from anywhere (a USB stick, Downloads) without installing.
- Requires Windows 10 or 11 (64-bit).
- New apps can trigger a Windows SmartScreen warning. If you downloaded the file from this page, choose **More info → Run anyway**.

## Updates

Each app checks this page for new versions and tells you when one is available (**Settings → Updates**).
Updates are protected: the update list is digitally signed, and every download is checked against its published SHA-256 fingerprint before it is installed. An update that didn't come from here is refused.

## Product keys

The apps are free to use. Some extra features unlock with a product key. Keys are checked on your PC and need no account.
For a key, or a problem with one: **louiecartoon.business@gmail.com**

## About this repository

This repository only holds the published downloads (under Releases) and the signed update files the apps read:

| File | Purpose |
|---|---|
| `latest.json` + `.sig` | Newest version of each app, its download links and fingerprints |
| `revoked.json` + `.sig` | Product keys that have been cancelled |

Source code is not published here. It is kept privately, each app in its own repository with its full version history.
