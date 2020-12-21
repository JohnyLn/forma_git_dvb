# Les commandes de base sur la console

## Table des matières

- [Initialisation repository local](#Initialiser-un-repository-local-sur-son-ordi)
- [Récupérer un repository Distant](#Récupérer-un-repository-distant-github)
- [Commande de base respository](#Sauvegarder-son-repository-local)
  - [Add](#Ajouter-des-fichiers)
  - [Status](#L'état-des-fichiers-ajoutés)
  - [Commit](#Valider-les-fichiers-et-sauvegarder)
- [Envoyer ses modifications sur github](#Envoyer-son-repository-local-sur-github)

## Initialiser un repository local sur son ordi

```shell
git init
git add -A
git commit -m "first commit"
```

## Récupérer un repository distant github

```shell
git clone url_du_repo_git_http_ou_ssh
```

## Sauvegarder son repository local

### Ajouter des fichiers

> Ajouter les fichiers avec **add**

```shell
git add nom_du_fichier
```

> **add -A** ou add all permet de rajouter tous les fichiers du répertoire courrant

```shell
git add -A
```

### L'état des fichiers ajoutés

> **status** permert de voir les fichiers qui ont été ajouté pour préparer à un commit

```shell
git status
```

### Valider les fichiers et sauvegarder

> Le **commit** permet la sauvegarde de vos fichiers qui ont été modifiés par git

```shell
git commit -m "message"
```

```shell
git add -A
git commit -m "message"
```

## Envoyer son repository local sur github

> **push** l'ensemble des derniers commit directement sur le serveur distant c'est à dire le repository github sur la branch par défaut main

```shell
git push origin main
```

```shell
git add -A
git status
git commit -m "message"
git push origin main
```
