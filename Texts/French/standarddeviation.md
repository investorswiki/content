---
keywords: Business,Corporate Finance and Accounting,Financial Ratios
title: Calcul de l&#39;écart type
description: Qu&#39;est-ce que l&#39;écart type ? L&#39;écart type est une mesure qui mesure la variabilité des rendements d&#39;un titre au fil du temps. Il peut être utilisé pour mesurer la volatilité
---

# Calcul de l'écart type
## Qu'est-ce que l'écart type ?

L'écart type est une mesure qui mesure la variabilité des rendements d'un [titre au fil du temps.](/security) Il peut être utilisé pour évaluer la [volatilité](/volatility) en fonction des performances passées et comparer un rendement futur aux rendements passés. L'écart type peut également quantifier la distribution des rendements de portefeuilles individuels et peut être utilisé sur différents types d'actifs, y compris les [obligations](/bond),. les matières premières et la crypto-monnaie. Cet article, cependant, se concentre sur les actions.

L'écart type montre à quel point le rendement d'une action est éloigné de son rendement moyen pour une période et peut également déterminer si un rendement pour une certaine période est une valeur aberrante. Il est utile de s'appliquer pendant les périodes de volatilité du cours des actions d'une société cotée en bourse, car de fortes fluctuations à la hausse et à la baisse sur une courte période peuvent aider à déterminer le risque d'investissement par rapport à la récompense.

## Comment calculer l'écart type à l'aide d'une feuille de calcul (exemple : Apple)

Comprendre l'écart type signifie d'abord comprendre la variance car l'écart type, mathématiquement parlant, est la racine carrée de la variance. La variance indique l'écart entre chaque retour et la moyenne de l'ensemble des données de retour.

Un nombre supérieur à 0 indique que les rendements d'un ensemble sont éloignés de la moyenne et éloignés les uns des autres, tandis qu'un nombre nettement supérieur à 0 indique qu'ils sont beaucoup plus éloignés de la moyenne. Étant donné que la variance des données est au carré, l'écart type ramène les données à la même unité de mesure (dans le cas des actions, le pourcentage) en prenant la racine carrée.

**Remarque** : l'écart type est représenté dans les formules par σ, la lettre minuscule grecque pour sigma.

Le moyen le plus efficace de calculer l'écart type, en particulier avec un grand ensemble de données telles que les cours quotidiens des actions, est via une feuille de calcul. Vous trouverez ci-dessous un exemple de calcul de l'écart type des rendements des actions d'Apple sur une période de trois mois.

**Étape 1** : collectez des données quotidiennes sur une période de trois mois. Cela équivaut à peu près à environ 20 jours par mois, et le premier jour sert de prix de base pour calculer le premier pourcentage de variation. Calculez la variation quotidienne en pourcentage de l'action Apple et exprimez les données en pourcentage. **Remarque** : La formule est affichée dans la cellule ainsi que dans la zone de champ dans le coin supérieur gauche de la feuille de calcul. Le cours de clôture des actions d'Apple (exprimé en dollars américains) tient compte des ajustements, y compris les fractionnements, les dividendes et/ou les distributions de gains en capital.

**Étape 2** : Calculez la moyenne des rendements à l'aide de la fonction MOYENNE.

**Étape 3** : Calculez la variance des rendements à l'aide de la fonction VAR.

**Étape 4** : Calculez l'écart type des rendements à l'aide de la fonction STDEV. **Remarque** : La moyenne et l'écart type sont exprimés en pourcentage, tandis que la variance est un nombre décimal.

## Comment interpréter l'écart type

Dans l'exemple ci-dessus pour Apple, les données montrent que le rendement moyen pour la période de trois mois était de 0,08 %. La variance indique la distance entre la plage de nombres et la moyenne. Mais l'écart type montre exactement à quel point les rendements sont éloignés de la moyenne. Avec un écart type de 1,91 %, cela suggère que la fourchette est de plus ou moins 1,91 point de pourcentage par rapport à la moyenne, ce qui signifie que les rendements d'Apple ont tendance à varier de -1,83 % à 1,99 %.

### Écart type comme probabilité dans une distribution normale

L'écart type peut être mieux illustré par le modèle de distribution normale de la probabilité, qui donne une vue statistique de l'endroit où l'écart type pourrait être. Dans la distribution normale, la plupart des scénarios de probabilité tendent à se produire plus près de la moyenne. Des cas plus rares ont tendance à se produire vers l'extérieur, vers les zones qui s'aplatissent appelées queues.

Dans le graphique ci-dessous, une distribution normale a la forme d'une cloche, d'où son surnom de courbe en cloche, le milieu de la courbe représentant la moyenne. Les chiffres répertoriés horizontalement sous le graphique sont connus sous le nom de scores z, qui vont de -3 à 3. Ce sont des points d'écart type et sont articulés différemment de la formule d'écart type, qui est exprimée en pourcentage.

