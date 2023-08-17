FROM openjdk:17-jdk-slim
WORKDIR /app
COPY edge-service/target/edge-service.jar app.jar
EXPOSE 8082
CMD ["java", "-jar", "app.jar"]
