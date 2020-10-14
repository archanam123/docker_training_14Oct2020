# Base Image
From ubuntu:16.04

#Maintainer of this Image

MAINTAINER Archana <archanam@outlook.com>


RUN apt-get update



# Install Apache Packages
RUN apt-get install apache2 -y


#Bring up the Apache App.

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
