FROM tomcat:9.0 
MAINTAINER Arunprasath
RUN wget https://github.com/arungc07/Amazon/blob/master/SKY/SKY-Web/target/SKY.war
WORKDIR /usr/local/tomcat
COPY SKY.war /usr/local/tomcat/webapps/
CMD ["/usr/local/tomcat/bin/catalina.sh", "run"]
