<h1 align="center">IDLE2Exe, v3.9.5</h1>
<h4 align="center">IDLE - официальная среда разработки от разработчиков Python. Но по умолчанию она запускается через pythonw.exe, что делает невозможным назначить её приложением по умолчанию для .py и редактировать их двойным кликом. Чтобы исправить это, был сделан IDLE2Exe.</h4>

## Предупреждения:
- Для работы программы необходим **Python 3.9.5** строго в C:\Program Files\Python39. Для установки в эту папку можно выбрать **"Install for all users"** во время установки.
Если **Python 3.9.5** установлен в другой папке, то читаем пункт **"В чём суть"**.
- Из-за прекращения поддержки **Python 3.9** не работает на **Windows 7 и ниже**. Корректная работа **IDLE2Exe** гарантируется на **Windows 10 64bit**.
## В чём суть: 

**IDLE2Exe** запускает из C:\Program Files\Python39\ среду IDLE. При этом, если выбрать **IDLE2Exe** для открывания **.py файлов** по умолчанию, то для всех **.py файлов** будут установлены нормальные иконки, и файлы можно будет запустить стандартным двойным кликом.

- **Если Python 3.9.5 установлен в другой папке, то в файлах Python в папке \Lib\idlelib необходимо найти idle.bat. В нём нужно заменить CurrentDir на прямые пути к pythonw.exe и idle.pyw (1 - в папке Lib, 2 - в Lib\idlelib). Пример того, как должен выглядеть idle.bat, есть загрузках репозитория.**

Для конвертации **.bat в .exe** можно использовать бесплатную программу от **[Tokyoneon](https://github.com/tokyoneon/B2E)**, а иконку взять из C:\Program Files\Python39\Lib\idlelib\Icons. В папке C:\Program Files\Python39\Lib\idlelib\ есть **idle.bat** от **самих разработчиков Python**, но чтобы при конвертации полученный .exe заработал, необходимо указать прямой путь к **pythonw.exe и idle.pyw**, или **использовать мой .bat**.

## Использование:
**Windows:**
- Скачайте **.exe-файл** по **[ссылке](https://github.com/MatroCholo/exeidle/releases)**
- Запустите и/или в меню "Открыть с помощью" выберите скачанный exe-файл. Приятного использования.

## Обратная связь:
- Telegram: https://t.me/MatroCholo
