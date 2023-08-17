FROM openjdk:17-jdk-slim
WORKDIR /app
COPY eureka-service/target/eureka-service.jar app.jar
EXPOSE 8761
CMD ["java", "-jar", "app.jar"]
