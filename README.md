data.php

Le fichier data.php agit comme une API côté serveur qui reçoit les données envoyées par l’ESP32.

Il récupère les données via une requête HTTP envoyée par l’ESP32
Il se connecte à une base de données 
Il enregistre les valeurs reçues
Il peut aussi vérifier une clé API pour sécuriser l’envoi des données

En résumé :
data.php sert à recevoir et stocker les données envoyées par l’ESP32.

Ce fonctionnement est typique des projets IoT où un microcontrôleur envoie des données vers un serveur web pour les stocker dans une base de données .

index.php

Le fichier index.php est la page web principale qui permet de visualiser les données.

Il se connecte à la base de données
Il récupère les données enregistrées par data.php
Il affiche les informations sous forme de tableau ou interface web
Il peut être consulté depuis un navigateur

En résumé :
index.php sert à afficher les données stockées dans la base de données.
