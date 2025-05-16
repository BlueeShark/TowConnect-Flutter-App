# TowConnect - Application de Dépannage de Véhicules

## Présentation du Projet

TowConnect est une application mobile développée avec Flutter qui met en relation des conducteurs en difficulté avec des dépanneurs professionnels. L'application offre une solution complète pour la gestion des demandes de dépannage en temps réel, avec des fonctionnalités de géolocalisation, de suivi en direct, et de paiement sécurisé.

![Logo de TowConnect](assets/images/logo.png)

## Fonctionnalités Principales

### Pour les Conducteurs
- **Demande de Dépannage d'Urgence** : Envoi rapide d'une demande avec photo du véhicule et géolocalisation précise
- **Suivi en Temps Réel** : Visualisation de la position du dépanneur et estimation du temps d'arrivée
- **Historique des Demandes** : Consultation de l'historique des interventions passées
- **Système de Paiement Intégré** : Règlement sécurisé directement via l'application
- **Notifications Push** : Alertes en temps réel sur l'état de la demande

### Pour les Mécaniciens/Dépanneurs
- **Tableau de Bord des Demandes** : Vue d'ensemble des demandes à proximité
- **Gestion des Interventions** : Acceptation et suivi des demandes de dépannage
- **Navigation GPS Intégrée** : Itinéraire optimisé vers le lieu de l'intervention
- **Profil Professionnel** : Mise en avant des compétences, tarifs et évaluations
- **Historique et Statistiques** : Suivi de l'activité et des performances

### Autres Fonctionnalités
- **Authentification Sécurisée** : Connexion par numéro de téléphone et OTP
- **Multi-langue** : Application disponible en français, anglais, espagnol et arabe
- **Mode Hors-ligne** : Fonctionnalités de base accessibles même sans connexion internet
- **Interface Intuitive** : Design épuré et navigation simplifiée pour une expérience utilisateur optimale

## Technologies Utilisées

### Frontend
- **Flutter** : Framework de développement cross-platform
- **Provider** : Gestion d'état et architecture MVVM
- **Google Maps** : Intégration cartographique et navigation
- **Material Design** : Interface utilisateur moderne et responsive

### Backend & Services
- **Firebase Authentication** : Gestion sécurisée des utilisateurs
- **Cloud Firestore** : Base de données NoSQL en temps réel
- **Firebase Storage** : Stockage des images de véhicules
- **Firebase Cloud Messaging** : Notifications push en temps réel
- **Firebase Cloud Functions** : Traitement backend serverless

### Intégrations API
- **Google Maps Platform** : Géocodage, calcul d'itinéraires et distances
- **Firebase MLKit** : Reconnaissance d'images (pour l'analyse des véhicules)
- **Système de paiement** : Intégration future prévue (Stripe)

### Outils de Développement
- **Git** : Gestion de versions
- **Flutter SDK** : Environnement de développement Flutter
- **Dart DevTools** : Débogage et analyse de performances
- **Flutter Lints** : Maintien de la qualité du code

## Architecture du Projet

L'application est structurée selon l'architecture MVVM (Model-View-ViewModel) avec une séparation claire des responsabilités :

- **Models** : Représentation des données (utilisateurs, demandes, véhicules)
- **Views/Screens** : Interface utilisateur et composants d'affichage
- **Providers** : Gestion de l'état et logique métier
- **Services** : Interaction avec les APIs et services externes
- **Utils** : Fonctions utilitaires et helpers

## Captures d'Écran

[Section à compléter avec des captures d'écran de l'application]

## Licence

© 2023 TowConnect - Tous droits réservés
