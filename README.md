# Projet SMOTE 

## Description du projet
Ce projet a pour objectif d’étudier l’impact de la méthode SMOTE sur la performance de modèles de classification supervisée dans un contexte de classes déséquilibrées. L’étude est menée sur un jeu de données d’assurance automobile et compare plusieurs approches de modélisation,
avec et sans rééquilibrage des classes.

Les expérimentations portent notamment sur une régression logistique et une Random Forest.

## Structure du projet
data/raw/ --> contient les données brutes 

data/processed --> contient les données prétraitées sous la forme de base d'apprentissage et de test

notebooks/ --> contient les 3 notebooks du projet 
    01_analyse_exploratoire.ipynb 
    02_pretraitement_des_donnees.ipynb
    03_modelisation.ipynb 

README.md
requirements.txt --> Contient les packages et les dépendances du projet 
.gitignore

## Ordre d'exécution des codes 
Etape 1 : 01_analyse_exploratoire.ipynb
Analyse descriptive du jeu de données et mise en évidence du déséquilibre des classes.

Etape 2 : 02_pretraitement_des_donnees.ipynb
Séparation des jeux d’apprentissage et de test, standardisation des variables numériques
et préparation des données pour la modélisation.

Etape 3 : 03_modelisation.ipynb
Modélisation, application de SMOTE, comparaison des modèles.

Les dépendances nécessaires à l’exécution du projet sont listées dans le fichier requirements.txt. 

L’environnement virtuel n’est pas versionné sur Git.  
Il peut être recréé à l’aide des commandes suivantes :

```bash
source .venv/Scripts/activate   # Windows
pip install -r requirements.txt