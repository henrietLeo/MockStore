FROM php:7.2-fpm-alpine

ENV SRC_DIR /home/store

COPY --from=composer /usr/bin/composer usr/bin/composer

WORKDIR ${SRC_DIR}/

EXPOSE 9000
