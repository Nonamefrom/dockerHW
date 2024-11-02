# Django REST API Docker Setup

## 1. Сборка Docker-образа
docker build -t my-django-app .

### Команды для запуска контейнера:
docker run -d -p 8000:8000 --env-file .env my-django-app

### Команды для остановки контейнера:
docker stop <container_id>

### Файл requests.http содержит список документации REST приложения SMARTHOME
url доступа = http://localhost:8000