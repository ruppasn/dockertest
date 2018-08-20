#pull base image
FROM openjdk:8-jdk-alpine

#expose port 8080
EXPOSE 8080


#copy hello world to docker image
ADD ./target/spring-boot-web-jsp-1.0.war spring-boot-web-jsp-1.0.war



#default command
CMD java -jar spring-boot-web-jsp-1.0.war

#CMD ["java -jar spring-boot-web-jsp-1.0.war"]

