FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD discover-service-0.0.1-SNAPSHOT.jar discover-service.jar
RUN sh -c 'touch /movie-catalog-service.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/discover-service.jar"]