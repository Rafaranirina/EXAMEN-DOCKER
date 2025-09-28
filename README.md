# EXAMEN-DOCKER
# INTRODUCTION

Avec l'utilisation de Docker 

la plate-forme Docker offre un haut degré de portabilité ,ce qui permet aux utilisateurs de s'enregistrement  et partager de conteneurs sur une  grande variéte d'hotes au sein d'environnement publics et privés .Il est alors possible de développer des aplications de façon plus efficiente,en utilisant moins de ressorces,et de déployer ces applications rapidement 

# jours 1

dockers ps
visualiser ou lister les conteneurs actifs
# docker ps
 Visualiser ou lister les conteneurs actifs

# docker ps -a
 Visualiser ou lister tous les conteneurs

# docker rm [conteneur]
Supprimer un conteneur inactif

# docker rm -f [conteneur]
 Supprimer un conteneur actif

# docker images
 Lister les images existantes

# docker rmi [image]
Supprimer une image

# docker exec -t -i [conteneur] /bin/bash
 Exécuter des commandes dans un conteneur actif

# docker inspect [conteneur]
Inspecter la configuration d’un conteneur

# docker build -t [image]
Construire une image à partir de Dockerfile

# docker history [image]
 Afficher l’historique d’une image

# docker  logs --tail 5[conteneur]
Visualiser les logs d'un conteneur 

# docker login
se connecter au registre

# docker search [image]
Récupérer une image


#  jours 2
# Evaluation Formative

#  Ou se stockés les volumes des Docker?
Vous dévez navigeur à :/var/lib/docker/volumes

#  un volume de Docker est:
* un espace de stockage connecté à un ou plusieurs conteneurs Docker
* Une image fonctionnelle à partir de laquelle on crée des conteneurs identiques
* Un snaphost de l'application que l'on deploie dans un cluster comme swarm 



# docker-compose up  
Lancer les conteneurs définis dans le fichier docker-compose.yml

# docker-compose down  
 Arrêter et supprimer les conteneurs, réseaux, volumes, et images créés par docker-compose up

# docker-compose build  
 Construire ou reconstruire les services définis dans le fichier docker-compose.yml

# docker-compose logs  
Afficher les logs des conteneurs gérés par docker-compose

# docker-compose logs --tail 5  
Afficher les 5 dernières lignes des logs des conteneurs

# docker-compose ps  
Lister les conteneurs gérés par docker-compose

# docker-compose stop  
Arrêter les conteneurs sans les supprimer

# docker-compose start  
Démarrer les conteneurs arrêtés

# docker-compose restart  
Redémarrer les conteneurs

# docker-compose exec [conteneur] bash  
Exécuter une commande dans un conteneur existant (mode interactif)

# docker-compose run [conteneur] bash  
Lancer un nouveau conteneur pour exécuter une commande

# docker-compose config  
Valider et afficher la configuration du fichier docker-compose.yml

# docker-compose top  
Afficher les processus en cours dans les conteneurs

# docker-compose kill  
Envoyer un signal SIGKILL aux conteneurs

# docker-compose pause  
Suspendre les conteneurs

# docker-compose unpause  
Reprendre les conteneurs suspendus

# docker-compose pull  
Télécharger les images définies dans le fichier docker-compose.yml

# docker-compose push  
Envoyer les images vers un registre

# docker-compose rm  
Supprimer les conteneurs arrêtés

# docker-compose scale  
Définir le nombre d’instances d’un service

# docker-compose version  
Afficher la version de Docker Compose


# JOURS 3

# docker-compose up -d  
Démarrer un ensemble de conteneur en arrière plan

# docker-compose down  
Stoppe un ensemble de conteneur

# docker-compose exec [service] [command]  
Exécute une commande au sein d’un service

# docker-compose logs (<ID>/<NAME>)  
Voir les logs d’un conteneur uniquement, au lieu de tous

# docker-compose stop  
Arrête tous les services situés dans votre docker-compose.yml sans supprimer

# docker-compose start  
Démarre tous les services situés dans votre fichier docker-compose.yml

# docker-compose pause  
Met en pause les conteneurs dans un service répertorié dans le fichier

# docker-compose unpause  
Reprend les conteneurs en pause dans un service

# docker-compose restart  
Redémarre tous les conteneurs d’un service

# docker-compose rm  
Supprime les conteneurs arrêtés dans un fichier

# docker-compose pull  
Télécharge uniquement les images à partir du docker-compose.yml

# docker-compose build  
Construit uniquement les images à partir du docker-compose.yml

# docker-compose ps  
Affiche la liste des conteneurs déployés

# docker-compose images  
Enumère toutes les images

# docker-compose top  
Affiche l’utilisation des conteneurs déployés à partir du fichier

# docker-compose config  
Visualise et valide un fichier docker-compose.yml


jour 4







