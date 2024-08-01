# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim
# Set the working directory in the container
WORKDIR /app
# Copy the JAR file to the container
COPY target/spring-petclinic-rest-3.2.1.jar /app/spring-petclinic-rest-3.2.1.jar
# Expose port 9967
EXPOSE 9967
# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/spring-petclinic-rest-3.2.1.jar"]

