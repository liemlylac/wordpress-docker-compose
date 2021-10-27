FROM wordpress:apache

RUN apt-get update && \
    apt-get -y install git


RUN cd /tmp && \
    git clone git://github.com/xdebug/xdebug.git && \
    cd xdebug && \
    git checkout xdebug_3_0 && \
    phpize && \
    ./configure --enable-xdebug && \
    make && \
    make install && \
    rm -rf /tmp/xdebug

COPY build/php/conf.d /usr/local/etc/php/conf.d


RUN docker-php-ext-enable xdebug