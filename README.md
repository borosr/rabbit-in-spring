<h1>Usage test for RabbitMQ with Spring Boot 2 and Spring Cloud</h1>

<h3>How to use</h3>

1. Download and install RabbitMQ server from <a href="https://www.rabbitmq.com/download.html">here</a>.
   (If you are a Mac user, you need to edit your path)
2. Start RabbitMQ server with: `rabbitmq-server`
   - For RabbitMQ WebUI, you need to run `rabbitmq-plugins enable rabbitmq_management` before server is started
   - Basicly you can login with username: `guest` and password is: `guest` only if you running server in localhost
3. Clone this project
4. Run `mvn test`
   (If you haven't installed Maven, run `./mvnw test`)

<h3>License</h3>

<p>
MIT License <br>
Copyright (c) 2018 Robert Boros</p>


