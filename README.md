# fastapi_invest_tracker
В курсе создается каркас веб-приложения для трекинга своего портфеля в Тинькофф Инвестициях.

Библиотеки, планирующиеся к использованию: alembic, sqlalchemy, fastapi-users, fastapi-cache, celery, redis, jinja.

Технологии: аутентификация пользователей (fastapi-users), кэширование запросов (redis), отложенные задачи (celery + redis), тестирование (pytest).

Фронтенд: react.

**Инструкция**

Для локального тестирования необходимо создать виртуальное окружение командой 'python3 -m venv venv' и активировать его. Команда venv\Scripts\activate.bat - для Windows; source venv/bin/activate - для Linux и MacOS.

Затем необходимо перейти в папку с нужным уроком и установить зависимости командой pip install -r requirements.txt.

Затем необходимо перейти в папку src командой cd src и запустить команду uvicorn main:app --reload для запуска сервера uvicorn.

После этого можно зайти в браузере по адресу http://localhost:8000/docs для просмотра доступных эндпоинтов.
