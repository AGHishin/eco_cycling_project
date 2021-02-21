FROM openjdk:11-jdk
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
# Inform Docker that the container is listening on the specified port at runtime.
EXPOSE 8070
ENTRYPOINT ["java","-jar","/app.jar"]