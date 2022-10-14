FROM tomcat:jre8-openjdk-slim-buster


RUN apt-get update
RUN apt-get install -y wget

 
COPY ./gradle-simple-master/build/libs/gradle-simple-master-2.0.jar gradle-simple-master.jar

EXPOSE 8080

CMD ["java","-jar","gradle-simple-master.jar"]   
