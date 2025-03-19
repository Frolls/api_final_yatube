# Yatube API

## Описание
Yatube API предоставляет доступ к функционалу социальной сети Yatube, позволяя взаимодействовать с постами, комментариями и подписками через RESTful API. С помощью данного API вы можете создавать, редактировать и удалять посты, оставлять комментарии, а также подписываться на других пользователей.

## Установка
1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/yourusername/api_final_yatube.git
    ```
2. Перейдите в директорию проекта:
    ```bash
    cd api_final_yatube
    ```
3. Установите виртуальное окружение:
    ```bash
    python -m venv venv
    ```
4. Активируйте виртуальное окружение:
    ```bash
    # Для Windows
    venv\Scripts\activate

    # Для MacOS/Linux
    source venv/bin/activate
    ```
5. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```

## Использование
Запустите сервер разработки:
```bash
python manage.py runserver
```

Документация API будет доступна по адресу `http://127.0.0.1:8000/redoc/`.
