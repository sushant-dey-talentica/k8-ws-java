FROM eclipse-temurin:21
WORKDIR /workspace/app
COPY ./target/inventory-service-0.0.1-SNAPSHOT.jar /workspace/app/
RUN apt-get update
EXPOSE 8082
CMD ["java", "-jar", "inventory-service-0.0.1-SNAPSHOT.jar"]