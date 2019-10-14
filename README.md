# Fitness Buddy
A social platform where fit and fitness enthusiast meet
## Run build and test
``mvn clean install``

## Build docker environment
- Prepare mvn docker dependency build ``./mvnw install dockerfile:build``
- Build container and start ``docker-compose up --build``
- Start container ``docker-compose start``
- Stop container ``docker-compose stop ``

## Swagger Documentation
http://localhost:8080/swagger-ui.html

## Health
http://localhost:8080/actuator/health