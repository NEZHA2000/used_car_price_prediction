# used_car_price_prediction
Machine Learning project to predict car prices
# 🚗 Prédiction des Prix des Voitures d'Occasion
## Projet Final – Data Science - Foundations & Machine Learning - Skillsbridges

### 1. Objectif du Projet
L'objectif de ce projet est de construire un modèle prédictif robuste pour estimer le prix des voitures d'occasion en utilisant l'algorithme **Random Forest Regressor**.

### 2. Technologies Utilisées
- **Langage :** Python
- **Librairies :** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

### 3. Pipeline de Données (Workflow)
- **Nettoyage & Extraction :** Transformation des données brutes, extraction de l'âge du véhicule, du kilométrage, du nombre d'accidents et de propriétaires.
- **Gestion des valeurs rares :** Regroupement des modèles de voitures rares sous la catégorie "Other" pour éviter le surapprentissage (Overfitting).
- **Préparation des données :** Imputation des valeurs manquantes et encodage (One-Hot Encoding) appliqués après le fractionnement des données (Train/Test Split) pour éviter les fuites de données (Data Leakage).

### 4. Résultats & Performance
Après optimisation des hyperparamètres, le modèle final (Random Forest) a atteint les performances suivantes sur le jeu de test :
- **R² Score (Test) :** 0.732
- **MAE (Erreur Absolue Moyenne) :** 3,909 $
- **RMSE (Erreur Quadratique Moyenne) :** 6,511 $

### 5. Principaux Facteurs de Prix (Feature Importance)
L'analyse de l'importance des variables montre que le **kilométrage (miles)** et l'**âge de la voiture** sont les deux facteurs les plus déterminants dans l'estimation du prix.
