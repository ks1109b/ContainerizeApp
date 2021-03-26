# ContainerizeApp

### Задача:
Упаковать готовое приложение в образ (т.е. создать Dockerfile и docker-compose.yml).

### Приложение: [db-api-for-docker.jar](https://github.com/netology-code/aqa-homeworks/raw/aqa4/docker/db-api-for-docker.jar)

### Процесс:
- запускаем docker-compose командой: ```docker-compose up -d --build```
- дожидаемся запуска приложения в контеййнере
- проверяем результат путем запроса: ```GET http://localhost:9999/api/cards```

### Результат:
![img](https://user-images.githubusercontent.com/73786860/112629367-4c5d4280-8e45-11eb-91fa-ae3e7578d492.png)
