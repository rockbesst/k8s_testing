FROM trafex/php-nginx
WORKDIR /etc/nginx/conf.d/
COPY kube.test.conf ./
#WORKDIR /etc/php/7.3/fpm/
#COPY php.ini ./php.ini
WORKDIR /var/www/html/
COPY ./wordpress ./

# RUN apt-get update \
#     && apt-get install -y php \
#                 php-cli \
#                 php-fpm \
#                 php-json \
#                 php-common \
#                 php-mysql \
#                 php-zip \
#                 php-gd \
#                 php-mbstring \
#                 php-curl \
#                 php-xml \
#                 php-pear \
#                 php-bcmath \
#                 nano \
#     && chown -R www-data:www-data /usr/share/nginx/html/