# Спортивный портал и бот технической поддержки.

## Описание

- **Telegram Bot**: Бот предназначен для осуществления помощи по спортивному веб-порталу.
- **Веб-сайт**: Сайт является самим спортивным веб-порталом. 

## Установка и настройка

### Требования

- Python (версия 3.12.6)
- Flask (или другой фреймворк для сайта, если нужно)
- Библиотека для работы с Telegram API (aiogram)

### Установка бота

1. Клонируйте репозиторий:

   
bash
git clone https://github.com/YoungTorvalds/SportClub.git
cd SportClub/

2. Установите зависимости:

   
bash
pip install -r requirements.txt

3. Отредактируйте файл `config.py` и добавьте необходимые настройки:

   
TELEGRAM_BOT_TOKEN=ваш_токен_бота
ADMINS_LIST=[ID телеграм аккаунтов администраторов]

4. Запустите бота:

   
bash
python bot_engine.py

### Установка сайта

1. Клонируйте репозиторий:

   
bash
git clone https://github.com/YoungTorvalds/SportClub.git
cd SportClub/

2. Установите зависимости:

   
bash
pip install -r requirements.txt


3. Запустите сайт:

   
bash
python main.py


## Использование

- Для взаимодействия с Telegram-ботом, найдите его по @SportClubPlimpbot в Telegram и используйте команды.
- Для доступа к веб-сайту, перейдите по локальному адресу.

## Команды бота

- `/start` - Запускает бота.
- `/admin` - Открывает админ-панель при наличии прав.
