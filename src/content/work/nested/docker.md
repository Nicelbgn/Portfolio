---
title: Docker
publishDate: 2024-19-01 00:00:00
img: /assets/image-docker.png
img_alt: projet docker
description: |
  L'objectif principal de Docker est de simplifier le déploiement et la gestion des applications en utilisant la virtualisation légère sous forme de conteneurs
tags:
  - Base de données
  - Docker Compose
  - Oracle VM VirtualBox


---
# Objectif 

L'objectif du projet est de mettre en place un front-end en Python pour collecter les votes, un front-end en JavaScript pour afficher les résultats, une base de données Redis pour stocker temporairement les votes du front-end Python, une base de données PostgreSQL pour stocker de manière permanente les votes afin de les afficher sur le front-end JavaScript, et enfin, un worker qui transférera les votes de la base de données Redis vers la base de données PostgreSQL.

Qu'est-ce que DOCKER?

Conteneurs : Les conteneurs sont des unités d'exécution légères et autonomes qui encapsulent le code, les dépendances et les configurations nécessaires à l'exécution d'une application. Ils reposent sur des images Docker, des instantanés préconfigurés de systèmes de fichiers contenant le logiciel requis.

Images : Une image Docker est un modèle immuable utilisé pour créer des conteneurs. Elle inclut le système de fichiers de base, le code source, les dépendances, les variables d'environnement et les configurations nécessaires à l'exécution d'une application.

Dockerfile : Un Dockerfile est un script texte définissant les étapes pour créer une image Docker. Il spécifie la base de l'image, les dépendances à installer, les configurations à appliquer, et d'autres instructions nécessaires à la construction d'une image.

Orchestration : Docker propose des outils d'orchestration tels que Docker Compose et Kubernetes, simplifiant la gestion, le déploiement et la mise à l'échelle d'applications composées de plusieurs conteneurs.

Registre Docker : Un registre Docker est un service stockant et distribuant des images Docker. Docker Hub est le registre public par défaut, mais l'utilisation de registres privés pour stocker vos propres images est également possible.

CLI (Interface en Ligne de Commande) : Docker offre une interface en ligne de commande permettant aux utilisateurs d'interagir avec les conteneurs, les images, les réseaux et d'autres composants de l'environnement Docker.

Docker
Docker simplifie le développement, le déploiement et la gestion des applications en résolvant les problèmes liés aux différences d'environnement entre les développeurs, les systèmes de test et de production.

Je vous invite à consulter mon GitHub pour obtenir une vision détaillée de mon projet.