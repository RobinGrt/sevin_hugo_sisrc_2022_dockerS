## Projet API REACT Docker Hugo 

Ce tutoriel va vous expliquer commencer executer mon projet API Docker avec docker compose.

### Les Prérequis

- Soyez sur d'avoir docker et docker compose d'installé
  - Windows ou macOS:
    [Install Docker Desktop](https://www.docker.com/get-started)
  - Linux: [Install Docker](https://www.docker.com/get-started) and then
    [Docker Compose](https://github.com/docker/compose)
    
 - Telecharger mon repo
 
 ```console
gh repo clone bysnoozy/sevin_hugo_sisrc_2022_dockerS
```
   
### Executer le docker compose

Dans un premier temps nous allons executer la commande ci-dessous 
Qui permet de lancer le fichier `docker-compose.yml`

```console
docker-compose up -d
```
### Se connecter a l'API

Nous allons nous connecter sur le frontend de l'application
Depuis un navigateur web taper :


```console
http://localhost:3000
```
### Creation de compte et Connexion

Une fois connecté cliquer en haut a droite sur `Sign UP`

![image](https://user-images.githubusercontent.com/31020571/152686770-3b0d43cf-532f-4faa-9fdf-85b784608fac.png)

Ensuite nous allons nous connecter via le bouton `Login`

![image](https://user-images.githubusercontent.com/31020571/152686818-293975a7-639a-4917-bf69-07d57091969e.png)

### Creation de post

Cliquer sur `New Post`

![image](https://user-images.githubusercontent.com/31020571/152686977-925a7ab1-7774-44e9-840a-0666be5099a9.png)

### Arreter les conteneurs

```console
docker-compose stop
```
