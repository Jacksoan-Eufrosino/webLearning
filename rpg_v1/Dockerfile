FROM ubuntu

MAINTAINER Jacksoan Eufrosino <jacksoan.elmar@hotmail.com>

WORKDIR /var/www/html

COPY . .

RUN apt-get update \
    && apt-get install -y nginx \
    && echo "daemon off;" >> /etc/nginx/nginx.conf

EXPOSE 80

CMD ["service","nginx","start"] 
