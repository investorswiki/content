---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Arbre Merkel
description: Arbre Merkel. Un moyen d&#39;organiser et de structurer de grandes quantités de données pour en faciliter le traitement. Une structure de données basée sur le hachage.
---

# Arbre Merkel
Un arbre Merkle est un moyen d'organiser et de structurer de grandes quantités de données pour les rendre plus simples à traiter. Dans le cas de la crypto-monnaie et de [la blockchain](/blockchain),. l'arbre de Merkle est utilisé pour structurer les données de transaction d'une manière moins gourmande en ressources.

Lorsqu'une transaction de crypto-monnaie est effectuée dans une structure arborescente Merkle, elle est hachée puis reçoit une valeur de hachage équivalente. Une fois chaque transaction hachée dans l'arbre Merkle, les valeurs de hachage produites sont associées à une autre valeur de hachage, puis à nouveau hachées. Par exemple, les valeurs de hachage 'AB' et 'AC' sont combinées pour créer 'ABC'.

Ce processus d'appariement des valeurs de hachage est répété jusqu'à ce qu'une valeur de hachage finale soit produite. La valeur de hachage finale, la racine Merkle, fournit un résumé de toutes les transactions qu'elle contient. Le résumé de la racine Merkle est ensuite inséré dans l'en-tête du bloc.

#### Sécurité des données

Une structure arborescente Merkle fournit un enregistrement facile d'accès des transactions dans un [bloc](/block). Ainsi, il est très simple de vérifier si les données d'un bloc ont été modifiées ou falsifiées. Cela est vrai car toute modification d'une transaction (ou de toute autre donnée associée) dans l'arborescence Merkle conduirait à une racine Merkle correspondante entièrement différente.

#### Utilisation efficace des ressources

Si les crypto-monnaies n'utilisaient pas les arbres de Merkle, chaque demande de vérification impliquerait d'énormes quantités d'informations envoyées sur le réseau. La structuration des données de transaction dans un arbre Merkle est une utilisation beaucoup plus efficace des ressources. La validation d'une transaction ne nécessite pas une copie complète du grand livre, car les données de transaction hachées peuvent être vérifiées dans une racine Merkle, nécessitant beaucoup moins d'informations envoyées à travers les nœuds et, par conséquent, moins de puissance de calcul pour analyser l'intégrité globale des données.

En d'autres termes, une structure arborescente Merkle permet aux utilisateurs de vérifier qu'une transaction individuelle a été incluse dans un bloc sans avoir à passer par le processus de téléchargement de l'intégralité de la blockchain. La technologie est un outil important pour les crypto-monnaies pour organiser les données de transaction et fonctionner aussi efficacement qu'elles le font. Sans les arbres de Merkle, il est probable que la plus grande demande de ressources entraînerait une diminution du nombre de [nœuds](/node) participant au réseau.

