---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Modèle de tarification des options binomiales
description: Un modèle d&#39;évaluation d&#39;options binomial est une méthode d&#39;évaluation d&#39;options qui utilise une procédure itérative et permet la spécification du nœud dans une période définie.
---

# Modèle de tarification des options binomiales
## Qu'est-ce que le modèle de tarification de l'option binomiale ?

Le modèle d'évaluation d'options binomial est une méthode d' [évaluation d'options](/valuation) développée en 1979. Le modèle d'évaluation d'options binomial utilise une procédure itérative, permettant la spécification de nœuds, ou de points dans le temps, pendant la période entre la date d'évaluation et la [date d'](/expiration-date) [expiration de l'option](/expiration-date).

Le modèle réduit les possibilités de variations de prix et supprime la possibilité d' [arbitrage](/arbitrage). Un exemple simplifié d' [arbre binomial](/binomial_tree) pourrait ressembler à ceci :

<!--87C9D3D79FF63D08201E6E848035602D-->

## Principes de base du modèle de tarification des options binomiales

Avec les modèles de prix d'option binomiaux, les hypothèses sont qu'il y a deux résultats possibles, d'où la partie binomiale du modèle. Avec un modèle de tarification, les deux résultats sont une hausse ou une baisse. Le principal avantage d'un modèle de tarification d'options binomial est qu'il est mathématiquement simple. Or ces modèles peuvent devenir complexes dans un modèle multi-période.

Contrairement au [modèle Black-Scholes](/blackscholes),. qui fournit un résultat numérique basé sur des intrants, le modèle binomial permet le calcul de l'actif et de l'option pour plusieurs périodes ainsi que la plage de résultats possibles pour chaque période (voir ci-dessous).

L'avantage de cette vue multi-période est que l'utilisateur peut visualiser l'évolution du prix de l'actif d'une période à l'autre et évaluer l'option en fonction des décisions prises à différents moments. Pour une [option basée aux États-Unis](/americanoption),. qui peut être exercée à tout moment avant la [date d'expiration](/expirationdate),. le modèle binomial peut fournir un aperçu du moment où l'exercice de l'option peut être conseillé et du moment où elle doit être conservée pendant des périodes plus longues.

En regardant l' [arbre binomial](/binomial_tree) des valeurs, un trader peut déterminer à l'avance quand une décision sur un [exercice](/exercise) peut se produire. Si l'option a une valeur positive, il y a possibilité d'exercice alors que si l'option a une valeur inférieure à zéro, elle doit être détenue pendant des périodes plus longues.

## Calcul du prix avec le modèle binomial

La méthode de base de calcul du modèle d'option binomial consiste à utiliser la même probabilité à chaque période de succès et d'échec jusqu'à l'expiration de l'option. Cependant, un trader peut incorporer différentes probabilités pour chaque période en fonction des nouvelles informations obtenues au fil du temps.

Un arbre binomial est un outil utile lors de la tarification [des options américaines](/americanoption) et [des options intégrées](/embeddedoption). Sa simplicité est à la fois son avantage et son inconvénient. L'arbre est facile à modéliser mécaniquement, mais le problème réside dans les valeurs possibles que l'actif sous-jacent peut prendre en une période de temps. Dans un modèle d'arbre binomial, l'actif sous-jacent ne peut valoir qu'exactement l'une des deux valeurs possibles, ce qui n'est pas réaliste, car les actifs peuvent valoir n'importe quel nombre de valeurs dans une plage donnée.

Par exemple, il peut y avoir 50/50 de chances que le prix de l'actif sous-jacent augmente ou diminue de 30 % en une période. Pour la deuxième période, cependant, la probabilité que le prix de l'actif sous-jacent augmente peut atteindre 70/30.

Par exemple, si un investisseur évalue un [puits de pétrole](/exploratory-well),. cet investisseur n'est pas sûr de la valeur de ce puits de pétrole, mais il y a 50/50 de chances que le prix augmente. Si les prix du pétrole augmentent au cours de la période 1, ce qui rend le puits de pétrole plus précieux et que les [fondamentaux du marché](/fundamentals) indiquent maintenant des augmentations continues des prix du pétrole, la probabilité d'une nouvelle appréciation des prix peut maintenant être de 70 %. Le modèle binomial permet cette flexibilité ; le modèle Black-Scholes ne le fait pas.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Exemple concret de modèle de tarification d'options binomiales

Un exemple simplifié d' [arbre binomial](/binomial_tree) ne comporte qu'une seule étape. Supposons qu'il existe une action dont le prix est de 100 $ par action. En un mois, le prix de cette action augmentera de 10 $ ou baissera de 10 $, créant cette situation :

- **Cours de l'action** = 100 $

- **Cours de l'action dans un mois (état supérieur)** = 110 $

- **Cours de l'action dans un mois (état bas)** = 90 $

Ensuite, supposons qu'il existe une option d'achat disponible sur cette action qui expire dans un mois et a un prix d'exercice de 100 $. À la hausse, cette option d'achat vaut 10 $ et à la baisse, elle vaut 0 $. Le modèle binomial peut calculer ce que devrait être le prix de l'option d'achat aujourd'hui.

À des fins de simplification, supposons qu'un investisseur achète la moitié d'une action et vende ou vende une option d'achat. L'investissement total aujourd'hui est le prix d'une demi-action moins le prix de l'option, et les gains possibles à la fin du mois sont :

- **Coût aujourd'hui** = 50 $ - prix de l'option

- **Valeur du portefeuille** (état supérieur) = 55 $ - max (110 $ - 100 $, 0) = 45 $

- **Valeur du portefeuille** (état bas) = 45 $ - max(90 $ - 100 $, 0) = 45 $

Le gain du portefeuille est égal, quelle que soit l'évolution du cours de l'action. Compte tenu de ce résultat, en supposant qu'il n'y a pas d'opportunités d'arbitrage, un investisseur devrait gagner le taux sans risque au cours du mois. Le coût aujourd'hui doit être égal au gain actualisé au taux sans risque pendant un mois. L'équation à résoudre est donc :

- **Prix de l'option** = 50 $ - 45 $ xe ^ (-taux sans risque x T), où e est la constante mathématique 2,7183.

En supposant que le taux sans risque est de 3 % par an et que T est égal à 0,0833 (un divisé par 12), le prix de l'option d'achat est aujourd'hui de 5,11 $.

Le modèle d'évaluation d'options binomial présente deux avantages pour les vendeurs d'options par rapport au modèle Black-Scholes. Le premier est sa simplicité, qui permet moins d'erreurs dans l'application commerciale. La seconde est son opération itérative, qui ajuste les prix en temps opportun afin de réduire la possibilité pour les acheteurs d'exécuter des stratégies d'arbitrage.

Par exemple, puisqu'il fournit un flux d'évaluations pour un [dérivé](/derivative) pour chaque nœud dans un laps de temps, il est utile pour évaluer des dérivés tels que les options américaines, qui peuvent être exécutées à tout moment entre la date d'achat et la date d'expiration. Il est également beaucoup plus simple que d'autres modèles de tarification tels que le modèle Black-Scholes.

## Points forts

- Le modèle est intuitif et est utilisé plus fréquemment dans la pratique que le modèle bien connu de Black-Scholes.

- Avec le modèle, il y a deux résultats possibles à chaque itération : un mouvement vers le haut ou un mouvement vers le bas qui suit un arbre binomial.

- Le modèle binomial d'évaluation des options évalue les options à l'aide d'une approche itérative utilisant plusieurs périodes pour évaluer les options américaines.

