# ![LERO VPN for Android](assets/banner-en.png)

<p align="center"><a href="README.md">Русский</a> · <b>English</b></p>

<p align="center">
  <a href="https://connect.leeroy.uz/download"><img src="https://img.shields.io/badge/Download-from%20website-6f86ff?style=for-the-badge" alt="Download from website"></a>
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-from%20GitHub-24292f?style=for-the-badge&logo=github" alt="Download from GitHub"></a>
</p>

The app for your [LERO VPN](https://connect.leeroy.uz) subscription: connect with one tap, and it picks the server for you. Whitelists keep you online when mobile internet only opens approved sites.

You need Android 8.0 or newer and an active subscription. The app is in beta.

<p align="center">
  <img src="assets/screenshots/dark-vpn.png" width="30%" alt="Home screen with the connect button">
  <img src="assets/screenshots/dark-servers.png" width="30%" alt="Server list">
  <img src="assets/screenshots/dark-profile.png" width="30%" alt="Account and devices">
</p>

## Install the app

1. Download the APK from the website or the release page. It's the same file.
2. Open the file and allow your browser to install apps when Android asks.
3. Sign in with the [@LeroConnect_bot Telegram bot](https://t.me/LeroConnect_bot) or paste your subscription link.

You're done when the home screen shows the connect button. The app offers new versions on its own.

## Verify the file

Each release lists its SHA-256 and a link to its VirusTotal report. Compare the checksum with the listed one:

```bash
shasum -a 256 lero-vpn-VERSION.apk
```

`VERSION` is the number in the downloaded file name. On Windows, use `Get-FileHash` in PowerShell instead of `shasum`.

## Get help

Message [@LeroConnectSupport_bot](https://t.me/LeroConnectSupport_bot) for support. Check the [server status page](https://connect.leeroy.uz/status) to see whether servers are up.

<sub>© 2026 LERO VPN. Uses Xray-core (MPL-2.0) and libXray (MIT).</sub>
