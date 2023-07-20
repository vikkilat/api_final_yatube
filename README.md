# Проект API для Yatube
 API Yatube для проекта социальной сети Yatube.
 
 ## Описание проекта:
 * Возможность создавать посты и комментарии к ним;
 * Подписываться на авторов;
 * Создавать группы.

## Стек технологий:
* Python 3.7
* Django
* Django Rest Framework
* Simple-JWT
 
## Как запустить проект:

* Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:vikkilat/api_yatube.git
```
```
cd api_yatube
```

* Cоздать и активировать виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```

* Установить зависимости из файла ```requirements.txt```:
```
pip install -r requirements.txt
```

* Выполнить миграции:
```
python manage.py migrate
```

* Запустить проект:
```
python manage.py runserver
```

## Автор:
[Латышева Виктория](https://github.com/vikkilat)

Python-разработчик (Backend)
