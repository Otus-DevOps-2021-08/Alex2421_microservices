# Alex2421_microservices
Alex2421 microservices repository


# https://github.com/Nordstrom/docker-machine/blob/master/docs/install-machine.md
    Задание №12 Docker-2
Технология контейнеризации. Введение в Docker

Сделано:
  Создание docker host
  Создание своего образа
  Работа с Docker Hub
Запуск проекта:
  docker build -t reddit:latest .
  docker run --name reddit -d --network=host reddit:latest
  docker tag reddit:latest alexander2411/otus-reddit:1.0
  docker push alexander2411/otus-reddit:1.0
  docker run --name reddit -d -p 9292:9292 alexander2411/otus-reddit:1.0
Проверка работоспособности:
  Перейти по ссылке http://<ip_adress>:9292
