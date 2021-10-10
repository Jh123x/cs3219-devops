FROM openjdk:11.0.2-jre-slim
WORKDIR /app
EXPOSE 8080
COPY ./customer-service-0.0.1-SNAPSHOT.jar ./customer-service.jar
CMD ["java", "-jar", "customer-service.jar"]

