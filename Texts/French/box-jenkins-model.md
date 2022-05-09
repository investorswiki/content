---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Modèle Box-Jenkins
description: Le modèle Box-Jenkins est un modèle mathématique conçu pour prévoir les données d&#39;une série chronologique spécifiée.
---

# Modèle Box-Jenkins
## Qu'est-ce que le modèle Box-Jenkins ?

Le modèle Box-Jenkins est un modèle mathématique conçu pour prévoir des plages de données en fonction des entrées d'une [série temporelle spécifiée](/timeseries). Le modèle Box-Jenkins peut analyser plusieurs types de données de séries chronologiques à des fins de prévision.

Sa méthodologie utilise les différences entre les points de données pour déterminer les résultats. La méthodologie permet au modèle d'identifier les tendances à l'aide de l'autorégression, des moyennes mobiles et de la différenciation saisonnière pour générer des prévisions.

[modèles de moyenne mobile intégrée autorégressive (ARIMA)](/autoregressive-integrated-moving-average-arima) sont une forme du modèle de Box-Jenkins. Les termes ARIMA et Box-Jenkins sont parfois utilisés de manière interchangeable.

## Comprendre le modèle Box-Jenkins

Les modèles Box-Jenkins sont utilisés pour [prévoir](/forecasting) une variété de points de données ou de plages de données anticipés, y compris les données commerciales et les prix futurs des titres.

Le modèle Box-Jenkins a été créé par deux mathématiciens : George Box et Gwilym Jenkins. Les deux mathématiciens ont discuté des concepts qui composent ce modèle dans une publication de 1970 intitulée "Time Series Analysis: Forecasting and Control".

Les estimations des paramètres du modèle de Box-Jenkins peuvent être très compliquées. Par conséquent, comme pour les autres modèles de régression de séries chronologiques, les meilleurs résultats seront généralement obtenus grâce à l'utilisation de logiciels programmables. Le modèle Box-Jenkins est également généralement mieux adapté aux prévisions à court terme de 18 mois ou moins.

## Méthodologie Box-Jenkins

Le modèle Box-Jenkins peut être l'un des nombreux modèles d'analyse de séries chronologiques qu'un prévisionniste rencontrera lors de l'utilisation d'un logiciel de prévision programmé. Dans de nombreux cas, le logiciel sera programmé pour utiliser automatiquement la méthodologie de prévision la mieux adaptée en fonction des données de [séries chronologiques](/timeseries) à prévoir. Box-Jenkins est considéré comme le meilleur choix pour les ensembles de données qui sont pour la plupart stables et à faible [volatilité](/volatility).

Le modèle Box-Jenkins prévoit les données en utilisant trois principes : l'autorégression, la différenciation et la moyenne mobile. Ces trois principes sont respectivement appelés p, d et q. Chaque principe est utilisé dans l'analyse de Box-Jenkins ; ensemble, ils sont collectivement représentés par ARIMA (p, d, q).

Le processus d'autorégression (p) teste les données pour leur niveau de stationnarité. Si les données utilisées sont stationnaires, cela peut simplifier le processus de prévision. Si les données utilisées ne sont pas stationnaires, elles devront être différenciées (d). Les données sont également testées pour leur ajustement moyen mobile (ce qui est fait dans la partie q du processus d'analyse). Dans l'ensemble, l'analyse initiale des données les prépare à la prévision en déterminant les paramètres (p, d et q), qui sont ensuite appliqués pour élaborer une prévision.

> Un choc ponctuel affectera les valeurs ultérieures d'un modèle de Box-Jenkins infiniment dans le futur. Par conséquent, l'héritage de la crise financière perdure dans les modèles autorégressifs d'aujourd'hui.

>

## Moyenne mobile intégrée autorégressive (ARIMA)

Box-Jenkins est un type de modèle de moyenne mobile intégrée autorégressive (ARIMA) qui mesure la force d'une variable dépendante par rapport à d'autres variables changeantes. L'objectif du modèle est de prédire les mouvements futurs des valeurs mobilières ou des marchés financiers en examinant les différences entre les valeurs de la série plutôt qu'en passant par les valeurs réelles.

Un modèle ARIMA peut être compris en décrivant chacun de ses composants comme suit :

- [Autorégression (AR)](/autoregressive) : fait référence à un modèle qui montre une variable changeante qui régresse sur ses propres valeurs décalées ou antérieures.

- Intégré (I) : représente la différenciation des observations brutes pour permettre à la série temporelle de devenir stationnaire, c'est-à-dire que les valeurs des données sont remplacées par la différence entre les valeurs des données et les valeurs précédentes.

- [Moyenne mobile (MA)](/movingaverage) : intègre la dépendance entre une observation et une erreur résiduelle issue d'un modèle de moyenne mobile appliqué à des observations décalées.

## Prévoir les cours des actions

L'une des utilisations de l'analyse du modèle de Box-Jenkins consiste à prévoir les cours des [actions](/stock). Cette analyse est généralement construite et codée via le logiciel R. L'analyse aboutit à un résultat logarithmique, qui peut être appliqué à l'ensemble de données pour générer les prix prévus pour une période de temps spécifiée dans le futur.

Les modèles ARIMA sont basés sur l'hypothèse que les valeurs passées ont un effet résiduel sur les valeurs actuelles ou futures. Par exemple, un investisseur utilisant un modèle ARIMA pour prévoir les cours des actions supposerait que les nouveaux acheteurs et vendeurs de ces actions sont influencés par les transactions récentes sur le marché lorsqu'ils décident du montant à offrir ou à accepter pour le titre.

Bien que cette hypothèse soit valable dans de nombreuses circonstances différentes, elle n'est pas toujours vraie. Par exemple, dans les années qui ont précédé la crise financière de 2008, la plupart des investisseurs n'étaient pas conscients des risques posés par les vastes portefeuilles de [titres adossés à des créances hypothécaires](/mbs) (MBS) détenus par de nombreuses sociétés financières.

À cette époque, un investisseur utilisant un modèle autorégressif pour prédire la performance des actions financières américaines aurait eu de bonnes raisons de prédire une tendance continue de prix des actions stables ou en hausse dans ce secteur. Cependant, une fois qu'il est devenu de notoriété publique que de nombreuses institutions financières risquaient un effondrement imminent, les investisseurs sont soudainement devenus moins préoccupés par les prix récents de ces actions et beaucoup plus préoccupés par leur exposition au risque sous-jacent.

Par conséquent, le marché a rapidement réévalué les actions financières à un niveau beaucoup plus bas, une décision qui aurait totalement déconcerté un modèle autorégressif.

## Points forts

- Les modèles de moyenne mobile intégrée autorégressive (ARIMA) sont une forme du modèle de Box-Jenkins.

- Le modèle Box-Jenkins est le mieux adapté pour les prévisions dans des délais de 18 mois ou moins.

- La méthodologie repose sur l'hypothèse que les événements passés influencent les événements futurs.

- Le modèle Box-Jenkins est une méthodologie de prévision utilisant des études de régression sur des données de séries chronologiques.

