---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Moyenne mobile intégrée autorégressive (ARIMA)
description: Une moyenne mobile intégrée autorégressive (ARIMA) est un modèle d&#39;analyse statistique qui exploite les données de séries chronologiques pour prévoir les tendances futures.
---

# Moyenne mobile intégrée autorégressive (ARIMA)
## Qu'est-ce qu'une moyenne mobile intégrée autorégressive (ARIMA) ?

Une moyenne mobile intégrée autorégressive, ou ARIMA, est un modèle d'analyse statistique qui utilise [des données de séries chronologiques](/timeseries) pour mieux comprendre l'ensemble de données ou pour prédire les tendances futures.

Un modèle statistique est autorégressif s'il prédit des valeurs futures basées sur des valeurs passées. Par exemple, un modèle ARIMA peut chercher à prédire les prix futurs d'une action en fonction de ses performances passées ou à prévoir les bénéfices d'une entreprise en fonction de périodes passées.

## Comprendre la moyenne mobile intégrée autorégressive (ARIMA)

Un modèle de moyenne mobile intégré autorégressif est une forme d' [analyse de régression](/regression) qui évalue la force d'une variable dépendante par rapport à d'autres variables changeantes. L'objectif du modèle est de prédire les mouvements futurs des valeurs mobilières ou des marchés financiers en examinant les différences entre les valeurs de la série plutôt qu'en passant par les valeurs réelles.

Un modèle ARIMA peut être compris en décrivant chacun de ses composants comme suit :

- [Autorégression (AR)](/autoregressive) : fait référence à un modèle qui montre une variable changeante qui régresse sur ses propres valeurs décalées ou antérieures.

