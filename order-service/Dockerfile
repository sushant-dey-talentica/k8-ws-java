FROM eclipse-temurin:21
WORKDIR /workspace/app
COPY ./target/order-service-0.0.1-SNAPSHOT.jar /workspace/app/
RUN apt-get update
EXPOSE 8080
CMD ["java", "-jar", "order-service-0.0.1-SNAPSHOT.jar"]