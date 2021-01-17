FROM php:8.0-fpm-alpine

RUN apk --update add vim curl wget git nodejs npm

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

RUN mkdir /var/www/larabloug

COPY . /var/www/larabloug

RUN chmod -R 777 /var/www/larabloug/storage/logs/

WORKDIR /var/www/larabloug
