# DS Delivery 
[![NPM](https://img.shields.io/npm/l/react)]( https://github.com/erickvrezende/dsdeliver-sds2/blob/main/LICENSE) 

# À propos du projet

https://sds2-erick.netlify.app

DS Delivery est une application full stack web et mobile créée pendant la 2ère édition de la **Semaine DevSuperior** (#sds2), événement organisé par [DevSuperior](https://devsuperior.com.br "Le site de DevSuperior").

L'application consiste en un système d'enregistrement et de livraison des commandes alimentaires, où les commandes sont passées dans l'application web, puis elles sont listées pour la livraison dans l'application mobile, qui utilise également la carte pour générer l'itinéraire du livreur au client.

## Layout mobile
![Mobile 1]( https://github.com/erickvrezende/assets/blob/main/raw/main/sds2/mobile1.png) ![Mobile 2]( https://github.com/erickvrezende/assets/blob/main/raw/main/sds2/mobile2.png) ![Mobile 3]( https://github.com/erickvrezende/assets/blob/main/raw/main/sds2/mobile3.png)

## Layout web
![Web 1](https://github.com/erickvrezende/assets/blob/main/raw/main/sds2/web1.png)

![Web 2](https://github.com/erickvrezende/assets/blob/main/raw/main/sds2/web2.png)

## Modèle conceptuel
![Modelo Conceitual](https://github.com/erickvrezende/assets/blob/main/raw/main/sds2/modelo-conceitual.png)

# Technologies utilisées 
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Leaflet
- Expo
## Mise en œuvre dans la production
- Back end: Heroku
- Front end web: Netlify
- Base de données: Postgresql

# Comment exécuter le projet

## Back end
Pré-requis: Java 11

```bash
# cloner le répertoire
git clone https://github.com/erickvrezende/dsdeliver-sds2.git

# entrer dans le dossier du projet back end
cd backend

# exécuter le projet
./mvnw spring-boot:run
```

## Front end web
Pré-requis: npm / yarn

```bash
# cloner le répertoire
git clone https://github.com/erickvrezende/dsdeliver-sds2.git

# entrer dans le dossier du projet front end web
cd front-web

# installer les dépendances
npm install

# exécuter le projet
npm start
```

# Auteur

Erick Vieira Rezende

https://www.linkedin.com/in/erick-vieira-rezende-573866118/?locale=fr_FR

