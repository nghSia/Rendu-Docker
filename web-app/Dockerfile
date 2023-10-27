# Utilisez une image de base Node.js
FROM node:12-alpine

# Créez un répertoire pour l'application dans le conteneur
WORKDIR /app

# Copiez les fichiers de l'application dans le conteneur
COPY . .

# Installez les dépendances de l'application
RUN npm install --production

# Exposez le port 3000
EXPOSE 3000

# Définissez la commande pour démarrer l'application
CMD ["node", "src/index.js"]