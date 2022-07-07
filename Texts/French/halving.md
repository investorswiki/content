---
keywords: Crypto
title: Réduire de moitié
description: Réduire de moitié. Lorsque la récompense globale d&#39;un actif cryptographique tombe à la moitié de ce qu&#39;elle était auparavant ; ceci est utilisé pour créer un taux d&#39;émission décroissant.
---

# Réduire de moitié
Dans l'espace des crypto-monnaies, le terme réduction de moitié fait référence à un processus qui réduit le taux d'émission de nouvelles pièces. Plus précisément, la réduction de moitié est la réduction périodique de la subvention globale accordée aux mineurs. La réduction de moitié garantit qu'un actif cryptographique suivra un taux d'émission stable jusqu'à ce que son [offre maximale](/maximum-supply) soit finalement atteinte.

En ce qui concerne Bitcoin, les nouvelles pièces sont générées en continu dans le cadre de la [récompense globale](/block-reward) (qui se compose de la subvention globale plus les frais de transaction). Ainsi, chaque fois qu'un mineur "découvre" et valide avec succès un nouveau [bloc](/block),. il gagne des pièces nouvellement créées en compensation de son travail.

Ainsi, le processus d' [extraction](/mining) est ce qui introduit de nouveaux [Bitcoins](/bitcoin) dans le système, et cela se fait à un rythme prévisible et contrôlé. De nouveaux blocs Bitcoin sont extraits, en moyenne, toutes les 10 minutes, et la subvention de bloc suit un taux de décroissance contrôlé. En conséquence, la réduction de moitié est ce qui garantit que la subvention globale diminuera de 50 % tous les 210 000 blocs (environ tous les quatre ans).

À partir du [bloc de genèse](/genesis-block),. la subvention globale de Bitcoin a été initialement fixée à 50 BTC. Ensuite, il a été réduit à 25 BTC en 2012 et à 12,5 BTC en 2016. La réduction de moitié suivante devrait avoir lieu vers mai 2020, réduisant la subvention globale à 6,25 BTC. Une fois que 32 moitiés se sont produites, le processus s'arrête et plus aucun Bitcoin ne sera créé. À ce stade, l'offre maximale de 21 millions de BTC sera atteinte.

[Suivez le Bitcoin Halving](/halving)

La réduction de moitié est une partie importante du protocole Bitcoin et, puisque le code est open source, tout le monde peut le voir. Par exemple, l'implémentation de Bitcoin Core est disponible sur [GitHub](/github),. et l'une des sections de code qui définit la subvention globale ressemble à ceci :

CAmount GetBlockSubsidy(int nHeight, const Consensus ::Params& consensusParams)

{

int halvings = nHeight / consensusParams.nSubsidyHalvingInterval ;

// Force la récompense du bloc à zéro lorsque le décalage vers la droite n'est pas défini.

si (moitiés >= 64)

renvoie 0 ;

CAmount nSubsidy = 50 * COIN ;

// La subvention est réduite de moitié tous les 210 000 blocs, ce qui se produira environ tous les 4 ans.

nSubvention >>= moitiés ;

retourner nSubvention ;

}

