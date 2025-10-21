# Backlog du projet

## Liste des tâches par User Story

--- 

#### US1 : Création de Compte
**Tâches associées (4) :**
- [ ] T1.1 : Concevoir le schéma de base de données pour les utilisateurs - 1 point
- [ ] T1.2 : Développer l'API de création de compte - 1 point
- [ ] T1.3 : Implémenter la validation des données utilisateur client/serveur - 1 point
- [ ] T1.4 : Créer le formulaire d'inscription front-end - 1 point

---

#### US2 : Connexion au Compte
**Tâches associées (4) :**
- [ ] T2.1 : Implémenter l'authentification JWT - 2 points
- [ ] T2.2 : Implémenter l'API de connexion (POST /auth/login) - 1 point
- [ ] T2.3 : Créer le formulaire de connexion front-end - 1 point

---
#### US3 : Gestion de Profil
**Tâches associées (3) :**
- [ ] T3.1 : Développer l'API de gestion de profil (GET/PUT /user/profile) - 1 point
- [ ] T3.2 : Interface de modification du profil utilisateur (formulaire front-end) - 1 point
- [ ] T3.3 : Implémenter la fonctionnalité de changement de mot de passe - 1 point

---
#### US4 : Création de Projet
**Tâches associées (3) :**
- [ ] T4.1 : Développer l'API de création de projet (POST /projects) - 1 point
- [ ] T4.2 : Concevoir la base de données pour les projets - 1 point
- [ ] T4.3 : Créer l'interface front-end pour la création de projet - 1 point

---
#### US5 : Gestion de Projet
**Tâches associées (5) :**
- [ ] T5.1 : Développer l'API de gestion des membres du projet (POST/DELETE /projects/:id/members) - 2 points
- [ ] T5.2 : Implémenter les paramètres de projet (PUT /projects/:id/settings) - 1 point
- [ ] T5.3 : Créer l'interface front-end pour la gestion des membres - 1 point
- [ ] T5.4 : Créer l'interface front-end pour les paramètres du projet - 1 point
- [ ] T5.5 : Mettre en place les contrôles d'accès basés sur les rôles - 1 point

---
#### US6 : Sauvegarde des Données
**Tâches associées (4) :**
- [ ] T6.1 : Créer la base de données de sauvegarde - 1 point
- [ ] T6.2 : Implémenter la fonctionnalité de sauvegarde automatique côté serveur - 2 points
- [ ] T6.3 : Implémenter la restauration des données automatique - 1 point

---
#### US7 : Création d'une Issue
**Tâches associées (2) :**
- [ ] T7.1 : Développer l'API de création d'issue (POST /projects/:id/issues), une issue est composée d'un titre, d'une description et d'une priorité - 1 point
- [ ] T7.2 : Créer le formulaire de création d'issue (front-end) - 1 point

---
#### US8 : Assignation d'une Issue
**Tâches associées (2) :**
- [ ] T8.1 : Développer l'API d'assignation d'issue (PUT /projects/:id/issues/:issueId/assign) - 1 point
- [ ] T8.2 : Créer le formulaire d'assignation d'issue (front-end) - 1 point

---
#### US9 : Modification du Statut d'une Issue
**Tâches associées (2) :**
- [ ] T9.1 : Développer l'API de modification du statut d'issue (PUT /projects/:id/issues/:issueId/status) - 1 point
- [ ] T9.2 : Créer l'interface front-end pour changer le statut (dropdown/boutons) - 1 point

---
#### US10 : Création de Tâches
**Tâches associées (2) :**
- [ ] T10.1 : Développer l'API de création de tâches liées aux issues (POST /projects/:id/issues/:issueId/tasks) - 1 point
- [ ] T10.2 : Créer le formulaire de création de tâches (front-end) - 1 point

---
#### US11 : Visualisation du Backlog
**Tâches associées (3) :**
- [ ] T11.1 : Développer l'API de récupération du backlog (GET /projects/:id/backlog) - 1 point
- [ ] T11.2 : Créer la vue liste du backlog (front-end) - 1 point
- [ ] T11.3 : Implémenter les filtres et tri du backlog - 1 point

---
#### US12 : Visualisation des Tâches (Kanban/Liste)
**Tâches associées (2) :**
- [ ] T12.1 : Créer la vue Kanban pour les tâches (front-end) - 1 point
- [ ] T12.2 : Implémenter le toggle entre vue Kanban et vue liste - 1 point

---
#### US13 : Vue des Tâches Assignées
**Tâches associées (2) :**
- [ ] T13.1 : Développer l'API pour récupérer les tâches assignées à un utilisateur (GET /users/me/tasks) - 1 point
- [ ] T13.2 : Créer le dashboard personnel des tâches assignées (front-end) - 1 point

---
#### US14 : Suivi du Temps
**Tâches associées (2) :**
- [ ] T14.1 : Ajouter les champs de temps estimé/passé à la base de données et API (PUT /tasks/:id/time) - 1 point
- [ ] T14.2 : Créer l'interface de saisie du temps (front-end) - 1 point

---
#### US15 : Création de Tags et Releases
**Tâches associées (2) :**
- [ ] T15.1 : Développer l'API de création de releases (POST /projects/:id/releases) - 1 point
- [ ] T15.2 : Créer l'interface de création de release/tag (front-end) - 1 point

---
#### US16 : Historique des Releases
**Tâches associées (2) :**
- [ ] T16.1 : Développer l'API d'historique des releases (GET /projects/:id/releases) - 1 point
- [ ] T16.2 : Créer la vue timeline des releases (front-end) - 1 point

