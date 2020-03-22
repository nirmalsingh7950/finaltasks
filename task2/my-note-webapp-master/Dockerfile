FROM php:7.3.3-apache
RUN apt-get update && apt-get upgrade -y

RUN docker-php-ext-install mysqli pdo_mysql



# WORKDIR /app
# COPY . /app
 
# Copy apache vhost file to proxy php requests to php-fpm container

# COPY vhost.conf /etc/apache2/sites-available/000-default.conf

# RUN docker-php-ext-install mysqli \
# && chown -R www-data:www-data /app

