Git & GitHub Project
Table of Contents

    Introduction
    Features
    Requirements
    Setup
    Basic Usage
    Common Commands
    How It Works
    Examples
    Authors

Introduction

Ce projet vise à introduire les concepts fondamentaux de la gestion de code source avec Git et son intégration avec GitHub. Il s'agit d'un guide pratique pour apprendre à manipuler les dépôts Git, collaborer efficacement sur des projets, et maîtriser les commandes essentielles du terminal.
Features

    Création et gestion de dépôts Git locaux et distants.
    Rédaction et gestion de fichiers README.md.
    Collaboration sur des projets via des branches et des pull requests.
    Résolution des conflits de fusion.
    Utilisation de GitHub pour héberger et gérer des dépôts.

Requirements

    Système d'exploitation : Ubuntu 20.04 LTS
    Git : Version 2.25 ou supérieure.
    Accès à Internet : Nécessaire pour interagir avec GitHub.
    Compte GitHub : Créé et configuré avec un Personal Access Token.
    Connaissances préalables : Aucune (idéal pour débutants).

Pré-requis pour l'installation de Git

Si Git n'est pas installé :

$ sudo apt-get update  
$ sudo apt-get upgrade  
$ sudo apt-get install git  

Setup

    Créer un dépôt GitHub :
        Connectez-vous à GitHub et créez un dépôt public.
        N'incluez pas de README.md, .gitignore, ou de licence.

    Cloner le dépôt sur votre machine locale :

$ git clone https://{TOKEN}@github.com/{USERNAME}/{REPOSITORY_NAME}.git  

Ajouter un fichier README.md :

$ echo "Mon premier projet GitHub !" > README.md  

Ajouter, committer, et pousser les modifications :

    $ git add README.md  
    $ git commit -m "Ajout du README.md"  
    $ git push origin main  

Basic Usage

Les commandes de base pour travailler avec Git incluent :

    Cloner un dépôt :

$ git clone <repository_url>  

Ajouter un fichier au suivi Git :

$ git add <filename>  

Committer des modifications :

$ git commit -m "Message de commit"  

Pousser les modifications vers GitHub :

    $ git push origin <branch_name>  

Common Commands
Commande	Description	Exemple
git status	Vérifie l'état des fichiers suivis.	$ git status
git branch	Liste ou crée des branches.	$ git branch new-feature
git checkout	Change de branche ou restaure un fichier.	$ git checkout main
git merge	Fusionne une branche dans la branche courante.	$ git merge new-feature
git pull	Récupère et fusionne les modifications distantes.	$ git pull origin main
git log	Affiche l'historique des commits.	$ git log
How It Works

    Initialisation : Créez un dépôt local avec git init.
    Suivi des fichiers : Ajoutez des fichiers au suivi Git avec git add.
    Historisation des modifications : Utilisez git commit pour enregistrer les changements.
    Collaboration : Travaillez sur des branches, fusionnez-les, et poussez vos contributions vers GitHub.

Examples
Exemple : Création et gestion d'un dépôt

# Initialisation d'un dépôt local
$ git init  

# Ajout d'un fichier
$ echo "Mon fichier de test" > fichier.txt  
$ git add fichier.txt  

# Commit des modifications
$ git commit -m "Ajout de fichier.txt"  

# Pousser vers GitHub
$ git remote add origin https://github.com/username/repo.git  
$ git push -u origin main  

Authors

    Gabriel Bescond
