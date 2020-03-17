# Dockerizing-a-Spring-Boot-API

Deploying Spring Boot Microservices on Docker

## Built With

- Java 8
- Docker

## Step 1

1. Open [Spring Starter](https://start.spring.io) to create a Java Maven application with Web dependentcy.

2. Import as an existing Maven project in your IDE

3. Create a simple controller class to test your API

4. In pom.XML, define packaging as JAR

5. Run command: mvn clean and mvn install to create jar file

## Step 2

1. Create Dockerfile in your working directory.

2. Run command: docker build -f DockerFile -t dockerdemo .

3. Run command: docker images to see if the dockerdemo image exists.

4. Run command: docker run -p 8082:8080 dockerdemo

The Spring Boot Application is running from the Docker container now.
