# Installation de laravel Grâce a Docker
Source : https://ianclemence.medium.com/setting-up-laravel-project-using-docker-step-by-step-guide-7c5720fbc2c8

## On install un Debian sur notre machine Windows grâce a WSL
```wsl --install -d Debian```
## On configure Debian par defaut
```wsl -s Debian```
## Il faut ensuite installer Docker pour Windows depuis leur site
---
## Un fois fait il faut se rendre dans le répertoire du projet et lancer la commande WSL
```wsl```
## On se retrouve donc dans une machine tournant sur debian. On va commencer par faire les mises à jour et installer curl
```sudo apt update && apt upgrade && apt install curl```
## On va ensuite crée le répertoire du projet grâce a la commande suivante
```curl -s https://laravel.build/ProjetLaravel | bash```
## On se rend dans le répertoire crée 
```cd ProjetLaravel```
## Et on active Sail
```./vendor/bin/sail up```
##
