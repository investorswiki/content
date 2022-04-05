---
keywords: Crypto
title: Bloc candidat
description: Bloc candidat. Un bloc temporaire créé par un nœud minier (mineur) à ajouter à la blockchain pour recevoir les récompenses de bloc.
---

# Bloc candidat
En quelques mots, un bloc candidat est un bloc qu'un nœud de minage (mineur) essaie de miner afin de recevoir la récompense de bloc. Ainsi, un bloc candidat peut être décrit comme un bloc temporaire qui sera soit validé, soit rejeté par le réseau. Les mineurs se font concurrence pour valider le bloc suivant et l'ajouter à la blockchain, mais ils doivent d'abord créer un bloc candidat pour participer à la compétition minière.

Les blocs candidats sont créés par les mineurs en collectant et en organisant plusieurs transactions non confirmées à partir du pool de mémoire. Les transactions sont ensuite hachées pour former une structure [arborescente Merkle](/merkle-tree),. qui produira éventuellement une racine Merkle (ou hachage racine). La racine Merkle est un hachage unique qui représente tous les hachages précédents de cet arbre et, par conséquent, toutes les transactions incluses dans ce bloc particulier.

Le hachage racine - avec le hachage du bloc précédent et un nombre aléatoire appelé [nonce](/nonce) - est ensuite placé dans l'en-tête du bloc. L'en-tête de bloc est ensuite haché par le mineur, générant une sortie basée sur ces composants (hachage racine, hachage du bloc précédent et nonce) plus quelques autres éléments. La sortie résultante est le hachage de bloc et servira d'identifiant unique du bloc nouvellement généré (bloc candidat).

Pour être considérée comme valide, la sortie (hash de bloc) doit commencer par un certain nombre de zéros (inférieur à une valeur cible définie par le protocole). Cela signifie que le processus de minage est basé sur de multiples tentatives (essais et erreurs) car les nœuds de minage doivent exécuter une myriade de fonctions de hachage avec différentes valeurs de nonce jusqu'à ce qu'un hachage de bloc valide soit finalement produit. Le hachage de bloc produit est ce qui prouve que le mineur a fait son travail (d'où la preuve de travail).

Une fois qu'un mineur a trouvé un hachage de bloc valide, son bloc candidat sera diffusé au reste des nœuds du réseau, qui vérifiera l'authenticité du hachage. Si tout est bon, le bloc candidat sera alors enregistré dans la blockchain. À ce stade, chaque nœud de validation met à jour sa copie des données de la blockchain pour refléter le bloc miné récemment, et le mineur recevra la récompense du bloc.

