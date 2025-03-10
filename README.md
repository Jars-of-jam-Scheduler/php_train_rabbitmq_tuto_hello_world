# RabbitMQ Tutorials - Hello World
## Docker
```bash
docker-compose build --no-cache php
docker-compose up -d
docker exec -it php_train_rabbitmq_tuto_hello_world-php-1 bash
```

### Executing RabbitMQ scripts

Inside the PHP Docker container:

```bash
cd src
php send.php
php receive.php
```
