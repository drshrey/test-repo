FROM ubuntu:14.04
RUN apt-get update
RUN apt-get install -y nginx
RUN apt-get install -y postgresql
ADD nginx.conf /etc/nginx/nginx.conf

ADD ./www-data /www-data

EXPOSE 80
CMD ["nginx"]
