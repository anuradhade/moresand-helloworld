#######################################################################
#           moresand nginx  - Dockerfile v0.2          #
#######################################################################

# Pull base image	
FROM nginx

MAINTAINER anuradha@gmail.com

# Remove default conf file
RUN rm /etc/nginx/conf.d/default.conf
RUN rm /etc/nginx/nginx.conf

# Copy new conf file
COPY nginx.conf /etc/nginx/nginx.conf
COPY loadbalance.conf /etc/nginx/conf.d/loadbalance.conf 

EXPOSE 80
