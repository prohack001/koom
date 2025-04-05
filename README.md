# koom

#Notebook - Classification de la Potabilité de l’Eau

Ce notebook présente une approche complète de classification supervisée pour déterminer si une eau est potable ou non à partir de données physico-chimiques.

## 📚 Description

Le projet applique des techniques de **machine learning** à un jeu de données composé de 12 variables . afin de prédire la potabilité (`is_safe`).

##  Pipeline utilisé

1. **Chargement et nettoyage des données**
2. **Analyse exploratoire rapide**
3. **Traitement des valeurs manquantes**
4. **Rééquilibrage des classes avec SMOTE**
5. **Modélisation avec plusieurs algorithmes** :
   - Random Forest
   - LightGBM (LGBM)
   - HistGradientBoosting
   - CatBoost
6. **Optimisation des hyperparamètres avec GridSearchCV**
7. **Évaluation des modèles**
8. **Visualisation de la matrice de confusion et des performances**

##  Résultats

| Modèle                 | Accuracy (de base) | Accuracy (optimisé) |
|------------------------|--------------------|----------------------|
| LGBM                   | 0.92               | **0.96**             |
| HistGradientBoosting   | 0.91               | **0.95**             |
| Random Forest          | 0.89               | 0.93                 |

🔍 **LGBM et HistGradientBoosting sont les plus performants**, surtout après optimisation.

## Fichiers

- `qualiteEasyPredict.ipynb` : Notebook principal
- `base2.csv` : Jeu de données utilisé

## À venir

- Déploiement possible via une API Flask

## Auteurs

- COMPAORE Walker Stanislas Rocksane  
- ILBOUDO Wendpingre-Nôoma Kieffer Schlegel  
- PARE Ina Aminatou Charifa

## 🔗 Licence

Ce projet est partagé à des fins éducatives. Libre à vous de l'adapter avec mention des auteurs.
