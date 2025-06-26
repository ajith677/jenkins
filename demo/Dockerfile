# Use OpenJDK 17 Alpine as the base image
FROM openjdk:17-alpine

# Set the working directory for clarity
WORKDIR /demo

# Copy the specific JAR file (replace with actual JAR name or use build argument)
COPY target/myapp.jar app.jar

# Expose port 8081 (matches Jenkinsfile's docker run command)

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "/app.jar"]