Le calcul de la distribution normale peut fournir des probabilités sur les paramètres des rendements potentiels. Disons qu'un day trader projette que les actions d'Apple gagnent 5% le jour après avoir annoncé des bénéfices et des revenus records pour le dernier trimestre déclaré. Quelle est la probabilité que l'action affiche un rendement de 5 % le lendemain ?

La formule de code z peut indiquer où se situerait le rendement sur le graphique de distribution normale.

En branchant le rendement, la moyenne et l'écart type projetés d'Apple tirés de la feuille de calcul ci-dessus :

> (5 % - 0,08 %) / 1,91 % = 2,57 écarts types au-dessus de la moyenne.

Un rendement potentiel de 5% sur les actions d'Apple serait de 2,57 écarts-types au-dessus de la moyenne, se situant entre 2 et 3 écarts-types par rapport à la moyenne. Statistiquement parlant, cela indique une probabilité de 2,28 % d'atteindre le rendement prévu de 5 %. Cette probabilité de 2,28 % est dérivée en soustrayant 95,44 % de 100 %, et la différence (4,56 %) est ensuite divisée par deux en raison des quantités égales de probabilité de chaque côté (négatif et positif) de la ligne symétrique dans le graphique de distribution normale. . Dans tous les cas, un gain quotidien de 5% sur les actions d'Apple ne serait pas courant.

Une autre façon d'interpréter la distribution normale est de dire que la probabilité que le rendement d'Apple (dans une fourchette de -1,83 % et 1,99 %) se situe entre -1 et 1 écart-type par rapport à la moyenne est de 68,26 %. La probabilité d'un écart type entre -2 et 2 est de 95,44 %, et entre -3 et 3, elle est de 99,74 %.

## Quel est le lien entre l'écart type et la volatilité ?

L'écart type peut montrer comment un rendement se rapporte à la moyenne. Un écart-type élevé indiquerait une volatilité élevée, et un rendement supérieur à la plage d'écart-type suggère qu'il s'agit d'une valeur aberrante. Une série de fluctuations à la hausse et à la baisse en dehors de cette fourchette pendant une période indiquerait également une forte volatilité.

## Points forts

- Il est calculé comme la racine carrée de la variance.

- L'écart-type, en finance, est souvent utilisé comme mesure du risque relatif d'un actif.

- L'écart type mesure la dispersion d'un jeu de données par rapport à sa moyenne.

- Une action volatile a un écart-type élevé, tandis que l'écart d'une action stable de premier ordre est généralement plutôt faible.

- En revanche, l'écart type calcule toute incertitude comme un risque, même lorsqu'elle est en faveur de l'investisseur, comme des rendements supérieurs à la moyenne.

## FAQ

### Que signifie un écart type élevé ?

Un grand écart-type indique qu'il y a beaucoup de variance dans les données observées autour de la moyenne. Cela indique que les données observées sont assez dispersées. Un écart-type petit ou faible indiquerait plutôt qu'une grande partie des données observées est étroitement regroupée autour de la moyenne.

### Pourquoi l'écart type est-il important ?

L'écart type est important car il peut aider les utilisateurs à évaluer les risques. Considérez une option d'investissement avec un rendement annuel moyen de 10% par an. Cependant, cette moyenne a été dérivée des rendements des trois dernières années de 50 %, -15 % et -5 %. En calculant l'écart type et en comprenant votre faible probabilité d'atteindre en fait une moyenne de 10 % au cours d'une année donnée, vous êtes mieux armé pour prendre des décisions éclairées et reconnaître le risque sous-jacent.

### Que vous dit l'écart type ?

L'écart type décrit la dispersion d'un ensemble de données. Il compare chaque point de données à la moyenne de tous les points de données, et l'écart type renvoie une valeur calculée qui décrit si les points de données sont proches ou s'ils sont étalés. Dans une distribution normale, l'écart type vous indique à quel point les valeurs sont éloignées de la moyenne.

### Comment calculez-vous l'écart type ?

L'écart type est calculé comme la racine carrée de la variance. Alternativement, il est calculé en trouvant la moyenne d'un ensemble de données, en trouvant la différence de chaque point de données à la moyenne, en mettant au carré les différences, en les additionnant, en divisant par le nombre de points dans l'ensemble de données moins 1, et en trouvant le carré racine.

### Comment trouvez-vous rapidement l'écart type ?

Si vous regardez visuellement la distribution de certaines données observées, vous pouvez voir si la forme est relativement maigre par rapport à la graisse. Les distributions plus grosses ont des écarts-types plus grands. Alternativement, Excel a intégré des fonctions d'écart type en fonction de l'ensemble de données.

