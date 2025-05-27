# Описание  
Проект API для Yatube представляет собой API для управления постами, комментариями, группами постов и подписками.

# Установка (Powershell)  
Клонировать репозиторий и перейти в его директорию:  
git clone https://github.com/vvadikk/api_final_yatube  
cd api_final_yatube  
Cоздать и активировать виртуальное окружение:  
python -m venv env  
.\venv\Scripts\Activate.ps1  
Установить зависимости из requirements.txt:  
python -m pip install --upgrade pip  
pip install -r requirements.txt  
Выполнить миграции:  
python yatube_api\manage.py migrate  
Запустить сервер:  
python yatube_api\manage.py runserver

Когда Вы запустите проект, по адресу http://127.0.0.1:8000/redoc/ будет доступна документация для API Yatube. В документации приведены примеры, как работает API. Документация представлена в формате Redoc.
