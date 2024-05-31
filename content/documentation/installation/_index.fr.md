---
title: Installation de Vigilo
weight: 2
---

## Installation du back-end

Les parties communs pour toutes les installations sont que l'appli android et l'appli web.
Les deux sont configurés par les utilisateurs pour se connecter au backend de leur association.

Une fois chargé du serveur et la région selectionnée, le site web ne communique qu'avec le backend hébergé sur le serveur de l'association qui gère les données pour cette région.
De même pour l'application Android, elle est configurée pour se connecter au backend de l'association.

Il est donc a vous en tant qua association d'héberger votre backend pour votre région.
Cela comporte les APIs pour l'application Android et le site web (comme par exemple [`get_issues.php`](/fr/api/#récupération-liste-observations)) ainsi que les pages d'administration comme `/admin/index.php`.
En resultat, toutes les données sont stockées sur votre serveur et il est de votre responsabilité de les protéger.

Le backend qui peut être installé de deux manières possibles.


### Serveur dédié avec Docker :

Le serveur dédié offre plus de souplesse, et permet d'heberger également d'autres applications.
Il necessite en outre plus de compétences en informatique pour l'installation ainsi que la maintenabilité.

[La procédure est disponible ici](/fr/documentation/installation/installation_dedie/)

### Hebergement mutualisé PHP/MySQL :

L'hebergement mutualisé est une solution plus accessible en terme de connaissances informatiques, mais il est possible que des problèmes de compatibilité soient constatés avec l'application.

[La procédure est disponible ici](/fr/documentation/installation/installation_mutualise/)

