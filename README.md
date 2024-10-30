# movieapp_microservice
movie app using Springboot framework. 
we have the User microservice, Theatre service and Movie microservice., and a config server to establish communication between them and dynamically load updated properties without having to restart the application.
- clone the repository. In 4 different terminals. Run these commands:
- cd Config-Server. mvn spring-boot:run
- cd movieapp-Simple.  mvn spring-boot:run
- cd theatre-Simple.  mvn spring-boot:run
- cd user-Simple.  mvn spring-boot:run
  Swagger documentation for Rest Apis can be viewed at:  http://localhost:8081/movie-service/swagger-ui.html
