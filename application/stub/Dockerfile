FROM openjdk:11-jre-slim
EXPOSE 8888
WORKDIR /stub
RUN mkdir mappings
COPY mappings/* mappings/
COPY wiremock-standalone-2.27.2.jar .
ENTRYPOINT ["java", "-jar", "wiremock-standalone-2.27.2.jar", "--verbose", "--port", "8888"]
