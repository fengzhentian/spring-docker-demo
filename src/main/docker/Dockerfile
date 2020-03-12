FROM openjdk:8-jre-slim
MAINTAINER test <test@zte-its.com>
VOLUME /tmp
WORKDIR /usr/local/src
ADD spring-docker-demo.jar app.jar
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar"]
EXPOSE 8080