# Formation Git et GitHub

## Index

- [Prérequis](#wrench-prérequis)
    - [Python](#installer-python)
    - [Visual Studio Code](#installer-visual-studio-code-vscode)
    - [GitHub](#créer-un-compte-github)
    - [Git](#installer-git)
- [Tutoriel Git](#pencil2-tutoriel-git)
- [Troubleshooting](#computer-troubleshooting)

## :wrench: Prérequis

### Installer Python

[Télécharger la dernière version de Python](https://www.python.org/downloads/)

### Installer Visual Studio Code (VSCode)

Installer un environnement de développement, e.g. [Visual Studio Code (VSCode)](https://code.visualstudio.com/download).

### Créer un compte GitHub

GitHub est une plateforme en ligne qui permet, entre autres, d'héberger des dépôts Git.

1. Allez sur https://github.com/ et cliquez sur "sign up". 
2. Remplissez le formulaire avec votre email professionnel, votre nom d'utilisateur (qui peut être modifié plus tard), un mot de passe...
3. Vérifiez votre adresse email
3. GitHub vous posera quelques questions pour configurer votre expérience.

#### Clé SSH

Avec une clé SSH, vous pouvez vous connecter à GitHub depuis votre machine sans fournir votre nom d'utilisateur et votre personal access token à chaque visite. Vous pouvez également utiliser une clé SSH pour signer des commits. 
Nous allons donc ajouter une nouvelle clé SSH à notre compte GitHub, pour lier notre machine locale au compte.

Il y a 3 étapes :
1. [Vérification des clés SSH existantes](https://docs.github.com/fr/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys)
2. Si vous n'avez pas de clés, en [générer une](https://docs.github.com/fr/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
3. [Ajout d'une nouvelle clé SSH à votre compte GitHub](https://docs.github.com/fr/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

### Installer Git

Git est le gestionnaire de versions le plus largement utilisé aujourd'hui. Il permet de conserver un historique des modifications et des versions de chaque fichier d'un projet. 

1. [Télécharger la dernière version de Git](https://git-scm.com/download/win)  
2. Accepter tous les choix par défaut
3. Dans un terminal (e.g. Windows PowerShell ou Git bash), tapez `git` pour vérifier la bonne installation
4. Dans ce même terminal, configurer votre identité. Renseigner l’email que vous avez utilisé pour créer votre compte GitHub.
    ```bash
    git config --global user.name "John Doe"
    git config --global user.email "johndoe@example.com"
    ```

## :pencil2: Tutoriel Git

- [Tutoriel Git et GitHub](https://elxse.notion.site/Git-et-Github-57337f89f6ae4ca9b6097507e88a1030)
- [Cheatsheet](https://training.github.com/downloads/fr/github-git-cheat-sheet.pdf)

## :computer: Troubleshooting

Si vous rencontrez quelconque problème ou avez des questions, n'hésitez pas à envoyer un mail à elise.chin@adway-conseil.com.

