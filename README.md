# SmartCam for Rokid AI Glasses

SmartCam is a hands-free rolling video recorder for Rokid AI Glasses. The free mode keeps short interval clips; Pro adds MARK and additional save options. This public repository contains the installable APK and documentation only. The application source code remains private.

## Download and install

Download [SmartCam-Freemium-v2.0.0.apk](SmartCam-Freemium-v2.0.0.apk) (SHA-256: `ca76b5d57a2d70451392cec0686ef2719c2811530831b0235b5adfc4e3c31799`).

Enable developer/ADB access on the glasses, connect them, and run:

```sh
adb devices
adb install -r SmartCam-Freemium-v2.0.0.apk
```

This is version 2.0.0 (`versionCode 34`), package `com.shabp.rokid.intervalrecorder`. It uses the same signing certificate as beta15, so `adb install -r` updates the installed app while retaining its data. Camera and microphone permissions are requested on first launch.

## Use

Recording starts after permissions are granted. MARK preserves the moments around a press; PAUSE/RESUME controls recording; STOP opens the save menu. Free mode offers the 3-minute interval option. Pro adds MARK, Total Recall, Marked only, 1-minute and 5-minute interval options. Finished videos appear in `Movies/Camera`.

The Pro screen displays the glasses' activation code. Visit [SmartCam activation](https://smartcam-activation.shabp.chatgpt.site/) to purchase Pro for that code. During the current device test, checkout uses **Paddle sandbox**. Test transactions are not commercial purchases.

The app checks license status at startup, on foreground resume, and roughly every minute while open. When the server reports a refund, it removes the cached Pro license and returns to Free mode. The vPro label indicates an active license; it is not a reset button.

## Compatibility and privacy

Designed for Rokid AI Glasses with sideloading enabled. Video and audio are recorded and saved on the glasses; SmartCam does not upload recordings. Internet access is used to check activation.

## Distribution

Copyright © 2026 ShaBP. SmartCam is proprietary software. This repository distributes the signed APK for installation and testing; no source code or open-source license is provided.
