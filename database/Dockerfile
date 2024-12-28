# Dockerfile pour MySQL 5.7
FROM mysql:8.0

# Copier le dump SQL dans le dossier d'initialisation
COPY ./gestion_produits.sql /docker-entrypoint-initdb.d/

# Définir le volume pour la persistance des données
VOLUME ["/var/lib/mysql"]
