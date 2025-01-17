# Etude de cas : Système de réservation de salles de réunion - SmartMeet

## Contexte

Une entreprise de conseil de 500 employés souhaite optimiser l'utilisation de ses salles de réunion réparties sur 3 sites.

## Besoins fonctionnels :

- Les employés doivent pouvoir réserver une salle depuis leur ordinateur ou smartphone
- Le système doit afficher la disponibilité en temps réel
- Les réservations récurrentes doivent être possibles
- Le système doit gérer les équipements disponibles (vidéoprojecteur, visioconférence...)
- Envoi automatique d'invitations par email aux participants
- Notification 10 minutes avant le début de la réunion

## Contraintes techniques :

- Intégration avec M365 Outlook pour la gestion des calendriers
- Authentification via Microsoft Entra ID existant
- Application web responsive et application mobile native (iOS/Android)
- Installation de tablettes Android à l'entrée de chaque salle

## Points d'attention :

- Gestion des conflits de réservation
- Performance pour l'affichage temps réel
- Facilité d'utilisation sur mobile
