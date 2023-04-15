# Описание
(**Этот проект позволяет людям:**)
*Писать посты.
*Доступна возможность загружать медиафафайлы. Выбирать для постов группы.
*Комментировать посты.
*Подписываться на авторов.
*Отслеживать свои подписки.

# Установка
> ###(**Как запустить проект:**)
> 1. Клонировать репозиторий и перейти в него в командной строке:
> https://github.com/Mans-Mans/api_final_yatube
> cd api_final_yatube
> 2. Cоздать и активировать виртуальное окружение:
> python -m venv env
> source env/bin/activate
> 3. Установить зависимости из файла requirements.txt:
> python3 -m pip install --upgrade pip
> pip install -r requirements.txt
> 4. Выполнить миграции:
> python3 manage.py migrate
> 5. Запустить проект:
> python3 manage.py runserver

# Примеры
##### http://127.0.0.1:8000/api/posts/ - запрос всех постов
##### http://127.0.0.1:8000/api/posts/4/ - запрос 4 поста
##### http://127.0.0.1:8000/api/groups/ - запрос всех групп
