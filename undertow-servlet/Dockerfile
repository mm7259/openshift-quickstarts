#random dockerfile taken from the internet
FROM java:8-jdk-alpine
COPY ./build/libs/java-app-0.0.1-SNAPSHOT.war /usr/app/
WORKDIR /usr/app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "java-app-0.0.1-SNAPSHOT.war"]
