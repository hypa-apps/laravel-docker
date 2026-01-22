FROM lorisleiva/laravel-docker:8.3

# Install missing dependencies
RUN apk add --no-cache \
    postgresql-client

RUN apk add --no-cache --virtual .build-deps openssl-dev \
  && docker-php-ext-install ftp \
  && apk del .build-deps
