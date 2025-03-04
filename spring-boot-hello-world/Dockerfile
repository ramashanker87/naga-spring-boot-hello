FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY target/spring-boot-hello-world-1.0.0.jar /app/spring-boot-hello-world.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app/spring-boot-hello-world.jar"]
