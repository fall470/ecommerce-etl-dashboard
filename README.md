

# 🛒 E-commerce-etl-dashboard

## 📌 Description

Ce projet a pour objectif de transformer un jeu de données e-commerce brut disponible sur *Kaggle* en informations exploitables grâce à un processus *ETL avec Python* et une *visualisation interactive sur Looker Studio*.

## ⚙ Étapes du projet

### 1. 📂 Chargement & Nettoyage des données

* Import des données brutes avec *Pandas*.
* Gestion des valeurs manquantes.
* Suppression des doublons.
* Conversion des dates.
* Export du fichier nettoyé en `ecommerce_clean.csv`.

### 2. 🔎 Analyses et transformations

* Segmentation client (Low / Mid / High Value).
* Calcul du *Customer Lifetime Value (CLV)*.
* Analyse par catégorie de produits.
* Analyse des méthodes de paiement.
* Étude des retours clients.
* Export des résultats dans plusieurs CSV (`customer_segmentation.csv`, `product_category_analysis.csv`, etc.).

### 3. 📊 Visualisation

Création d’un *dashboard interactif* sur *Looker Studio* permettant de suivre :

* Les KPI clés (CA, transactions, retours, CLV).
* La segmentation client.
* La répartition des transactions par catégorie de produits.
* Les revenus par méthode de paiement.

## 🚀 Technologies utilisées

* *Python (Pandas)*
* *Jupyter Notebook*
* *Looker Studio*

## ✅ Conclusion

Ce projet m’a permis de mettre en pratique un pipeline *ETL complet*, depuis le traitement de données brutes jusqu’à la création d’un dashboard interactif.
Il démontre l’importance de la **qualité des données** et de leur **visualisation** pour aider à la prise de décision.

 Ce projet peut servir de base pour des cas réels dans le domaine de l’**e-commerce** et être enrichi avec des techniques avancées de *Machine Learning* pour la prédiction des ventes et le scoring client.

