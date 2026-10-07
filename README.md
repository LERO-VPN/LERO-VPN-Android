<p align="center">
  <img src="assets/banner-ru.png" alt="LERO VPN для Android" width="100%">
</p>

<p align="center">
  <b>Русский</b> · <a href="README.en.md">English</a>
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/LERO-VPN/android?include_prereleases&label=%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F&color=6f86ff&style=flat-square" alt="Последняя версия"></a>
  <img src="https://img.shields.io/badge/Android-8.0%2B-3fd29b?style=flat-square&logo=android&logoColor=white" alt="Android 8.0+">
  <img src="https://img.shields.io/badge/arm64-v8a-a774ff?style=flat-square" alt="arm64-v8a">
  <a href="https://t.me/LeroConnect_bot"><img src="https://img.shields.io/badge/Telegram-%D0%B1%D0%BE%D1%82-2aabee?style=flat-square&logo=telegram&logoColor=white" alt="Telegram-бот"></a>
</p>

# LERO VPN для Android

**LERO VPN** — VPN на собственной инфраструктуре. Включается одним касанием, сам выбирает сервер и держит соединение, а белые списки помогают оставаться на связи, когда мобильный интернет пускает только на разрешённые сайты.

## Возможности

- **Одно касание** — нажал на щит, и трафик защищён. Сервер выбирается автоматически.
- **Белые списки** — отдельные серверы для режима, когда оператор открывает только разрешённые сайты; расход виден прямо на главном экране.
- **Серверы** — порядок как в панели, задержка по кнопке «Проверить пинг».
- **Аккаунт** — тариф, устройства, остаток белых списков, продление.
- **Автоподключение, смена сервера при сбое и защита при обрыве** — VPN не пропадает незаметно.
- **Приложения без VPN** — выбери, каким программам ходить напрямую.
- **Тёмная и светлая тема**, русский и английский язык — по настройкам телефона.
- **Обновления внутри приложения** — новая версия приходит сама.

## Скриншоты

<p align="center">
  <img src="assets/screenshots/dark-vpn.png" width="31%" alt="Главная">
  &nbsp;
  <img src="assets/screenshots/dark-servers.png" width="31%" alt="Серверы">
  &nbsp;
  <img src="assets/screenshots/dark-profile.png" width="31%" alt="Аккаунт">
</p>

<details>
<summary>Светлая тема</summary>
<p align="center">
  <img src="assets/screenshots/light-vpn.png" width="31%" alt="Главная — светлая тема">
  &nbsp;
  <img src="assets/screenshots/light-servers.png" width="31%" alt="Серверы — светлая тема">
  &nbsp;
  <img src="assets/screenshots/light-profile.png" width="31%" alt="Аккаунт — светлая тема">
</p>
</details>

## Скачать

| Где | Ссылка |
|---|---|
| Наш сайт (основной) | https://connect.leeroy.uz/download |
| GitHub (запасной) | [Последний выпуск](../../releases/latest) |

Файл один и тот же. Требования: Android 8.0 и новее, процессор arm64 — подходит почти любой телефон последних лет.

## Установка

1. Скачай APK.
2. Android спросит, можно ли устанавливать приложения из браузера, — разреши. Это нужно один раз.
3. Открой приложение и войди через [Telegram-бота](https://t.me/LeroConnect_bot) или по ссылке подписки. На странице подписки есть кнопка «Добавить в LERO VPN».

Подписку можно оформить в [боте](https://t.me/LeroConnect_bot) или на [сайте](https://connect.leeroy.uz).

## Проверка файла

К каждому выпуску приложены **SHA-256** и ссылка на отчёт **VirusTotal**. Проверить сумму:

```bash
# Linux
sha256sum lero-vpn-*.apk
# macOS
shasum -a 256 lero-vpn-*.apk
```

```powershell
# Windows
Get-FileHash lero-vpn-*.apk -Algorithm SHA256
```

Сумма должна совпасть с указанной в выпуске. APK подписан ключом LERO VPN: Android не установит поверх обновление с чужой подписью.

## Поддержка

- Поддержка в Telegram: [@LeroConnectSupport_bot](https://t.me/LeroConnectSupport_bot)
- Статус серверов: https://connect.leeroy.uz/status
- Почта: support@leeroy.uz

## Права

© 2026 LERO VPN. Все права защищены.

Приложение использует компоненты с открытыми лицензиями: [Xray-core](https://github.com/XTLS/Xray-core) (MPL-2.0), [libXray](https://github.com/XTLS/libXray) (MIT).
