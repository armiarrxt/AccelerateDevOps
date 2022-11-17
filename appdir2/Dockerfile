FROM openjdk:8-jre-alpine
RUN mkdir /spring-petclinic
WORKDIR /spring-petclinic

#Add application
ADD ./spring-petclinic-1.5.1.jar /spring-petclinic/spring-petclinic-1.5.1.jar

EXPOSE 8080
ENTRYPOINT ["java", "-jar", "spring-petclinic-1.5.1.jar"]