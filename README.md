# Prédicteur de CO₂ basé sur des données industrielles simulées

Ce projet est une démonstration d'un mini-projet de machine learning utilisant des données synthétiques pour prédire les émissions de CO₂ à partir de facteurs industriels (énergie, production, transport, déchets). L'objectif est de comprendre les étapes de la modélisation supervisée avec Scikit-learn.

## 📊 Données

Les données sont générées de manière réaliste avec une distribution normale autour de moyennes plausibles pour :

- **Consommation énergétique** (en MWh)
- **Volume de production** (en unités)
- **Distance de transport** (en tonnes.km)
- **Déchets produits** (en tonnes)

La variable cible est **les émissions de CO₂**, calculée selon une relation linéaire + bruit.

## 🔧 Technologies utilisées

- Python
- Pandas, NumPy
- Scikit-learn (modèle : Random Forest)
- Matplotlib
- Jupyter Notebook

## 🔍 Étapes principales

1. **Génération et sauvegarde des données** (`donnees_predicteur_carbone_plus_precises.csv`)
2. **Préparation des données** : séparation en features/cible, normalisation
3. **Entraînement** d’un modèle Random Forest
4. **Évaluation** avec MAE et RMSE
5. **Visualisation** des résultats (optionnel)

## 🧪 Résultats

- **MAE** : ~X.XX tonnes de CO₂  
- **RMSE** : ~X.XX tonnes de CO₂

*(Les valeurs peuvent varier à cause du bruit aléatoire)*

## 📁 Fichiers

- `generate_data.ipynb` → génération + modélisation
- `donnees_predicteur_carbone_plus_precises.csv` → données synthétiques
- `README.md` → documentation du projet

## 🎯 Objectif pédagogique

Ce projet m’a permis d’explorer :
- La simulation de jeux de données
- Le flux complet d’un projet de régression
- L’utilisation de Scikit-learn pour modéliser et évaluer un problème réel

---

📌 *Ce projet n'est pas issu de données réelles mais vise à illustrer un cas d’usage courant dans l’industrie : la prédiction d’indicateurs environnementaux à partir de données opérationnelles.*
