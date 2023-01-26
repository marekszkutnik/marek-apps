FROM openjdk:8-jdk-alpine

COPY prime-number-service-ws-0.1.2-SNAPSHOT.jar prime-number-service.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/prime-number-service.jar"]
