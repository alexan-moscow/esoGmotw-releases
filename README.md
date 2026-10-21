# esoGmotw

[English](#english) · [Русский](#русский)

## English

A Windows program that builds your guild's «News» (MOTD) for The Elder Scrolls Online from addon data and copies the finished text so you can paste it into the game.

- **News blocks** made of addon data and your own texts; drag to change the order.
- **Charts** from trade data and donations, with a configurable period, colors and line format.
- **Character counter using the game's rules** (limit 2048) and a preview.
- **Colors and special symbols** to insert.
- **Copy** as text or as a picture; move your settings to another computer with a file.
- **Interface language:** Russian and English (chosen at the first launch and in settings).

The data is read from the files of the addons [Arkadius' Trade Tools](https://www.esoui.com/downloads/info1752-ArkadiusTradeTools.html), [ITTs Donation Bot](https://www.esoui.com/downloads/info2765-ITTsDonationBotITTDB.html) and [AwesomeGuildStore](https://www.esoui.com/downloads/info695-AwesomeGuildStore.html). The program only reads them and changes nothing in the game or its files.

### Installation

Download `esoGmotw-win-Setup.exe` from the [Releases](../../releases/latest) page and run it. No administrator rights are needed; if necessary, the installer will install the .NET 8 Desktop Runtime. After that the program updates itself.

The files are not digitally signed, so Windows SmartScreen may show a warning: «More info» → «Run anyway». Some antivirus programs may react to the self-extracting installer: the SHA-256 fingerprint and the VirusTotal result are given in the description of every release.

## Русский

Программа для Windows, которая собирает «Новости» (MOTD) гильдии в The Elder Scrolls Online из данных аддонов и копирует готовый текст для вставки в игру.

- **Блоки новостей** из данных аддонов и собственных текстов, порядок меняется перетаскиванием.
- **Чарты** по торговым данным и взносам с настройкой периода, цветов и вида строк.
- **Счётчик знаков по правилам игры** (предел 2048) и предпросмотр.
- **Цвета и спецсимволы** для вставки.
- **Копирование** текстом или картинкой, перенос настроек на другой компьютер файлом.
- **Язык интерфейса:** русский и английский (выбор при первом запуске и в настройках).

Данные берутся из файлов аддонов [Arkadius' Trade Tools](https://www.esoui.com/downloads/info1752-ArkadiusTradeTools.html), [ITTs Donation Bot](https://www.esoui.com/downloads/info2765-ITTsDonationBotITTDB.html) и [AwesomeGuildStore](https://www.esoui.com/downloads/info695-AwesomeGuildStore.html). Программа их только читает и ничего в игре и в её файлах не меняет.

### Установка

Скачайте `esoGmotw-win-Setup.exe` на странице [Releases](../../releases/latest) и запустите. Права администратора не нужны, при необходимости установщик поставит .NET 8 Desktop Runtime. Дальше программа обновляется сама.

Файлы не подписаны цифровой подписью, поэтому Windows SmartScreen может показать предупреждение: «Подробнее» → «Выполнить в любом случае». Некоторые антивирусы могут реагировать на самораспаковывающийся установщик: отпечаток SHA-256 и результат проверки на VirusTotal есть в описании каждого выпуска.
