<p align="center">
  <img src="assets/airlynk-logo.png" width="140" alt="AirLynk logo">
</p>

<h1 align="center">AirLynk</h1>

<p align="center">
  <b>Share files. Anywhere.</b><br>
  Send files and folders between your phone and your PC, nearby or far away.<br>
  No size limit, no account, no cloud upload.
</p>

<p align="center"><a href="https://airlynk.in">airlynk.in</a></p>

## Download

| Platform | Get AirLynk |
|---|---|
| **Android** | [Google Play](https://play.google.com/store/apps/details?id=com.airlynk.app) |
| **Windows 10 and 11** (64-bit) | [Microsoft Store](https://apps.microsoft.com/detail/9NHVZ89SQHJG) · `winget install airlynk` · [Installer (EXE)](https://github.com/aluvalasathish/airlynk-releases/releases/latest) |
| **macOS** | Coming soon |
| **Linux** | Coming soon |
| **iPhone and iPad** | Coming soon |

## Install on Windows

Three ways to get the same app. **Needs** Windows 10 version 1809 or later, 64-bit; Windows 11 on Arm runs it through emulation.

### Microsoft Store

[Get AirLynk from the Microsoft Store](https://apps.microsoft.com/detail/9NHVZ89SQHJG) and click **Get** or **Install**. There's no admin prompt or download warning, and the Store keeps AirLynk updated.

### winget

In Terminal, Command Prompt or PowerShell:

```
winget install airlynk
```

This installs the Microsoft Store version.

### Installer (EXE)

For PCs without the Microsoft Store:

1. Open the [latest release](https://github.com/aluvalasathish/airlynk-releases/releases/latest) and download `AirLynk-<version>-Setup.exe` under **Assets**. The `latest.json` file next to it is for the app's updates; you don't need it.
2. Run it. Windows asks for permission, because the installer sets up AirLynk for everyone on the PC and adds a firewall rule so devices can connect to it directly.
3. If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**. The installer isn't code-signed yet. Every update AirLynk installs is checked against its own signature first (see [Updates](#updates)).

### After installing

- **Send with AirLynk** is in File Explorer's right-click menu. With the installer version on Windows 11, it's under **Show more options**.
- AirLynk can keep running in the tray after you close the window, so your paired devices can still send to your PC. You can turn this off in Settings.
- To uninstall: **Settings → Apps → Installed apps → AirLynk**.

### Updates

- **Microsoft Store and winget:** the Microsoft Store installs updates for you.
- **Installer (EXE):** AirLynk updates itself. It checks for a new version every 6 hours and shows a popup when one is ready, and every update is signed and checked before it's installed.

Either way, an update never interrupts a transfer.

## What AirLynk does

- Send photos, videos, documents and whole folders, with no size limit
- Share a link or a QR code, send to devices on the same Wi-Fi, or to your paired devices
- Pair your phone and PC once, then send to each other any time
- Files go directly from device to device, end-to-end encrypted, and are never uploaded to a cloud drive
- Works with AirLynk for Android: phone to PC and PC to phone

## Privacy

Read the [privacy policy](https://airlynk.in/privacy-policy). The Windows app has no ads and no analytics.

## Help

- Website: [airlynk.in](https://airlynk.in)
- Email: [sathishaluvala@airlynk.in](mailto:sathishaluvala@airlynk.in)
- Found a problem? [Open an issue](https://github.com/aluvalasathish/airlynk-releases/issues) or send an email.

## About this repository

This repository holds AirLynk's release files: the Windows installer, and the signed update file (`latest.json`) the app reads to find new versions. The source code isn't public.

© 2026 Sathish Aluvala
