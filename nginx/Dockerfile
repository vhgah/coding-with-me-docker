FROM nginx:stable-alpine3.17

WORKDIR /var/www/html

# COPY coding-with-me-api coding-with-me-api

COPY coding-with-me-admin/dist coding-with-me-admin

COPY coding-with-me-docker/nginx/default.conf /etc/nginx/nginx.conf

COPY coding-with-me-docker/nginx/conf.d/*.conf /etc/nginx/conf.d/
