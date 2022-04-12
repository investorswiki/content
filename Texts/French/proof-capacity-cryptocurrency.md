---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Preuve de capacité (Crypto-monnaie)
description: La preuve de capacité est un mécanisme de consensus qui utilise l&#39;espace disque dur d&#39;un nœud minier pour décider des droits miniers sur le réseau blockchain.
---

# Preuve de capacité (Crypto-monnaie)
## Qu'est-ce que la preuve de capacité (PoC) pour les crypto-monnaies ?

La preuve de capacité (PoC) est un algorithme de [mécanisme de consensus](/consensus-mechanism-cryptocurrency) utilisé dans les chaînes de blocs qui permet aux appareils de [minage](/bitcoin-mining) du réseau d'utiliser leur espace disque disponible pour décider des droits de minage et valider les transactions. Cela contraste avec l'utilisation de la puissance de calcul du dispositif de minage (comme dans l' algorithme [de preuve de travail](/proof-work) ) ou de la participation du mineur dans les crypto-monnaies (comme dans l' algorithme [de preuve de participation](/proof-stake-pos) ).

## Comprendre la preuve de capacité

La preuve de capacité est apparue comme l'une des nombreuses solutions alternatives au problème de la consommation d'énergie élevée dans les systèmes de preuve de travail (PoW) et de la thésaurisation de crypto-monnaie dans les systèmes de preuve de participation (PoS).

La preuve de capacité permet aux dispositifs de minage, également appelés nœuds, sur le réseau [blockchain](/blockchain) d'utiliser l'espace vide de leur disque dur pour miner les crypto- [monnaies disponibles](/cryptocurrency).

Au lieu de modifier à plusieurs reprises les nombres dans l'en-tête de bloc et le hachage répété pour la valeur de la solution comme dans un système PoW, PoC fonctionne en stockant une liste de solutions possibles sur le disque dur du dispositif d'exploration avant même que l'activité minière ne commence.

Plus le disque dur est grand, plus on peut stocker de valeurs de solution possibles sur le disque dur, plus un mineur a de chances de faire correspondre la valeur de hachage requise de sa liste, ce qui augmente les chances de gagner la récompense de minage.

Pour faire une analogie, si les récompenses de loterie sont basées sur la correspondance du plus grand nombre de numéros sur le ticket gagnant, alors un joueur avec une liste plus longue de solutions possibles aura de meilleures chances de gagner. De plus, le joueur est autorisé à continuer à utiliser les numéros de bloc de billets de loterie encore et encore à plusieurs reprises.

[Burstcoin](/burstcoin) est une crypto-monnaie qui utilise un système de preuve de capacité. Les autres pièces qui l'utilisent sont Storj, Chia et SpaceMint.

## Comment fonctionne la PoC : tracer et exploiter

Le protocole de preuve de capacité implique un processus en deux étapes qui implique le traçage et l'exploration.

Tout d'abord, le disque dur est tracé : la liste de toutes les valeurs [nonce possibles est créée par hachage répété de données, y compris le compte d'un mineur.](/nonce) Chacun de ces nonces contient 8192 hachages, qui sont numérotés de 0 à 8191. Tous les hachages sont appariés en "scoops", ce qui signifie que les hachages adjacents sont combinés pour former une paire de deux. Par exemple, les hachages 0 et 1 constituent le scoop 0, les hachages 2 et 3 constituent le hachage 1, etc.

La deuxième étape implique l'exercice minier proprement dit, au cours duquel un mineur calcule un nombre de scoop. Par exemple, si un mineur commence l'activité minière et génère un scoop numéro 38, le mineur ira alors au scoop numéro 38 du nonce 1 et utilisera les données de ce scoop pour calculer une valeur limite.

Le processus est répété pour calculer le délai pour chaque nonce détenu sur le disque dur du mineur. Suite au calcul de tous les délais, celui avec le délai minimum est sélectionné par le mineur.

Un délai représente la durée en secondes qui doit s'écouler depuis que le dernier bloc a été forgé avant qu'un mineur ne soit autorisé à forger un nouveau bloc. Si personne d'autre n'a forgé un bloc dans ce délai, le mineur peut forger un bloc et réclamer la récompense du bloc.

Par exemple, si le mineur X propose un délai minimum de 36 secondes et qu'aucun autre mineur ne peut forger le bloc dans les 36 prochaines secondes, X s'assurera la possibilité de forger le bloc suivant et d'être récompensé.

## Avantages et inconvénients de la preuve de capacité

Le PoC présente plusieurs avantages par rapport aux systèmes PoW et PoS, ainsi que certains inconvénients importants, notamment :

<h5><a href="">TTT</a></h5>

## Points forts

- Le principal avantage d'un système PoC est son efficacité par rapport aux systèmes de preuve de travail (PoW) et de preuve de participation (PoS).

- Les chaînes de blocs fonctionnant sur preuve de capacité incluent Storj, Burst, Chia et SpaceMint.

- Les systèmes d'authentification par preuve de capacité (PoC) utilisent de l'espace libre sur le disque dur d'un appareil pour stocker des solutions à un problème de hachage de crypto-monnaie.

