FROM maven:3.9.12-eclipse-temurin-17

WORKDIR /opt

COPY . . 

RUN mvn clean package -DskipTests

EXPOSE 8082

ENTRYPOINT ["java", "-jar", "target/product-service-1.0.0.jar"]

