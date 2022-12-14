
# api_yamdb упакованный в docker контейнер

### Описание
Приложение api_yamdb в связке контейнеров docker:
- контейнер с базой данных: postgre
- контейнер с django приложением и unicorn
- контейнер с nginx

### Технологи
Django==2.2.24
djangorestframework==3.12.4
gunicorn==20.0.4
posetgre
nginx
docker

### Запуск проекта
- docker-compouse up -d
- http://localhost/admin

