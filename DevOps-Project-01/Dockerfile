FROM openjdk:21

WORKDIR /app

COPY target/app.war app.war

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.war"]
