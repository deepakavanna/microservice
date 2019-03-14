FROM openjdk:8-jre-alpine
WORKDIR /app
EXPOSE 8080
COPY ./target/gs-rest-service-0.1.0.jar  /app 
ENTRYPOINT ["sh", "-c"]
CMD ["java -jar /app/gs-rest-service-0.1.0.jar"] 
