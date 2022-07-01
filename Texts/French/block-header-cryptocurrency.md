---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: En-tête de bloc (Crypto-monnaie)
description: En-tête de bloc. Une section dans un bloc contenant des métadonnées et un résumé des transactions du bloc. Il s&#39;agit des informations hachées lors de l&#39;extraction.
---

# En-tête de bloc (Crypto-monnaie)
L'en-tête de bloc est une section dans un [bloc](/block) qui sert de résumé du reste du bloc. Il est composé de toutes les [métadonnées](/metadata),. telles que l'heure et la [difficulté auxquelles](/difficulty) le bloc a été [miné](/mining),. la [racine Merkle](/merkle-tree) des transactions incluses et le [nonce](/nonce). Le [hash](/hash) du bloc précédent est également présent , ce qui nous permet de créer la "chaîne" de blocs. Essentiellement, l'en-tête de bloc contient toutes les données qui ne sont pas la liste des transactions brutes elle-même.

Un en-tête de bloc est ce que les mineurs hachent pour essayer de rendre le bloc valide. C'est beaucoup plus efficace que de hacher l'intégralité du bloc, qui peut être composé de milliers de transactions. Il serait beaucoup plus fastidieux pour un mineur de changer le nonce et de ressasser un bloc entier de 2 Mo à chaque tentative. Comparez cela avec le hachage des en-têtes de bloc de Bitcoin, par exemple, qui ont une longueur fixe de 80 octets.

Les en-têtes de bloc sont excellents du point de vue du minage, mais en raison de leur petite taille, ils sont également idéaux pour les clients légers. La blockchain Bitcoin est trop volumineuse pour être stockée par des appareils tels que les smartphones. Si la chaîne avait 100 000 blocs de 1 Mo, vous consommeriez 100 Go d'espace. Mais avec seulement les en-têtes de bloc pour ces mêmes blocs, vous ne prendriez que 0,008 Go ou 8 Mo.

De cette manière, les appareils disposant de moins de bande passante ou d'espace de stockage peuvent toujours effectuer un certain degré de validation. Étant donné que la racine Merkle encapsule toutes les transactions, ils peuvent vérifier ultérieurement si une transaction a été incluse dans un bloc particulier. Cela a un coût - l'utilisateur doit toujours compter sur un tiers pour lui fournir les informations nécessaires. Cela dit, les clients légers sont préférables à un système où les utilisateurs n'effectuent aucune vérification.

## Points forts

- Ils sont hachés pour créer une preuve de travail pour les récompenses minières.

- Les en-têtes de bloc identifient des blocs individuels dans une blockchain.

- Les blocs sont superposés verticalement, en commençant par le "bloc de genèse".

- Le numéro de version Bitcoin vous aide à garder une trace des changements dans le protocole.

- Chaque en-tête de bloc contient trois ensembles de métadonnées de bloc et plusieurs composants individuels.

