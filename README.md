### **Описание:**

Этот проект является REST API для проекта Yatube. Ссылка на основной проект:
```
https://github.com/Dmitriy-2022/Yatube
```
---
### **Запуск проекта:**

Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/...

cd yatube_api/
```

Cоздать и активировать виртуальное окружение:
```
python3 -m venv venv

source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
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
