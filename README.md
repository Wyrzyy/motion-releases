# Motion VPN — установщики

**[Скачать Motion для Windows](https://github.com/Wyrzyy/motion-releases/releases/latest/download/Motion-Setup.exe)** — VPN и твики, всегда последняя версия.

**[Скачать Motion Lite](https://github.com/Wyrzyy/motion-releases/releases/latest/download/Motion-Lite-Setup.exe)** — только VPN, без твиков и программ. Ставится отдельно от обычной версии: своя папка и свои настройки.

- Windows 10 и 11, 64-бит.
- Скачайте установщик и запустите. Уже установленный Motion обновится на месте.
- Дальше Motion обновляется сам, когда выходит новая версия.
- Установщик пока без подписи Microsoft, поэтому Windows может показать окно SmartScreen: «Подробнее» → «Выполнить в любом случае».

Здесь нет исходного кода, только официальные установщики. Каждое обновление подписано ключом Motion, и приложение проверяет подпись перед установкой.

Все версии и что в них нового — в [Releases](https://github.com/Wyrzyy/motion-releases/releases).

## Открытые компоненты

Код Motion закрыт. Вместе с ним установщик ставит ядро VPN — открытые программы и данные, без изменений:

- [Xray-core](https://github.com/XTLS/Xray-core) — Mozilla Public License 2.0
- [sing-box](https://github.com/SagerNet/sing-box) — GNU GPL v3
- базы адресов [Xray-rules-dat](https://github.com/XTLS/Xray-rules-dat) — GNU GPL v3; данные [IPinfo Lite](https://ipinfo.io/lite) (CC BY-SA 4.0) и [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community) (MIT)

Точные версии, ссылки на исходный код и полные тексты лицензий — в файле `THIRD-PARTY-NOTICES.txt` в каждом релизе и в папке `core` установленного Motion.
