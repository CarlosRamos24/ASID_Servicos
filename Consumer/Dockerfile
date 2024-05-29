FROM openjdk:21
ARG JAR_FILE=consumer.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 8105
