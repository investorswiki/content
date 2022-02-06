---
keywords: Crypto
title: Filtre de floraison
description: Filtre de floraison. Une structure de données qui peut être utilisée pour informer l&#39;utilisateur si un élément particulier fait partie d&#39;un ensemble d&#39;éléments
---

# Filtre de floraison
Un filtre Bloom est une structure de données qui peut être utilisée pour informer l'utilisateur si un élément particulier fait partie d'un ensemble. Bien qu'il ne puisse pas dire avec certitude si un élément est dans l'ensemble, il peut dire avec certitude si l'élément n'y est pas.

Créés par Burton Howard Bloom en 1970, les filtres Bloom sont une offre attrayante pour une gamme d'applications en raison de leur efficacité dans l'utilisation de l'espace. Dans certaines crypto-monnaies (notamment Bitcoin), elles jouent un rôle essentiel dans la vérification simplifiée des paiements, ou SPV.

En utilisant un client SPV, les utilisateurs peuvent interagir avec le réseau Bitcoin sans exécuter un nœud complet. Les nœuds complets sont livrés avec certaines exigences de stockage et de calcul qui les rendent peu maniables pour fonctionner sur des appareils à faible puissance comme les smartphones. Les clients SPV, d'autre part, interrogent simplement les nœuds complets pour obtenir des informations pertinentes sur le ou les portefeuilles de l'utilisateur.

La solution la plus simple pour relayer ces données à l'utilisateur serait de rendre les nœuds complets conscients des clés du client, de sorte que seules les transactions pertinentes leur soient envoyées. De toute évidence, il s'agit d'une solution médiocre car la vie privée du client serait sacrifiée. D'autre part, télécharger toutes les transactions uniquement pour en supprimer la majorité serait un gaspillage de bande passante. Entrez les filtres Bloom.

Illustrons. Supposons qu'un client, Alice, ait une transaction de grande valeur dont il ne veut pas que Bob, qui exécute un nœud complet, soit au courant. Elle construit un filtre Bloom, que nous allons illustrer sous la forme d'une grille 10x1 :

Elle transmet les données de transaction qui l'intéressent à travers deux fonctions de hachage différentes, qui génèrent deux nombres entre 0 et 9. Appelons-les 4 et 7. Elle envoie le filtre à Bob.

En regardant cette grille, vous n'avez aucune idée des données qu'Alice a transmises au filtre. Si vous aviez un ensemble dans lequel les données étaient contenues, vous pourriez le hacher et le comparer avec le filtre - s'il y a une correspondance, il est possible que ce soit l'information demandée par Alice.

En même temps, il y aura probablement de nombreuses entrées qui correspondront à 4 et 7, donc Bob ne peut pas déterminer quelle partie des données intéresse Alice. Il renvoie simplement toutes les correspondances et Alice les filtre de son côté.

Il s'agit, bien sûr, d'une grossière simplification excessive, mais cela démontre le concept : les filtres Bloom masquent les véritables intérêts du client. Ce n'est pas une méthode parfaite (il y a toujours des inquiétudes quant à sa confidentialité), mais c'est une amélioration par rapport à une requête non protégée à un nœud.

