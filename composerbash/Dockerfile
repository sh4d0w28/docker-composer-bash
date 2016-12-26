FROM composer/composer:1.1

MAINTAINER Maxim Edush <edush.maxim@gmail.com>

RUN cp -f /bin/bash /bin/sh

RUN pecl install xdebug
RUN docker-php-ext-enable xdebug

ENTRYPOINT ["/bin/bash", "-c"]
