FROM	php:7.4.6-fpm-alpine

RUN     apk add --no-cache postgresql-dev && \
        docker-php-ext-install pdo pdo_pgsql pgsql

