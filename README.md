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
| **macOS 12 and later** | [Apple chip](https://github.com/aluvalasathish/airlynk-releases/releases/latest) · [Intel](https://github.com/aluvalasathish/airlynk-releases/releases/latest) · [Universal](https://github.com/aluvalasathish/airlynk-releases/releases/latest) (.dmg) |
| **Linux** (64-bit) | [.deb package](https://github.com/aluvalasathish/airlynk-releases/releases/latest) · [AppImage](https://github.com/aluvalasathish/airlynk-releases/releases/latest) |
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

## Install on macOS

**Needs** macOS 12 Monterey or later. AirLynk is signed and notarized by Apple.

### Which file

There's one file for each kind of Mac, and one that works on both. To check yours, open the Apple menu → **About This Mac**:

- **Chip** shows Apple M1, M2, M3 or later → `AirLynk-<version>-mac-apple-silicon.dmg`
- **Processor** shows Intel → `AirLynk-<version>-mac-intel.dmg`
- Not sure → `AirLynk-<version>-mac-universal.dmg`, about twice the size, works on either

### Install

1. Download your file from the [latest release](https://github.com/aluvalasathish/airlynk-releases/releases/latest).
2. Open it and drag **AirLynk** onto **Applications**.
3. Open AirLynk from Applications. The first time, macOS asks whether to open an app downloaded from the internet: click **Open**.
4. macOS asks once to let AirLynk find devices on your local network. Click **Allow**, so your phone and other computers on the same Wi-Fi can find your Mac and send to it directly. If your Mac's firewall is on, also allow AirLynk to accept incoming connections.

### After installing

- **Send with AirLynk** is in the Finder's right-click menu, under **Services** (or **Quick Actions**). You can also drop files on AirLynk's Dock icon, or choose **Open With → AirLynk**.
- AirLynk can keep running in the menu bar after you close the window, so your paired devices can still send to your Mac. You can turn this off in Settings, and **⌘Q** quits it.
- To uninstall: quit AirLynk and drag it from Applications to the Trash.

### Updates

AirLynk updates itself. It checks for a new version every 6 hours and shows a popup when one is ready, and every update is signed and checked before it's installed. It asks for your password only if your account can't change the Applications folder. Keep AirLynk in Applications: a copy opened straight from the `.dmg` can't update itself. A universal copy updates to the smaller file for your Mac. An update never interrupts a transfer.

## Install on Linux

Two ways to get the same app. **Needs** a 64-bit PC with glibc 2.34 or later: Ubuntu 22.04 and later, Debian 12 and later, Fedora, and most others released since 2022.

### .deb package

For Ubuntu, Debian, Mint and other systems that use `apt`:

1. Download `airlynk_<version>_amd64.deb` from the [latest release](https://github.com/aluvalasathish/airlynk-releases/releases/latest).
2. Open it in your software installer, or from a terminal:
   ```
   sudo apt install ./airlynk_<version>_amd64.deb
   ```
3. AirLynk is in your app menu, and `airlynk` works from a terminal.

### AppImage

For any other Linux, or to try AirLynk with no install:

1. Download `AirLynk-<version>-x86_64.AppImage` from the [latest release](https://github.com/aluvalasathish/airlynk-releases/releases/latest).
2. Make it runnable and open it:
   ```
   chmod +x AirLynk-*.AppImage
   ./AirLynk-*.AppImage
   ```
3. It adds itself to your app menu the first time it runs.

### After installing

- **Send with AirLynk** is in the right-click menu of GNOME Files, Nemo and Dolphin.
- AirLynk can keep running in the background after you close the window, so your paired devices can still send to it. You can turn this off in Settings.
- To uninstall the `.deb`: `sudo apt remove airlynk`. The AppImage just needs deleting.

### Updates

AirLynk updates itself. It checks for a new version every 6 hours and shows a popup when one is ready, and every update is signed and checked before it's installed. The `.deb` asks for your password to install the update; the AppImage replaces its own file. An update never interrupts a transfer.

## What AirLynk does

- Send photos, videos, documents and whole folders, with no size limit
- Share a link or a QR code, send to devices on the same Wi-Fi, or to your paired devices
- Pair your phone and PC once, then send to each other any time
- Files go directly from device to device, end-to-end encrypted, and are never uploaded to a cloud drive
- Works with AirLynk for Android: phone to computer and computer to phone, on Windows, macOS and Linux

## Privacy

Read the [privacy policy](https://airlynk.in/privacy-policy). The desktop app has no ads and no analytics.

## Help

- Website: [airlynk.in](https://airlynk.in)
- Email: [sathishaluvala@airlynk.in](mailto:sathishaluvala@airlynk.in)
- Found a problem? [Open an issue](https://github.com/aluvalasathish/airlynk-releases/issues) or send an email.

## About this repository

This repository holds AirLynk's release files: the Windows installer, the Mac `.dmg` files, the Linux `.deb` and AppImage, and the signed update file (`latest.json`) the app reads to find new versions. The source code isn't public.

© 2026 Sathish Aluvala
