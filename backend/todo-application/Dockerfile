# Use an official OpenJDK runtime as a parent image
FROM openjdk:17

# Set the working directory
WORKDIR /app

# Copy the backend JAR file into the container
COPY target/todo-application-0.0.1-SNAPSHOT.jar todo-application-0.0.1-SNAPSHOT.jar

# Expose the port that Spring Boot runs on
EXPOSE 8090

# Run the JAR file
CMD ["java", "-jar", "todo-application-0.0.1-SNAPSHOT.jar"]
