---
keywords: Investing,Cryptocurrency,Bitcoin
title: Preuve de travail (PoW)
description: La preuve de travail décrit le processus qui permet au réseau bitcoin de rester robuste en rendant difficile le processus d&#39;extraction ou d&#39;enregistrement des transactions.
---

# Preuve de travail (PoW)
## Qu'est-ce qu'une preuve de travail (PoW) ?

La preuve de travail (PoW) décrit un système qui nécessite un effort non négligeable mais réalisable afin de dissuader les utilisations frivoles ou malveillantes de la puissance de calcul, telles que l'envoi de spams ou le lancement d'attaques par déni de service. Le concept a ensuite été adapté à la sécurisation de l'argent numérique par Hal Finney en 2004 grâce à l'idée de "preuve de travail réutilisable" utilisant l'algorithme de hachage SHA-256.

Après son introduction en 2009, Bitcoin est devenu la première application largement adoptée de l'idée PoW de Finney (Finney a également été le destinataire de la première transaction bitcoin). La preuve de travail constitue également la base de nombreuses autres [occurrences de](/cryptocurrency) [cryptage](/cryptocurrency),. permettant un consensus sécurisé et décentralisé.

## Comprendre la preuve de travail

Cette explication se concentrera sur la preuve de travail telle qu'elle fonctionne dans le réseau [bitcoin](/bitcoin). Le bitcoin est une monnaie numérique qui s'appuie sur une sorte de [registre distribué](/distributed-ledger-technology-dlt) connu sous le nom de « [blockchain](/blockchain) ». Ce grand livre contient un enregistrement de toutes les transactions en bitcoins, organisées en "blocs" séquentiels, de sorte qu'aucun utilisateur n'est autorisé à dépenser deux fois ses avoirs. Afin d'empêcher toute falsification, le grand livre est public ou "distribué" ; une version modifiée serait rapidement rejetée par les autres utilisateurs.

Dans la pratique, les utilisateurs détectent la falsification par le biais de [hachages](/hash),. de longues chaînes de chiffres qui servent de preuve de travail. Mettez un ensemble donné de données via une fonction de hachage (bitcoin utilise SHA-256), et il ne générera jamais qu'un seul hachage. En raison de "l'effet d'avalanche", cependant, même une petite modification de n'importe quelle partie des données d'origine entraînera un hachage totalement méconnaissable. Quelle que soit la taille de l'ensemble de données d'origine, le hachage généré par une fonction donnée aura la même longueur. Le hachage est une fonction à sens unique : il ne peut pas être utilisé pour obtenir les données d'origine, mais uniquement pour vérifier que les données qui ont généré le hachage correspondent aux données d'origine.

Générer n'importe quel hachage pour un ensemble de transactions bitcoin serait trivial pour un ordinateur moderne, donc pour transformer le processus en "travail", le réseau bitcoin définit un certain niveau de "difficulté". Ce paramètre est ajusté de manière à ce qu'un nouveau bloc soit « [miné](/bitcoin-mining) » — ajouté à la blockchain en générant un hachage valide — environ toutes les 10 minutes. La définition de la difficulté est accomplie en établissant une ["cible" pour le hachage](/target-hash) : plus la cible est basse, plus l'ensemble de hachages valides est petit, et plus il est difficile d'en générer un. En pratique, cela signifie un hachage qui commence par une très longue chaîne de zéros.

> La preuve de travail a été initialement créée en tant que solution proposée au problème croissant des spams.

>

## Considérations particulières

Puisqu'un ensemble de données donné ne peut générer qu'un seul hachage, comment les mineurs s'assurent-ils qu'ils génèrent un hachage en dessous de la cible ? Ils modifient l'entrée en ajoutant un entier, appelé [nonce](/nonce) ("nombre utilisé une fois"). Une fois qu'un hachage valide est trouvé, il est diffusé sur le réseau et le bloc est ajouté à la blockchain.

L'exploitation minière est un processus concurrentiel, mais il s'agit plus d'une loterie que d'une course. En moyenne, quelqu'un générera une preuve de travail acceptable toutes les dix minutes, mais personne ne sait qui ce sera. Les mineurs se regroupent pour augmenter leurs chances de miner des blocs, ce qui génère des frais de transaction et, pour un temps limité, une récompense en bitcoins nouvellement créés.

La preuve de travail rend extrêmement difficile la modification de tout aspect de la blockchain, car une telle modification nécessiterait de ré-exploiter tous les blocs suivants. Il est également difficile pour un utilisateur ou un groupe d'utilisateurs de monopoliser la puissance de calcul du réseau, car les machines et la puissance nécessaires pour compléter les fonctions de hachage sont coûteuses.

