
 

# Blog Project

Un projet de blog complet utilisant le stack MERN (MongoDB, Express, React, Node.js). Ce projet permet de gérer des articles de blog avec une authentification utilisateur via JWT et un stockage d'images avec Cloudinary.

## Prérequis

- **MongoDB** : Installez MongoDB en local ou utilisez MongoDB Cloud. [Accéder au site de MongoDB](https://www.mongodb.com).
- **Cloudinary** : Créez un compte pour stocker les images. [Accéder au site de Cloudinary](https://cloudinary.com).

## Configuration

### Variables d'Environnement

Dans le dossier `backend`, créez un fichier `.env` et ajoutez les informations suivantes :

```plaintext
PORT=8000
MONGO_URI=your_mongodb_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name_from_cloudinary
CLOUDINARY_API_KEY=your_api_key_from_cloudinary
CLOUDINARY_API_SECRET=your_api_secret_from_cloudinary
APP_EMAIL_ADDRESS=your_email_service_for_sending_email
APP_EMAIL_PASSWORD=your_email_service_password
CLIENT_DOMAIN=http://localhost:3000

````
### Install BackEnd with npm

```bash
  cd backend
  npm install
```

### Install FrontEnd with npm


```bash
  cd FrontEnd
  npm install
```





