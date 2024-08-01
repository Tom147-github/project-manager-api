FROM php:8.2-fpm

COPY ./docker/php/php.ini /usr/local/etc/php/php.ini

COPY --from=composer:2.7.7 /usr/bin/composer /usr/bin/composer