FROM openjdk:21-jdk
VOLUME /tmp
COPY bootstrap/*.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]