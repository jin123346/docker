FROM openjdk:17
ARG JAR_FILE=./*.jar
COPY ${JAR_FILE} app.jar
CMD  ["java", "-jar", "app.jar"]