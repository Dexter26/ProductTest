FROM openjdk:8-jdk-alpine
LABEL org.opencontainers.image.authors="dexter"
COPY target/docker-product-server-1.0.0.jar product-server.jar
ENTRYPOINT ["java","-jar","product-server.jar"]