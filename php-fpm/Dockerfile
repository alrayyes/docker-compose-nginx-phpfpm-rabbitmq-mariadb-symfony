FROM andthensome/docker-php-5.3-fpm

# Install php packages we need
RUN pecl install xdebug-2.2.7 \
	&& docker-php-ext-enable xdebug

COPY php.ini /usr/local/etc/php/php.ini

COPY fix-cache-log.sh /usr/bin/fix-cache-log.sh

WORKDIR /var/www