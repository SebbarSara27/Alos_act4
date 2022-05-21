# Alos_act4

**Ce tp présente principalement comment utiliser docker pour déployer des projets de séparation front-end et back-end , organiser des images via l'outil de composition docker, créer des conteneurs basés sur des images, et déployer des applications dans des conteneurs.**
## Structure du fichier :
> Backend :  qui va reprendre le backend  du projet
> 
> Frontend : qui va reprendre le fronkend  du projet .
 
### Dockerfile :
Le fichier de configuration Dockerfile. Configure un conteneur Docker lorsque vous l'exécutez docker build. Largement préférable à docker commit.

### Docker-compose :
Compose est un outil permettant de définir et d'exécuter des applications Docker multi-conteneurs. Avec Compose, vous utilisez un fichier YAML pour configurer les services de votre application. Ensuite, avec une seule commande, vous créez et démarrez tous les services de votre configuration.
En utilisant la commande suivante, vous pouvez démarrer votre application :
```
docker-compose -f <docker-compose-file> up
```
Vous pouvez également exécuter docker-compose en mode détaché à l'aide de l'indicateur -d, puis vous pouvez l'arrêter chaque fois que nécessaire avec la commande suivante :
```
docker-compose stop
```
