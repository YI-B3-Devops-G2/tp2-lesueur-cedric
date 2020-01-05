# B3 Devops - TP 2
## Info
mail: cedric.lesueur@ynov.com

github​_username: cedro23

## Objectif

Le but du TP est d'avoir un reverse proxy géré à l'aide de Nginx qui oriente soit sur la page principale
de Nginx, soit sur la réponse de base d'une API, soit sur une réponse spécifique de la même API.

## Prérequis

- Docker & Docker Compose
- Powershell

## Installation

Après avoir cloner le repo, il suffit d'aller à la racine du répertoire du projet et de lancer la commande 
`docker-compose -f ./docker-compose.dev.yaml up --build --force-recreate`

## Routes

`localhost:3000` &rarr; Page de base de Nginx

`localhost:3000/api` &rarr; Page de base de l'API

`localhost:3000/api/status` &rarr; Page spécifique de l'API

## Complications

J'ai découvert Docker lors de ce projet et du précédant. J'ai eu du mal à comprendre le système de fonctionnement des fichiers Dockerfile et docker-compose, mais avec un peu de recherche et d'aide j'ai réussi à atteindre l'objectif voulu.