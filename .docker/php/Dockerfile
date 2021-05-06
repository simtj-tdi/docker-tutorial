FROM php:7.4-fpm-alpine

RUN docker-php-ext-install pdo pdo_mysql mysqli

# Install Bash Git
RUN apk --no-cache add bash git