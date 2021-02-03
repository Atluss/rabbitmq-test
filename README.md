# My RabbitMQ Sandbox

This my sandbox for RabbitMQ.

### Run RabbitMQ

```bash
cd docker
docker-compose up
```

[http://localhost:15672](http://localhost:15672)

login/pass: guest / guest

port | desc
---|---
5672 | standard port to access rabbit (`amqp://guest:guest@localhost:5672/`)
15672 | port to access admin console

### Run test

```
go get -u ./...
go mod vendor
```

### Links
[Guide Habr (Rus)](https://habr.com/ru/post/488654/) \
[Tutorial From RabbitMQ (Eng)](https://www.rabbitmq.com/tutorials/tutorial-one-go.html) \
[Docker Hub](https://hub.docker.com/_/rabbitmq)
