# NYC Airbnb Pricing Strategy & Market Optimizer 🗽

[![Language - R](https://img.shields.io/badge/Language-R-blue.svg)](https://www.r-project.org/)
[![Focus - Machine Learning](https://img.shields.io/badge/Focus-Machine_Learning-green.svg)](#)

## 🎯 1. L'Enjeu (Business & Métier)
Analyse d'un marché de **48 895 annonces**. L'objectif est d'optimiser le positionnement tarifaire des hôtes pour maximiser le taux d'occupation dans un environnement ultra-concurrentiel.

## 💡 2. La Solution (Produit)
Un pipeline de Machine Learning capable de prédire le prix optimal selon les caractéristiques du bien et sa localisation.
* **Insights Clés** : Manhattan et Brooklyn dominent l'offre. Le type de chambre est le levier de prix principal.
* **Outil** : Heatmap interactive pour visualiser les opportunités d'investissement.

## 🛠 3. L'Exécution (Technique)
Comparaison de modèles pour garantir la précision des prédictions.
* **Nettoyage** : Traitement massif des données brutes (train.csv).
* **Modélisation** : Utilisation d'un **Arbre de Décision** pour gérer les relations non-linéaires complexes.

### Performance
| Métrique | Arbre de Décision (Retenu) | Régression Linéaire |
| :--- | :--- | :--- |
| **MAE (Erreur moyenne)** | **49.93 $** | 50.21 $ |
| **RMSE (log)** | **0.46** | 0.46 |

## 📂 4. Documentation & Livrables
Pour une analyse approfondie de la méthodologie et des résultats :
* [📊 Consulter le Rapport complet (PDF)](Analyzing%20Airbnb%20Market%20Trends%20in%20New%20York%20City_final.pdf)
* [🌐 Voir l'Analyse Interactive (HTML)](nyc_airbnb_analysis.html)

---
*Projet réalisé par **Fodé DIAKHABY** & équipe.*
