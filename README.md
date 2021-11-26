# releases
Build configs
# Запуск redis и rabbitmq с помощью docker-compose файла
Загрузить redis image
```
docker pull redis
```
Загрузить rabbitmq image
```
docker pull rabbitmq
```
В папке с docker-compose файлом
* для создания контейнера
```
docker-compose up
```
* для запуска
```
docker-compose start
```
* для завершения
```
docker-compose stop
```
Необходимо обновить RabbitMQ.DI до последней версии
