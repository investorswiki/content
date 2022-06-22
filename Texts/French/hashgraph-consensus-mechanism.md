---
keywords: Investing,Cryptocurrency,Blockchain
title: Consensus des hashgraphes
description: Le consensus Hashgraph fonctionne différemment des mécanismes de consensus blockchain plus connus. Apprenez-en plus à ce sujet et sur son fonctionnement.
---

# Consensus des hashgraphes
## Qu'est-ce que le consensus Hashgraph ?

Le consensus Hashgraph est une alternative à - ou la prochaine génération de - la technologie derrière les mécanismes de consensus blockchain. Au lieu d'utiliser la puissance de calcul des grands réseaux pour vérifier les transactions, les transactions sont enregistrées et confirmées via un protocole qui utilise la communication de nœud.

Un hashgraph est un registre décentralisé à peu près de la même manière qu'une blockchain. Il stocke les informations, les sécurise avec la cryptographie, limite l'accès et utilise les données stockées comme vérification. Cependant, un réseau de hashgraph atteint un consensus d'une manière très différente de celle d'une blockchain.

Le consensus du hashgraph est atteint en utilisant des concepts appelés "commérages", "commérages sur les commérages" et le vote virtuel. Les concepteurs du système rapportent qu'il résout les problèmes inhérents aux [algorithmes de construction de consensus](/algorithm),. tels que la [preuve de travail](/proof-work) (PoW), en termes de meilleure vitesse et d'efficacité accrue.

> Le consensus hashgraph (commérages, commérages sur les commérages et vote virtuel) est le mécanisme utilisé par le grand livre distribué Hedera pour valider et confirmer les transactions.

>

## Comprendre le consensus des hashgraphes

Hashgraph est une alternative à la blockchain. Semblable à une blockchain, il stocke les données et les crypte. Un hachage est généré pour les informations de transaction, et de nouvelles transactions ou données sont ajoutées et développées. Cependant, une blockchain est un registre composé de blocs de données. Chaque bloc est lié au bloc précédent à l'aide de ses données, vérifiées par un réseau de validateurs pour créer le bloc suivant. Ce processus crée une chaîne. Un hashgraph n'est pas une chaîne - toutes les informations sont conservées dans un registre chiffré et chaque utilisateur participe au processus de validation, pas seulement les validateurs.

Par exemple, Alice crée une transaction avec Bob, et toutes les informations qu'elle connaît lui sont données. Bob fait alors une transaction avec Kris. Toutes les informations dont dispose Bob sont communiquées à Kris. Kris traite avec Eli et tout ce qu'elle sait est transféré. Cela se poursuit sur tout le réseau, la chaîne bavardant essentiellement sur les événements qui se déroulent. Chaque nœud sait ce que tous les autres nœuds savent, il n'y a donc pas besoin de validation informatique.

Au fur et à mesure que les commérages se propagent d'un utilisateur à l'autre, le réseau utilise des algorithmes et l'automatisation pour s'assurer que l'état du registre de hashgraph est mis à jour et identique.

### Potins

Les informations sur les données sont appelées "commérages". La structure de données contenue dans une transaction est :

- Un horodatage

- Plus de transactions ou de zéros

- Deux hachages des conteneurs parents

- Une signature cryptée.

Les deux hachages sont les derniers événements de deux nœuds de synchronisation qui comparent leurs informations. Les nœuds créent en permanence des événements et se synchronisent.

> Hashgraph—le grand livre—est plus efficace que la blockchain car aucune énergie n'est gaspillée sur des blocs qui ne sont pas acceptés. Toutes les informations sont conservées dans un hashgraph.

>

### Potins sur les potins

Les informations sur les données de transaction sont appelées "commérages sur les commérages". Les informations sont synchronisées dans le réseau de hashgraph à l'aide d'un événement appelé "synchronisation des potins". Une synchronisation de potins est un historique collaboratif des "événements de potins" tout au long du hashgraph. De cette façon, les données ne peuvent pas être modifiées ou falsifiées, et il y a consensus.

### Vote virtuel

