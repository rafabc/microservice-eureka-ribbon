# microservice-eureka-ribbon
This is a poc about microservice with netflix suite


This project is compoused of three maven modules:
First of all launch mvn clean install


######Eureka Server
start this module with mvn spring-boot:run
Running on port 1111
After that you can see the eureka dashboard on http://localhost:1111

######Car Microservice
start this module with mvn spring-boot:run
Running on port 2222
After that you can test the microservi with the next url http://localhost:2222/car/3

######Microservice Client
start this module with mvn spring-boot:run
Running on port 8080
After that you can test the microservice with the next url http://localhost:8080/client-car/3



