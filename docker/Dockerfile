FROM openjdk:alpine

COPY build/libs/listascontrol-0.1.0.jar /api/listas-control.jar

WORKDIR /api

EXPOSE 8080

ENV LANG C.UTF-8

RUN ls /api

ENTRYPOINT java -jar /api/listas-control.jar