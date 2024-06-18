---
title: Politique de confidentialité
description: "La présente Politique de Confidentialité encadre l'utilisation et la protection des données personnelles des services de Chill Utility, incluant son site internet et l'application sur la plateforme Discord (Discord Inc.)."
layout: simple
slug: 'politique-confidentialite'
---

{{< lead >}}
La présente Politique de Confidentialité encadre l'utilisation et la protection des données personnelles des services de Chill Utility, incluant son site internet et l'application sur la plateforme Discord (Discord Inc.).

Cette politique constitue l'accord contractuel régissant la collecte, l'utilisation et la protection des informations personnelles des « Utilisateurs », qui accèdent aux services proposés par Chill Utility par le biais du site internet ou de l'application. En utilisant nos services, vous consentez expressément à la collecte, à l'utilisation et à la divulgation de vos informations conformément à cette Politique de Confidentialité.
{{< /lead >}}

## Gestion des Données Personnelles (avant-propos)

Des détails complets sur chaque type de données personnelles collectées sont fournis dans les sections dédiées de cette politique de confidentialité. Les données personnelles peuvent être librement fournies par l'Utilisateur ou, dans le cas des données d'utilisation, collectées automatiquement lors de l'utilisation de l'application.

Dans les cas où l'application précise expressément que certaines données ne sont pas obligatoires, les Utilisateurs sont libres de ne pas communiquer ces données sans conséquences sur la disponibilité ou le fonctionnement du service.

Les Utilisateurs qui ne savent pas quelles données personnelles sont obligatoires sont invités à contacter le propriétaire. Toute utilisation d'outils de suivi – par l'application ou par les propriétaires de services tiers utilisés servent à fournir le service requis par l'Utilisateur.

Les Utilisateurs sont responsables de toutes les données personnelles de tiers obtenues, publiées ou partagées via l'application et confirment qu’ils ont le consentement du tiers pour fournir les données au propriétaire.

## Informations détaillées sur le traitement des données personnelles

### Site

Le site internet ne récolte aucune donnée personnelle à l'heure actuelle.  
Il s'agit d'un site vitrine, dont le fonctionnement ne dépend d'aucun cookie ni d'aucun outil de suivi.  
Tout changement éventuel sera indiqué dans une mise à jour de la présente Politique de Confidentialité.

L'intégralité du code source du site est disponible à cette adresse : https://github.com/chill-utility/chill-utility.github.io

### Application

#### Données persistées dans la base de données de Chill Utility

- Compteur
  - Progression du compteur
  - ID du serveur Discord rattaché à la progression du compteur
- Commande `/config`
  - Données saisies dans les commandes et menus de configuration
- Serveurs Discord
  - Langue préférée (configuration des serveurs)
  - ID des serveurs
  - Nombre de membres des serveurs
- Modération
  - IDs des serveurs Discord attachés aux commandes de modération 
  - IDs des utilisateurs Discord saisis dans les commandes et menus de modération
  - IDs des utilisateurs Discord ayant lancé les actions de modération
  - Raisons des actions de modération précisées dans les commandes et menus de modération

#### Intents

{{< alert "circle-info" >}}
Les intents Discord sont des règles qui expliquent à Discord quels types de contenus et actions l'application peut voir et utiliser.
{{< /alert >}}

| Intent           | Cas d'utilisation                                                                                                                              |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| Guild Members    | Commandes de modération et statistiques des membres                                                                                            |
| Message Content  | Mini-jeu du compteur (besoin de lire les messages des utilisateurs pour le déroulement du jeu)                                                 |
| Guilds           | Informations sur les serveurs Discord (comme la langue préférée de chaque serveur ainsi que leur nom)                                          |
| Guild Presences  | Fonctionnalité _Vanity_ (permet d'observer le statut des membres afin de leur donner un rôle s'ils contiennent un contenu en particulier       |
| Guild Moderation | Utilisée pour les bannissements et les exclusions (pour détecter si un membre est déjà sanctionné et pour gérer les bannissements temporaires) |

[Pour plus d'informations techniques, vous pouvez vous référer à la page dédiée de Discord sur les _Gateway Intents_.](https://discord.com/developers/docs/topics/gateway#gateway-intents)

---

Dernière mise à jour de la présente politique de confidentialité le : mardi 18 juin 2024.
