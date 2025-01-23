# RabbitMQ Hello World

PHP simplest study on RabbitMQ message queue, with a basic UI for sending messages.

## How to run

### Run RabbitMQ
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4.0-management

### Run receiver
php receive.php

### Run sender
Navigate to index.html and send a message
