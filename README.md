# Projet Big Data – Investissement dans Airbnb à Paris (France)

## Contexte 📌

Projet d’analyse des données Airbnb (listings et reviews) à Paris pour évaluer les opportunités d’investissement immobilier. 
Les données proviennent de Inside Airbnb et incluent prix, disponibilité, localisation, types de logements et retours clients.

## Objectifs 🎯

* Compréhension et audit des données disponibles.
* Nettoyage, enrichissement et structuration dans une base PostgreSQL.
* Analyse des prix, disponibilités, et comportements des utilisateurs.
* Construction d’indicateurs et rapports pour orienter les décisions d’investissement.
* Déploiement de pipelines Big Data (NiFi, Spark) pour traitement et ingestion.

## Méthodologie (Gestion de projet Big Data) 🛠️ 
* Définition & cadrage

Besoin : Identifier les zones les plus attractives pour l’investissement Airbnb.
Outils : analyse exploratoire des données, « bête à cornes » pour clarifier besoins et contraintes.

* Objectifs SMART :

Sélectionner les annonces les plus consultées.
Étudier la répartition des types de chambres par zone.
Analyser prix, disponibilité et corrélations entre variables.
Visualiser la dynamique du marché Airbnb.

* Conception de l’architecture technique:
  
Nettoyage et transformation (Python, Pandas, Numpy).
Base structurée (PostgreSQL).
Pipeline d’ingestion (NiFi, conversion CSV → JSON → PostgreSQL).
Analyse avancée (Spark pour calculs distribués).
Visualisation (Matplotlib, Seaborn).

* realisation :
  
Audit qualité et traitement des CSV.
Code Python pour préparation, analyse et visualisation.
Création et alimentation d’une base PostgreSQL.
Ingestion automatisée via NiFi.
Calculs statistiques et agrégations distribuées avec Spark.

* Résultats :
  
Tableaux de bord et graphiques (prix par zone, disponibilité, types de chambres).
Indicateurs d’investissement (corrélations prix/nombre de nuits, attractivité des quartiers).
Rapports structurés pour décision stratégique.



