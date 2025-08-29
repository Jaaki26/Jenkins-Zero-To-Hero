# Use Java 17 runtime
FROM eclipse-temurin:17-jre-alpine

# Artifact name from Maven build
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

# Copy jar into container
COPY ${artifact} app.jar

# Run the jar
ENTRYPOINT ["java","-jar","app.jar"]
