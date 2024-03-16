# Дипломная работа "Backend-приложение для автоматизации закупок"

## Запуск API

    Внести в файл settings.py почту и пароль в поля EMAIL_HOST_USER и EMAIL_HOST_PASSWORD соответственно.
    Также, по необходимости, если будете использовать другой почтовый сервис, отредактируйте остальные параметры.
    
    После этого, в терминале, вводим следующие команды:    

    pip install -r requirements.txt
    python manage.py makemigrations backend
    python manage.py migrate
    python manage.py runserver

## Запросы для проверки работы API

    Для проверки можно использовать запросы по линку ниже

[Примеры запросов в PostMan](https://www.postman.com/aviation-participant-20195870/workspace/netology-pd-diplom)