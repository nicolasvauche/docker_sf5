# Docker & Symfony4  
Installation d'un environnement LAMP avec Docker et Symfony4.  

## Installation  

1. Cloner le dépôt Git :  
`$ git clone https://github.com/nicolasvauche/docker_sf4.git`  

2. Dupliquer le fichier `.env-sample` et le renommer en `.env` :  
`$ cd docker_sf4`  
`$ cp .env-sample .env`  
Modifier ce fichier en renseignant vos informations (ports et base de données)

3. Dupliquer le fichier `.bashrc-sample` et le renommer en `.bashrc` :  
`$ cp .bashrc-sample .bashrc`  

4. Monter les conteneurs Docker (MySQL, Adminer, PHP 7.4-apache) :  
`$ docker compose up`  

5. Ouvrir un autre onglet de votre terminal, et accéder à la console de votre conteneur principal :  
`$ docker exec -it [TODO]`