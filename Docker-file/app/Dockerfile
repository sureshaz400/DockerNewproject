FROM tomcat:8-jre11-slim
LABEL "Project"="vprofile"
LABEL "Author"="Suresh"
RUN rm -rf ./usr/local/tomcat/webapps/*
COPY target/vprofile-v2.war /usr/local/tomcat/webapps/Root.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps