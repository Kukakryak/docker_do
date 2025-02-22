FROM ubuntu:22.04
RUN apt update
RUN apt install wget curl nginx -y
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
COPY ./html/index.html /var/www/html
CMD [ "nginx" ]