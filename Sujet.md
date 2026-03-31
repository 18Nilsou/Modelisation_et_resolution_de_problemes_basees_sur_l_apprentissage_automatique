```
Introduction à l’apprentissage automatique : problème ouvert
```
# Détection automatique de pathologies

## à partir de données cliniques tabulaires synthétiques (SynMedTab-800)

```
Travail
2-3 personnes
```
```
Rendu
Notebook (code +
commentaires)
```
```
Durée
2 séances de TP
```

## Contexte et motivation

```
Dans ce projet, nous considérons un jeu de données cliniques tabulaires synthétique, conçu
pour reproduire des conditions réalistes rencontrées en pratique médicale. Il comprend des
variables quantitatives telles que l’âge, la pression artérielle systolique, le cholestérol, la
glycémie à jeun et l’indice de masse corporelle (IMC), ainsi que des variables catégorielles
décrivant le statut tabagique (Never, Former, Current), le niveau d’activité physique (Low,
Moderate, High), les antécédents familiaux (Yes/No) et la qualité de l’alimentation (Poor,
Fair, Good, Excellent).
```
```
Dans ce contexte, les approches d’apprentissage automatique offrent une voie prometteuse
pour assister les cliniciens dans la détection automatique à partir de mesures objectives et
reproductibles. Ce projet propose de construire, d’évaluer et de comparer plusieurs modèles
prédictifs, en adoptant une démarche rigoureuse conforme aux standards du machine
learning appliqué à la santé.
```
## Données

```
Présentation du dataset
```
Vous disposez du jeu de données **SynMedTab-800** , un dataset synthétique représentant
des données cliniques réalistes. Chaque observation correspond à un patient et est décrite
par un ensemble de variables quantitatives et qualitatives issues de mesures cliniques et de
facteurs liés au mode de vie.
Les variables incluent notamment des indicateurs physiologiques (âge, pression artérielle,
cholestérol, glycémie, indice de masse corporelle) ainsi que des variables catégorielles telles
que le statut tabagique, le niveau d’activité physique, les antécédents familiaux et la qualité
de l’alimentation.
La variable cible correspond à la présence ou à l’absence de la pathologie :

```
— 1 : présence de la pathologie
```
```
— 0 : absence de la pathologie
```
```
Ce que vous devez faire avec les données
La préparation des données est une étape à part entière du projet. Vous êtes libres dans
vos choix méthodologiques, mais ceux-ci devront être justifiés. À titre indicatif, cette
étape comprend généralement :
```
```
— Le chargement et la prise en main du jeu de données
```
```
—Une analyse exploratoire permettant de comprendre la distribution des variables, les
déséquilibres de classes et les éventuelles corrélations
```
```
— La détection et le traitement des valeurs manquantes ou aberrantes
```
```
— La mise en forme des données en vue de l’entraînement des modèles
```
## Objectif du projet


```
L’objectif est de développer un modèle de classification binaire capable de prédire la
présence ou l’absence d’une pathologie chez un patient, à partir de données cliniques.
```
Vous devrez mettre en oeuvre la boucle d’apprentissage automatique pratiquée dans les
travaux précédents, en allant de l’exploration des données jusqu’à l’analyse des résultats.

```
Remarque importante
Ce projet est délibérément ouvert. Il n’existe pas une seule bonne réponse : vos choix
de modèles, de features, de stratégie d’évaluation et d’optimisation sont laissés à votre
initiative. Ce qui est évalué, c’est la rigueur de votre démarche et la qualité de
votre analyse , pas uniquement la performance finale.
```
## Travail attendu

```
Exploration et préparation des données
```
Avant toute modélisation, une analyse exploratoire sérieuse est attendue. Elle doit permettre
de comprendre la structure du dataset et de motiver les choix de prétraitement qui suivront.

```
Modélisation et comparaison
```
Vous devez entraîner et comparer **plusieurs modèles** , en progressant du plus simple au
plus complexe. Cette progression doit permettre de mesurer l’apport de chaque approche.
Le choix des modèles et de leur configuration vous appartient entièrement.

```
Évaluation
La nature médicale du problème rend le choix des métriques d’évaluation particulièrement
important. Les métriques suivantes sont obligatoires :
```
```
— Matrice de confusion
```
```
— Précision
```
```
— Rappel
```
```
— F1-score
```
```
— Courbe ROC
```
```
Analyse des résultats
L’analyse ne doit pas se limiter à comparer des chiffres. Une réflexion approfondie est
attendue sur les performances de chaque modèle vis-à-vis des deux classes :
```
```
—Comment le modèle se comporte-t-il face à la classe positive (présence de pathologie)?
Quelles sont les conséquences cliniques d’un faux négatif?
```
```
—Comment gère-t-il la classe négative (absence de pathologie)? Quelles sont les
conséquences d’un faux positif pour le patient?
```
```
—Le jeu de données est-il équilibré? Si non, en quoi cela influence-t-il le choix des
```

```
métriques et des modèles?
```
—Quelles sont les limites de votre approche? Qu’auriez-vous fait différemment avec plus
de temps ou de données?

## Livrables

**Un notebook Jupyter** reproductible, commenté et structuré, contenant l’intégralité du
code (exploration, prétraitement, entraînement, évaluation). Le notebook doit pouvoir
s’exécuter de bout en bout sans erreur. Votre démarche, vos choix méthodologiques et
votre analyse des résultats doivent être rédigés dans le notebook.

```
Mise en garde
L’utilisation d’outils d’intelligence artificielle générative pour produire le rapport ou le
code est autorisée à condition d’être explicitement mentionnée et que le contenu
produit soit compris, maîtrisé et assumé par les auteurs. Tout travail identique
entre deux binômes sera sanctionné.
```

