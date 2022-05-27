# Проект «API для Yatube»
### Описание
API для Yatube
### Технологии
 - Django 2.2.16
 - djangorestframework
 - djangorestframework-simplejwt
 - requests
### Запуск проекта в dev-режиме
# Проект «API для Yatube»
### Описание
API для Yatube
### Технологии
Django 2.2.16
djangorestframework
djangorestframework-simplejwt
requests
### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
 ```
- python -m venv env
- source env/scripts/activate
- python -m pip install --upgrade pip
```
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
``` 
 - Выполнить миграции:
``` 
python manage.py migrate
```
- В папке с файлом manage.py выполните команду:
```
python manage.py runserver
```

 Примеры запросов к API можно найти после запуска сервера
 ```
 http://127.0.0.1:8000/redoc/
 ```
 Как пример http://127.0.0.1:8000/api/v1/posts/ с Post запросом 
  ```
 {
"text": "string",
"image": "string",
"group": 0
}
 ```
### Автор
Сергей Кастов
