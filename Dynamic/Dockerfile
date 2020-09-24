FROM tomcat:9.0

EXPOSE 8081

ARG WAR_FILE=/target/*.war

COPY ${WAR_FILE} /usr/local/tomcat/webapps

MAINTAINER "nagendra166"