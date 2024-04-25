FROM tomcat:10

WORKDIR /usr/local/tomcat/webapps

COPY DimMoneyAppRM97798.war /usr/local/tomcat/webapps/DimMoneyAppRM97798.war

EXPOSE 8080

VOLUME /usr/local/tomcat/webapps

CMD ["catalina.sh", "jpda", "start"]