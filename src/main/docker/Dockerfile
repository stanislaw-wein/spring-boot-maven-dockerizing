FROM openjdk:14-alpine

EXPOSE 8080

WORKDIR /usr/local/bin/

COPY maven/demo-0.0.1-SNAPSHOT.war webapp.war

CMD ["java","-Dspring.profiles.active=docker","-Djava.security.egd=file:/dev/./urandom","-jar","webapp.war"]
