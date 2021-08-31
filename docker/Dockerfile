FROM openjdk:11-jdk-slim

EXPOSE 19132/tcp
EXPOSE 19132/udp

WORKDIR /home

ADD . /home

ENTRYPOINT ["java", "-jar", "Waterdog.jar"]