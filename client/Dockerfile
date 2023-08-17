FROM openjdk:17-jdk-slim
WORKDIR /app
COPY client/target/client.jar app.jar
EXPOSE 8081
CMD ["java", "-jar", "app.jar"]
