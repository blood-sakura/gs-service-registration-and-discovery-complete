FROM java:8

MAINTAINER Lin

ADD ${artifactName}.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app.jar"]