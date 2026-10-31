# APSI-NE — Détection intelligente des intrusions réseau

Projet de fin de formation APSI-NE — 2026

## Auteur
- Nom : Seydou Dangande Abdoul Aziz
- Établissement : École des Mines, de l'Industrie et de la Géologie (EMIG)
- Filière : Génie logiciel

## Présentation
Ce projet porte sur la conception et l'évaluation d'un système intelligent de détection d'intrusions réseau à l'aide du Machine Learning.

Deux modèles sont étudiés :
- Random Forest : classification du trafic réseau.
- Isolation Forest : détection d'anomalies, entraînée sur le trafic normal.

Une expérimentation complémentaire étudie l'effet d'une perturbation synthétique des données sur les performances des modèles.

## Dataset
UNSW-NB15. Les données brutes ne sont pas incluses dans ce dépôt. Elles doivent être téléchargées depuis leur source officielle et placées dans data/raw/.

## Structure
- reports/ : rapport final PDF.
- notebooks/ : notebook Jupyter.
- results/ : résultats, métriques et graphiques.
- requirements.txt : dépendances Python.

## Installation
Créer un environnement virtuel avec python3 -m venv .venv, l'activer avec source .venv/bin/activate, puis installer les dépendances avec python3 -m pip install -r requirements.txt.

## Exécution
Lancer JupyterLab avec la commande jupyter lab et ouvrir le notebook dans notebooks/.

## Limites
Les expérimentations sont réalisées sur le dataset UNSW-NB15. Les résultats ne constituent pas une validation en environnement de production.

## Licence
Aucune licence de réutilisation n'est accordée pour le moment.
