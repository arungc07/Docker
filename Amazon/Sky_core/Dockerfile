FROM tomcat:9.0 
MAINTAINER Arunprasath
RUN wget https://github.com/arungc07/Amazon/blob/master/SKY/SKY-Core/target/SKY-Core-1.0-SNAPSHOT.jar
WORKDIR /usr/local/tomcat
COPY SKY-Core-1.0-SNAPSHOT.jar /usr/local/tomcat/webapps/
CMD ["/usr/local/tomcat/bin/catalina.sh", "run"]
