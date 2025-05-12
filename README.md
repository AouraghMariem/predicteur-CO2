# Prédicteur de CO₂ basé sur des données industrielles simulées

Ce projet utilise un modèle de régression basé sur un Random Forest pour prédire les émissions de CO₂ d'une entreprise en fonction de différentes variables telles que la consommation énergétique, la production, la distance de transport et les déchets produits. Le but est de fournir une estimation des émissions de CO₂ pour aider à la réduction de l'empreinte carbone des entreprises.

## Données

Les données sont générées de manière réaliste avec une distribution normale autour de moyennes plausibles pour :

- **Consommation énergétique** (en MWh)
- **Volume de production** (en unités)
- **Distance de transport** (en tonnes.km)
- **Déchets produits** (en tonnes)

La variable cible est **les émissions de CO₂**, calculée selon une relation linéaire + bruit.

## Technologies utilisées

- Python
- Pandas, NumPy
- Scikit-learn (modèle : Random Forest)
- Matplotlib
- Jupyter Notebook

## Étapes principales

1. **Génération et sauvegarde des données** (`donnees_predicteur_carbone_plus_precises.csv`)
2. **Préparation des données** : séparation en features/cible, normalisation
3. **Entraînement** d’un modèle Random Forest
4. **Évaluation** avec MAE et RMSE
5. **Visualisation** des résultats (optionnel)



