# 🚀 Prédiction des Atterrissages de Fusées SpaceX - Projet Capstone

## 📌 Présentation du projet

Ce projet s'inscrit dans le cadre du cours de synthèse en science des données appliquées.
L'objectif est d'analyser les données de lancements de SpaceX et de construire des modèles de machine learning capables de **prédire si le premier étage d’une fusée Falcon 9 atterrira avec succès**.

Cette prédiction est essentielle car la réutilisation des fusées permet de **réduire considérablement les coûts de lancement**.

---

## 🎯 Objectifs

* Collecter des données réelles via API et web scraping
* Nettoyer et préparer les données (data wrangling)
* Explorer les données à l’aide de visualisations
* Construire et évaluer des modèles de classification
* Créer des cartes interactives et tableaux de bord

---

## 📊 Données utilisées

Le dataset contient notamment :

* Numéro de vol et date
* Version du booster
* Masse de la charge utile
* Type d’orbite
* Site de lancement
* Résultat de l’atterrissage (variable cible)
* Informations sur la réutilisation

Sources des données :

* API REST de SpaceX
* Wikipédia (web scraping)

---

## 🧠 Modèles de Machine Learning

Les modèles suivants ont été entraînés et évalués :

* Régression Logistique
* SVM (Support Vector Machine)
* Arbre de décision
* K-Nearest Neighbors (KNN)

### 📈 Résultats

| Modèle                | Précision |
| --------------------- | --------- |
| Régression Logistique | 0.83      |
| SVM                   | 0.83      |
| Arbre de décision     | 0.83      |
| KNN                   | 0.83      |

👉 Tous les modèles obtiennent une performance similaire (~83%), ce qui indique une bonne structure des données.

---

## 🗺️ Visualisation des données

* Graphiques avec Matplotlib et Seaborn
* Cartes interactives avec Folium
* Analyse géographique des sites de lancement

---

## ⚙️ Technologies utilisées

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Folium
* Scikit-learn
* BeautifulSoup (Web Scraping)
* API REST

---

## 📁 Structure du projet

```
├── notebooks/
│   ├── data_collection_api.ipynb
│   ├── web_scraping.ipynb
│   ├── data_wrangling.ipynb
│   ├── eda_visualization.ipynb
│   ├── interactive_map_folium.ipynb
│   └── machine_learning.ipynb
│
├── data/
│   └── spacex_launch_data.csv
│
├── README.md
```

---

## 🚀 Principales conclusions

* Le succès des lancements dépend de plusieurs facteurs comme la masse de la charge utile et le type d’orbite
* Certains sites de lancement ont de meilleurs taux de réussite
* La réutilisation du booster joue un rôle clé dans la réduction des coûts

---

## 📌 Conclusion

Ce projet illustre l’ensemble du processus en science des données :
collecte → nettoyage → exploration → modélisation → visualisation.

Les résultats obtenus montrent qu’il est possible d’utiliser des données publiques pour prédire efficacement le succès des atterrissages de fusées.

---

## 📬 Contact

N'hésitez pas à me contacter pour toute question ou suggestion.
