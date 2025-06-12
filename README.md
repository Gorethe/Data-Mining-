Contexte:
Ce projet a pour objectif d'analyser un jeu de données sur les diamants afin d'identifier les caractéristiques influençant leur prix 
et d'aider les consommateurs à faire le meilleur choix. Le jeu de données contient 53 940 entrées et 10 variables, 
incluant des informations sur le poids, la qualité de la coupe, la couleur, la clarté, les dimensions et le prix des diamants.

Auteurs:
TOUMBA-NGONGO-Christine
BYAOMBE-MWINDULWA-Dieudonné

Variables du jeu de données:
Variables quantitatives:
price : Prix du diamant en dollars US (326 $ à 18 823 $).

carat : Poids du diamant en carats (0,2 à 5,01).

x : Longueur du diamant en millimètres (0 à 10,74).

y : Largeur du diamant en millimètres (0 à 58,9).

z : Profondeur du diamant en millimètres (0 à 31,8).

depth : Pourcentage total de la profondeur (43 à 79).

table : Largeur du sommet du diamant par rapport au point le plus large (43 à 95).

Variables qualitatives:
color : Couleur du diamant (de J, le pire, à D, le meilleur).

cut : Qualité de la coupe (Fair, Good, Very Good, Premium, Ideal).

clarity : Mesure de la clarté (I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF).

Objectifs:
Exploration des données : Comprendre la structure et les caractéristiques du jeu de données.

Analyse descriptive : Calculer des statistiques descriptives et visualiser les distributions des variables.

Analyse des corrélations : Identifier les relations entre les variables, notamment leur impact sur le prix.

Analyse factorielle : Réduire la dimensionnalité des données et identifier les facteurs principaux influençant le prix.

Méthodologie:
Chargement des données : Utilisation de pandas pour lire le fichier CSV.

Nettoyage et préparation : Vérification des valeurs manquantes et des types de données.

Statistiques descriptives : Calcul des moyennes, écarts-types, et autres métriques pour chaque variable.

Visualisation : Création de graphiques  pour illustrer les distributions et les relations entre variables.

Analyse des corrélations : Calcul des coefficients de corrélation pour identifier les liens entre les variables quantitatives.

Analyse factorielle : Utilisation de techniques comme l'ACP pour réduire la dimensionnalité et extraire les facteurs clés.

Résultats clés:
Corrélation forte : Une forte corrélation positive (0,92) a été observée entre le poids (carat) et le prix, indiquant que les diamants plus lourds tendent à être plus chers.

Impact de la qualité : Les variables qualitatives (cut, color, clarity) influencent également le prix, avec des variations significatives selon les catégories.

Visualisations : Les boxplots ont révélé des distributions concentrées pour certaines variables (comme depth et table) et des valeurs aberrantes pour d'autres (comme price).

Outils utilisés:
Python : Langage de programmation principal.

Bibliothèques : pandas, numpy, matplotlib, seaborn, scipy, sklearn.

Environnement : Google Colab pour l'exécution du notebook.

Merci.
