# Base Image

FROM ubuntu:16.04

# Maintainer of this Image

MAINTAINER Archana <archanam@outlook.com>

RUN apt-get update

RUN apt-get install apache2 -y

copy archana.html /var/www/html/hello.html

CMD ["/usr/sbin/apache2ctl","-D","FOREGROUND"]
