# Alex2421_microservices
Alex2421 microservices repository


Приложение запустил в двух сетях,
С помощью docker network connect объеденил UI-COMMENT/UI-POST, DB-POST/DB-COMMENT.

Запустил сборку приложения с помощью Docker-compose. Параметризованные параметры записаны в файл docker-compose.yml.
Добавлено переменное окружение, сетевые алиасы.
 Имя проекта задается с помощью параметра container_name.

Создал docker-compose.override.yml
Для того чтобы поменять код приложения можно с помощью монтирования volume.
Puma запускается с ключом --debug -w 2
