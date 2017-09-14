# Projet VAICU -  Valorisation et Analyse d’Images de Circulation Urbaine

## Descriptif du projet

Ce projet a pour but d'analyser des images de caméra de circulation pour en extraire des informations telles que les conditions de circulation, les accidents, le flux de piétons, etc.

## Environnement de développement

Nous utilisons le gestionnaire de paquets Conda via la distribution
[Miniconda](https://conda.io/miniconda.html).

Pour créer l'environnement :
```bash
conda env create -f environment.yml
source activate vaicu-env
pip install -r src/dashboard/requirements.txt
```
À l'avenir, il s'agira uniquement d'activer l'environement :
```bash
source activate vaicu-env
```
Sauf quand le fichier `environment.yml` est modifié, il faut alors rouler :
```bash
conda env update -f environment.yml
```
