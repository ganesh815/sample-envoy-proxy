FROM openjdk:alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/product-service.jar product-service.jar
ENV PORT 9400
ENV DISCOVERY_URL http://172.22.45.38:9200
ENTRYPOINT ["java", "-jar", "/product-service.jar"]
EXPOSE ${PORT}