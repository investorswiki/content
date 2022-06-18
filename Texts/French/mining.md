---
keywords: Crypto
title: Exploitation minière
description: Exploitation minière. La vérification des transactions sur un réseau blockchain, dans laquelle les transactions sont ajoutées en tant qu&#39;entrées dans le registre blockchain.
---

# Exploitation minière
Le minage est le processus par lequel les transactions de [crypto -monnaie](/cryptocurrency) sont collectées, vérifiées et enregistrées dans un registre numérique connu sous le nom de [blockchain](/blockchain). Le travail effectué par les mineurs est essentiel pour maintenir l'intégrité du réseau et est également responsable de l'introduction de nouvelles pièces dans le système.

Au sein du système bancaire traditionnel, la monnaie fiduciaire est imprimée et distribuée par les institutions financières et les autorités gouvernementales - mais pour la plupart des crypto-monnaies, l'émission de nouvelles pièces n'est pas entre les mains d'entités centralisées. Au lieu de cela, de nouvelles unités de crypto-monnaie sont générées via le processus d'extraction, qui suit un ensemble prédéfini de règles établies par le protocole sous-jacent. Alors que le protocole définit quelles sont les règles primaires, les algorithmes dits de consensus décrivent comment ces règles seront suivies (par exemple, lors de la validation des transactions).

En prenant Bitcoin comme exemple, les participants impliqués dans le processus de minage sont appelés nœuds de minage (ou simplement mineurs), et ils jouent un rôle clé dans la sécurité du réseau blockchain. Le travail d'un mineur consiste à rassembler les transactions non confirmées du pool de mémoire et à les organiser dans un [bloc candidat](/candidate-block) qu'il tentera de valider.

Lors de la création d'un bloc candidat, un mineur inclut une transaction dans laquelle il s'envoie la [récompense du bloc](/block-reward) à lui-même. Cette transaction est connue sous le nom de transaction coinbase et est souvent la première à être enregistrée dans un bloc.

Une fois la liste des transactions non confirmées formée, chaque transaction est hachée et leurs sorties sont organisées en paires. Ces paires sont ensuite hachées, produisant de nouvelles sorties qui sont également organisées en paires et hachées à nouveau. Le processus est répété jusqu'à ce qu'un seul hachage soit produit, appelé hachage racine ou racine de l' [arbre de Merkle](/merkle-tree).

Le hachage racine est ensuite combiné avec le hachage du bloc précédemment confirmé, ainsi qu'un nombre pseudo-aléatoire appelé [nonce](/nonce) (plus quelques autres paramètres). Ces éléments sont ensuite hachés, produisant le hachage de bloc pour ce bloc candidat.

Cependant, le mineur ne réussira que si la sortie résultante (hachage de bloc) pour son bloc candidat est inférieure à une valeur prédéterminée (cible). Par conséquent, le processus est basé sur des essais et des erreurs et ils doivent exécuter de nombreuses fonctions de hachage avec différents nonces afin de trouver un résultat valide. Le premier mineur à trouver un hachage valide valide son bloc candidat et obtient la récompense du bloc. L'ensemble du processus prend dix minutes, en moyenne.

Une fois qu'un bloc est validé, il est ajouté à la blockchain et les mineurs commencent à travailler sur le bloc suivant. Le hachage valide produit par les mineurs fonctionne comme la preuve de leur travail et c'est pourquoi l'algorithme de consensus Bitcoin est appelé Proof of Work. Chaque bloc confirmé a un hachage de bloc unique qui agit comme un identifiant.

La [récompense de bloc](/block-reward) est définie par le protocole Bitcoin et diminue tous les 210 000 blocs (environ quatre ans). Initialement, la récompense globale était de 50 BTC et est maintenant de 12,5 BTC.

