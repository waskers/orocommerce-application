FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive
ENV LC_ALL=C.UTF-8

RUN sudo apt install software-properties-common
RUN add-apt-repository -y ppa:ondrej/php
RUN apt-get update
RUN apt-get install -y \
    php8.1 php8.1-fpm php8.1-cli php8.1-pdo php8.1-mysqlnd php8.1-xml php8.1-soap \
    php8.1-gd php8.1-zip php8.1-intl php8.1-mbstring php8.1-opcache php8.1-curl \
    php8.1-bcmath php8.1-ldap php8.1-pgsql php8.1-dev php8.1-mongodb