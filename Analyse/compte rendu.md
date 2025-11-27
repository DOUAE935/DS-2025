Compte Rendu : Analyse du Dataset "Finance Data"
1️⃣ Objectif

L’objectif de cette analyse est de découvrir et visualiser les principales caractéristiques d’un dataset financier disponible sur Kaggle (nitindatta/finance-data).
On cherche à :

Identifier les variables clés.

Comprendre les distributions et corrélations.

Mettre en évidence des tendances ou anomalies potentielles.

2️⃣ Chargement et structure des données

Le dataset a été chargé en utilisant la librairie kagglehub pour obtenir un DataFrame pandas.

Les premières lignes permettent de voir les colonnes principales et les types de données.

La fonction df.info() a montré :

Le nombre de lignes et colonnes.

Le type de chaque variable (numérique ou texte).

La présence éventuelle de valeurs manquantes.

La fonction df.describe() fournit des statistiques descriptives :

Moyenne, médiane, écart-type.

Minimum et maximum pour chaque variable numérique.

3️⃣ Analyse exploratoire
a) Distribution des variables

Les histogrammes permettent de visualiser la distribution des valeurs pour chaque colonne numérique.

Cela aide à identifier :

Les variables avec une forte dispersion.

Les valeurs extrêmes ou anomalies potentielles.

b) Corrélations

La heatmap des corrélations permet de voir les relations entre variables numériques.

Les corrélations positives ou négatives importantes peuvent indiquer des liens forts entre certaines variables financières (ex. : volume vs prix, revenus vs dépenses).

4️⃣ Visualisations proposées

Histogrammes pour chaque colonne numérique : compréhension des distributions.

Matrice de corrélation (heatmap) : identification des relations linéaires.

Ces graphiques permettent d’avoir une première vision synthétique du dataset avant toute modélisation ou prévision.

5️⃣ Perspectives

Après cette première exploration, plusieurs pistes d’analyse peuvent être envisagées :

Étudier les tendances temporelles si le dataset contient des dates ou périodes financières.

Analyser les performances des actifs ou indicateurs financiers.

Détecter les anomalies ou outliers pour nettoyage et modélisation future.

Utiliser des modèles statistiques ou de machine learning pour prévoir les valeurs financières ou classifier des événements.

✅ Conclusion
Le dataset a été chargé avec succès et une analyse exploratoire initiale a été réalisée. Les visualisations fournissent des informations clés sur les distributions et corrélations. Cette étape prépare le terrain pour une analyse plus approfondie ou pour des modèles prédictifs financiers.
