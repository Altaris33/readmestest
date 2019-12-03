**Application Social Company Blog**
===

1. [Description](#Description)
2. [Démarrage & Installation](#Démarrage-&-Installation)
3. [Utilisation avancée](#Utilisation-avancée)
4. [Configuration avancée](#Configuration-avancée)
5. [Extension/Personnalisation](#Extension/Personnalisation)
6. [Crédits](#Crédits)
7. [Liens](#Liens)

## Description

_Cette partie vise à décrire le projet du blog pour Entreprise sociale_


Le projet Social Company Blog a pour objectif de créer un système de blogposts afin que des utilisateurs inscrits puissent publier, modifier et supprimer des articles. </br>
Le microframework utilisé en Flask. Flask est un microframework léger créé afin de démarrer des applications légères en simplicité (KISS). Il embarque au démarrage les extensions WerkZeug et Jinja. Au fur et à mesure que le projet gagne en complexité, il est possible d'ajouter des extensions.


## Démarrage & Installation

_Cette partie décrit comment démarrer et installer les dépendences Python et Flask_


- Windows </br>
    - Télécharger l'executable pour Windows + variable  d'environnement à ajouter. </br>
    - Vérifier que PIP est installé -> _pip help_. </br>
    - Installer VirtualEnv -> _pip install virtualenv_. </br>
    - Récupérer le fichier requirements.txt contenant toutes les dépendances Flask. </br>
- Linux and MacOS. </br>
    - Vérifier la version de Python installée avec _python3 --version_.  </br>
    - Récupérer le fichier requirements.txt contenant toutes les dépendences Flask. 

## Utilisation avancée

- Utilisateur confirmé
    - Inscription -> /register
    - Connexion une fois inscrit -> /login
    - Publication de poste -> /create
- Développeur
    - Evolution -> gestion des erreurs liées aux id non-existants
    - Ajout de style sur les vues (CSS, Bootstrap)  

## Configuration avancée



## Crédit

- Remerciement à Jose Portilla, formateur en data sciences et Python.
- Utilisation du site officiel du microframework Flask

## Liens
- Documentation Flask : http://flask.palletsprojects.com/en/1.1.x/
- Releases: https://pypi.org/project/Flask/
- Code source: https://github.com/Altaris33/flaskblog