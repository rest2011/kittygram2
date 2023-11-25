## Проект kittygram2

Проект для практической отработки возможностей API. Доступен функционал по добавлению материалов, редактированию, удалению.

## Технологии

Python 3.9, Django 3.2, Django Rest Framework

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram2.git
```

```
cd kittygram2
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
## Автор 
Ринат Хаматьяров (https://github.com/rest2011)
