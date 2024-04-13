## Anonymous_project
<p><b>Team.name:</b> <i>cannot access private member declared in class Team</i>.</p>
<p><b>Hackathon.name:</b> <i>cannot access private member declared in class Hackathon</i>.</p>
<p><b>Project.name:</b> <i>cannot access private member declared in class Project</i>.</p>

## Содержание
- [Реализованная функциональность](#реализованная-функциональность)
- [Особенности проекта](#особенности-проекта)
- [Основной стек технологий](#основной-стек-технологий)
- [Среда запуска](№среда-запуска)
- [Использование](#использование)
- [Разработчики](#разработчики)

## Реализованная функциональность
- поиск конфиденциальных данных (паспортных данных, телефонов, данных аккаунтов, данных СНИЛСа, данных банковских карт и QR-кодов) в тексте сообщений;
- поиск конфиденциальных данных (паспортных данных, телефонов, данных аккаунтов, данных СНИЛСа, данных банковских карт и QR-кодов) в тексе вложенных .pdf-файлов;
- поиск конфиденциальных данных (паспортных данных, телефонов, данных аккаунтов, данных СНИЛСа, данных банковских карт и QR-кодов) на изображениях вложенных .pdf-файлов;

## Особенности проекта
- Использование регулярных выражений для выявления наличия конфиденциальных данных в письмах.
- Дополнительное desktop-приложение для удобной разметки датасета. Пользователь выбирает папку с .eml файлами, последовательно отображает их пользователю и при нажатии на кнопку соответствующего дефекта сохраняет текст письма в формате .txt в соответствующей папке.
<br>

![Иллюстрация к проекту](https://github.com/Whynot46/Anonymous_project/blob/main/img/markup_example.PNG)

## Основной стек технологий
- Python 3.11.0
- Re
- OpenCV
- Os
- Email
- ScanQR

## Среда запуска
<p>Для развёртывания проекта необходимо виртуальное окружение с установленным пакетом <a href="https://github.com/ejeklint/ArduinoWebsocketServer">Python 3.10.0</a></p>
<p>Для создания и активации виртуального окружения последовательно введите последующие команды в терминал: </p>

For Windows:
```
python -m venv venv
venv\Scripts\activate.bat
```

For Linux/MacOS:
```
python3 -m venv venv
source venv/bin/activate
```

## Использование
Скачайте репозиторий:
<br>
<br>
For Windows:
```
git clone https://github.com/Whynot46/Anonymous_project
```
For Linux:
```
sudo git clone https://github.com/Whynot46/Anonymous_project
```
<hr>
Установите необходимые библиотеки с помощью команды:
<br>
<br>
For Windows:

```
pip install -r requirements.txt
```
For Linux:
```
pip3 install -r requirements.txt
```
<hr>
Запустите проект с помощью команды:
<br>
<br>
For Windows:

```
py main.py
```
For Linux:
```
python3 main.py
```

## Разработчики
- [Алексей Пахалев](https://github.com/Whynot46) | Project manager/Python Middle developer |
- Фролкова Дарья | Python Junior developer |
- [Мальцев Никита](https://github.com/Malcev-Nikita) | Fullstack developer/Python Middle developer |
- [Нурмухамедов Наиль](https://github.com/Tatarenok) | Python Junior developer |
- [Воронов Александр](https://github.com/Korga-01) | Python Junior developer |
