# springcloudconfig

In this folder we have two project to test spring cloud config.

- Module configserver is the server config that integrate the github url repository. We can start this with command: ./mvnw spring-boot:run .

- Module configclient is the microservice client of server config. Start it by this command ./mvnw spring-boot:run

- Finally you test config by targetting this endpoint:  curl http://localhost:8080/whoami/Djibril 

