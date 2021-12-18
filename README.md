# Alex2421_microservices
Alex2421 microservices repository


Задание_17: Создание и запуск системы мониторинга Prometheus

1.Создан образ prometheus
2.Создан образ blackbox-exporter/добавлены экспортеры в prometheus:
3.Prometheus-node-exporter
4.Percona-mongodb_exporter
5.Prometheus-blackbox-exporter

Добавлены сервисы в docker-compose.yml:
-prometheus -node-exporter -mongodb-exporter -blackbox-exporter

Созданы Makefile для сборки образов
Для запуска сервиса:
Чтобы собрать образы нужно выполнить команду:

make
Для запуска использовать команду:
cd docker && docker-compose up -d
