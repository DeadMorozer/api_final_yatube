Описание.
YaTube - web-приложение, реализующее социальную сеть, позволяющее пользователям вести дневники, подписываться друг на друга и оставлять комментарии (API на Django & Django REST framework).

Запуск проекта.
Клонировать и перейти в репозиторий:
git clone git@github.com:DeadMorozer/api_final_yatube.git
cd api_final_yatube

Cоздать и активировать виртуальное окружение:
python -m venv env
source venv/Scripts/activate
 
Установить зависимости из файла requirements.txt:
pip install -r requirements.txt
 
Выполнить миграции:
python manage.py migrate

Запустить проект:
python manage.py runserver
 
Переход на локальный сервер:
http://127.0.0.1:8000/
 
Примеры запросов:
http://127.0.0.1:8000/redoc/
