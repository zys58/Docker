FROM nimmis/alpine-apache-php5:latest

#COPY repositories /etc/apk/repositories
RUN apk update && apk upgrade && \
    apk add php5-fpm php5-cli && \
    apk add php5-pdo_mysql &&\ 
	apk add php5-iconv php5-memcache &&\
	apk add php5-soap php5-xdebug &&\
    cd /tmp && curl -sS https://getcomposer.org/installer | php && mv composer.phar /usr/local/bin/composer &&\
    rm -rf /var/cache/apk/*