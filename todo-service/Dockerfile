FROM inlineno1/amazonlinux2:latest
MAINTAINER james lee <inlineno1@gmail.com>

ADD ./target/todo-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/todo-service.jar"]

EXPOSE 8080