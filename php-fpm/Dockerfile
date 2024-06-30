FROM php:8.1-fpm

RUN apt-get update \
    && apt-get install -y \
        mariadb-client \
        libmariadb-dev \
    && docker-php-ext-install pdo pdo_mysql

WORKDIR /var/www/html

# COPY coding-with-me-api coding-with-me-api

EXPOSE 9000

CMD ["php-fpm"]
