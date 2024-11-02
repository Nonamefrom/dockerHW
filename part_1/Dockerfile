# Используем официальный образ Nginx
FROM nginx:latest

# Копируем наш index.html в директорию Nginx, заменяя стандартную страницу
COPY index.html /usr/share/nginx/html/index.html

# Открываем порт 80 для доступа
EXPOSE 80