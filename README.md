# Список команд для сборки и запуска контейнера:
1. docker build --tag=my_nginx .
2. docker run -it -d -p 8000:80 --name=nginx my_nginx
3. curl localhost:8000/