<p align="center">
  <img src="logo.png" width="128" alt="Panther Connect">
</p>

<h1 align="center">Panther Connect</h1>

<p align="center">
  Быстрый и свободный интернет на Android, Windows и macOS. Одна кнопка, авто-выбор лучшего сервера, работает там, где другие не могут.
</p>

<p align="center">
  <a href="https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-arm64-v8a.apk"><img src="https://img.shields.io/badge/Android-.apk-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"></a>
  &nbsp;
  <a href="https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-Setup-x64.exe"><img src="https://img.shields.io/badge/Windows-.exe-0078D4?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows"></a>
  &nbsp;
  <a href="https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-macOS.dmg"><img src="https://img.shields.io/badge/macOS-.dmg-000000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS"></a>
</p>

---

## Возможности

- **Одна кнопка.** Вошёл через Telegram или по ключу доступа — нажал — работает.
- **Авто-выбор сервера.** Приложение само держит самый быстрый сервер и переключается, если он просел.
- **Обход блокировок.** VLESS + Reality на ядре Xray, отдельная группа серверов «ОБХОД» для сетей с ограничениями.
- **Российские сайты напрямую.** Режим, в котором банки и Госуслуги открываются без VPN и не ругаются на иностранный IP.
- **Сплит-туннелирование.** Выбери приложения, которые идут мимо VPN.
- **Без утечек.** Весь трафик и DNS идут через туннель, IPv6 не уходит мимо.
- **Без слежки в приложении.** Нет аналитики, рекламы и трекеров. Журнал посещений на устройстве выключен.
- **Проверка IP.** После подключения видно, из какой страны тебя видит интернет.
- **Одна подписка — все устройства.** Один ключ работает на телефоне, на Windows и на Mac.

## Скачать

| | Платформа | Файл |
|:-:|---|---|
| ![Android](https://img.shields.io/badge/-Android-3DDC84?logo=android&logoColor=white) | Android (почти все телефоны) | [PantherVPN-arm64-v8a.apk](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-arm64-v8a.apk) |
| ![Android](https://img.shields.io/badge/-Android-3DDC84?logo=android&logoColor=white) | Android (старые 32-битные устройства) | [PantherVPN-armeabi-v7a.apk](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-armeabi-v7a.apk) |
| ![Windows](https://img.shields.io/badge/-Windows-0078D4?logo=windows11&logoColor=white) | Windows 10 / 11 (64-бит) | [PantherConnect-Setup-x64.exe](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-Setup-x64.exe) |
| ![macOS](https://img.shields.io/badge/-macOS-000000?logo=apple&logoColor=white) | macOS 12+ (Apple Silicon и Intel) | [PantherConnect-macOS.dmg](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-macOS.dmg) |
| ![iOS](https://img.shields.io/badge/-iOS-8E8E93?logo=apple&logoColor=white) | iPhone / iPad | в разработке |

Все версии и список изменений — на странице [Releases](https://github.com/DevUxnod/Panther-network/releases).

## Как установить

### Android

1. Скачай `.apk` по ссылке выше и открой файл.
2. Android попросит разрешить установку из этого источника — разреши.
3. Если Play Protect предупредит о неизвестном приложении — нажми «Всё равно установить»: приложение распространяется не через Google Play, поэтому Google его не знает.
4. Открой Panther Connect и нажми «Войти через Telegram» (бот подтвердит вход сам) — или вставь ключ доступа из бота.

Новые версии приложение ставит само. Если у тебя версия 1.0.x — скачай новый `.apk` и установи поверх, подписка и настройки сохранятся.

### Windows

1. Скачай `PantherConnect-Setup-x64.exe` и запусти.
2. Если Windows покажет синее окно «Система Windows защитила ваш компьютер» — нажми **Подробнее → Выполнить в любом случае**. Программа пока не подписана сертификатом, поэтому Windows не знает издателя.
3. В окне «Разрешить этому приложению вносить изменения?» нажми «Да» — права нужны для сетевого адаптера, окно будет появляться при каждом запуске.
4. Вставь ключ доступа из бота или нажми «Войти через Telegram».

Крестик сворачивает его в трей (значок рядом с часами), соединение продолжает работать; полный выход — правый клик по значку → «Выход». Новые версии приложение ставит само.

### macOS

1. Скачай `PantherConnect-macOS.dmg`, открой образ и перетащи **Panther Connect** в папку «Программы».
2. При первом запуске macOS может написать, что не удалось проверить разработчика. Нажми по приложению **правой кнопкой → «Открыть»**; на macOS 15 и новее — закрой предупреждение, затем **Системные настройки → Конфиденциальность и безопасность → «Всё равно открыть»**. Это нужно один раз.
3. При первом подключении macOS спросит пароль от Mac — устанавливается служба подключения. Дальше подключения идут без пароля.
4. Вставь ключ доступа из бота или нажми «Войти через Telegram».

Значок приложения живёт в строке меню вверху экрана: красный крестик прячет окно, соединение продолжает работать; полный выход — через меню значка или ⌘Q. Новые версии приложение ставит само.

Подписку можно получить в Telegram-боте [@VpnPantherBot](https://t.me/VpnPantherBot).

## Проверка подлинности

Скачивай приложение только отсюда или из официального бота. Настоящий APK подписан сертификатом с отпечатком SHA-256:

```
83:E7:48:75:AF:2D:15:0B:19:AB:80:F2:36:49:C4:F8:4E:22:D8:A5:B4:96:AE:92:7B:29:7B:C1:34:A3:B4:74
```

К каждому релизу приложен файл `SHA256SUMS.txt` с контрольными суммами всех файлов (APK, установщика Windows и образа macOS).

## Поддержка

- Помощь и вопросы: [@HQpantherBot](https://t.me/HQpantherBot)
- Подписка и оплата: [@VpnPantherBot](https://t.me/VpnPantherBot)
- Сайт: [panthervpn.org](https://panthervpn.org)

Если что-то не работает: в приложении открой **Настройки → Логи → Отправить** и перешли файл в поддержку. В файле нет адресов серверов, ключей и ссылки подписки.

## Открытые компоненты

Приложение использует [Xray-core](https://github.com/XTLS/Xray-core) (MPL-2.0), [flutter_v2ray_client](https://github.com/amir-zr/flutter_v2ray_client) (MIT), флаги [circle-flags](https://github.com/HatScripts/circle-flags) (MIT), шрифты Unbounded и Golos Text (OFL). Версии для Windows и macOS дополнительно используют [sing-box](https://github.com/SagerNet/sing-box) (GPL-3.0) для TUN-адаптера; официальные сборки Xray-core и sing-box поставляются без изменений.

<details>
<summary><b>English</b></summary>

**Panther Connect** is a fast Android, Windows and macOS client built on Xray-core (VLESS + Reality).

- One-tap connect with automatic best-server selection
- Sign in via Telegram or with an access key
- Split tunneling: pick apps that bypass the tunnel
- Works on restricted networks
- No traffic or DNS leaks; no analytics, ads or trackers in the app
- Shows your exit country after connecting

**Download:** [PantherVPN-arm64-v8a.apk](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-arm64-v8a.apk) (most phones) · [armeabi-v7a](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-armeabi-v7a.apk) (old 32-bit devices) · [Windows installer](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-Setup-x64.exe) (Windows 10/11, 64-bit) · [macOS](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-macOS.dmg) (macOS 12+, Apple Silicon & Intel)

Get a subscription in the Telegram bot [@VpnPantherBot](https://t.me/VpnPantherBot), sign in via Telegram (or paste the access key) and connect. Support: [@HQpantherBot](https://t.me/HQpantherBot).

</details>
