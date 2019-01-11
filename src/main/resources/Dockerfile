FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD springboot-demo-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8888
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
CMD java -jar app.jar
