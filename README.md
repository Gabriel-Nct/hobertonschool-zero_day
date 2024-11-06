Description

Ce projet initie à la gestion de versions avec Git et à l'utilisation de GitHub. Vous apprendrez à configurer et utiliser des dépôts, collaborer sur des branches, et suivre des pratiques de commits et de documentation.
Objectifs d'apprentissage

À la fin de ce projet, vous devriez être capable de :

    Expliquer la gestion de code source et distinguer Git de GitHub
    Créer et configurer un dépôt Git
    Rédiger un README efficace et des messages de commit clairs
    Utiliser les commandes essentielles : clone, add, commit, push, pull
    Travailler en équipe via les branches et la résolution de conflits
    Comprendre les fichiers à inclure ou exclure (.gitignore)

Prérequis

    README.md : obligatoire à la racine et dans le répertoire git
    Utilisation de la ligne de commande pour toutes les opérations
    Installation de Git (si nécessaire) :

    $ sudo apt-get update
    $ sudo apt-get install git

Commandes Git essentielles

    Cloner un dépôt : git clone <repo>
    Créer et ajouter un fichier : touch <file> && git add <file>
    Commit : git commit -m "Message"
    Pousser vers GitHub : git push origin main
    Créer une branche : git branch <branch-name>
    Fusionner une branche : git merge <branch-name>

Structure du Projet

    Dossiers : bash, c, js
    Fichiers :
        bash/best et bash/school : scripts Bash
        c/c_is_fun.c et fichiers js/main.js et js/index.js

Collaboration

    Création de branches pour développer des fonctionnalités.
    Résolution de conflits lors de la fusion.
    Mise à jour locale : récupérer les modifications distantes.

Tâches avancées

    Résolution de conflits lors de la fusion de branches
    Exclusion de fichiers (.gitignore)
