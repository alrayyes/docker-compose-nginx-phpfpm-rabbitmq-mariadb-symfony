FROM php:fpm-alpine

RUN docker-php-ext-install pdo_mysql

COPY php.ini /usr/local/etc/php/php.ini

WORKDIR /var/www