FROM openjdk:8-jdk-alpine
ADD target/*.jar .
EXPOSE: 8080
ENTRYPOINT ["java","-jar","spring-boot-docker.jar"]
