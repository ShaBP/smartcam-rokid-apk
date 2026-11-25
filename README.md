# SmartCam for Rokid AI Glasses

SmartCam is a hands-free video recorder for Rokid AI Glasses. It joins your chosen clips into one video. This repository distributes the signed Android APK and installation guide.

## Download and install

Download [SmartCam-Freemium-v2.2.7.apk](SmartCam-Freemium-v2.2.7.apk) (SHA-256 `9c402a4eda59a71b695bf77f49e3e0d32b417f7c2313598c8f7e1941e918ad57`).

Enable developer/ADB access on the glasses, connect them, and run:

```sh
adb devices
adb install -r SmartCam-Freemium-v2.2.7.apk
```

This is version 2.2.7 (`versionCode 43`), package `com.shabp.rokid.intervalrecorder`. It uses the original SmartCam signing certificate, so an in-place update retains app data. Grant camera and microphone permissions when prompted.

## Free and Pro

- **Free** includes Constant Recording and five-second clips every minute. Use NOW to capture an extra clip in timed mode.
- **Pro** adds MARK, Total Recall, Marked only, more interval choices, Chill or Upbeat music, and 3× export at 30 fps. Total Recall saves roughly the last three minutes in full plus earlier highlights.
- Saved videos appear in `Movies/Camera`. SmartCam trims the opening second of playback on save to skip the camera fade-in. Very short clips retain enough footage to play.

To activate Pro, enter the code on the glasses' Pro screen at [SmartCam activation](https://smartcam-pro.pages.dev/). SmartCam Pro is a one-time purchase. The limited-time launch price is $4.99 USD.

## Compatibility and privacy

Designed for Rokid AI Glasses with sideloading enabled. Video and audio stay on the glasses. Internet access is used to check activation.

Copyright © 2026 ShaBP. SmartCam is proprietary software.
