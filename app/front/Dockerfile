# Utiliser un serveur web léger comme image de base
FROM nginx:alpine

# Définir le répertoire de travail sur /app/front
WORKDIR /app/front

# Copier le contenu du répertoire front dans le conteneur
COPY . /app/front

# Copier le script d'entrée
COPY entrypoint.sh /docker-entrypoint.sh

# Définir les autorisations du script d'entrée
RUN chmod +x /docker-entrypoint.sh

# Exposer le port 80
EXPOSE 80

# Commande d'exécution
CMD ["/docker-entrypoint.sh"]
