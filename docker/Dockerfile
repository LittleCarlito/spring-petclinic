FROM openjdk:8u282-jre
MAINTAINER Steven Meier <smeier5@depaul.edu>
COPY spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar .
EXPOSE 8484
ENTRYPOINT ["java", "-jar", "./spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar", "--spring.profiles.active=mysql"]