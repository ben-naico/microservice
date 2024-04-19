FROM azul/zulu-openjdk:21-jdk-crac-latest
LABEL maintainer="benjohnsonv98@gmail.com"
VOLUME /app
ADD build/libs/service-registery-0.0.1-SNAPSHOT.jar serviceregistery.jar
EXPOSE 8093
ENTRYPOINT ["java", "-jar", "/serviceregistery.jar"]