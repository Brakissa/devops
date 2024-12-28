# Dockerfile pour l'application PHP5
FROM php:8.3-apache
RUN docker-php-ext-install mysqli pdo_mysql

# Copier les fichiers de l'application
COPY ./ /var/www/html/

# Définir les permissions pour le dossier uploads
RUN chmod -R 777 /var/www/html/uploads

