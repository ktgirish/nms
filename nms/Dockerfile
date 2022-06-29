From tomcat:9.0.60-jdk11-temurin
RUN rm -rf /usr/local/tomcat/webapps/*
COPY ./target/nms-*.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh","run"]