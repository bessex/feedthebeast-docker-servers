FROM openjdk:8u212-jre-alpine

# Install dependencies
RUN apk add --no-cache -U \
    wget \
    unzip \
    bash

RUN mkdir -p /opt/minecraft

WORKDIR /opt/minecraft

EXPOSE 25565
