Для корректной отправки логов в Loki необходимо истправить в файле 02-flb-cm.yaml адрес сервера Loki на актуальный.

Для установки в кластер необходимо выполнить команды 

$ git clone https://github.com/kravzo/sf-django-pg-fluentbit

$ kubectl apply -f sf-django-pg-fluentbit/*
