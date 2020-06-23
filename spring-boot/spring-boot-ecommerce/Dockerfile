FROM openjdk:12
ADD target/docker-spring.jar docker-spring.jar
EXPOSE 8086
ENTRYPOINT ["java", "-jar", "docker-spring.jar"]