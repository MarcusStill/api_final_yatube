# Yatube_project

## _API к проекту Yatube_project_

Yatube - Социальная сеть для публикации личных дневников (https://github.com/MarcusStill/yatube_project)

### Установка
- Клонируте репозиторий с проектом
```
https://github.com/MarcusStill/api_yatube.git
```
- Установите и активируйте виртуальное окружение
```
python -m venv env
```
```
source env/bin/activate
```
- Установите зависимости из файла requirements.txt
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
Выполните миграции:
```
python manage.py migrate
```
Запустите dev сервер:
- В папке с файлом manage.py выполните команду:
```
python manage.py runserver
``` 
### Описание
Документация к API проекта доступна по следующему адресу:
http://127.0.0.1:8000/redoc/
