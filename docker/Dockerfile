FROM amazoncorretto:17
LABEL authors="rodrigoloureiro"
WORKDIR /app
COPY app.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]