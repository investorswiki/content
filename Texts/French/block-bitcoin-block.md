---
keywords: Investing,Cryptocurrency,Blockchain
title: Bloquer (Bloc Bitcoin)
description: Les blocs sont des structures de données dans une base de données où les données de transaction de crypto-monnaie sont enregistrées en permanence ; une fois écrit, il ne peut pas être modifié ou supprimé.
---

# Bloquer (Bloc Bitcoin)
## Qu'est-ce qu'un bloc (Blockchain Block) ?

Les blocs sont des structures de données dans la base de données de la blockchain, où les données de transaction dans une blockchain de crypto-monnaie sont enregistrées en permanence. Un bloc enregistre tout ou partie des transactions les plus récentes non encore validées par le réseau. Une fois les données validées, le bloc est fermé. Ensuite, un nouveau bloc est créé pour que de nouvelles transactions soient saisies et validées.

Un bloc est donc un stockage permanent d'enregistrements qui, une fois écrits, ne peuvent pas être modifiés ou supprimés.

## Comment fonctionne un bloc (Blockchain Block)

Un réseau [blockchain](/blockchain) est témoin d'une grande activité de transaction. Lorsqu'il est utilisé dans la crypto-monnaie, le maintien d'un enregistrement de ces transactions aide le système à suivre la quantité utilisée ou non et les parties impliquées. Les transactions effectuées pendant une période donnée sont enregistrées dans un fichier appelé bloc, qui est la base du réseau blockchain.

Un bloc stocke des informations. Un bloc contient de nombreuses informations, mais il n'occupe pas une grande quantité d'espace de stockage. Les blocs incluent généralement ces éléments, mais cela peut varier d'un type à l'autre :

- **Magic number** : un nombre contenant des valeurs spécifiques qui identifient ce bloc comme faisant partie du réseau d'une crypto-monnaie particulière.

- **Blocksize** : définit la taille limite du bloc afin que seule une quantité spécifique d'informations puisse y être écrite.

- **En-tête de bloc** : Contient des informations sur le bloc.

- **Compteur de transactions** : un nombre qui représente le nombre de transactions stockées dans le bloc.

- **Transactions** : une liste de toutes les transactions d'un bloc.

L'élément transaction est le plus grand car il contient le plus d'informations. Il est suivi en taille de stockage par l'en-tête de bloc, qui comprend ces sous-éléments :

- **Version** : la version de la crypto-monnaie utilisée.

- **Hachage du bloc précédent** : Contient un hachage (numéro crypté) de l'en-tête du bloc précédent.

- **Hash Merkle root** : Hash des transactions dans l' [arbre Merkle](/merkle-tree) du bloc courant.

- **Heure** : un horodatage pour placer le bloc dans la blockchain.

- **Bits** : La cote de difficulté du hachage cible, indiquant la difficulté à résoudre le nonce.

- **Nonce** : Le numéro crypté qu'un mineur doit résoudre pour vérifier le bloc et le fermer.

Un nombre de 32 bits dans l'en-tête est appelé un nonce—le programme de minage utilise des nombres aléatoires pour "deviner" le nonce dans le [hachage](/hash). Lorsqu'un nonce est vérifié, le hachage est résolu lorsque le nonce, ou un nombre inférieur à celui-ci, est deviné. Ensuite, le réseau ferme ce bloc, en génère un nouveau avec un en-tête et le processus se répète.

Différents mécanismes sont utilisés pour parvenir à un consensus; le plus populaire pour la crypto-monnaie est [la preuve de travail](/proof-work) (PoW), la preuve de participation (PoS) le devenant davantage en raison de la consommation d'énergie réduite par rapport au PoW.

## Relation de l'exploitation minière aux blocs

L'exploitation minière est le terme utilisé pour résoudre le nombre qui est le nonce, le seul nombre qui peut être modifié dans un en-tête de bloc. C'est également le processus utilisé par le réseau de la crypto-monnaie si la preuve de travail est utilisée dans le protocole.

L'extraction de crypto-monnaie est généralement considérée comme un problème mathématique complexe. il s'agit en fait d'un nombre aléatoire généré par hachage. Le hachage est le processus de cryptage des informations à l'aide de la méthode de cryptage utilisée par une crypto-monnaie. Par exemple, Bitcoin utilise SHA256 pour son algorithme de chiffrement. Pour qu'un mineur génère le numéro "gagnant", le programme de minage doit utiliser SHA 256 pour hacher des nombres aléatoires et les placer dans le nonce pour voir s'il s'agit d'une correspondance.

> Résoudre le hachage de nombres aléatoires dans le cadre du protocole de preuve de travail est ce qui demande tant d'énergie et de puissance de calcul. Un vaste réseau de mineurs et suffisamment d'énergie pour alimenter un petit pays sont nécessaires pour le faire fonctionner.

>

La difficulté réside dans le fait que tous les en-têtes de bloc précédents sont chiffrés de manière aléatoire. Par conséquent, l'en-tête de bloc actuel est un nombre chiffré généré de manière aléatoire sur la base des nombres chiffrés générés de manière aléatoire des blocs précédents et des informations du bloc actuel.

## Autres utilisations de blocs et de chaînes de blocs

Parce que la plupart des définitions de blockchain font référence à Bitcoin parce que c'était la première crypto-monnaie à en utiliser une, de nombreuses personnes associent des blocs et des blockchains à Bitcoin. Cependant, d'autres crypto-monnaies utilisent également des blocs et des chaînes de blocs. Il est important de noter que le réseau d'Ethereum possède une crypto-monnaie appelée ether qui utilise également des blocs et une blockchain.

Cependant, Ethereum et sa blockchain ont été conçus pour de multiples utilisations qui vont bien au-delà de la crypto-monnaie. Par exemple, des jetons non fongibles, des contrats intelligents, des applications financières décentralisées, etc. ont été développés à l'aide d'Ethereum.

## Points forts

- Les blocs et les blockchains ne sont pas utilisés uniquement par les crypto-monnaies. Ils ont également de nombreuses autres utilisations.

- Les blocs sont identifiés par de longs nombres qui incluent des informations de transaction chiffrées des blocs précédents et de nouvelles informations de transaction.

- Les blocs et les informations qu'ils contiennent doivent être vérifiés par un réseau avant que de nouveaux blocs puissent être créés.

- Un bloc est un endroit dans une blockchain où les informations sont stockées et cryptées.

## FAQ

### Qu'est-ce que la Blockchain en termes simples ?

Une blockchain est une base de données qui stocke et crypte les informations de manière liée, de sorte que les informations précédentes ne puissent pas être modifiées, et un groupe vérifie toutes les entrées avant qu'elles ne soient finalisées par un consensus - un accord sur l'exactitude des données.

### À quoi servent les blockchains ?

Les chaînes de blocs sont utilisées dans la crypto-monnaie, les applications financières décentralisées, les jetons non fongibles, avec de plus en plus d'utilisations en développement constant.

### Comment un bloc Blockchain est-il créé ?

Les blocs sont créés lorsque les mineurs ou les validateurs de blocs valident avec succès les informations chiffrées dans l'en-tête de bloc, ce qui incite à la création d'un nouveau bloc.

