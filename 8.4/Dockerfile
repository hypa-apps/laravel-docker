FROM lorisleiva/laravel-docker:8.4

# Install missing dependencies
RUN apk add --no-cache \
    postgresql-client

RUN docker-php-ext-install ftp