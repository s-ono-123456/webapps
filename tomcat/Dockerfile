FROM tomcat:9.0.1-alpine
LABEL com.example.vendor="testvendor" \
      com.example.maintainer="testuser@example.com"
RUN rm -rf /usr/local/tomcat/conf/server.xml
COPY tomcat-users.xml /usr/local/tomcat/conf/
COPY server.xml /usr/local/tomcat/conf/
RUN rm -rf /usr/local/tomcat/webapps/ROOT
CMD ["catalina.sh", "run"]
