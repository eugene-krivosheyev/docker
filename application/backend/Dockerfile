FROM p142h/base:1.0.0
EXPOSE 8080
WORKDIR /dbo
COPY dbo-1.0-SNAPSHOT.jar .
ENTRYPOINT ["java", "-jar", "dbo-1.0-SNAPSHOT.jar"]
CMD ["--spring.profiles.active=qa"]
