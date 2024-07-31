# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the application JAR file to the container
COPY target/your-spring-boot-app.jar app.jar

# Expose the port the app runs on
EXPOSE 8080

# Run the JAR file
ENTRYPOINT ["java", "-jar", "app.jar"]