> Si une partie d'un réseau minier commence à accepter une autre preuve de travail, on parle de [hard fork](/hard-fork).

>

## Exemple de preuve de travail

La preuve de travail nécessite qu'un ordinateur s'engage de manière aléatoire dans des fonctions de hachage jusqu'à ce qu'il arrive à une sortie avec le nombre minimum correct de zéros non significatifs. Par exemple, le hachage du bloc #660000, extrait le 4 décembre 2020 est 0000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. La récompense globale pour ce hachage réussi était de 6,25 BTC.

Ce bloc contiendra toujours 745 transactions impliquant un peu plus de 1 666 bitcoins, ainsi que l'en-tête du bloc précédent. Si quelqu'un essayait de modifier le montant d'une transaction même de 0,000001 bitcoin, le hachage résultant serait méconnaissable et le réseau rejetterait la tentative de fraude.

## FAQ sur la preuve de travail

### Que signifie une preuve de travail ?

PoW exige que les nœuds d'un réseau fournissent la preuve qu'ils ont dépensé de la puissance de calcul (c'est-à-dire du travail) afin de parvenir à un consensus de manière décentralisée et d'empêcher les mauvais acteurs de dépasser le réseau.

### Comment la preuve de travail valide-t-elle une transaction cryptographique ?

Le travail lui-même est arbitraire. Pour Bitcoin, cela implique des itérations d'algorithmes de hachage SHA-256. Le "gagnant" d'un cycle de hachage, cependant, agrège et enregistre les transactions du mempool dans le bloc suivant. Parce que le "gagnant" est choisi au hasard proportionnellement au travail effectué, cela incite tout le monde sur le réseau à agir honnêtement et à n'enregistrer que les vraies transactions.

### Pourquoi les crypto-monnaies ont-elles besoin d'une preuve de travail ?

Parce qu'elles sont décentralisées et peer-to-peer par conception, les chaînes de blocs telles que les réseaux de crypto-monnaie nécessitent un moyen d'atteindre à la fois le consensus et la sécurité. La preuve de travail est l'une de ces méthodes qui la rend trop gourmande en ressources pour essayer de dépasser le réseau. Il existe également d'autres mécanismes de preuve qui sont moins gourmands en ressources, mais qui présentent d'autres inconvénients ou défauts, comme la [preuve](/proof-stake-pos) [d'enjeu (PoS)](/proof-stake-pos) et [la preuve de brûlure](/proof-burn-cryptocurrency). Sans mécanisme de preuve, le réseau et les données qui y sont stockées seraient vulnérables aux attaques ou au vol.

### Bitcoin utilise-t-il la preuve de travail ?

Oui. Il utilise un algorithme PoW basé sur la fonction de hachage SHA-256 afin de valider et de confirmer les transactions ainsi que d'émettre de nouveaux bitcoins en circulation.

### En quoi la preuve de participation (PoS) diffère-t-elle du PoW ?

PoS est un mécanisme de consensus qui attribue au hasard le nœud qui exploitera ou validera les transactions de bloc en fonction du nombre de pièces que ce nœud détient. Plus il y a de jetons dans un portefeuille, plus le pouvoir minier lui est effectivement accordé. Bien que le PoS soit beaucoup moins gourmand en ressources, il présente plusieurs autres défauts, notamment une plus grande probabilité d' [attaque de 51 %](/51-attack) dans des altcoins plus petits et des incitations à accumuler des jetons et à ne pas les utiliser.

## Points forts

- La preuve de participation (POS) était l'un des nombreux nouveaux mécanismes de consensus créés comme alternative à la preuve de travail.

- La preuve de travail (PoW) est un mécanisme de consensus décentralisé qui oblige les membres d'un réseau à déployer des efforts pour résoudre un casse-tête mathématique arbitraire afin d'empêcher quiconque de jouer avec le système.

- La preuve de travail à grande échelle nécessite d'énormes quantités d'énergie, qui ne font qu'augmenter à mesure que de plus en plus de mineurs rejoignent le réseau.

- En raison de la preuve de travail, Bitcoin et d'autres transactions de crypto-monnaie peuvent être traitées de pair à pair de manière sécurisée sans avoir besoin d'un tiers de confiance.

- La preuve de travail est largement utilisée dans l'extraction de crypto-monnaie, pour valider les transactions et extraire de nouveaux jetons.

