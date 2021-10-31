# Docker file para creación de imagen de apache + PHP + Passenger
FROM ubuntu:latest

MAINTAINER Jeremy Reyes B. <jjrb6@hotmail.com>

RUN apt-get update && \
    apt install -y software-properties-common && \
    add-apt-repository ppa:ondrej/php && \
    apt install -y php7.4 && \
    apt install -y php-xdebug \
    apt-get clean