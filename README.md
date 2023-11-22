# spring-rest-actuator

RESTful Web Service with Spring Boot Actuator

```bash
./gradlew clean build && java -jar build/libs/spring-rest-actuator-0.0.1.jar
```

Check actuator health status:

```bash
curl -i http://localhost:8080/actuator/health
```

Check endpoint info:

```bash
curl -i http://localhost:8080/hello-world\?name\=John
```
