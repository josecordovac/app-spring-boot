# App Spring Boot

# springboot-app

Minimal [Spring Boot](http://projects.spring.io/spring-boot/) sample app.

## Requirements

For building and running the application you need:

- [JDK 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven 3.9.6](https://maven.apache.org)

## Create database 

* Server: SQL Server
* Database: ProductosDB

## Review connection string

File: src/main/resources/application.properties

```shell
spring.datasource.url=jdbc:sqlserver://localhost:1433;databaseName=ProductosDB;encrypt=false
```

Replace host or port:

* host: localhost
* port: 1433

## Running the application locally

There are several ways to run a Spring Boot application on your local machine.

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```

## Copyright

Released under the Apache License 2.0. See the [LICENSE](https://github.com/codecentric/springboot-sample-app/blob/master/LICENSE) file.
