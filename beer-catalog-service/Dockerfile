FROM openjdk:17-jdk-slim
WORKDIR /app
COPY beer-catalog-service/target/beer-catalog-service.jar app.jar
EXPOSE 8081
CMD ["java", "-jar", "app.jar"]
