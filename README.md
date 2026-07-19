# Analyse des matchs de football

Projet d'analyse de données et de machine learning sur les matchs de football internationaux (1872-2017).

## 📌 Objectif

Explorer les données historiques de matchs de football, identifier des tendances et entraîner un modèle prédictif pour prédire le vainqueur d'un match.

## 📊 Données

- **Source** : International Football Results (Kaggle)
- **Période** : 1872 à 2017
- **Volume** : 40 000+ matchs
- **Colonnes** : date, équipe domicile, équipe extérieur, scores, tournoi, pays, etc.

## 🔍 Analyses réalisées

| Analyse | Description |
|---------|-------------|
| **1** | Top 10 des équipes avec le plus de victoires |
| **2** | Top 10 des équipes avec le plus de buts marqués |
| **3** | Évolution du nombre de matchs par année (1872-2017) |
| **4** | Top 10 des compétitions avec le plus de matchs |
| **5** | Répartition des résultats (victoire domicile, extérieur, nul) |

## 🤖 Modèle prédictif

- **Algorithme** : Random Forest
- **Précision** : 65 %
- **Objectif** : Prédire si l'équipe à domicile va gagner le match
- **Caractéristiques** : équipes, tournoi, terrain neutre

### Exemple de prédiction

Test sur la finale de la Coupe du Monde 2026 :

- **Espagne vs Argentine** (terrain neutre)
- Probabilité de victoire pour l'Espagne : **3 %**
- Prédiction : **Pas de victoire** (Argentine favorite)

## 🛠️ Technologies utilisées

- **Python** : pandas, matplotlib, scikit-learn
- **Environnement** : Google Colab

## 📁 Structure du projet
