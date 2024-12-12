FROM openjdk:17-jdk-alpine
MAINTAINER "Ashu"
EXPOSE 7000
COPY ./target/EurekaServiceDocker.jar  EurekaServiceDocker.jar 

CMD ["java","-jar","EurekaServiceDocker.jar"]

#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
#WORKDIR  /usr/local/bin/
