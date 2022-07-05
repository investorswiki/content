---
keywords: Economy,Economics,Behavioral Economics
title: Induction en arrière
description: Dans la théorie des jeux, l&#39;induction à rebours est le processus consistant à déduire à rebours de la fin d&#39;un problème ou d&#39;un scénario pour déduire une séquence d&#39;actions optimales.
---

# Induction en arrière
## Qu'est-ce que l'induction à rebours ?

L'induction vers l'arrière dans [la théorie des jeux](/gametheory) est un processus itératif de raisonnement vers l'arrière dans le temps, à partir de la fin d'un problème ou d'une situation, pour résoudre une forme extensive finie et des jeux séquentiels, et déduire une séquence d'actions optimales.

## L'induction en arrière expliquée

L'induction à rebours est utilisée pour résoudre des jeux depuis que John von Neumann et Oskar Morgenstern ont établi la théorie des jeux comme matière académique lorsqu'ils ont publié leur livre **Theory of Games and Economic Behavior** en 1944.

A chaque étape du jeu, l'induction à rebours détermine la stratégie optimale du joueur qui effectue le dernier coup de la partie. Ensuite, l'action optimale de l'avant-dernier joueur en mouvement est déterminée, en prenant l'action du dernier joueur comme donnée. Ce processus se poursuit en arrière jusqu'à ce que la meilleure action pour chaque instant ait été déterminée. En effet, on détermine l' [équilibre de Nash](/nash-equilibrium) de chaque sous-jeu du jeu original.

Cependant, les résultats déduits de l'induction à rebours échouent souvent à prédire le jeu humain réel. Des études expérimentales ont montré que le comportement « rationnel » (tel que prédit par la théorie des jeux) se manifeste rarement dans la vie réelle. Les joueurs irrationnels peuvent en fait finir par obtenir des gains plus élevés que prévu par l'induction à rebours, comme illustré dans le [jeu du mille-pattes](/centipede-game).

Dans le jeu du mille-pattes, deux joueurs ont alternativement la possibilité de prendre une plus grande part d'un pot d'argent croissant ou de passer le pot à l'autre joueur. Les gains sont arrangés de sorte que si le pot est passé à son adversaire et que l'adversaire prend le pot au tour suivant, on reçoit un peu moins que si on avait pris le pot à ce tour. Le jeu se termine dès qu'un joueur prend la réserve, ce joueur obtenant la plus grande partie et l'autre joueur obtenant la plus petite partie.

## Exemple d'induction en arrière

Par exemple, supposons qu'Izaz passe en premier et doive décider s'il doit « prendre » ou « passer » la réserve, qui s'élève actuellement à 2 $. S'ils prennent, alors Izaz et Jian gagnent 1 $ chacun, mais si Izaz passe, la décision de prendre ou de passer doit maintenant être prise par Jian. Si Jian prend, ils obtiennent 3 $ (c'est-à-dire la réserve précédente de 2 $ + 1 $) et Izaz obtient 0 $. Mais si Jian passe, Izaz doit maintenant décider de prendre ou de passer, et ainsi de suite. Si les deux joueurs choisissent toujours de passer, ils reçoivent chacun un gain de 100 $ à la fin de la partie.

Le but du jeu est que si Izaz et Jian coopèrent tous les deux et continuent à passer jusqu'à la fin du jeu, ils obtiennent le paiement maximum de 100 $ chacun. Mais s'ils se méfient de l'autre joueur et s'attendent à ce qu'il «prenne» à la première occasion, l'équilibre de Nash prédit que les joueurs prendront la réclamation la plus faible possible (1 $ dans ce cas).

L'équilibre de Nash de ce jeu, où aucun joueur n'a d'incitation à s'écarter de la stratégie qu'il a choisie après avoir examiné le choix d'un adversaire, suggère que le premier joueur remporterait le pot dès le premier tour du jeu. Cependant, en réalité, relativement peu de joueurs le font. En conséquence, ils obtiennent un gain plus élevé que le gain prédit par l'analyse des équilibres.

## Résolution de jeux séquentiels à l'aide de l'induction inverse

Ci-dessous, un simple jeu séquentiel entre deux joueurs. Les étiquettes contenant le joueur 1 et le joueur 2 sont les ensembles d'informations pour les joueurs un ou deux, respectivement. Les nombres entre parenthèses au bas de l'arbre sont les gains à chaque point respectif. Le jeu est également séquentiel, donc le joueur 1 prend la première décision (gauche ou droite) et le joueur 2 prend sa décision après le joueur 1 (haut ou bas).

<!--360C571136D68BDF7B1BE984014B1A1C-->

L'induction à rebours, comme toute théorie des jeux, utilise les hypothèses de rationalité et de maximisation, ce qui signifie que le joueur 2 maximisera son gain dans une situation donnée. À chaque ensemble d'informations, nous avons deux choix, quatre en tout. En éliminant les choix que le joueur 2 ne choisira pas, nous pouvons affiner notre arbre. De cette manière, nous marquerons les lignes en bleu qui maximisent le gain du joueur pour l'ensemble d'informations donné.

<!--E78C02A07C982A1B447ED0D16A9FCE40-->

Après cette réduction, le joueur 1 peut maximiser ses gains maintenant que les choix du joueur 2 sont connus. Le résultat est un équilibre trouvé par induction vers l'arrière du joueur 1 choisissant « à droite » et du joueur 2 choisissant « en haut ». Vous trouverez ci-dessous la solution du jeu avec le chemin d'équilibre en gras.

<!--4DEC4364358F0D1CB7D219006F74D652-->

Par exemple, on pourrait facilement mettre en place un jeu similaire à celui ci-dessus en utilisant des entreprises comme joueurs. Ce jeu pourrait inclure des scénarios [de lancement de produits .](/rollout) Si la société 1 voulait lancer un produit, que pourrait faire la société 2 en réponse ? La société 2 lancera-t-elle un produit concurrent similaire ? En [prévoyant](/forecasting) les ventes de ce nouveau produit dans différents scénarios, nous pouvons mettre en place un jeu pour prédire comment les événements pourraient se dérouler. Vous trouverez ci-dessous un exemple de la façon dont on pourrait modéliser un tel jeu.

<!--D102F649421403ABBDD56A5C1B29CF03-->

