# Prédiction de l'Attrition des Clients Bancaires

### Machine Learning · Deep Learning · Intelligence Artificielle Explicable (XAI)

**Projet de Fin d'Année (PFA) — ENSAO Oujda**  
**Année universitaire : 2025–2026**

## Présentation du projet

Ce projet vise à analyser et prédire l'attrition des clients bancaires (*Customer Churn*) à l'aide de techniques de Machine Learning et de Deep Learning.

L'objectif est d'identifier les clients susceptibles de quitter leur banque, de comprendre les facteurs associés à leur départ et de proposer des actions de fidélisation adaptées.

## Objectifs

- **Prédire** le risque de départ des clients bancaires.
- **Comparer** les performances de plusieurs algorithmes prédictifs.
- **Expliquer** les prédictions grâce aux techniques d'IA explicable.
- **Proposer** des recommandations de rétention client.

## Données utilisées

Le projet repose sur deux jeux de données :

1. **Bank Customer Churn Prediction** : données générales sur les clients bancaires.
2. **Credit Card Churn** : données relatives à l'attrition des clients détenteurs de cartes bancaires.

## Méthodologie

Le projet suit plusieurs étapes :

1. Exploration et analyse des données (EDA).
2. Préparation et transformation des données.
3. Entraînement des modèles de Machine Learning.
4. Développement d'un réseau de neurones MLP.
5. Évaluation et comparaison des performances.
6. Interprétation des prédictions avec SHAP et DiCE.
7. Élaboration de recommandations de fidélisation.

## Modèles utilisés

- Régression logistique
- Random Forest
- XGBoost
- Multi-Layer Perceptron (MLP)

Les modèles sont notamment évalués à l'aide de l'AUC-ROC.

## Intelligence artificielle explicable

**SHAP** permet d'identifier la contribution des différentes variables aux prédictions des modèles.

**DiCE** permet de générer des explications contrefactuelles, afin d'explorer les changements de caractéristiques susceptibles de modifier une prédiction.

## Technologies utilisées

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, TensorFlow/Keras, SHAP, DiCE et Jupyter Notebook.

## Exécution du projet

1. Télécharger ou cloner le dépôt GitHub.
2. Installer les dépendances :

   `python -m pip install -r requirements.txt`

3. Placer les deux fichiers CSV dans le même dossier que le notebook.
4. Lancer Jupyter Notebook depuis le dossier du projet.
5. Ouvrir `PFA_Churn_Bancaire_ENSAO.ipynb`.
6. Exécuter les cellules dans l'ordre.

## Résultats et perspectives

Le projet permet de comparer plusieurs approches de prédiction du churn, d'analyser les facteurs associés au départ des clients et de transformer les résultats des modèles en recommandations métier.

Il illustre l'utilisation de la Data Science et de l'IA explicable pour soutenir la prise de décision dans le secteur bancaire.

## Contexte académique

Projet réalisé dans le cadre de la formation en **Management et Gouvernance des Systèmes d'Information (MGSI)** à l'École Nationale des Sciences Appliquées d'Oujda (ENSAO), Université Mohammed Premier, Maroc.
