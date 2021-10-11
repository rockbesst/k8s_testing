# FROM luzifer/alpine-nginx-php
# WORKDIR /var/www/
# COPY ./wordpress ./

FROM nginx:latest
WORKDIR /var/www/
COPY ./wordpress ./
RUN apt-get update \
    && apt-get install -y php \
                php-cli \
                php-fpm \
                php-json \
                php-common \
                php-mysql \
                php-zip \
                php-gd \
                php-mbstring \
                php-curl \
                php-xml \
                php-pear \
                php-bcmath \
                nano
