FROM php:8.0-apache
RUN apt update \
  && apt install -y libfreetype6-dev libjpeg62-turbo-dev libpng-dev libonig-dev\
  && docker-php-ext-install pdo_mysql mysqli mbstring gd iconv
