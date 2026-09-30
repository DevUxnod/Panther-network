<p align="center">
  <img src="logo.png" width="128" alt="Panther VPN">
</p>

<h1 align="center">Panther VPN</h1>

<p align="center">
  Быстрый VPN-клиент для Android и Windows. Одна кнопка, авто-выбор лучшего сервера, обход блокировок.
</p>

<p align="center">
  <a href="https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-arm64-v8a.apk"><b>⬇ Android (.apk)</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-Setup-x64.exe"><b>⬇ Windows (.exe)</b></a>
</p>

---

## Возможности

- **Одна кнопка.** Вставил ссылку подписки — нажал — работает.
- **Авто-выбор сервера.** Приложение само держит самый быстрый сервер и переключается, если он просел.
- **Обход блокировок.** VLESS + Reality на ядре Xray, отдельная группа серверов «ОБХОД» для сетей с ограничениями.
- **Российские сайты напрямую.** Режим, в котором банки и Госуслуги открываются без VPN и не ругаются на иностранный IP.
- **Без утечек.** Весь трафик и DNS идут через туннель, IPv6 не уходит мимо.
- **Без слежки в приложении.** Нет аналитики, рекламы и трекеров. Журнал посещений на устройстве выключен.
- **Проверка IP.** После подключения видно, из какой страны тебя видит интернет.
- **Одна подписка — все устройства.** Один ключ работает и на телефоне, и на компьютере.

## Скачать

| Платформа | Файл |
|---|---|
| Android (почти все телефоны) | [PantherVPN-arm64-v8a.apk](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-arm64-v8a.apk) |
| Android (старые 32-битные устройства) | [PantherVPN-armeabi-v7a.apk](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-armeabi-v7a.apk) |
| Windows 10 / 11 (64-бит) | [PantherConnect-Setup-x64.exe](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-Setup-x64.exe) |
| macOS, iOS | в разработке |

Все версии и список изменений — на странице [Releases](https://github.com/DevUxnod/Panther-network/releases).

## Как установить

### Android

1. Скачай `.apk` по ссылке выше и открой файл.
2. Android попросит разрешить установку из этого источника — разреши.
3. Если Play Protect предупредит о неизвестном приложении — нажми «Всё равно установить»: приложение распространяется не через Google Play, поэтому Google его не знает.
4. Открой Panther VPN, вставь ссылку подписки и нажми кнопку подключения.

Обновления ставятся поверх: скачай новый `.apk` и установи — подписка и настройки сохранятся.

### Windows

1. Скачай `PantherConnect-Setup-x64.exe` и запусти.
2. Если Windows покажет синее окно «Система Windows защитила ваш компьютер» — нажми **Подробнее → Выполнить в любом случае**. Программа пока не подписана сертификатом, поэтому Windows не знает издателя.
3. В окне «Разрешить этому приложению вносить изменения?» нажми «Да» — права нужны для сетевого адаптера, окно будет появляться при каждом запуске.
4. Вставь ключ доступа из бота или нажми «Войти через Telegram».

На Windows приложение называется **Panther Connect**. Крестик сворачивает его в трей (значок рядом с часами), соединение продолжает работать; полный выход — правый клик по значку → «Выход». Новые версии приложение ставит само.

Подписку можно получить в Telegram-боте [@VpnPantherBot](https://t.me/VpnPantherBot).

## Проверка подлинности

Скачивай приложение только отсюда или из официального бота. Настоящий APK подписан сертификатом с отпечатком SHA-256:

```
83:E7:48:75:AF:2D:15:0B:19:AB:80:F2:36:49:C4:F8:4E:22:D8:A5:B4:96:AE:92:7B:29:7B:C1:34:A3:B4:74
```

К каждому релизу приложен файл `SHA256SUMS.txt` с контрольными суммами всех файлов (APK и установщика Windows).

## Поддержка

- Помощь и вопросы: [@HQpantherBot](https://t.me/HQpantherBot)
- Подписка и оплата: [@VpnPantherBot](https://t.me/VpnPantherBot)
- Сайт: [app.panther.pics](https://app.panther.pics)

Если что-то не работает: в приложении открой **Настройки → Логи → Отправить** и перешли файл в поддержку. В файле нет адресов серверов, ключей и ссылки подписки.

## Открытые компоненты

Приложение использует [Xray-core](https://github.com/XTLS/Xray-core) (MPL-2.0), [flutter_v2ray_client](https://github.com/amir-zr/flutter_v2ray_client) (MIT), флаги [circle-flags](https://github.com/HatScripts/circle-flags) (MIT), шрифты Unbounded и Golos Text (OFL). Версия для Windows дополнительно использует [sing-box](https://github.com/SagerNet/sing-box) (GPL-3.0) для TUN-адаптера; официальные сборки Xray-core и sing-box поставляются без изменений.

<details>
<summary><b>English</b></summary>

**Panther VPN** is a fast VPN client for Android and Windows built on Xray-core (VLESS + Reality).

- One-tap connect with automatic best-server selection
- Works on restricted networks
- No traffic or DNS leaks; no analytics, ads or trackers in the app
- Shows your exit country after connecting

**Download:** [PantherVPN-arm64-v8a.apk](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-arm64-v8a.apk) (most phones) · [armeabi-v7a](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherVPN-armeabi-v7a.apk) (old 32-bit devices) · [Windows installer](https://github.com/DevUxnod/Panther-network/releases/latest/download/PantherConnect-Setup-x64.exe) (Windows 10/11, 64-bit; the app is called Panther Connect there)

Get a subscription in the Telegram bot [@VpnPantherBot](https://t.me/VpnPantherBot), paste the link into the app and connect. Support: [@HQpantherBot](https://t.me/HQpantherBot).

</details>
