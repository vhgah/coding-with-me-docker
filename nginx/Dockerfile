FROM nginx:stable-alpine3.17

WORKDIR /var/www/html

COPY coding-with-me-api coding-with-me-api

COPY docker/nginx/default.conf /etc/nginx/nginx.conf

COPY docker/nginx/conf.d/*.conf /etc/nginx/conf.d/
