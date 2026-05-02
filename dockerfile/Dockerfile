FROM php:8.4-fpm

RUN apt update && apt install -y libldap2-dev \
    && docker-php-ext-configure ldap \
    && docker-php-ext-install ldap
