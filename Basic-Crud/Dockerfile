FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/BasicCrud-0.0.1-SNAPSHOT.jar /app/Basic-Crud.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/app/Basic-Crud.jar"]
