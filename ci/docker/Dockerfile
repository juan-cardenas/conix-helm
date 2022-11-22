FROM openjdk:8-alpine

ENV TZ="America/Guayaquil"

EXPOSE 8080
ADD conix-services/build/libs/conix-services-1.1.7-SNAPSHOT.jar /usr/share/app.jar
ENTRYPOINT ["/usr/bin/java", "-jar", "/usr/share/app.jar"]