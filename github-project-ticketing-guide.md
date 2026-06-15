# Gestion des tickets GitHub Projects

## Objectif

L'objectif du ticketing est de :
- Centraliser les demandes et les problèmes.
- Prioriser le travail de l'équipe.
- Faciliter le suivi de l'avancement.
- Conserver un historique des décisions et des corrections.
- Améliorer la communication entre les équipes métier et techniques.

---

# Types de tickets

## Feature

Une Feature correspond à une nouvelle fonctionnalité ou une évolution métier.

### Exemples
- Ajout de l'authentification SSO
- Création d'un tableau de bord
- Export des données au format Excel

## Bug

Un Bug correspond à un comportement incorrect ou inattendu du système.

### Exemples
- Impossible de se connecter avec un compte valide
- Erreur 500 lors de la création d'un utilisateur
- Mauvais calcul d'un montant

## Task / Technique

Une Task représente une activité technique sans impact fonctionnel direct.

### Exemples
- Mise à jour d'une dépendance
- Refactoring d'un module
- Ajout de tests automatisés

---

# Structure d'un ticket

## Titre

Format recommandé :

- [FEATURE] Ajouter l'export CSV des utilisateurs
- [BUG] Erreur lors de la suppression d'un projet

## Description

### Pour une Feature

#### Contexte
Pourquoi cette fonctionnalité est-elle nécessaire ?

#### Description
Que doit faire la fonctionnalité ?

#### Critères d'acceptation
- Condition 1
- Condition 2
- Condition 3

### Pour un Bug

#### Description du problème
Décrire le comportement observé.

#### Étapes de reproduction
1. Étape 1
2. Étape 2
3. Étape 3

#### Résultat attendu
Comportement attendu.

#### Résultat observé
Comportement actuel.

---

# Labels

## Type
- feature
- bug
- task
- documentation
- enhancement

## Priorité
- priority:critical
- priority:high
- priority:medium
- priority:low

## Domaine
- frontend
- backend
- api
- database
- security
- infrastructure
- ci-cd

## Statut
- ready
- in-progress
- review
- blocked
- done

---

# Gestion des fixes

## Branche

- feature/123-export-csv
- bugfix/456-fix-delete-project
- task/789-update-dependencies

## Pull Request

Référencer le ticket :

Fixes #123

ou

Closes #123

---

# Definition of Done

Un ticket est terminé lorsque :

- Le développement est terminé.
- Les critères d'acceptation sont respectés.
- Les tests passent.
- La revue de code est validée.
- La Pull Request est mergée.
- Le ticket est fermé.

---

# Workflow recommandé

Backlog → Ready → In Progress → Code Review → Testing → Done
