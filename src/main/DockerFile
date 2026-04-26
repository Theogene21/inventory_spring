# Use full Java image (NOT slim)
FROM openjdk:17-jdk

# Set working directory
WORKDIR /app

# Copy JAR from target folder
COPY target/*.jar app.jar

# Expose port
EXPOSE 8080

# Run application
ENTRYPOINT ["java","-jar","app.jar"]
