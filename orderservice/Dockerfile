FROM openjdk:17-slim as build

COPY target/orderservice-0.0.1-SNAPSHOT.jar orderservice-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar", "orderservice-0.0.1-SNAPSHOT.jar"]