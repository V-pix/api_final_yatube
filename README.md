# Как запустить проект Api_final:
## Клонировать репозиторий и перейти в него в командной строке:
```bash
git clone git@github.com:V-pix/api_final_yatube.git
cd api_final_yatube
```
## Cоздать и активировать виртуальное окружение:
```bash
python -m venv venv
source venv/Scripts/activate
```
## Установить зависимости из файла requirements.txt:
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```
## Выполнить миграции:
```bash
python manage.py migrate
```
## Запустить проект:
```bash
python manage.py runserver
```