# Girag_microservices
Girag microservices repository

# ДЗ №12: "Технология контейнеризации. Введение в Docker"
Установлен `Docker`, `docker-compose` и `docker-machine`.
Создан новый проект на `GCE` и при помощи `docker-machine` создан Docker-хост.
Написан `Dockerfile`, который будет использоваться для создания образа с нашим приложением `Reddit App`. Предварительно также был подготовлен конфиг БД `mongod.conf`, файл `db_config` с переменной окружения и `start.sh` – скрипт запуска приложения.
Собран образ на основе подготовленного Докерфайла. Образ успешно загружен на `Docker Hub` в публичный репозиторий `girag/otus-reddit`.
