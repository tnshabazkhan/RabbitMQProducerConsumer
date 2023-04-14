# RabbitMQProducerConsumer
This application has a .Net 7 Rest Application acting as a RabbitMQ producer, .Net 7 Console application acting as a consumer of the queue. RabbitMQ official docker image is used for running RabbitMQ

Steps to Run.

1. Pull and Run rabbitmq:3-management Docker image from Dockerhub
2. Rub Both .Net API poject and Console application paralelly as Multiple project startup in Visual Studio
3. Add new products using the API and we should see the console application reading the messages from RabbitMQ and printing it on the console.
