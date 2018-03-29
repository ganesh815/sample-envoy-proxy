FROM openjdk:alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/person-service.jar person-service.jar
ENV PORT 9300
ENV DISCOVERY_URL http://172.22.45.38:9200
ENTRYPOINT ["java", "-jar", "/person-service.jar"]
EXPOSE ${PORT}