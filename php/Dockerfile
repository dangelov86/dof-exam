FROM php:fpm

ADD ../app /var/www/html

RUN apt-get update
RUN pear channel-discover pear.nrk.io
RUN pear install nrk/Predis
