FROM tomcat

WORKDIR /usr/local/tomcat

COPY ./tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
COPY ./context.xml /usr/local/tomcat/webapps/manager/META-INF/context.xml
COPY ./src/target/petclinic.war /usr/local/tomcat/webapps/petclinic.war

EXPOSE 8080
