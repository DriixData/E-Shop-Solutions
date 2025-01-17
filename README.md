# 🛍 Missions DATA : Analyse des ventes d'E-Shop Solutions

Bienvenue sur le projet **Missions DATA** mené dans le cadre de la formation Data Analyst avec la Wild Code School. Cette initiative est une méthodologie d’apprentissage, conçue pour se concentrer sur les besoins métiers tout en combinant rôle-play, analyse de données, et interaction client. Voici une présentation complète de la démarche et des résultats obtenus dans le cadre de notre mission.

## Contexte des Missions DATA

Voici les principales étapes :

1. **Choix du Dataset** : Chaque élève sélectionne un jeu de données pertinent via Kaggle, Data.gouv.fr ou d'autres sources. Ce dataset doit permettre une étude complète mais être modérément complexe en termes de nettoyage.
2. **Validation et Brief Client** : Une fois le dataset validé par le formateur, l'élève prépare un Brief Client fictif comportant :
   * Nom et description du client
   * Nature de la mission
   * Livrables attendus
3. **Mission DATA** : Le formateur organise des sessions sur deux jours, impliquant des interactions entre binômes élèves en rôles de Client et Data Analyst.

### Chronologie d'une Mission DATA

* **JOUR 0 : Présentation de la Mission**
  * Introduction par le formateur.
  * Choix des datasets.
  * Formation des binômes Client/Data Analyst.
* **JOUR 1 : Brief Client**
  * Rencontre initiale entre Client et Data Analyst (échange sur le projet, collecte des besoins).
* **JOUR 2 : Retour Client**
  * Première ébauche présentée au Client, retour constructif.
* **JOUR 2 : Présentation finale**
  * Livrable final présenté en fin de journée.

## 📋 Aperçu du Projet

Ce projet consiste à analyser un jeu de données de ventes pour **E-Shop Solutions**, un détaillant en ligne basé au Royaume-Uni, spécialisé dans les cadeaux uniques pour diverses occasions. Le jeu de données couvre toutes les transactions du **1er décembre 2010 au 9 décembre 2011** et offre une vue transnationale des activités de vente. L'analyse visait à fournir des informations sur les performances de l'entreprise et le comportement des clients, avec un accent particulier sur les clients en gros.

### Livrables Clés

- **Nettoyage des données et analyse exploratoire (EDA) :** Une étude approfondie du jeu de données pour découvrir des motifs, des valeurs aberrantes et des tendances.
- **Tableau de bord interactif Power BI :** Un tableau de bord convivial et esthétique permettant aux parties prenantes d'explorer les résultats de manière dynamique.

![image](https://github.com/user-attachments/assets/1eab91c2-4f63-4bff-9620-a679e41a3009)

## 🗂️ Détails du Jeu de Données

- **Source :** Transactions d'E-Shop Solutions. [Lien Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data?resource=download)
- **Période :** Du 1er décembre 2010 au 9 décembre 2011.
- **Contenu :**
  - Données transactionnelles des ventes en ligne.
  - Attributs inclus : InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, et Country.

**Remarque :** Le jeu de données nécessitait un prétraitement important pour traiter les valeurs manquantes, les valeurs aberrantes et les incohérences.

## 🔍 Étapes et Méthodologie

### 1. **Nettoyage des Données**

- Traitement des IDs clients manquants en les supprimant ou en les imputant selon le contexte.
- Suppression des doublons pour assurer l’intégrité des données.
- Gestion des valeurs aberrantes dans les colonnes **Quantity** et **UnitPrice**.
- Standardisation des formats de texte pour les descriptions de produits.

### 2. **Analyse Exploratoire des Données (EDA)**

- Investigation :
  - Produits et catégories les plus vendus.
  - Tendances des revenus mensuels.
  - Répartition des ventes par pays.
- Identification des indicateurs clés de performance (KPI) tels que :
  - **Revenu Total**
  - **Valeur Moyenne des Commandes (AOV)**
  - **Métriques de Fidélisation Client**

### 3. **Développement du Tableau de Bord**

Création d’un **tableau de bord interactif Power BI** comprenant :

- Répartition des revenus par produit, mois et pays.
- Segmentation des clients en gros et au détail.
- Visualisations mettant en évidence :
  - Les tendances des ventes.
  - Les clients à forte valeur.
  - Les performances des stocks.

## 🛠️ Outils et Technologies Utilisés

- **Python :** Pour le prétraitement des données et l’EDA en utilisant des bibliothèques telles que Pandas, NumPy, Matplotlib et Seaborn.
- **Power BI :** Pour créer le tableau de bord interactif.
- **Jupyter Notebook :** Pour documenter le processus de nettoyage et d’analyse.
- **Git & GitHub :** Contrôle de version et partage du projet.

## 💡 Principaux Résultats

1. **Produits les plus vendus :** Mise en évidence des articles les plus populaires générant des revenus.
2. **Tendances saisonnières :** Détection des pics pendant les périodes de fêtes.
3. **Répartition des clients :** Les clients basés au Royaume-Uni ont contribué à la majorité des revenus, avec une participation significative des clients en gros.
4. **Anomalies :** Identification des commandes annulées ou partiellement réalisées ayant un impact sur les revenus.

## 📊 Aperçu du Tableau de Bord

Une capture du tableau de bord Power BI inclut :

- Revenus par mois et par pays.
- Filtres interactifs pour une analyse détaillée.
- Meilleurs produits et leurs tendances de vente.

Pour une vue détaillée, veuillez consulter le [fichier Power BI](link-to-dashboard).

## 🚀 Comment Exécuter le Projet

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/your-username/e-shop-solutions-sales-analysis.git
   ```
2. Installez les bibliothèques Python requises :
   ```bash
   pip install -r requirements.txt
   ```
3. Lancez le notebook Jupyter pour l’EDA :
   ```bash
   jupyter notebook sales_analysis.ipynb
   ```
4. Ouvrez le fichier Power BI (`E-Shop_Dashboard.pbix`) pour une exploration interactive.

## 📁 Structure du Dépôt

```
📂 E-Shop-Solutions-main
├── 📁 dashboard
│   └── E-Shop_Dashboard.pbix
├── 📁 data
│   └── data_clean.csv
│   └── data.csv
├── 📁 notebooks
│   └── sales_analysis.ipynb
├── README.md
└── requirements.txt
```

## 🙋‍♂️ Contact

Pour toute question ou opportunité de collaboration, n’hésitez pas à me contacter :

[Votre mon profil LinkedIn](https://www.linkedin.com/in/c3dr1c/)
