DOUAE EL FAGROUCH FINANCE GP2
![J130052815](https://github.com/user-attachments/assets/9cdb152e-6e7b-4171-9ec1-69e0df566a76)

📝 COMPTE RENDU – Analyse du dataset “Heart Disease”
1. Introduction

L’objectif de cette étude est d’analyser le dataset Heart Disease, disponible dans la librairie ucimlrepo, afin de comprendre les facteurs expliquant la présence d’une maladie cardiaque chez les patients.
Le dataset contient 303 observations et 14 variables portant sur des caractéristiques médicales (âge, cholestérol, tension, fréquence cardiaque, etc.).

2. Description du dataset

Le dataset provient de l’Université de Californie Irvine (UCI).
La variable cible se nomme num (renommée dans le code target) :

target = 0 → Pas de maladie cardiaque

target = 1 → Présence de maladie cardiaque

Les variables incluent notamment :

age : âge du patient

sex : sexe (1 = homme, 0 = femme)

cp : type de douleur thoracique

trestbps : pression artérielle au repos

chol : cholestérol

thalach : fréquence cardiaque maximale atteinte

oldpeak : dépression du segment ST

ca, thal, etc.

3. Statistiques descriptives principales

Les statistiques calculées montrent :

Âge moyen : ~54 ans

Cholestérol moyen : ~247 mg/dl

Fréquence cardiaque maximale : moyenne ~150 bpm

oldpeak : indicateur clinique important avec une moyenne autour de 1

Interprétation simple :

Les patients sont globalement d’âge moyen à avancé.

Le niveau de cholestérol est relativement élevé, ce qui peut contribuer au risque cardiaque.

L’indicateur oldpeak, souvent utilisé en cardiologie, est révélateur de stress cardiaque.

4. Visualisations
4.1 Distribution des âges

Un histogramme montre que la majorité des patients ont entre 45 et 60 ans, ce qui correspond à la tranche où le risque cardiaque augmente.

4.2 Heatmap des corrélations

La matrice de corrélation révèle que :

cp (douleur thoracique),

thalach (fréquence cardiaque),

oldpeak (dépression ST)

sont fortement liées à la présence de maladie cardiaque.

Cela confirme que ces indicateurs sont pertinents dans le diagnostic cardiologique.

4.3 Maladie selon le sexe

Le graphique countplot montre clairement que :

Les hommes (sex = 1) présentent plus de cas de maladie cardiaque.

Les femmes sont moins représentées et moins touchées.

5. Interprétation générale

Les résultats montrent que plusieurs facteurs influencent fortement la présence de maladies cardiaques :

L’âge avancé

Le type de douleur thoracique

Une faible fréquence cardiaque maximale

Une dépression du segment ST élevée (oldpeak)

Le sexe masculin

Ces résultats correspondent aux connaissances médicales : les hommes et les personnes ayant des anomalies du segment ST sont plus exposés à des risques cardiaques.

6. Conclusion

Ce rapport montre que :

Le dataset est propre, complet et adapté à une étude prédictive.

Les analyses descriptives et graphiques permettent d’identifier les variables médicales les plus importantes.

Les résultats confirment des facteurs de risque connus comme l’âge, le cholestérol, le type de douleur thoracique, la dépression ST et le sexe.

Ce travail constitue une base solide pour aller plus loin, notamment pour :

✔ construire un modèle prédictif (régression logistique, SVM, arbre de décision)
✔ évaluer la précision du modèle
✔ générer un rapport scientifique complet
<img width="531" height="396" alt="image" src="https://github.com/user-attachments/assets/a3642b1b-f12b-4c8c-b55a-2ef7de537492" />

