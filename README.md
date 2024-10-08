# Телеграм-бот для управления базой данных клиентов

Этот проект представляет собой телеграм-бота, который позволяет администратору управлять базой данных клиентов. Бот поддерживает операции добавления, изменения, удаления и просмотра информации о клиентах.

## Установка

1. Клонируйте репозиторий на свой локальный компьютер:

```bash
git clone https://github.com/quxinu/aiogram_order_manager.git
```

2. Установите необходимые зависимости:

```bash
pip install aiogram psycopg2 colorama configobj pyshorteners

```

3. Создайте файл конфигурации `.env` и укажите в нем токен вашего бота:

```
BOT_TOKEN=ваш_токен_тг_бота_здесь
DB_NAME=имя_вашей_базы_данных
USER=имя_пользователя_бд
PASSWORD=пароль_для_бд
HOST=адрес_хоста_бд
PORT=порт_бд
```

4. Запустите бота:

```bash
python tg.py
```

## Использование

После запуска бота, он будет готов к использованию в телеграм боте.
