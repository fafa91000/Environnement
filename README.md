# Environnement

Cet environnement est destiné à supporter le déploiement des exemples fournis dans les modules suivants :
- [IHM] (https://github.com/Snekkja/IHM)
- [WebServices] (https://github.com/Snekkja/WebServices)

## Installation

Il est nécessaire de disposer de :
- Docker \([Windows] (https://docs.docker.com/engine/installation/windows/), [MacOS] (https://docs.docker.com/engine/installation/mac/) ... \)
- [Docker-Compose] (https://docs.docker.com/compose/install/)
- [Git] (https://git-scm.com/) ou d'un client Git tel que [GitHub Windows] (https://desktop.github.com/) ou [SmartGit] (http://www.syntevo.com/smartgit/)

## Récupération de l'environnement

#### Client Git
Utilisez votre client Git pour cloner le projet en utilisant l'URL publique `https://github.com/Snekkja/Environnement.git`.

#### GitBash

Ouvrez une invite GitBash.

Placez vous dans le dossier racine qui accueillera le projet.

Lancez la commande `git clone https://github.com/Snekkja/Environnement.git`.

## Utilisation

#### Démarrer l'environnement

Lancez Docker Quickstart Terminal (Windows et MacOS) ou une invite de commande (Unix).

Placez vous à la racine du projet récupéré.

Lancez la commande `docker-compose up -d --force-recreate`.

#### Eteindre l'environnement

Lancez la commande `docker-compose down`

#### Redémarrer les composants de l'environnement

Lancez la commande `docker-compose restart`

#### Vérifier l'état des composants de l'environnement

Lancez la commande `docker-compose ps` ou `docker ps`
