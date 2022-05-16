---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Crypto-monnaie)
description: Une racine Merkle contient des informations sur chaque hachage de transaction qui s&#39;est jamais trouvé sur un bloc particulier dans une blockchain.
---

# Merkle Root (Crypto-monnaie)
## Qu'est-ce qu'une racine de Merkle ?

Une racine Merkle est le [hachage](/hash) de tous les hachages de toutes les transactions qui font partie d'un bloc dans un réseau [blockchain](/blockchain).

## Comprendre une racine Merkle

Une blockchain est composée de différents blocs qui sont liés les uns aux autres (d'où le nom de blockchain). Un arbre de hachage, ou l' [arbre de Merkle](/merkle-tree),. encode les données de la blockchain de manière efficace et sécurisée. Il permet la vérification rapide des données de la blockchain, ainsi que le déplacement rapide de grandes quantités de données d'un nœud informatique à l'autre sur le réseau de blockchain peer-to-peer.

Chaque transaction effectuée sur le réseau blockchain est associée à un hachage. Cependant, ces hachages ne sont pas stockés dans un ordre séquentiel sur le bloc, mais plutôt sous la forme d'une structure arborescente telle que chaque hachage est lié à son parent suivant une relation arborescente parent-enfant.

Puisqu'il existe de nombreuses transactions stockées sur un bloc particulier, tous les hachages de transaction dans le bloc sont également hachés, ce qui se traduit par une racine Merkle.

Par exemple, considérons un bloc de sept transactions. Au niveau le plus bas (appelé le niveau feuille), il y aura quatre hachages de transaction. Au niveau un au-dessus du niveau feuille, il y aura deux hachages de transaction, chacun se connectant à deux hachages qui se trouvent en dessous d'eux au niveau feuille. En haut (niveau deux), il y aura le dernier hachage de transaction appelé la racine, et il se connectera aux deux hachages en dessous (au niveau un).

En fait, vous obtenez un arbre binaire à l'envers, chaque nœud de l'arbre se connectant à seulement deux nœuds en dessous (d'où le nom "arbre binaire"). Il a un hachage racine en haut, qui se connecte à deux hachages au niveau un, chacun se connectant à nouveau aux deux hachages au niveau trois (niveau feuille), et la structure continue en fonction du nombre de hachages de transaction.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Le hachage commence aux nœuds de niveau le plus bas (niveau feuille) et les quatre hachages sont inclus dans le hachage des nœuds qui y sont liés au niveau un. De même, le hachage se poursuit au niveau un, ce qui conduit à des hachages de hachages atteignant des niveaux supérieurs, jusqu'à ce qu'il atteigne le seul hachage racine supérieur.

Ce hachage racine est appelé racine de Merkle et, en raison de la liaison arborescente des hachages, il contient toutes les informations sur chaque hachage de transaction qui existe sur le bloc. Il offre une valeur de hachage en un seul point qui permet de valider tout ce qui est présent sur ce bloc.

Par exemple, si l'on doit vérifier une transaction qui prétend provenir du bloc #137, il suffit de vérifier l'arbre Merkle du bloc, sans se soucier de vérifier quoi que ce soit sur les autres blocs de la blockchain, comme le bloc #136 ou le bloc # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Entrez la racine Merkle, ce qui accélère encore la vérification. Puisqu'il contient toutes les informations sur l'arbre entier, il suffit de vérifier ce hachage de transaction, son nœud frère (s'il existe), puis de remonter jusqu'à ce qu'il atteigne le sommet.

Essentiellement, l'arbre Merkle et le mécanisme racine Merkle réduisent considérablement les niveaux de hachage à effectuer, permettant une vérification et des transactions plus rapides.

## Points forts

- Les racines de Merkle sont au cœur du calcul nécessaire pour maintenir les crypto-monnaies comme le bitcoin et l'éther.

- Les racines de Merkle sont utilisées dans la crypto-monnaie pour s'assurer que les blocs de données transmis entre pairs sur un réseau peer-to-peer sont entiers, intacts et inchangés.

- Une racine Merkle est un moyen mathématique simple de vérifier les données sur un arbre Merkle.

