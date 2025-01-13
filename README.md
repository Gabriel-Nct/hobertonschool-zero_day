# Git & GitHub Project

## Table of Contents

1.  [Introduction](#introduction)
2.  [Features](#features)
3.  [Requirements](#requirements)
4.  [Setup](#setup)
5.  [Basic Usage](#basic-usage)
6.  [Common Commands](#common-commands)
7.  [How It Works](#how-it-works)
8.  [Examples](#examples)
9.  [Authors](#authors)

----------

## Introduction

Ce projet vise à introduire les concepts fondamentaux de la gestion de code source avec Git et son intégration avec GitHub. Il s'agit d'un guide pratique pour apprendre à manipuler les dépôts Git, collaborer efficacement sur des projets, et maîtriser les commandes essentielles du terminal.

----------

## Features

-   Création et gestion de dépôts Git locaux et distants.
-   Rédaction et gestion de fichiers `README.md`.
-   Collaboration sur des projets via des branches et des pull requests.
-   Résolution des conflits de fusion.
-   Utilisation de GitHub pour héberger et gérer des dépôts.

----------

## Requirements

-   **Système d'exploitation :** Ubuntu 20.04 LTS
-   **Git :** Version 2.25 ou supérieure.
-   **Accès à Internet :** Nécessaire pour interagir avec GitHub.
-   **Compte GitHub :** Créé et configuré avec un Personal Access Token.
-   **Connaissances préalables :** Aucune (idéal pour débutants).

----------

## How It Works

1.  **Initialisation** : Créez un dépôt local avec `git init`.
2.  **Suivi des fichiers** : Ajoutez des fichiers au suivi Git avec `git add`.
3.  **Historisation des modifications** : Utilisez `git commit` pour enregistrer les changements.
4.  **Collaboration** : Travaillez sur des branches, fusionnez-les, et poussez vos contributions vers GitHub.

----------


## Examples

### Exemple : Création et gestion d'un dépôt

```bash
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
```

----------

## Authors

-   **Gabriel Bescond**


