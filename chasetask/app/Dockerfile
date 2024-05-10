FROM openjdk:latest

WORKDIR /app

COPY target/app.jar /app/

EXPOSE 8080

CMD ["java", "-jar", "app.jar"]