---
#### US17 : Création de Cas de Test
**Tâches associées (2) :**
- [ ] T17.1 : Développer l'API de création de cas de test (POST /projects/:id/test-cases) - 1 point
- [ ] T17.2 : Créer le formulaire de création de cas de test (front-end) - 1 point

---
#### US18 : Exécution d'un Cas de Test
**Tâches associées (2) :**
- [ ] T18.1 : Développer l'API d'exécution de test (POST /test-cases/:id/execute) - 1 point
- [ ] T18.2 : Créer l'interface d'exécution et mise à jour des résultats (front-end) - 1 point

---
#### US19 : Tableau de Bord des Tests
**Tâches associées (2) :**
- [ ] T19.1 : Développer l'API des statistiques de tests (GET /projects/:id/test-dashboard) - 1 point
- [ ] T19.2 : Créer le dashboard des tests avec graphiques (front-end) - 1 point

---
#### US20 : Création et Édition de Documentation
**Tâches associées (2) :**
- [ ] T20.1 : Développer l'API CRUD pour la documentation (POST/PUT/GET/DELETE /projects/:id/docs) - 1 point
- [ ] T20.2 : Créer l'éditeur Markdown pour la documentation (front-end) - 1 point

---
#### US21 : Organisation de la Documentation
**Tâches associées (2) :**
- [ ] T21.1 : Implémenter le système de catégories/sections pour la documentation (base de données + API) - 1 point
- [ ] T21.2 : Créer la navigation arborescente de la documentation (front-end) - 1 point

---
#### US22 : Liaison Documentation et Issues
**Tâches associées (2) :**
- [ ] T22.1 : Développer l'API de liaison documentation-issues (POST /docs/:id/link-issue) - 1 point
- [ ] T22.2 : Créer l'interface de liaison dans l'éditeur de documentation (front-end) - 1 point

--- 

## Planification des Sprints

### Sprint 1 (25/10 au 05/11)

**Objectifs :**
- Permettre aux utilisateurs de créer un compte et se connecter.
- Permettre la création de base d'un projet.

**Tâches prévues :**

#### US1 : Création de Compte
- T1.1 : Concevoir le schéma de base de données pour les utilisateurs — 1 pt  
- T1.2 : Développer l'API de création de compte — 1 pt  
- T1.3 : Implémenter la validation des données utilisateur client/serveur — 1 pt  
- T1.4 : Créer le formulaire d'inscription front-end — 1 pt  

#### US2 : Connexion au Compte
- T2.1 : Implémenter l'authentification JWT — 2 pts  
- T2.2 : Implémenter l'API de connexion — 1 pt  
- T2.3 : Créer le formulaire de connexion front-end — 1 pt  

#### US4 : Création de Projet
- T4.1 : Développer l'API de création de projet — 1 pt  
- T4.2 : Concevoir la base de données pour les projets — 1 pt  
- T4.3 : Créer l'interface front-end pour la création de projet — 1 pt  


**Répartition des tâches :**


**Coût total du Sprint :**
10 points

### Sprint 2 (06/11 au 19/11)

**Objectifs :**
- Permettre la gestion du profil utilisateur (édition et mot de passe).  
- Gérer la structure et les membres d’un projet.  
- Mettre en place la sauvegarde automatique des données. 

**Tâches prévues :**

#### US3 : Gestion de Profil
- T3.1 : Développer l'API de gestion de profil — 1 pt  
- T3.2 : Interface de modification du profil utilisateur — 1 pt  
- T3.3 : Changement de mot de passe — 1 pt  

#### US5 : Gestion de Projet
- T5.1 : Développer l'API de gestion des membres — 2 pts  
- T5.2 : Implémenter les paramètres de projet — 1 pt  
- T5.3 : Créer l'interface front-end pour la gestion des membres — 1 pt  
- T5.4 : Créer l'interface front-end pour les paramètres du projet — 1 pt  
- T5.5 : Contrôles d'accès basés sur les rôles — 1 pt  

#### US6 : Sauvegarde des Données
- T6.1 : Créer la base de données de sauvegarde — 1 pt  
- T6.2 : Implémenter la sauvegarde automatique — 2 pts  
- T6.3 : Implémenter la restauration automatique — 1 pt  

### Coût total du Sprint 2 : **13 points**


### Sprint 3 (20/11 au 03/12)

**Objectifs :**


**Tâches prévues :**

- Gestion des issues, tâches et backlog.  
- Visualisation, suivi, releases, tests et documentation.  

#### US7 à US10 : Issues et Tâches
- T7.1 / T7.2 — 2 pts  
- T8.1 / T8.2 — 2 pts  
- T9.1 / T9.2 — 2 pts  
- T10.1 / T10.2 — 2 pts  

#### US11 à US14 : Backlog, Kanban, Assignations, Temps
- T11.1 / T11.2 / T11.3 — 3 pts  
- T12.1 / T12.2 — 2 pts  
- T13.1 / T13.2 — 2 pts  
- T14.1 / T14.2 — 2 pts  

#### US15 à US22 : Releases, Tests, Documentation
- T15.1 / T15.2 — 2 pts  
- T16.1 / T16.2 — 2 pts  
- T17.1 / T17.2 — 2 pts  
- T18.1 / T18.2 — 2 pts  
- T19.1 / T19.2 — 2 pts  
- T20.1 / T20.2 — 2 pts  
- T21.1 / T21.2 — 2 pts  
- T22.1 / T22.2 — 2 pts  

**Coût total du Sprint 3 :** **27 points**


