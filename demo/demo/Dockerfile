# TODO: Select Base Image
# FROM ...
FROM eclipse-temurin:25-jdk-alpine
WORKDIR /app

# TODO: Copy JAR file
# COPY ...
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
# TODO: Set Entrypoint
# ENTRYPOINT ...
ENTRYPOINT ["java","-jar","app.jar"]