# Use a base image with Java installed
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the jar file into the container
COPY spring-petclinic-rest-3.2.1.jar /app/spring-petclinic-rest-3.2.1.jar

# Expose the port the application runs on
EXPOSE 9967

# Define the command to run the jar file
ENTRYPOINT ["java", "-jar", "spring-petclinic-rest-3.2.1.jar"]
