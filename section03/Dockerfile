# image de base à utiliser
FROM alpine

# installation des dépendances
RUN apk add --no-cache redis

# processus à lancer au démarrage
CMD ["redis-server"]

# Lancement de la création du conteneur :
#$ docker build -t mon-conteneur-redis .
#$ docker run -d mon-conteneur-redis
