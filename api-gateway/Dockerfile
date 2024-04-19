FROM azul/zulu-openjdk:21-jdk-crac-latest
LABEL maintainer="benjohnsonv98@gmail.com"
VOLUME /app
ADD build/libs/api-gateway-0.0.1-SNAPSHOT.jar apigateway.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "/apigateway.jar"]