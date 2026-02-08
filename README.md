🎬 Cinema-Analytics-Dashboard

Cinema+ : Solution BI de Performance Cinématographique

📌 Problématique

Dans l'industrie du cinéma, les données de production (budgets), de distribution (studios) et de performance (recettes, notes) sont souvent dispersées ou silotées. Il est difficile pour un décideur de :

Identifier rapidement la corrélation entre le budget investi et la rentabilité réelle par genre.

Comparer les performances financières des studios sur une période longue (10 ans).

Visualiser l’évolution des tendances du marché (ex: recettes annuelles) de manière interactive.

💡 Solution Apportée

J’ai conçu un tableau de bord décisionnel complet sous Excel, capable de transformer des données brutes en indicateurs stratégiques (KPIs).
La solution repose sur une architecture robuste, garantissant l’intégrité et la fluidité des analyses.

🛠️ Stack Technique & Méthodologie

ETL (Power Query) : Nettoyage, transformation et normalisation des données sources (gestion des doublons, formats de devises, types de données).

Modélisation de données : Mise en place d’un Modèle en étoile (Star Schema) pour optimiser les relations entre la table de faits (Ventes/Films) et les tables de dimensions (Temps, Studio, Genre).

Analyse de données (DAX) : Création de mesures calculées complexes pour extraire des insights précis, telles que :

Rentabilité moyenne :

Rentabilité = Recettes / Budget
	
Calcul des recettes totales et du nombre de billets vendus selon différents filtres.

Visualisation (Dataviz) : Conception d’une interface utilisateur ergonomique, avec filtres dynamiques (Slicers) par année, mois et genre.

📈 Résultats Clés (Insights)

Pilotage financier : Visualisation directe du ratio Budget vs Recettes (351 Mrd € de recettes totales).

Analyse sectorielle : Identification des genres Animation et Horreur comme leviers de rentabilité.

Performance Studio : CinéMax se distingue avec des recettes dépassant 722 M€.

📂 Comment utiliser ce projet

Téléchargez le fichier .xlsx.

Explorez les différents segments (Années, Genres, Studios) pour mettre à jour les graphiques en temps réel.

Consultez l’onglet "Modèle de données" (Power Pivot) pour visualiser les relations et les mesures DAX.
