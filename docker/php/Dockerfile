FROM php:7.4-fpm

WORKDIR /code

# Software Dependencies
RUN apt-get update
RUN apt-get install -y \
    libxml2-dev \
    libpng-dev \
    libxslt1-dev \
    libzip-dev \
    libpq-dev

# PHP Extensions
RUN docker-php-ext-install \
  gd \
  intl \
  pdo_pgsql \
  xsl \
  zip \
  soap \
  bcmath
