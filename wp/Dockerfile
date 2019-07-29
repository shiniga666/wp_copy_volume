FROM wordpress:latest
COPY . /var/www/html

RUN apt-get update && apt-get install -y \
    	apt-utils \
	vim \
	libfreetype6-dev \
        libmcrypt-dev \
        libpng-dev \
        libjpeg-dev \
        libxml2-dev
#RUN chown -R www-data:www-data /var/www/html
#USER www-data
#VOLUME /var/www/html


