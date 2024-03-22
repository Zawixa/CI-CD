# CI-CD

Ce modèle comprend des sections pour une introduction, des prérequis, l'installation et la configuration de l'environnement de développement, l'exécution de tests, le déploiement, et les contributions. Vous pouvez ajuster ce modèle selon les besoins spécifiques de votre projet.

# Pipeline de CI/CD pour une Application Flask

Ce projet illustre la mise en place d'une pipeline de CI/CD pour une application Flask simple, visant à afficher des recettes de cuisine. Le but est d'adopter les bonnes pratiques DevOps, notamment l'utilisation d'un dépôt Git, la mise en place de tests unitaires, et le déploiement automatique sur Azure Web App à travers GitHub Actions.

## Prérequis

- [Git](https://git-scm.com/downloads)
- [Python 3](https://www.python.org/downloads/)
- Compte sur [GitHub](https://github.com/)
- Compte sur [Azure](https://azure.microsoft.com/)

## Installation et Configuration

### Clonage du dépôt


git clone <lien_du_dépôt>
cd <nom_du_dossier>

### Configuration de l'environnement de développement

1. Créez un environnement virtuel et activez-le :


    python3 -m venv venv
    source venv/bin/activate
  

2. Installez les dépendances :


    pip install -r requirements.txt
  

### Exécution des Tests

Exécutez les tests unitaires pour vous assurer que l'application fonctionne correctement :


python -m pytest -v


### Lancement de l'application en local

Pour exécuter l'application localement :


python app.py


## Déploiement

Le déploiement sur Azure Web App se fait automatiquement via la pipeline CI/CD configurée dans GitHub Actions à chaque push sur la branche principale. Assurez-vous de configurer vos secrets Azure dans GitHub pour permettre le déploiement.
