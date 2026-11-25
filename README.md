# YouTube Downloader — Windows installer

Download the latest version from **[Releases](../../releases/latest)**:
`YouTubeDownloader-Setup-win-x64-vX.Y.Z.exe`

## Install

1. Download the setup file from the latest release.
2. Run it and click **Next → Install**. No administrator rights are needed (it installs for your user account).
3. Start **YouTube Downloader** from the Start menu or the desktop shortcut.

**Requirements:** Windows 10 (1809 or later) or Windows 11, 64-bit. Nothing else needs to be installed — the .NET runtime, yt-dlp and FFmpeg are included.

> Windows SmartScreen may show *"Windows protected your PC"* because the installer is not code-signed. Click **More info → Run anyway**.

## Updates

The app checks this page for new releases. When one is available, the **Update** button in the app's title bar lights up — click it and the new version is downloaded, verified against the published SHA-256 checksum, installed and restarted automatically. Your settings and history are kept.

## Verify a download (optional)

```powershell
Get-FileHash .\YouTubeDownloader-Setup-win-x64-v1.0.0.exe -Algorithm SHA256
```

Compare the result with `SHA256SUMS.txt` in the same release.

## Responsible use

Download only content you own or have permission to download (your own uploads, Creative Commons videos, or content whose rights holder allows it). The app does not bypass DRM, sign-in, age, membership, payment or region restrictions and never uses your browser cookies or accounts.

## Third-party software

yt-dlp (Unlicense), FFmpeg (LGPL 2.1+, BtbN build), Deno (MIT), .NET/WPF (MIT). YouTube is a trademark of Google LLC; this project is not affiliated with Google.
