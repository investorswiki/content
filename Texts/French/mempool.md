---
keywords: Crypto
title: Mempool
description: Memopool. Mécanisme d&#39;un nœud pour garder une trace des transactions non confirmées que le nœud a vues (mais qui n&#39;ont pas encore été ajoutées à un bloc).
---

# Mempool
Un mempool (une contraction de la mémoire et du pool) est le mécanisme d'un nœud de crypto-monnaie pour stocker des informations sur les transactions non confirmées. Il agit comme une sorte de salle d'attente pour les transactions qui n'ont pas encore été incluses dans un [bloc](/block).

Lorsqu'une transaction est diffusée, elle est envoyée d'un nœud à ses pairs, qui la transmettront ensuite à leurs pairs. Cela continue jusqu'à ce que la transaction ait été largement propagée, prête pour que les mineurs l'ajoutent à un bloc. Il est vital que cette zone tampon existe, car les transactions ne sont pas immédiatement ajoutées à la blockchain.

Les nœuds exécuteront une série de vérifications pour s'assurer que la transaction est valide, c'est-à-dire vérifier que les signatures sont correctes, que les sorties ne dépassent pas les entrées et que les fonds n'ont pas déjà été dépensés. S'il ne remplit pas ces conditions, il est rejeté.

On parle souvent de mempool, mais il faut préciser qu'il n'existe pas de pool universel partagé par tous les nœuds. Chacun est configuré différemment et reçoit des transactions à des moments différents. Les appareils bas de gamme aux ressources limitées peuvent ne consacrer que de petites quantités de mémoire à la journalisation des transactions, tandis que les appareils haut de gamme peuvent en consacrer beaucoup plus.

Comme les mineurs sont principalement motivés par les profits, les transactions avec des frais plus élevés sont celles qui sont les plus susceptibles d'être éliminées du mempool en premier lorsqu'elles sont confirmées. Il est difficile d'estimer avec précision les frais, en particulier lorsque l'espace de bloc est limité et que la demande est élevée, mais le mempool fournit un point de départ.

Pour estimer les frais, on peut se tourner vers les transactions non confirmées en cours. Il va de soi que les utilisateurs ne devraient pas payer trop cher en période de faible débit. Ils ne doivent pas non plus sous-payer les transactions urgentes aux heures de pointe, car cela peut prendre un certain temps avant que cela ne soit confirmé. En tenant compte de la répartition des frais à un moment donné, ils peuvent faire une estimation éclairée de la rapidité avec laquelle leur transaction sera incluse.

