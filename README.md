# Analyse de la performance des ventes – Superstore (Tableau)

## 📊 Présentation du projet

Ce projet analyse la performance des ventes d’une entreprise de distribution fictive basée aux États-Unis à partir du **dataset Superstore**.  
L’objectif est de fournir une **analyse orientée métier** à travers des tableaux de bord interactifs réalisés avec **Tableau Public**, appuyée par une **préparation légère des données en Python**.

L’analyse vise à :
- Comprendre l’évolution des ventes et de la rentabilité dans le temps
- Identifier les catégories et sous-catégories de produits performantes ou déficitaires
- Localiser les zones de risque impactant le profit
- Proposer des recommandations actionnables pour la prise de décision

---

## 🎯 Questions métier

Ce projet répond aux questions suivantes :

1. Comment les ventes et le profit évoluent-ils dans le temps ?
2. Quelles catégories et sous-catégories de produits génèrent la rentabilité ?
3. Où se concentrent les pertes ?
4. La rentabilité est-elle répartie équitablement sur le portefeuille produits ?
5. Quelles actions peuvent améliorer la performance globale ?

---

## 🗂 Description du jeu de données

- **Source** : Dataset Superstore (entreprise fictive)
- **Période analysée** : 2014 – 2017
- **Granularité** : Transactions au niveau des commandes
- **Variables principales** :
  - Sales, Profit, Quantity, Discount
  - Category, Sub-Category
  - Segment client
  - Informations géographiques (État, Région)

---

## 🧹 Préparation des données (Python)

Une préparation légère des données a été réalisée en **Python (pandas)** avant l’analyse dans Tableau :

- Chargement et inspection du jeu de données
- Vérification des valeurs manquantes et des doublons
- Création d’un **code ISO par État (`ISO_Code`)** afin d’assurer un mapping géographique fiable dans Tableau
- Export d’un jeu de données nettoyé pour l’analyse visuelle

Cette étape garantit la cohérence des données et améliore la qualité des visualisations géographiques.

---

## 📈 Tableaux de bord Tableau

La story Tableau est composée de **5 dashboards**, suivant une logique de storytelling allant du global vers l’action :

1. **Executive Summary**  
   Indicateurs clés (Sales, Profit, Profit Ratio, Orders) et tendances globales.

2. **Analyse Géographique**  
   Identification des États rentables et déficitaires.

3. **Analyse de la performance produits**  
   Analyse des ventes et du profit par catégorie et sous-catégorie.

4. **Analyse Clients & Segments**  
   Comparaison de la rentabilité selon les segments clients.

5. **Synthèse & Recommandations**  
   Récapitulatif des principaux constats et recommandations métier.

---

## 🔍 Principaux enseignements

- Le chiffre d’affaires total sur la période atteint environ **2,3 millions de dollars**.
- La **marge globale est de 12,45 %**, avec une progression continue des ventes et du profit.
- Les pertes sont **fortement concentrées** : seules **3 sous-catégories sont déficitaires**, contre **14 rentables**.
- La rentabilité varie fortement selon les sous-catégories, révélant des opportunités d’optimisation.

---

## 💡 Recommandations métier

- Revoir les **stratégies de prix et de remises** sur les sous-catégories déficitaires afin d’améliorer la marge.
- Continuer à investir dans les **sous-catégories performantes** pour soutenir la croissance du chiffre d’affaires.
- Suivre l’évolution du profit dans le temps pour **anticiper les risques émergents**.

---

## 🛠 Outils utilisés

- **Python** (pandas) – préparation des données  
- **Tableau Public** – visualisation et storytelling  
- **GitHub** – versionnement et documentation du projet  

---

## 📌 Objectif du projet

Ce projet a été réalisé dans le cadre d’un **portfolio Data Analyst**, avec un accent particulier sur :

- L’analyse orientée métier
- Le storytelling et la lisibilité des résultats
- La conception de dashboards professionnels
- La formulation de recommandations actionnables

---
