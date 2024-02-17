Ce projet utilise Docker pour créer un environnement WordPress avec Nginx comme>

## Prérequis

Assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Étapes

1. **Cloner le dépôt Git :**

   ```bash
   git clone <URL_DU_REPO>
   cd wordpress-sites
## Configuration
cp .env.example .env
nano .env  



2. ** Démarrer les service ***

docker-compose up -d
 3. *** Accéder à WordPress ***

 Ouvrez votre navigateur et accédez à http://localhost:8085