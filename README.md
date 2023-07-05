# scrap

# Парсер резюме с сайта hh.kz

Этот скрипт позволяет парсить резюме с сайта hh.kz и сохранять данные в базу данных PostgreSQL.

## Установка

1. Склонируйте репозиторий:
git clone https://github.com/DoZhD1k/scrap


2. Установите необходимые зависимости:
pip install requests
pip install beautifulsoup4
pip install psycopg2
pip install time
pip install unicodedata
pip install urllib.parse
pip install hashlib
pip install psycopg2
pip install os
pip install csv

3. Настройте параметры подключения к базе данных в коде (`database`, `user`, `password`, `host`, `port`).

4. Создайте таблицу `resumes` в базе данных PostgreSQL. Если таблица уже существует, она не будет перезаписана.

5. Запустите скрипт:
python res.py

## Использование

1. Создайте CSV-файл `roles.csv` и добавьте в него ключевые слова для поиска резюме.

2. Запустите скрипт `res.py`.

3. Скрипт будет отправлять запросы на сайт hh.kz, парсить резюме и сохранять данные в базу данных PostgreSQL.

## Вклад

Вы можете внести свой вклад в улучшение этого скрипта, выполнив следующие действия:

1. Форкните репозиторий.

2. Создайте новую ветку:
git checkout -b updated/scrap

3. Внесите необходимые изменения и коммиты.

4. Отправьте пул-реквест с вашими изменениями.
