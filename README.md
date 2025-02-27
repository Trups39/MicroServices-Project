
# MicroServices-Project
Application Overview
We will be building a simple e-commerce application where customers can order products. Our application contains the following services:

Product Service

Order Service

Inventory Service

Notification Service

To focus on the principles of Spring Cloud and Microservices, we will develop services with essential functionality rather than creating fully-featured e-commerce services.
<img width="709" alt="image" src="https://github.com/user-attachments/assets/0ee878a5-b1f6-40c2-95a9-5d4781935635" />


## How to run the application using Docker

1. Run `mvn clean package -DskipTests` to build the applications and create the docker image locally.
2. Run `docker-compose up -d` to start the applications.

## How to run the application without Docker

1. Run `mvn clean verify -DskipTests` by going inside each folder to build the applications.
2. After that run `mvn spring-boot:run` by going inside each folder to start the applications.