- **Intégré (I) :** représente la différenciation des observations brutes pour permettre à la série chronologique de devenir stationnaire (c'est-à-dire que les valeurs des données sont remplacées par la différence entre les valeurs des données et les valeurs précédentes).

- [Moyenne mobile (MA)](/movingaverage) : intègre la dépendance entre une observation et une erreur résiduelle issue d'un modèle de moyenne mobile appliqué à des observations décalées.

## Paramètres ARIMA

Chaque composant dans ARIMA fonctionne comme un paramètre avec une notation standard. Pour les modèles ARIMA, une notation standard serait ARIMA avec p, d et q, où des valeurs entières remplacent les paramètres pour indiquer le type de modèle ARIMA utilisé. Les paramètres peuvent être définis comme :

- **p** : le nombre d'observations de retard dans le modèle ; également connu sous le nom d'ordre de décalage.

- **d** : le nombre de fois que les observations brutes sont différenciées ; également connu sous le nom de degré de différenciation.

- q : la taille de la fenêtre moyenne mobile ; également connu sous le nom d'ordre de la moyenne mobile.

Dans un modèle de [régression linéaire](/nonlinear-regression),. par exemple, le nombre et le type de termes sont inclus. Une valeur 0, qui peut être utilisée comme paramètre, signifierait que ce composant particulier ne devrait pas être utilisé dans le modèle. De cette façon, le modèle ARIMA peut être construit pour remplir la fonction d'un modèle ARMA, ou même de simples modèles AR, I ou MA.

> Étant donné que les modèles ARIMA sont compliqués et fonctionnent mieux sur de très grands ensembles de données, des algorithmes informatiques et des techniques d'apprentissage automatique sont utilisés pour les calculer.

>

## Moyenne mobile intégrée autorégressive (ARIMA) et stationnarité

Dans un modèle de moyenne mobile intégré autorégressif, les données sont différenciées afin de les rendre stationnaires. Un modèle qui montre la stationnarité est celui qui montre que les données sont constantes dans le temps. La plupart des données économiques et de marché montrent des tendances, de sorte que le but de la différenciation est de supprimer toutes les tendances ou structures saisonnières.

[La saisonnalité](/seasonality),. ou lorsque les données montrent des modèles réguliers et prévisibles qui se répètent sur une année civile, peut affecter négativement le modèle de régression. Si une tendance apparaît et que la stationnarité n'est pas évidente, de nombreux calculs tout au long du processus ne peuvent pas être effectués avec une grande efficacité.

> Un choc ponctuel affectera indéfiniment les valeurs ultérieures d'un modèle ARIMA dans le futur. Par conséquent, l'héritage de la crise financière perdure dans les modèles autorégressifs d'aujourd'hui.

>

## Considérations particulières

Les modèles ARIMA sont basés sur l'hypothèse que les valeurs passées ont un effet résiduel sur les valeurs actuelles ou futures. Par exemple, un investisseur utilisant un modèle ARIMA pour prévoir les cours des actions supposerait que les nouveaux acheteurs et vendeurs de ces actions sont influencés par les transactions récentes sur le marché lorsqu'ils décident du montant à offrir ou à accepter pour le titre.

Bien que cette hypothèse soit valable dans de nombreuses circonstances, ce n'est pas toujours le cas. Par exemple, dans les années qui ont précédé la crise financière de 2008, la plupart des investisseurs n'étaient pas conscients des risques posés par les vastes portefeuilles de [titres adossés à des créances hypothécaires](/mbs) (MBS) détenus par de nombreuses sociétés financières.

À cette époque, un investisseur utilisant un modèle autorégressif pour prédire la performance des actions financières américaines aurait eu de bonnes raisons de prédire une tendance continue de prix des actions stables ou en hausse dans ce secteur. Cependant, une fois qu'il est devenu de notoriété publique que de nombreuses institutions financières risquaient un effondrement imminent, les investisseurs sont soudainement devenus moins préoccupés par les prix récents de ces actions et beaucoup plus préoccupés par leur exposition au risque sous-jacent. Par conséquent, le marché a rapidement réévalué les actions financières à un niveau beaucoup plus bas, une décision qui aurait totalement déconcerté un modèle autorégressif.

## Questions fréquemment posées

### À quoi sert ARIMA ?

ARIMA est une méthode de prévision ou de prévision des résultats futurs basée sur une série chronologique historique. Il est basé sur le concept statistique de corrélation en série, où les points de données passés influencent les points de données futurs.

### Quelles sont les différences entre les modèles autorégressifs et les modèles à moyenne mobile ?

ARIMA combine les fonctionnalités autorégressives avec celles des moyennes mobiles. Un processus autorégressif AR(1), par exemple, est un processus dans lequel la valeur actuelle est basée sur la valeur immédiatement précédente, tandis qu'un processus AR(2) est un processus dans lequel la valeur actuelle est basée sur les deux valeurs précédentes. Une moyenne mobile est un calcul utilisé pour analyser des points de données en créant une série de moyennes de différents sous-ensembles de l'ensemble de données complet afin de lisser l'influence des valeurs aberrantes. Grâce à cette combinaison de techniques, les modèles ARIMA peuvent prendre en compte les tendances, les cycles, la saisonnalité et d'autres types de données non statiques lors de la réalisation de prévisions.

### Comment fonctionnent les prévisions ARIMA ?

La prévision ARIMA est obtenue en connectant des données de séries chronologiques pour la variable d'intérêt. Un logiciel statistique identifiera le nombre approprié de décalages ou la quantité de différenciation à appliquer aux données et vérifiera la stationnarité. Il produira ensuite les résultats, qui sont souvent interprétés de la même manière qu'un modèle de régression linéaire multiple.

## Points forts

- Les modèles de moyenne mobile intégrée autorégressive (ARIMA) prédisent les valeurs futures en fonction des valeurs passées.

- ARIMA utilise des moyennes mobiles décalées pour lisser les données des séries chronologiques.

- Ils sont largement utilisés dans l'analyse technique pour prévoir les prix futurs des titres.

- Les modèles autorégressifs supposent implicitement que le futur ressemblera au passé.

- Par conséquent, ils peuvent s'avérer inexacts dans certaines conditions de marché, comme les crises financières ou les périodes de changement technologique rapide.

