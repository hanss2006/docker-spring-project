FROM tomcat:9-jdk17-openjdk-slim
COPY "target/docker-spring-*.war" "/usr/local/tomcat/webapps/api#docker-spring.war"
ENV JAVA_OPTS="-Duser.timezone=Europe/Moscow -Dfile.encoding=UTF8"
EXPOSE 8080
EXPOSE 8000
CMD ["catalina.sh", "run"]