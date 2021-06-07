FROM adoptopenjdk/openjdk11:alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
EXPOSE 8080
ENTRYPOINT ["java","-Dspring.data.mongodb.uri=mongodb://mongo:27017/data-rest","-jar","/app.jar"]