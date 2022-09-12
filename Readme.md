# Démonstration pour l'ADIRC

Date : 22/09/2022

## Objectifs
Présentation rapide d'un environnement GitOps

## Principaux composants
- Visual Studio Code
- Github
- Env0
- Scaleway

## Déroulé
- Présentation Env0 : organisation, ajout Git credentials, ajout Scaleway variables
- Passage du repository en mode public
- Gitclone d'un repository
- Ouverture dans VSC et présentation des principaux fichiers
- Ouverture Env0 : présentation organisation, projet
- Ouverture Scaleway
- Configuration Env0 : ajout template, création environnement
- Déploiement environnement via Env0
- Vérification Scaleway
- Vérification accès serveur via ssh + curl localhost 
- Modification main.tf pour ajout accès port 80
- Vérification prise en compte de la modification (relance terraform plan/apply)
- Vérification accès web
- Destroy


