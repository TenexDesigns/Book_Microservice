# Use an official OpenJDK runtime as a parent image
FROM openjdk:20-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/apigateway-0.0.1-SNAPSHOT.jar /app/apigateway-0.0.1-SNAPSHOT.jar

# Expose the port your application will run on (default for Spring Boot is 8080)
EXPOSE 8765

# Define the command to run the application when the container starts
CMD ["java", "-jar", "apigateway-0.0.1-SNAPSHOT.jar"]