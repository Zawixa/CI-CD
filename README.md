# CI-CD

Le projet a pour objectif de moderniser une application web et de la déployer rapidement avec une Pipline.

**Prérequis :**

Compte GitHub
Compte Microsoft Azure
Python 3.x

**Configuration du projet :**

**Créer un dépôt git sur GitHub :** Clonez ce dépôt pour démarrer votre propre projet.

**Initialisez votre projet Flask :** Utilisez le code fourni pour mettre en place l'application Flask.

**Configurez une Azure Web App :** Créez une Web App sur Azure pour le déploiement de l'application.

**Récupérez votre Azure Profile :** Assurez-vous d'avoir vos credentials Azure pour configurer les secrets dans GitHub Actions.

Mise en place de la pipeline CI/CD

Le fichier .github/workflows/azure-webapps-python.yml contient la configuration de la pipeline CI/CD. Pour l'adapter à un autre contexte, suivez ces étapes :

**Modifiez les secrets :** Configurez vos variables d'environnement AZURE_WEBAPP_PUBLISH_PROFILE dans les secrets de GitHub pour qu'ils correspondent à votre Azure Web App.

**Modifier les variables :** Adapter les différentes variables du codes comme AZURE_WEBAPP_NAME ou PYTHON_VERSION afin qu'ils correspondent à votre environnement.

**Personnalisez le workflow :** Adaptez les étapes de build, test, et déploiement selon les besoins de votre application et de votre environnement de production.
