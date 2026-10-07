# ![LERO VPN для Android](assets/banner-ru.png)

<p align="center"><b>Русский</b> · <a href="README.en.md">English</a></p>

<p align="center">
  <a href="https://connect.leeroy.uz/download"><img src="https://img.shields.io/badge/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C-%D1%81%20%D1%81%D0%B0%D0%B9%D1%82%D0%B0-6f86ff?style=for-the-badge" alt="Скачать с сайта"></a>
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C-%D1%81%20GitHub-24292f?style=for-the-badge&logo=github" alt="Скачать с GitHub"></a>
</p>

Приложение для подписки [LERO VPN](https://connect.leeroy.uz): включается одной кнопкой, сервер выбирает само. Белые списки держат связь, когда мобильный интернет открывает только разрешённые сайты.

Нужен Android 8.0 или новее и действующая подписка. Приложение в бета-версии.

<p align="center">
  <img src="assets/screenshots/dark-vpn.png" width="30%" alt="Главный экран с кнопкой подключения">
  <img src="assets/screenshots/dark-servers.png" width="30%" alt="Список серверов">
  <img src="assets/screenshots/dark-profile.png" width="30%" alt="Аккаунт и устройства">
</p>

## Установить

1. Скачай APK с сайта или со страницы выпуска — файл одинаковый.
2. Открой файл и разреши браузеру устанавливать приложения, когда Android спросит.
3. Войди через [бота @LeroConnect_bot](https://t.me/LeroConnect_bot) или вставь ссылку подписки.

Готово, когда на главном экране видна кнопка подключения. Новые версии приложение предлагает само.

## Проверить файл

У каждого выпуска указаны SHA-256 и ссылка на отчёт VirusTotal. Сверь сумму с указанной:

```bash
shasum -a 256 lero-vpn-ВЕРСИЯ.apk
```

`ВЕРСИЯ` — номер из имени скачанного файла. На Windows вместо `shasum` используй `Get-FileHash` в PowerShell.

## Поддержка

Пиши [в поддержку @LeroConnectSupport_bot](https://t.me/LeroConnectSupport_bot). Работу серверов видно на [странице статуса](https://connect.leeroy.uz/status).

<sub>© 2026 LERO VPN. Использует Xray-core (MPL-2.0) и libXray (MIT).</sub>
