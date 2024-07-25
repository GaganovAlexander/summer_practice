# Летняя практика

Этот репозиторий содержит проект для парсинга и анализа данных о расписании вокзалов с сайта РЖД.

## Структура проекта

- `urls.json`: Набор вручную собранных ссылок для парсинга данных о расписании с сайта РЖД.
- `main.ipynb`: Jupiter Notemook в котором была проведена работа по парсингу, анализу данных и построению инфографики.

## Установка

Для настройки окружения и структуры каталогов выполните следующие шаги:

1. Клонируйте репозиторий:

    ```sh
    git clone https://github.com/GaganovAlexander/summer_practice.git
    cd summer_practice
    ```

2. Запустите команду установки:

    #### Для Unix-подобных систем (Linux, macOS):
    ```sh
    python -m venv venv && source venv/bin/activate && pip install -r requirements.txt && mkdir -p data/csv data/json
    ```

    #### Для Windows:
    ```sh
    python -m venv venv && venv\Scripts\activate && pip install -r requirements.txt && mkdir data\csv data\json
    ```

3. Запустите выполнения ноутбука через Jupiter, VSCode или другие среды.