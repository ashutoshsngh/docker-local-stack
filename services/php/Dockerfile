FROM php:7.1-fpm

#updates
RUN apt-get update && apt-get install -y \
		libmcrypt-dev \
		libjpeg-dev \
        libpng-dev

# mark volume/s as externally mounted
VOLUME ["/var/www/html"]

# starting point
WORKDIR /var/www/html

# make web server connect to this port
EXPOSE 9000