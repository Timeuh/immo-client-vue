# immo-client-vue
Projet immo-client-vue.

## Installation
### Prérequis :
Avoir docker installé sur votre machine.


### 1. **Cloner le dépôt :**

Clonner le dépôt GitHub suivant dans le répertoire de votre choix :
````http request
   https://github.com/Timeuh/immo-client-vue
  ```` 
  
### 2. **Lancer le docker-compose :**
Si c'est la premiere fois que vous utiliser le projet, faire au préalable cette commande :
````bash
docker run --rm -v .:/app -w /app node:20-alpine npm install --loglevel=verbose
  ````
Puis 

Lancer la commande suivante à la racine du projet :
````bash
   docker-compose up -d
  ````   

### Optionnel :
Si vous avez un environnement différent de celui
par défaut, vous pouvez créer un fichier .env à la racine du projet 
et le configurer comme le fichier .env.example.


   
   


