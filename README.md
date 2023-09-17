# Store             
 
## Описание:
Онлайн магазин, с возможностью добавление товаров через джанго админку, платежная система подключается по Вашему выбору, реализована логика активация аккаунта с помощью подтверждения электронной почты, письмо отправляется при регистрации, с использованием очереди задач (Celery) в качестве брокера сообщений выступает Redis.

## Технологии:
Python, Django, DRF, Unittest, Django debug toolbar, Django ORM, PostgreSQL, Redis, Celery

<details>
<summary><h2>Как запустить проект:</h2></summary>

### *Клонируйте репозиторий:*
```
git@github.com:VGuzelik/Store.git
```

### *Установите и активируйте виртуальное окружение:*
Win:
```
python -m venv venv
venv/Scripts/activate
```

Mac:
```
python3 -m venv venv
source venv/bin/activate
```

### *Установите зависимости из файла requirements.txt:*
```
pip install -r requirements.txt
```

### *Перейдите в директорию с файлом manage.py, создайте и примените миграции (python3 для Mac):*
```
cd yatube
python manage.py makemigrations
python manage.py migrate
```

### *Создайте суперпользователя (python3 для Mac):*
```
python manage.py createsuperuser
```

### *Запустите сервер (python3 для Mac):*
```
python manage.py runserver
```
</details>

## Разработчик:
[Гузелик Виктор](https://github.com/VGuzelik)
