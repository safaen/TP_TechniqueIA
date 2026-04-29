# 📊 TP Technique d'Intelligence Artificielle

## 👨‍🏫 Encadré par : Mustapha Ghiati

---

## 📁 Description du projet

Ce repository contient deux travaux pratiques réalisés dans le cadre du module **Techniques d'Intelligence Artificielle**.

L'objectif est de mettre en œuvre des techniques de **Machine Learning**, notamment :
- le preprocessing des données
- la création de pipelines
- la modélisation
- l’évaluation des performances

---

## 🔹 TP1 : Pipeline de base

### 📌 Objectif
Mettre en place un pipeline complet pour la préparation des données et l'entraînement d’un modèle de régression.

### 🔧 Étapes réalisées
- Chargement du dataset (diamonds)
- Analyse des variables
- Séparation en données d’entraînement et de test
- Encodage des variables catégorielles (OrdinalEncoder)
- Normalisation des données (MinMaxScaler)
- Création d’un pipeline avec `ColumnTransformer`
- Entraînement d’un modèle (Random Forest)
- Évaluation avec RMSE et R²

---

## 🔹 TP2 : Pipeline avancé

### 📌 Objectif
Améliorer le pipeline en intégrant des techniques avancées de transformation des données.

### 🔧 Étapes réalisées
- Reprise du preprocessing du TP1
- Feature Engineering avec `PolynomialFeatures`
- Sélection des variables pertinentes avec `SelectKBest`
- Intégration dans un pipeline complet
- Entraînement du modèle
- Évaluation et comparaison des performances

---

---

## 🔹 TP5 : Decision Tree Classification

### 📌 Objectif
Construire un modèle de classification basé sur un arbre de décision pour prédire la satisfaction des clients d’une compagnie aérienne à partir du dataset **Invistico_Airline.csv**.

### 🔧 Étapes réalisées
- Chargement du dataset airline avec Pandas
- Exploration des données (`head()`, `shape`, `dtypes`)
- Analyse de la variable cible `satisfaction`
- Vérification de l’équilibre des classes
- Détection des valeurs manquantes
- Suppression des lignes contenant des valeurs nulles
- Encodage de la variable cible :
  - `satisfied → 1`
  - `neutral or dissatisfied → 0`
- Séparation des variables explicatives (X) et cible (y)
- Split des données en train/test
- Entraînement d’un modèle `DecisionTreeClassifier`
- Prédiction sur les données de test
- Évaluation du modèle avec :
  - Accuracy
  - Precision
  - Recall
  - F1 Score

### 📊 Résultats obtenus
- Accuracy : **93.71%**
- Precision : **94.31%**
- Recall : **94.21%**
- F1 Score : **94.26%**

### 🎯 Compétences développées
- Classification supervisée
- Data preprocessing
- Gestion des valeurs manquantes
- Encodage de variables catégorielles
- Évaluation d’un modèle de classification
- Compréhension du fonctionnement des arbres de décision

---
## 🛠️ Technologies utilisées

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn

---

## 📊 Métriques utilisées

- RMSE (Root Mean Squared Error)
- R² (Coefficient de détermination)

---

## 🎯 Objectifs pédagogiques

- Comprendre le rôle du preprocessing
- Maîtriser les pipelines en Machine Learning
- Appliquer des techniques de feature engineering
- Évaluer et améliorer un modèle

---

## 👨‍💻 Auteur

NYAN Safae

---
