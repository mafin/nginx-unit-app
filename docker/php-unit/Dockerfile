FROM docker.io/nginx/unit:1.28.0-php8.1

WORKDIR /www

COPY ../../app/ .
COPY ./docker/php-unit/docker-entrypoint.d/config.json /docker-entrypoint.d/

EXPOSE 8080
