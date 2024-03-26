# Use an OpenJDK base image
FROM amazoncorretto:17

# Set the working directory inside the container
WORKDIR /configserver

# Copy the packaged Spring Boot application JAR file into the container
COPY ./configserver-0.0.1-SNAPSHOT.jar /configserver

# Expose the port that your Spring Boot application listens on
EXPOSE 8081

# Command to run the Spring Boot application
CMD ["java", "-jar", "configserver-0.0.1-SNAPSHOT.jar"]
