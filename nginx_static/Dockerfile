FROM nginx:alpine

#This is the custom nginxconfiguration
COPY docker/nginx.conf /etc/nginx/conf.d/default.conf

#copy the html and css files to the appropriate location inthe container
COPY html/ usr/share/nginx/html

EXPOSE 80