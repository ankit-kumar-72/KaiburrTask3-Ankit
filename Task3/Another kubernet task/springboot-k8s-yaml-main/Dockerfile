FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/springboot-k8s-demo.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