Le vote virtuel se produit lorsque les nœuds comparent des événements et parviennent à un consensus via un algorithme de vote. Voici comment cela fonctionne : une transaction se voit attribuer un horodatage lorsqu'un nœud le reçoit. Lorsqu'il passe aux autres nœuds du réseau, il se voit attribuer un horodatage qui est une médiane de tous les horodatages de cette transaction reçus par les nœuds du réseau. La médiane agit comme le résultat du vote. Cela crée un système de transaction plus équitable qu'une blockchain car le réseau décide, pas un nœud.

### Tolérance aux pannes

Comme pour la plupart des registres distribués et de la blockchain, il y a toujours une chance qu'un participant au réseau ne soit pas honnête. Il peut y avoir des retards de communication ou une latence du réseau qui empêchent les nœuds de communiquer correctement.

Des mécanismes de consensus sont conçus pour traiter ces défauts en fixant des critères de tolérance aux pannes. Les développeurs doivent prendre en compte et prendre en compte les mauvais acteurs, les mauvaises connexions, la latence du réseau et d'autres problèmes de réseau. Le consensus hashgraph peut tolérer qu'un tiers du réseau agisse de manière malveillante. Il serait tolérant aux pannes byzantines asynchrones - le niveau de sécurité le plus élevé - ce qui signifie que les nœuds honnêtes d'un réseau continuent de fonctionner même s'il y a des acteurs malveillants.

## En quoi Hashgraph est-il différent de Blockchain ?

Hashgraph est une structure de données qui conserve les enregistrements de qui a dit qui quoi et dans quel ordre ils l'ont fait. Il s'agit d'une histoire collaborative d'événements de potins au fur et à mesure que les participants ajoutent et partagent des informations, ce qui valide les transactions beaucoup plus rapidement qu'une blockchain.

Blockchain ajoute les informations de transaction précédentes aux nouvelles informations de transaction et les chiffre. Un tiers est nécessaire pour valider les transactions entre les parties. Hashgraph n'a pas besoin de ce processus lent à cause du protocole de potins.

> Le consensus hashgraph est beaucoup plus rapide que les mécanismes de consensus blockchain, avec des temps moyens de confirmation des transactions en secondes plutôt qu'en minutes.

>

Bitcoin et de nombreuses autres crypto-monnaies ont des problèmes de synchronisation des messages. Cependant, la tolérance aux pannes byzantines asynchrones de hashgraph surmonte le problème de la synchronisation des messages en supposant que les messages perdus ou retardés finiront par arriver à leurs destinations.

Par exemple, si deux transactions se produisent simultanément, un réseau blockchain choisit dans quel ordre les transactions ont eu lieu. Dans certaines blockchains, les frais de transaction donnent la priorité à la confirmation. D'autres réseaux peuvent décider quelle transaction est confirmée en fonction du nombre de jetons qu'un validateur a jalonnés. Dans ces blockchains, un nœud influence le résultat.

Le consensus hashgraph élimine l'influence qu'un nœud ou un groupe de nœuds peut avoir sur les transactions. Étant donné qu'il existe un horodatage sur chaque transaction et que chaque transaction est communiquée à l'ensemble du réseau, les problèmes de synchronisation des transactions sont résolus.

## Points forts

- Le système de grand livre distribué hashgraph n'a pas été largement adopté par la communauté crypto.

- Le consensus Hashgraph utilise des informations sur l'information plutôt que le contenu lui-même pour créer un consensus.

- Les informations primaires dans le hashgraph sont appelées "commérages" et les informations secondaires sont appelées "commérages sur les commérages".

## FAQ

### Comment fonctionne le consensus Hashgraph ?

Le consensus Hashgraph fonctionne en utilisant des horodatages de consensus et des "commérages", dans lesquels chaque nœud communique tout ce qu'il sait à des nœuds aléatoires dans des "événements de ragots".

### Qu'est-ce que le consensus Hashgraph ?

Le consensus hashgraph est un mécanisme utilisé dans un grand livre distribué hashgraph pour valider les transactions.

### Le hashgraph remplacera-t-il la blockchain ?

Hashgraph est conçu pour être - et commercialisé comme - une amélioration de la technologie blockchain, mais il reste à voir s'il la remplacera. Il n'a pas encore autant d'intérêt et d'adoption pour les développeurs que la technologie blockchain.

