# Use the official OpenJDK image as base
FROM openjdk:11

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled JAR file into the container at /app
COPY target/my-application.jar /app

# Make port 8080 available to the world outside this container
EXPOSE 8080

# Run the JAR file
CMD ["java", "-jar", "my-application.jar"]
