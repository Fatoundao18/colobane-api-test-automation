# Colobane E-Commerce API Test Automation

## Description

Projet d'automatisation des tests d'une API REST E-Commerce avec Postman et Newman.

## Technologies utilisées

- Postman
- Newman
- JavaScript
- Node.js
- Git
- GitHub

## Tests réalisés

### Products

- Récupération de tous les produits
- Récupération d'un produit par ID
- Gestion d'une dépendance dynamique
- Récupération d'un produit avec un ID dynamique

### Users

- Récupération de tous les utilisateurs
- Récupération d'un utilisateur par ID

### Carts

- Récupération de tous les paniers
- Récupération d'un panier par ID

### Categories

- Récupération des catégories de produits

### Negative Tests

- Produit inexistant
- Utilisateur inexistant
- Endpoint invalide

## Résultats

Les tests sont exécutés automatiquement avec Newman.

Dernière exécution :

- 12 requêtes
- 49 assertions
- 0 échec
- 0 erreur

## Exécution des tests

Depuis la racine du projet :

```powershell
newman run ".\postman\collections\colobane-api-tests.json" -e ".\postman\environments\Colobane Environment.postman_environment.json"