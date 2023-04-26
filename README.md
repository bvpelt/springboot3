# Springboot 3

From See https://www.youtube.com/watch?v=H6HwoWZtngs

## Create project
```shell
curl https://start.spring.io/starter.tgz  -d dependencies=web,actuator  -d javaVersion=17  -d bootVersion=3.0.6  -d type=maven-project | tar -xzf -

```
## Run springboot using maven
```shell
 ./mvnw spring-boot:run
```

## Documentation
See https://docs.spring.io/spring-boot/docs/3.0.6-SNAPSHOT/maven-plugin/reference/htmlsingle/ 

## Buildpack
Make a docker container
```shell
./mvnw spring-boot:build-image
```
