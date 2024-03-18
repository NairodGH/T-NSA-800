Demonstrative repository of DevSecOps using Trivy's sarif codeql scans on a given sample application for the MsC 1 2024 T-NSA-800 project.\
GitHub Advanced Security is either available on:
- a private repository under a GitHub Entreprise organization
- a public repository

Our original project-generated repository is under the GitHub Entreprise Epitech organization but they disabled the feature so I'm creating this repository to showcase it at the review.\
Here's the original sample-app's french README:

<ul>

# Sample app

- Utilise une base mysql
- Site en PHP
- Gestion schéma DB 
- Tests
- Déploiement kube

## Avant tout votre fichier .env 

Créer un fichier .env dans le dossier sample-app du repo

```conf
DB_CONNECTION=mysql
DB_HOST=xxx.xxx.xxx.xxx
DB_PORT=3306
DB_DATABASE=db_name
DB_USERNAME=username
DB_PASSWORD=passwd
```

## Création du schéma 

```bash
php artisan migrate
```

## Seed du jeu de données 

```bash
php artisan db:seed
```

</ul>