# Build Simple Spring Boot Application on Local

This tutorial shows how to create simple spring application.


## Clone Git Repository
```
$ git clone https://github.com/Jooho/spring-cloud-kubernetes-sample.git

```

## Build application with Maven 
```
$ cd spring-cloud-kubernetes-sample

$ mvn package && java -jar target/gs-spring-boot-0.1.0.jar

 ....
.   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v1.2.2.RELEASE)

....

## Test with curl command
```
$ curl localhost:8080

Greetings from Spring Boot!
```


Now, you have simple spring boot application !.

Move to next tutorial.
