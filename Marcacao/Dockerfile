FROM openjdk:21
ARG JAR_FILE=marcacao.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 8091
