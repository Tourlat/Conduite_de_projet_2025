# Tests

### Tests Backend:

- Test d'Intégration avec les controllers, services et repositories et un docker container pour la base de données
    * Authentification: register, login
    * Project: création du projet
    * User: changement du mot de passe

### Tests Frontend:

- Frontend tests
    * Tests unitaires et d’intégration réalisés avec Vitest :
        * Vérification du rendu des composants
        * Validation des événements et état réactifs
        * Simulation d’action utilisateur

- CI/CD
    * Github workflows qui exécutent les tests frontend et backend automatiquement pour chaque pull request et chaque push/commit sur la branche main


--- IGNORE ---
- Ajouter coverage UI frontend (img)
- Ajouter coverage backend (img)