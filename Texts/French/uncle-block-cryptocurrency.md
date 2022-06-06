---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Bloc Ommer
description: Les blocs Ommer sont des blocs non sélectionnés par le réseau Ethereum pour être ajoutés à la blockchain. Apprenez-en plus sur eux et sur ce qu&#39;ils font pour le réseau.
---

# Bloc Ommer
## Qu'est-ce qu'un bloc Ommer ?

Il est possible que deux blocs soient créés simultanément par un réseau. Lorsque cela se produit, un bloc sera laissé de côté. Ce bloc restant est appelé un bloc ommer. Dans le passé, ils étaient appelés blocs oncles, faisant référence aux relations familiales utilisées pour décrire les positions de bloc au sein d'une blockchain.

## Comprendre les blocs Ommer

Dans une blockchain publique comme Ethereum et Bitcoin, il est essentiel d'utiliser une méthode qui garantit que les données de la blockchain sont vérifiées et ajoutées par consensus. Il est tout aussi important d'empêcher la modification des données. De nombreuses chaînes de blocs utilisent une structure de données appelée arbre de Merkle pour y parvenir.

Un arbre de Merkle établit des relations ancestrales pour des blocs de données. Les informations des blocs précédents sont incluses dans de nouveaux blocs, similaires à l'ADN transmis entre les générations. Cela crée le concept d'un parent, du frère du parent, de l'enfant et des blocs de la fratrie similaires à une représentation graphique d'un arbre généalogique.

Voici comment cela fonctionne : le premier bloc d'un arbre pourrait être nommé bloc A. Le bloc suivant créé à partir du bloc A serait considéré comme l'enfant du bloc A et inclurait les informations de A plus les siennes.

> Ethereum est en train de passer d'un consensus de preuve de travail à un consensus de preuve d'enjeu. Dans le cadre du mécanisme de consensus de preuve de participation, des blocs ommer peuvent toujours être produits et se voir récompenser des frais de transaction.

>

Ce bloc pourrait être appelé bloc B mais pourrait être représenté par B~a~. B est le nom du nouveau bloc et "a" fait référence aux données du bloc parent. Cette relation parent/enfant se poursuit à mesure que d'autres blocs sont ajoutés avec les informations de chaque bloc précédent. Cela crée un arbre généalogique et une blockchain.

Considérons maintenant si deux blocs ont été validés et créés simultanément à partir de B~a. Ce sont des blocs~ C~ab~ et C~ab2,~ blocs frères du même bloc parent. Un seul peut être ajouté à la blockchain, le réseau choisit donc C~ab~. C~ab2~ est un fork de la blockchain d'origine mais n'y est pas ajouté ni validé. Enfin, un autre bloc est miné sur la blockchain qui gardait C~ab.~ Il s'agit du bloc D~cab.~ C~ab2 est le frère du ~parent de ~D~cab~, donc~ C~ab2~ est un ommer bloquer.

## Considérations particulières

Ces blocs orphelins étaient essentiellement des bogues dans le code, des sous-produits involontaires et accidentels du processus de minage. Cependant, Ethereum a incité les mineurs de blocs ommer pour plusieurs raisons :

- Pour permettre de créer plus de blocs ommer en tant que sous-produit de temps de bloc plus courts et d'accélérer le réseau.

- Diminuer la centralisation des incitations pour les grands pools miniers. Ces pools emploient de grandes fermes minières et réclament la majorité des récompenses en crypto-monnaie, laissant peu de choses aux mineurs individuels.

- Augmenter la sécurité du réseau en complétant le travail sur la blockchain principale en permettant d'inclure le travail effectué sur les blocs ommer.

Les blocs Ommer sont délibérément incorporés dans la blockchain d'Ethereum à l'aide du protocole de validation de son mécanisme de consensus, Casper the Friendly GHOST (Greedy Heaviest Object Sub Tree). Lorsqu'un fork de blockchain se produit à partir de blocs créés simultanément, une règle de consensus des deux tiers des validateurs de réseau sélectionne le bloc à utiliser.

<!--7D655E4B296C31937FEB1522C669FA07-->

## Points forts

- Les blocs Ommer sont similaires aux orphelins Bitcoin mais ont une utilisation intégrée, contrairement à leurs homologues Bitcoin.

- Les blocs Ommer sont créés dans la blockchain Ethereum lorsque deux blocs sont créés et soumis au registre à peu près au même moment. Un seul peut entrer dans le grand livre.

- Les mineurs ou validateurs Ethereum sont récompensés pour la création de blocs ommer dans le système Ethereum par le biais de frais de transaction pour payer leur travail.

## FAQ

### Qu'est-ce qu'un bloc Ommer (oncle) ?

Le bloc oncle est l'ancien nom d'un bloc ommer. Les développeurs et la communauté Ethereum ont décidé qu'il n'y avait aucune raison d'avoir des noms spécifiques au genre, ils ont donc choisi ommer comme nouveau nom.

### Quel est le taux Ommer (Oncle) d'Ethereum ?

Le taux ommer (anciennement taux oncle) est le taux auquel le réseau produit des blocs ommer. Le taux change quotidiennement et dépend du nombre de transactions effectuées.

### Qu'est-ce que la récompense Ommer (oncle) d'Ethereum ?

Dans le cadre du mécanisme de consensus de preuve de travail, les récompenses pour les blocs ommer représentaient un petit pourcentage de la récompense du bloc, plus les frais de transaction. Lorsque Ethereum passera à la preuve de participation, les blocs ommer recevront des frais de transaction.

