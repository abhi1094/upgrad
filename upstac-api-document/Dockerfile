FROM openjdk:14-jdk-alpine

MAINTAINER upgrad

WORKDIR /opt/app

COPY ./target/upstac-api-0.0.1-SNAPSHOT.jar /opt/app/upstac-api-0.0.1-SNAPSHOT.jar

ENV PATH="${PATH}:${JAVA_HOME}/bin"

EXPOSE 8082

ENTRYPOINT [ "java", "-jar", "/opt/app/upstac-api-0.0.1-SNAPSHOT.jar"]

