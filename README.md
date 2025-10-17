# Loan Default Prediction – ML Initiation

## Description
Ce projet est une introduction au machine learning appliqué à la prédiction des défauts de paiement de prêts. Il inclut le nettoyage des données, l’exploration des comportements clients et la création d’un modèle supervisé (régression logistique) pour prédire si un client fera défaut.

Les codes sont organisés en deux notebooks principaux :

- **Visualisation et nettoyage des données** : traitement des valeurs manquantes, conversion des types, création de nouvelles colonnes pour transactions et prêts par client, exploration des corrélations.
- **Modélisation ML** : séparation des variables explicatives (X) et de la cible (y), imputation des valeurs manquantes, standardisation, entraînement d’un modèle de régression logistique, évaluation avec matrice de confusion et rapport de classification.

## Fonctionnalités principales
- Nettoyage et exploration des données clients et prêts  
- Création de nouvelles colonnes pour enrichir les données (nombre de transactions, nombre de prêts, retard de paiement)  
- Analyse des corrélations entre variables  
- Séparation des données en jeu d’entraînement et de test  
- Imputation des valeurs manquantes et standardisation des variables  
- Entraînement et évaluation d’un modèle de régression logistique  
- Visualisation des performances avec matrice de confusion et heatmap

## Technologies utilisées
- Python 
- Pandas, NumPy 
- Scikit-learn (train_test_split, LogisticRegression, StandardScaler, SimpleImputer)  
- Seaborn & Matplotlib 
