FROM ubuntu:latest

RUN apt-get update -yqq \
 && apt-get -yqq install nginx

#ADD conf/global.conf /etc/nginx/conf.d/
#ADD conf/nginx.conf /etc/nginx/nginx.conf
#ADD index.html /var/www/html/index.html

EXPOSE 80

CMD ["nginx"]