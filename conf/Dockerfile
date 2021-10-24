FROM php:7.4-apache

RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli && a2enmod auth_basic && a2enmod info && a2enmod status && a2enmod auth_digest
