# WOLF OTT CONFIG SERVER

## Description
Ce dépôt contient les fichiers de configuration centralisés pour tous les microservices du projet "WOLF OTT MANAGEMENT". Le serveur de configuration utilise Spring Cloud Config pour fournir des configurations dynamiques aux microservices suivants :

- `auth-service`
- `device-service`
- `discovery-server`
- `epg-service`
- `gateway-service`
- `line-service`
- `notification-service`
- `server-service`
- `stream-service`
- `ticketing-service`
- `user-service`

Les configurations sont écrites en format YAML et peuvent être modifiées à tout moment pour refléter les besoins en environnement de production, de développement, ou de test.

## Prérequis

- **JDK 17**
- **Maven 3.x**

Assurez-vous que ces dépendances sont installées sur votre machine.

## Structure des Fichiers

Chaque microservice possède son propre fichier de configuration au format YAML.
