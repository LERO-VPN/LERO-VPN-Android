# LERO VPN для Android

Официальные сборки приложения **LERO VPN** для Android. Здесь только готовые файлы (APK) и их описание — исходного кода в этом репозитории нет.

- Сайт: https://connect.leeroy.uz
- Telegram-бот: https://t.me/LeroConnect_bot

## Как скачать

Откройте раздел **[Releases](../../releases)** и скачайте `.apk` из последнего выпуска. Тот же файл лежит на нашем сайте — GitHub нужен как запасной источник.

Требования: Android 8.0 и новее, процессор arm64 (почти все телефоны последних лет).

## Как установить

1. Скачайте APK.
2. Android спросит, можно ли устанавливать приложения из браузера, — разрешите (нужно один раз).
3. Откройте приложение и войдите через Telegram-бота или по ссылке подписки.

Новые версии приложение находит само и предлагает обновиться.

## Как проверить файл

К каждому выпуску приложены SHA-256 и ссылка на отчёт VirusTotal.

```bash
# Linux
sha256sum lero-vpn-*.apk
# macOS
shasum -a 256 lero-vpn-*.apk
# Windows (PowerShell)
Get-FileHash lero-vpn-*.apk -Algorithm SHA256
```

Сумма должна совпасть с указанной в выпуске. APK подписан ключом LERO VPN: Android не установит поверх обновление с чужой подписью.

---

# LERO VPN for Android

Official **LERO VPN** Android builds. This repository contains release binaries (APK) and their description only — no source code.

Download the `.apk` from **[Releases](../../releases)** (the same file as on https://connect.leeroy.uz). Requires Android 8.0+ on arm64. Each release lists the SHA-256 and a VirusTotal report link; the APK is signed with the LERO VPN key.

## Права и лицензии / Rights and licenses

© 2026 LERO VPN. Все права защищены / All rights reserved. Распространение файлов из этого репозитория от чужого имени запрещено.

Приложение использует сторонние компоненты с открытыми лицензиями — их исходный код доступен у авторов / The app uses third-party open-source components:

- [Xray-core](https://github.com/XTLS/Xray-core) — MPL-2.0
- [libXray](https://github.com/XTLS/libXray) — MIT
