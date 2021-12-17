<h2 align="center">MD Hub</h2>


**Ссылки**:
- [Telegram](https://t.me/MaxWormer)
- [Сайт](https://wormer-code.com)

### Описание проекта:
MD Hub — многофункциональный сервис поиска товаров в интернет-магазинах и сравнения цен. Он охватывает самые разнообразные категории товаров: электроника, компьютеры, бытовая техника, автотовары, оборудование для ремонта и строительства, туристическое снаряжение, детские товары и многое другое.


### Инструменты разработки

**Стек:**
- Python >= 3.9
- Django >= 4.0
- PostgreSQL 14.1

## Разработка

### 1) Клонировать репозиторий

    git clone ссылка_сгенерированная_в_вашем_репозитории

### 2) Создать виртуальное окружение

#### - OS Windows

    python -m venv venv

#### - OS Linux

    python3 -m venv venv

### 3) Активировать виртуальное окружение

#### - OS Windows

    venv\Scripts\activate.bat

#### - OS Linux

    source venv/bin/activate

### 4) Устанавливить зависимости:

    pip install -r requirements.txt

### 5) Выполнить команду для выполнения миграций

    python manage.py migrate
    
### 6) Создать суперпользователя

    python manage.py createsuperuser
    
### 7) Запустить сервер

    python manage.py runserver

## License

[BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)

Copyright (c) 2021-present, Wormer - Cherviakov Maksim



