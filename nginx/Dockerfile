
FROM ubuntu 
MAINTAINER anderson (andersonazotsie@gmail.com) 
RUN apt-get update 
RUN apt-get install -y nginx 
EXPOSE 80
ADD index.html /var/www/html 
ENTRYPOINT ["/usr/sbin/nginx", "-d", "daemon off;"]
