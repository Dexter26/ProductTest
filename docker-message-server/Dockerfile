FROM openjdk:8-jdk-alpine
LABEL org.opencontainers.image.authors="dexter"
COPY target/docker-message-server-1.0.0.jar message-server.jar
ENTRYPOINT ["java","-jar","/message-server.jar"]