# IWNO6: Создание многоконтейнерного приложения
# Цель работы
#### Ознакомиться с работой многоконтейнерного приложения на базе docker-compose.
# Задание
#### Создать php приложение на базе трех контейнеров: nginx, php-fpm, mariadb, используя docker-compose.
# Конфигурационные файлы
![1в](https://github.com/IvanRazdorognii/containers06/assets/159126939/a5731b15-e534-4a30-8389-4360242c1522)
![2в](https://github.com/IvanRazdorognii/containers06/assets/159126939/988c591a-55e0-4061-b047-ae897f4b25a4)
![3в](https://github.com/IvanRazdorognii/containers06/assets/159126939/5569cdf3-63f9-4d11-8c21-5328340bfb6e)
![4в](https://github.com/IvanRazdorognii/containers06/assets/159126939/96ff42f6-8fc3-4122-904d-133d3999c58a)
![5в](https://github.com/IvanRazdorognii/containers06/assets/159126939/25443bb7-372e-4979-bf23-8fbf154d3cb6)
![6в](https://github.com/IvanRazdorognii/containers06/assets/159126939/42e4edbb-5870-420a-a7d3-7974cf5ca117)
# Запуск и тестирование
![7в](https://github.com/IvanRazdorognii/containers06/assets/159126939/98a97fba-671d-4d2f-9e90-6ed0afe91622)
# Вопросы:
#### В каком порядке запускаются контейнеры?
* Вначале database, потом контейнеры backend и frontend
#### Где хранятся данные базы данных?
* Данные MySQL хранятся в Docker томе под названием db_data, привязанном к папке /var/lib/mysql в контейнере.
#### Как называются контейнеры проекта?
* database, frontend,backend.
#### Вам необходимо добавить еще один файл app.env с переменной окружения APP_VERSION для сервисов backend и frontend. Как это сделать?
![8в](https://github.com/IvanRazdorognii/containers06/assets/159126939/87c9ae72-46b6-45db-9811-c74c994b8e40)
![9в](https://github.com/IvanRazdorognii/containers06/assets/159126939/d234ed7e-c781-4cf5-8542-6023d04eecbc)

