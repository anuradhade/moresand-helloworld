#######################################################################
#           moresand mysql  - Dockerfile v0.3                         #
#######################################################################

# Pull base image
FROM mariadb:10.5

MAINTAINER anuradha@gmail.com

# Add a database Name
ENV MYSQL_DATABASE employeer

# All scripts in docker-entrypoint-initdb.d/ are automatically executed
COPY ./scripts/ /docker-entrypoint-initdb.d/


