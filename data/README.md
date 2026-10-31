# Données du projet APSI-NE

## Dataset utilisé

Ce projet utilise le dataset UNSW-NB15 pour l'expérimentation
et l'évaluation de modèles de détection d'intrusions réseau.

## Source officielle

Les données sont disponibles sur le site de l'Université
de Nouvelle-Galles du Sud (UNSW Canberra) :

https://research.unsw.edu.au/projects/unsw-nb15-dataset

## Fichiers nécessaires

Télécharger les deux fichiers suivants :

- UNSW_NB15_training-set.csv
- UNSW_NB15_testing-set.csv

## Installation locale

Après téléchargement, placer les fichiers dans le dossier :

data/raw/

Structure attendue :

data/
├── README.md
└── raw/
    ├── UNSW_NB15_training-set.csv
    └── UNSW_NB15_testing-set.csv

## Important

Les fichiers bruts ne sont pas versionnés sur GitHub.
Ils doivent être téléchargés séparément depuis la source officielle.

Le dossier data/raw/ est volontairement exclu du dépôt
par le fichier .gitignore.

## Référence académique

Moustafa, N. et Slay, J. (2015).
UNSW-NB15: A Comprehensive Data Set for Network
Intrusion Detection Systems.
Military Communications and Information Systems Conference (MilCIS).
