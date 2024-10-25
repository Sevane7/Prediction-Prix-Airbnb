# Prédiction des Prix Airbnb

Ce projet, qui constitue mes premiers pas en machine learning, a pour objectif d'explorer les bases de la modélisation prédictive et de l'analyse de données, en particulier dans la prédiction des prix des locations Airbnb. Il est axé sur le nettoyage de données et l'évaluation de différents modèles, pour une meilleure compréhension des étapes essentielles en science des données et en machine learning.

## Table des Matières
- [Contexte](#contexte)
- [Données](#données)
- [Objectifs du Projet](#objectifs-du-projet)
- [Pré-requis](#pré-requis)
- [Structure du Code](#structure-du-code)
- [Exploration des Données (EDA)](#exploration-des-données-eda)
- [Préparation des Données](#préparation-des-données)
- [Modélisation et Évaluation](#modélisation-et-évaluation)
- [Résultats et Conclusions](#résultats-et-conclusions)
- [Améliorations Futures](#améliorations-futures)
- [Auteurs](#auteurs)

## Contexte
Le marché de la location de courte durée, particulièrement avec des plateformes comme Airbnb, est influencé par de nombreux facteurs (emplacement, équipement, période de l'année, etc.). Ce projet a pour but de comprendre les principaux facteurs qui influencent les prix et de construire un modèle prédictif pour estimer ces prix avec précision.

## Données
Les données utilisées proviennent de la plateforme Airbnb et contiennent des informations telles que :
- **Caractéristiques du logement** : Nombre de chambres, équipements, capacité d'accueil, etc.
- **Informations de localisation** : Quartier, proximité des points d'intérêt, etc.
- **Autres variables** : Commentaires des utilisateurs, disponibilité, etc.

Les étapes de préparation des données incluent **le nettoyage, l'encodage des variables catégorielles**, et la **gestion des valeurs manquantes**.

## Objectifs du Projet
1. **Comprendre les facteurs influençant les prix** : Utiliser des analyses descriptives pour identifier les caractéristiques importantes.
2. **Construire un modèle prédictif** : Utiliser différents algorithmes de machine learning pour prédire le prix des annonces.
3. **Évaluer les performances des modèles** : Comparer les modèles pour choisir le plus performant.

## Pré-requis
Ce projet nécessite Python 3.8+ et utilise les bibliothèques suivantes :
- `pandas` : Pour le traitement et l'analyse des données
- `numpy` : Pour les calculs numériques
- `matplotlib` et `seaborn` : Pour la visualisation des données
- `scikit-learn` : Pour la modélisation prédictive

Pour installer les dépendances, exécutez la commande suivante :
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
