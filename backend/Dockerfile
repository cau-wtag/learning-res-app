FROM eclipse-temurin:17-jre
WORKDIR /app

# Copy the pre-built JAR from the workflow artifact download step
COPY target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]