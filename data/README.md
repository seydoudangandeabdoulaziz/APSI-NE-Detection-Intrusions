# Données du projet APSI-NE

## Dataset utilisé

Ce projet utilise le dataset UNSW-NB15 pour l'expérimentation
et l'évaluation de modèles de détection d'intrusions réseau.

## Source officielle

Université de Nouvelle-Galles du Sud (UNSW Canberra) :

https://research.unsw.edu.au/projects/unsw-nb15-dataset

## Fichiers nécessaires

Trois fichiers sont utilisés dans ce projet :

- NUSW-NB15_features.csv
- UNSW_NB15_training-set.csv
- UNSW_NB15_testing-set.csv

## Installation locale

Télécharger les trois fichiers depuis la source officielle
et les placer dans le dossier data/raw/.

Structure attendue :

data/
├── README.md
└── raw/
    ├── NUSW-NB15_features.csv
    ├── UNSW_NB15_training-set.csv
    └── UNSW_NB15_testing-set.csv

## Important

Les données brutes ne sont pas publiées sur GitHub.
Elles doivent être téléchargées séparément.

Le dossier data/raw/ est exclu du dépôt par .gitignore.
