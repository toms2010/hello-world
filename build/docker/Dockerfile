FROM openjdk:8-alpine
WORKDIR /app
COPY libs libs/
COPY resources resources/
COPY classes classes/
ENTRYPOINT ["java", "-cp", "/app/resources:/app/classes:/app/libs/*", "com.example.demo.DemoApplication"]
EXPOSE 8080
