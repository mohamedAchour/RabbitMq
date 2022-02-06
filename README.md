# RabbitMq

## RabbitMq message broker tutorials

In this project, we'll go through all steps to tun RabbitMq locally using docker container on a **Linux machine**.

**TODO:**

- [Install Docker](https://docs.docker.com/engine/installation/), then
  run `docker-compose up` or `docker-compose up -d` to run docker image in background. Control-C or `docker-compose down` will cleanly stop the container.
- Install pika (package RabbitMQ client library for Python): `pip install pika`

## Run Instructions

- Open three terminals
- Terminal 1: run RabbitMq container `docker-compose up`.
- Terminal 2: run the prodcuer.py script.
- Terminal 3: run the consumer.py script.
- If you did everything right, you'll get something like this: ![successful manipulation result](img1.png)
