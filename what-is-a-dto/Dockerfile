FROM openjdk:17-ea-slim-buster
#24-oraclelinux9
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
