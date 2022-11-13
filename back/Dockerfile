FROM tomcat:9-jdk17-openjdk
COPY "target/*docker-spring*.war" "/usr/local/tomcat/webapps/api#docker-spring.war"
ENV JAVA_OPTS="-Duser.timezone=Europe/Moscow -Dfile.encoding=UTF8"
ENV JPDA_ADDRESS 8000
ENV JJPDA_TRANSPORT dt_socket
EXPOSE 8080
EXPOSE 8000
CMD ["catalina.sh", "run"]