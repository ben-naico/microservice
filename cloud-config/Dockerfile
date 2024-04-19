FROM azul/zulu-openjdk:21-jdk-crac-latest
LABEL maintainer="benjohnsonv98@gmail.com"
VOLUME /app
ADD build/libs/cloud-config-0.0.1-SNAPSHOT.jar cloudconfig.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "/cloudconfig.jar"]