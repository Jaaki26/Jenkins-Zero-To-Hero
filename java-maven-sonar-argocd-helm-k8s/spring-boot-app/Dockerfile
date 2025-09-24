# You can change this base image to anything else
# Use Eclipse Temurin JDK 21 (official image)
FROM eclipse-temurin:21-jre-alpine

# Simply the artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
