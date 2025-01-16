# E-Shop Solutions : Analyse des Ventes

## 📋 Aperçu du Projet

Ce projet consiste à analyser un jeu de données de ventes pour **E-Shop Solutions**, un détaillant en ligne basé au Royaume-Uni, spécialisé dans les cadeaux uniques pour diverses occasions. Le jeu de données couvre toutes les transactions du **1er décembre 2010 au 9 décembre 2011** et offre une vue transnationale des activités de vente. L'analyse visait à fournir des informations sur les performances de l'entreprise et le comportement des clients, avec un accent particulier sur les clients en gros.

### Livrables Clés
- **Nettoyage des données et analyse exploratoire (EDA) :** Une étude approfondie du jeu de données pour découvrir des motifs, des valeurs aberrantes et des tendances.
- **Tableau de bord interactif Power BI :** Un tableau de bord convivial et esthétique permettant aux parties prenantes d'explorer les résultats de manière dynamique.

---

## 🗂️ Détails du Jeu de Données
- **Source :** Transactions d'E-Shop Solutions.
- **Période :** Du 1er décembre 2010 au 9 décembre 2011.
- **Contenu :**
  - Données transactionnelles des ventes en ligne.
  - Attributs inclus : InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, et Country.
  
**Remarque :** Le jeu de données nécessitait un prétraitement important pour traiter les valeurs manquantes, les valeurs aberrantes et les incohérences.

---

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

---

## 🛠️ Outils et Technologies Utilisés
- **Python :** Pour le prétraitement des données et l’EDA en utilisant des bibliothèques telles que Pandas, NumPy, Matplotlib et Seaborn.
- **Power BI :** Pour créer le tableau de bord interactif.
- **Jupyter Notebook :** Pour documenter le processus de nettoyage et d’analyse.
- **Git & GitHub :** Contrôle de version et partage du projet.

---

## 💡 Principaux Résultats
1. **Produits les plus vendus :** Mise en évidence des articles les plus populaires générant des revenus.
2. **Tendances saisonnières :** Détection des pics pendant les périodes de fêtes.
3. **Répartition des clients :** Les clients basés au Royaume-Uni ont contribué à la majorité des revenus, avec une participation significative des clients en gros.
4. **Anomalies :** Identification des commandes annulées ou partiellement réalisées ayant un impact sur les revenus.

---

## 📊 Aperçu du Tableau de Bord
Une capture du tableau de bord Power BI inclut :
- Revenus par mois et par pays.
- Filtres interactifs pour une analyse détaillée.
- Meilleurs produits et leurs tendances de vente.

Pour une vue détaillée, veuillez consulter le [fichier Power BI](link-to-dashboard).

---

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

---

## 📁 Structure du Dépôt
```
📂 E-Shop-Solutions-Sales-Analysis
├── 📁 data
│   └── e_shop_sales.csv
├── 📁 notebooks
│   └── sales_analysis.ipynb
├── 📁 dashboard
│   └── E-Shop_Dashboard.pbix
├── requirements.txt
└── README.md
```

---

## 🙋‍♂️ Contact
Pour toute question ou opportunité de collaboration, n’hésitez pas à me contacter :
- **Email :** your.email@example.com
- **LinkedIn :** [Votre profil LinkedIn](https://www.linkedin.com/in/your-profile)
- **GitHub :** [Votre profil GitHub](https://github.com/your-username)
