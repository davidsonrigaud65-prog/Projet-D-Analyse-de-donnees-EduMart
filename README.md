# 📊 Projet d'Analyse de Données - EduMart

### 👥 Auteurs du projet :  **Davidson RIGAUD**

**Date :** 10 janvier 2026

---

### 📂 Structure du Projet
```text
┌── Data
│   ├── customers.csv                (données clients)
│   ├── products.csv                 (catalogue produits)
│   └── order_lines.csv              (lignes de commande)
├── Scripts
│   ├── Chargement, Comprehension et nettoyage des donnees.ipynb
│   ├── ICP (Indicateur Clé de Performance).ipynb
│   ├── Jointures (Merge) pour enrichir les ventes.ipynb
│   └── Main.ipynb                   (Point d'entrée)
├── Livrables
│   ├── Données_nettoyées
│   ├── KPI_calculés
│   └── Jointure_et_pivot table
└── Rapport.pdf  
⚙️ Ordre d'exécution
Étape 1 : Nettoyage des données (types, NaN, anomalies).

Étape 2 : Calcul des KPI (CA, panier moyen, etc.).

Étape 3 : Enrichissement avec jointures et analyse par segment/catégorie.

🛠️ Concepts Pandas utilisés
Exploration : read_csv, info, describe, value_counts

Nettoyage : to_datetime, fillna, drop_duplicates

Analyse : groupby, pivot_table, merge

💡 Conseils
Exécuter les étapes dans l'ordre chronologique.

Utiliser le script Main.ipynb pour une vue d'ensemble.
 "nbformat": 4,
 "nbformat_minor": 5
}
