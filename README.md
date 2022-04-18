# Yudalx_platform
Yudalx Platform repository

HomeWork №1

- Написан Dockerfile который собирает контейнер с nginx
- Ссылка на образ devopstank/nginx-base-app:1.1
- Написан конфиг для nginx default.conf для отдачи файлов помещенных по пути /app
- Написан манифест web-pod.yaml для запуска контейнера с nginx в k8s
- Запушен образ с hipster-frontend devopstank/microservices-demo-frontend
- Добавлены env в сгенеренный манифест hipster-frontend