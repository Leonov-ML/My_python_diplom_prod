## Установка
Склонируйте репозиторий с помощью git:
    git clone https://github.com/Leonov-ML/My_python_diplom_prod.git

1. Для первого запуска проекта выполните команду из директории проекта:

 `docker-compose up -d --build`

 2. Далее выполните миграции внутри контейнера:

  `docker-compose run django python manage.py migrate`

 3. Для последующих запусков используйте команду: 

 `docker-compose up -d`

**Приложение доступно по адресу:**

http://127.0.0.1:8000/
