# Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from the host machine to the container
COPY target/BasicCrud-0.0.1-SNAPSHOT.jar /app/Basic-Crud.jar

# Expose the port your Spring Boot app runs on
EXPOSE 8080

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "/app/Basic-Crud.jar"]
