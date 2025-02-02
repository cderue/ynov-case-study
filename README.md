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

## User Stories

Voici un ensemble de **User Stories** pour un **système de réservation d’espace de travail** dans une startup de location de bureaux pour le coworking.

---
 
- **US001 - Réserver un espace de travail**  
  > En tant qu'**utilisateur**, je veux pouvoir **réserver un espace de travail** pour une période donnée afin de m'assurer d'avoir un bureau disponible.  

- **US002 - Modifier ou annuler une réservation**  
  > En tant qu'**utilisateur**, je veux pouvoir **modifier ou annuler ma réservation** afin d'ajuster mes besoins en fonction de mon emploi du temps.  

- **US003 - Voir les disponibilités en temps réel**  
  > En tant qu'**utilisateur**, je veux pouvoir **consulter en temps réel la disponibilité des espaces de travail** afin de choisir un créneau adapté.  

- **US004 - Recevoir une confirmation de réservation**  
  > En tant qu'**utilisateur**, je veux recevoir un **email/SMS de confirmation** après ma réservation afin d’avoir une preuve et les détails de ma réservation.  

- **US005 - Réserver un espace de travail récurrent**  
  > En tant qu'**utilisateur**, je veux pouvoir **réserver un espace sur une base récurrente** (quotidienne, hebdomadaire, mensuelle) afin de sécuriser mon bureau pour une période prolongée.  

- **US006 - Vérifier l’historique des réservations**  
  > En tant qu'**utilisateur**, je veux pouvoir **voir l'historique de mes réservations passées et à venir** afin de mieux organiser mon planning.  

- **US007 - Ajouter ou modifier des salles et équipements**  
  > En tant qu'**administrateur**, je veux pouvoir **ajouter, modifier ou supprimer des salles et équipements** afin de mettre à jour l'offre disponible pour les clients.  

- **US008 - Filtrer les espaces par équipements**  
  > En tant qu'**utilisateur**, je veux pouvoir **rechercher des espaces en fonction des équipements disponibles** (écran, projecteur, imprimante, etc.) afin de trouver un espace adapté à mes besoins.  

- **US009 - Vérifier l’état et la disponibilité des équipements**  
  > En tant qu'**administrateur**, je veux pouvoir **suivre l’état et la disponibilité des équipements** pour assurer leur bon fonctionnement et anticiper les réparations.  
 
- **US010 - Effectuer un paiement en ligne**  
  > En tant qu'**utilisateur**, je veux pouvoir **payer ma réservation en ligne** par carte bancaire ou autres moyens de paiement afin de garantir ma réservation.  

- **US011 - Recevoir une facture après paiement**  
  > En tant qu'**utilisateur**, je veux recevoir une **facture détaillée après chaque paiement** afin d’avoir une preuve pour ma comptabilité.  

- **US012 - Gérer les abonnements**  
  > En tant qu'**utilisateur**, je veux pouvoir **souscrire à un abonnement mensuel ou annuel** pour bénéficier d’un accès régulier aux espaces de travail et simplifier ma facturation.  

- **US013 - Gérer les réductions et codes promo**  
  > En tant qu'**administrateur**, je veux pouvoir **créer et gérer des réductions et codes promo** afin d’attirer plus d’utilisateurs et fidéliser la clientèle.  

- **US014 - Suivi des paiements et relances en cas d’impayés**  
  > En tant qu'**administrateur**, je veux pouvoir **suivre les paiements en attente et envoyer des relances** en cas d’impayés afin d’assurer la gestion financière du service.  
 
- **US015 - Accéder au coworking via un QR Code ou badge**  
  > En tant qu'**utilisateur**, je veux pouvoir **accéder à l’espace réservé via un QR Code ou un badge** afin de simplifier mon entrée et éviter les attentes.  

- **US016 - Laisser un avis sur une salle ou un équipement**  
  > En tant qu'**utilisateur**, je veux pouvoir **laisser un avis et une note** sur les espaces et équipements utilisés afin d’aider les autres utilisateurs à choisir et d’améliorer le service.  

- **US017 - Notifier les utilisateurs en cas de problème ou d’indisponibilité**  
  > En tant qu'**administrateur**, je veux pouvoir **notifier les utilisateurs en cas d’annulation, de problème technique ou d’indisponibilité** afin de leur proposer une solution alternative.  

- **US018 - Générer des rapports et statistiques**  
  > En tant qu'**administrateur**, je veux pouvoir **générer des rapports d’utilisation des espaces et équipements** afin d’optimiser la gestion des ressources et améliorer l’expérience client.  

---

Ce backlog de **User Stories** permet de cadrer les fonctionnalités du **système de réservation** et de prioriser le développement. Besoin d’ajouter d’autres fonctionnalités spécifiques ? 😊
