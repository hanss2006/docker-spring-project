FROM tomcat:9-jdk17-openjdk-slim
COPY target/docker-spring-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/api#docker-spring.war
EXPOSE 8080
CMD ["catalina.sh", "run"]