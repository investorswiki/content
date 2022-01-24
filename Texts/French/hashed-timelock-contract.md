---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Contrat de verrouillage de temps haché (HTLC)
description: Contrat TimeLock haché (HTLC). Fait référence à une fonctionnalité spéciale utilisée pour créer des contrats intelligents capables de modifier les canaux de paiement.
---

# Contrat de verrouillage de temps haché (HTLC)
Le terme Hashed TimeLock Contract (HTLC) fait référence à une fonctionnalité spéciale utilisée pour créer [des contrats intelligents](/smart-contract) capables de modifier les canaux de paiement. Techniquement, la fonctionnalité HTLC permet la mise en œuvre de transactions limitées dans le temps entre deux utilisateurs. En pratique, le destinataire d'une transaction HTLC doit accuser réception du paiement en soumettant une preuve cryptographique dans un délai déterminé (nombre de blocs). Si le destinataire renonce ou ne réclame pas le paiement, les fonds seront retournés à l'expéditeur d'origine.

La fonctionnalité HTLC est appliquée à la fois aux canaux de paiement bidirectionnels et routés pour permettre les transferts de fonds sécurisés sur différents canaux, sans nécessiter la confiance d'aucun des intermédiaires.

Deux éléments clés distinguent HTLC des transactions de crypto-monnaie standard, à savoir :

- Hashlock : une fonction qui limite les dépenses de fonds jusqu'à ce qu'une certaine donnée soit divulguée publiquement (en tant que preuve cryptographique). Cette preuve peut également être appelée pré-image du hashlock. La pré-image est simplement l'information utilisée pour générer le hashlock et pour débloquer ultérieurement ses fonds.

- Timelock : est une fonction qui limite la dépense de fonds jusqu'à un moment précis (ou hauteur de bloc) dans le futur. Cela peut être réalisé dans Bitcoin, par exemple, en utilisant des fonctions telles que CheckLockTimeVerify ou CheckSequenceVerify.

Le Bitcoin Lightning Network est l'un des cas d'utilisation les plus populaires des contrats hasshed timelocked. En implémentant HTLC dans les canaux de paiement, les fonds peuvent être transférés d'un utilisateur à l'autre via des canaux de paiement interconnectés, sans nécessiter aucun niveau de confiance. Ce processus est connu sous le nom de routage réseau. Il permet à Alice d'échanger des fonds avec Carol même s'ils ne sont pas directement connectés via un canal de paiement. Les HTLC permettent à Alice d'envoyer ses fonds à Carol par l'intermédiaire d'autres participants du réseau (par exemple, Bob) - et les fonctions de verrouillage et de verrouillage du temps garantissent que Bob ne peut pas intercepter les fonds.

En plus d'être utilisés sur le Lightning Network, les HTLC peuvent également être utiles dans d'autres contextes, tels que [les échanges atomiques inter-chaînes](/atomic-swaps),. les contrats financiers intelligents et l'entiercement, et bien plus encore.

## Points forts

- Les paiements utilisant les HTLC sont conditionnels et présentent donc des avantages d'efficacité pour les transactions blockchain. Cette propriété fait des HTLC un outil fondamental utilisé par le réseau foudre.

- Ce type de contrat intelligent oblige le destinataire d'un paiement à le reconnaître dans un certain délai ou à le perdre.

- Un contrat de verrouillage temporel haché (HTLC) réduit le risque de contrepartie dans les contrats intelligents décentralisés en créant efficacement un séquestre basé sur le temps qui utilise une phrase de passe cryptographique.

## FAQ

### Combien coûte un contrat intelligent ?

Sur la blockchain Ethereum, un déploiement de contrat intelligent prend du gaz, ce qui coûte Gwei (une dénomination inférieure d'éther). Selon la complexité du contrat, le déploiement d'un contrat intelligent peut coûter des milliards de Gwei. Les contrats moins complexes comme un simple échange sont beaucoup moins chers.

### Qu'est-ce qu'un contrat intelligent ?

Un contrat intelligent est un programme stocké sur une blockchain qui s'exécute lorsque des conditions spécifiques sont remplies.

### Qu'est-ce qu'un contrat Timelock ?

Un contrat timelock est un contrat intelligent intégré dans une blockchain qui exécute une transaction à un moment précis. Ils sont utilisés dans les contrats de verrouillage du temps haché et les canaux de paiement où des délais de paiement spécifiques sont nécessaires.

### Bitcoin a-t-il des contrats intelligents ?

Initialement, la blockchain de Bitcoin n'était pas en mesure d'exécuter des contrats intelligents. Cependant, la mise à niveau de Taproot en 2021 a permis à la blockchain d'utiliser des contrats intelligents dans les transactions.

