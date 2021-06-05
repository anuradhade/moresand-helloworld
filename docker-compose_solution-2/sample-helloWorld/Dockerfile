#######################################################################
#            moresand hellow-world Application - Dockerfile v0.1          #
#######################################################################

# Pull base image
FROM tomcat:8.0-alpine

MAINTAINER anuradha@gmail.com
	
# Set working directory
WORKDIR /usr/local/tomcat/webapps/

#Copy to sample war in working directory
COPY sample.war /usr/local/tomcat/webapps/

EXPOSE 8080
CMD ["catalina.sh", "run"]
