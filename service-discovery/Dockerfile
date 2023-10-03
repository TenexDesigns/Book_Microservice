# Use an official OpenJDK runtime as a parent image
FROM openjdk:20-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container at /app
COPY target/service-discovery-0.0.1-SNAPSHOT.jar /app/service-discovery-0.0.1-SNAPSHOT.jar

EXPOSE 8761

# Specify the command to run your application
CMD ["java", "-jar", "service-discovery-0.0.1-SNAPSHOT.jar"]