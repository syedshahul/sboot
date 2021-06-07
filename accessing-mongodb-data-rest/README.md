# Wiki

Maven Build
============
```
mvn clean install
```
Run Spring Boot App
===================
```
./mvnw spring-boot:run
```
Build Docker Image using Dockerfile
====================================
```
docker build -t monnashahul/spring-mongodb-rest .
```
Push Docker Image
=================
Login to docker from your terminal before push the image.
```
docker push monnashahul/spring-mongodb-rest:latest
```
Build Docker
======================
```
docker-compose -f mongostack.yml up
```
