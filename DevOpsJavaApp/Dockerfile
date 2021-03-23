FROM tomcat:8.5.38

MAINTAINER "lakshmanandevops@gmail.com"

RUN echo "Creating docker image for Java WebApp"

ADD ./target/JavaApp.war /usr/local/tomcat/webapps/

RUN chmod +x /usr/local/tomcat/bin/catalina.sh

CMD ["catalina.sh", "run"]