FROM openjdk:8-jdk-slim
RUN apt-get update ; apt-get install -y git
RUN git clone https://github.com/docker-hy/spring-example-project
WORKDIR /spring-example-project
RUN /spring-example-project/mvnw package
ENTRYPOINT ["java"]
CMD ["-jar", "/spring-example-project/target/docker-example-1.1.3.jar"]
EXPOSE 8080
