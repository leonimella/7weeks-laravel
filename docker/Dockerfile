FROM php:8.0-fpm-alpine

RUN apk --update add vim curl wget git

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

RUN mkdir /var/www/larabloug

WORKDIR /var/www/larabloug
