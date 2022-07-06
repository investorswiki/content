---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 est une proposition d&#39;évolution de Binance qui introduit un mécanisme de gravure en temps réel dans Binance Smart Chain. Cela rend la tokenomics BNB plus dynamique et décentralisée.
---

# BEP-95
BEP-95 est une proposition d'évolution de Binance qui introduit un mécanisme de gravure en temps réel dans Binance Smart Chain. Il a été introduit pour rendre la tokenomics de BNB encore plus dynamique et décentraliser davantage le réseau.

Avec BEP-95, le réseau brûlera un ratio fixe des frais de gaz de chaque bloc que les validateurs collectent. Le ratio exact sera déterminé via les mécanismes de gouvernance de BSC. Les brûlures auront lieu même après que BSC ait atteint son objectif de 100 millions de BNB. En réduisant l'offre de BNB, une pression à la hausse est exercée sur le prix de la pièce. Le BEP peut également diminuer le nombre de délégants et de validateurs BNB reçus. Cependant, avec la pression à la hausse des prix, la valeur fiduciaire pourrait également augmenter, compensant toute réduction des pièces.

Pour mettre cela techniquement en œuvre, le réseau collecte les frais de gaz de chaque bloc et les répartit entre deux contrats intelligents :

**1. Contrat de récompense du système.** 1/16 des frais d'essence entreront dans le contrat de récompense du système jusqu'à ce qu'il atteigne un maximum de 100 BNB. Ces pièces seront utilisées comme subventions globales inter-chaînes.

**2. Contrat ValidatorSet.** Tous les autres frais de gaz entreront dans le contrat ValidatorSet et seront partagés quotidiennement avec les délégants et les validateurs via Binance Chain.

Pour effectuer une gravure, le contrat ValidatorSet a une variable burnRatio. Lors de la finalisation de chaque bloc, un validateur signera une transaction transférant ses frais de gaz aux contrats intelligents. La fonction de dépôt contient une logique de gravure qui déclenche la formule simple : burnRatio * gasFee. Cette somme sera ensuite transférée à l'adresse de gravure. Le burnRatio sera initialement fixé à 10 %.

Les validateurs BSC pourront voter via des propositions pour modifier le montant du burnRatio. Ce mécanisme de gouvernance se produit sur Binance Chain, et tout membre de la communauté peut soumettre une proposition pour examen avec un dépôt minimum de 2 000 BNB. Tous les BNB jalonnés derrière une proposition et lors d'un vote sont rendus après qu'une décision a été prise. Le quorum est atteint à 50 % et le changement sera immédiatement mis en œuvre via une communication inter-chaînes.

