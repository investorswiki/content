---
keywords: Investing,Laws and Regulations,Cybersecurity
title: Boîte grise
description: La boîte grise est le test d&#39;un logiciel avec une connaissance limitée de son fonctionnement interne.
---

# Boîte grise
## Qu'est-ce qu'une boîte grise ?

La boîte grise fait référence au test d'un logiciel pour lequel il existe une connaissance limitée de son fonctionnement interne. Le test de la boîte grise est une technique de piratage éthique où le pirate doit utiliser des informations limitées pour identifier les forces et les faiblesses du réseau de sécurité d'une cible.

## Comprendre les boîtes grises

La boîte grise est l'hybride du test de la boîte blanche, où le testeur examine la logique interne et la structure du code du logiciel, et du test [de la boîte noire](/blackbox),. où le testeur ne sait rien du code du logiciel. Pour comprendre les tests en boîte grise, nous devons d'abord comprendre les tests en boîte noire et les tests en boîte blanche.

### Tests de la boîte noire et de la boîte blanche

Le test de la boîte noire ne regarde rien de plus que les entrées de l'utilisateur et la sortie que le logiciel produit compte tenu de ces entrées. Les tests de boîte noire ne nécessitent aucune connaissance du langage de programmation ou d'autres détails techniques. Il s'agit d'un type de test de haut niveau utilisé dans les tests de système et les tests d'acceptation. Les ingénieurs logiciels ont besoin d'un document de spécification des exigences logicielles (SRS) pour effectuer des tests de boîte noire. Ce test adopte une perspective [d'utilisateur final](/end-user) où le testeur de boîte noire ne sait pas comment les sorties sont générées à partir des entrées.

Les tests en boîte blanche nécessitent une connaissance approfondie des techniques et des plates-formes utilisées pour créer des logiciels, y compris le langage de programmation approprié. Il s'agit d'un type de test de bas niveau utilisé dans les tests unitaires et les tests d'indication. Les ingénieurs logiciels doivent comprendre le langage de programmation utilisé pour créer l'application afin de comprendre son code source. Les principaux objectifs des tests en boîte blanche sont de renforcer la sécurité, d'examiner comment les entrées et les sorties circulent dans l'application et d'améliorer la conception et la convivialité. Lorsqu'un testeur de boîte blanche n'obtient pas la sortie attendue d'une entrée donnée, le résultat est considéré comme un bogue qui doit être corrigé.

## Comment fonctionnent les tests de la boîte grise

Les tests de boîte grise incluent des composants importants des tests de boîte noire et blanche pour obtenir un meilleur résultat que l'un ou l'autre pourrait obtenir seul. Les utilisateurs finaux et les développeurs effectuent des tests en boîte grise avec une connaissance limitée (partielle) du code source d'une application. Les tests de la boîte grise peuvent être manuels ou automatisés. Il est plus complet et prend plus de temps que les tests en boîte noire, mais pas aussi complet ou long que les tests en boîte blanche. Les testeurs de boîte grise nécessitent des documents de conception détaillés.

Le test de la boîte grise consiste à identifier les entrées, les sorties, les principaux chemins et les sous-fonctions. Il passe ensuite au développement d'entrées et de sorties pour les sous-fonctions, à l'exécution de cas de test pour les sous-fonctions et à la vérification de ces résultats.

## Exemple de boîte grise

Un testeur de boîte grise peut vérifier et corriger les liens sur un site Web. Si un lien ne fonctionne pas, le testeur modifie le [code HTML](/html) pour essayer de faire fonctionner le lien, puis revérifie l'interface utilisateur pour voir si le lien fonctionne. Un testeur de boîte grise peut également tester une calculatrice en ligne. Le testeur définirait les entrées - des formules mathématiques telles que 1 + 1, 2 * 2, 5-4 et 15/3 - puis vérifierait que la calculatrice fournit les sorties correctes compte tenu de ces entrées. Le testeur de la boîte grise a accès au code HTML de la calculatrice et peut le modifier si des erreurs sont identifiées.

Les tests en boîte grise examinent à la fois l'interface utilisateur de l'application, ou couche de présentation, et son fonctionnement interne, ou code. Il est principalement utilisé dans les tests d'intégration et les tests de pénétration, mais il ne convient pas aux tests d' [algorithmes](/algorithm). Les tests de boîte grise sont généralement utilisés pour tester l'interface utilisateur, la sécurité ou les fonctionnalités en ligne d'une application grâce à des techniques telles que les tests de matrice, les tests de [régression , les](/regression) tests de réseau orthogonal et les tests de modèle. Les testeurs de la boîte grise sont les plus susceptibles d'identifier les problèmes spécifiques au contexte.

« Gris » fait référence à la capacité partielle du testeur à voir le fonctionnement interne de l'application. "Blanc" fait référence à la capacité de voir à travers l'interface du logiciel son fonctionnement interne, et "noir" fait référence à l'incapacité de voir le fonctionnement interne du logiciel. Les tests en boîte grise sont parfois appelés tests translucides, tandis que les tests en boîte blanche sont parfois appelés tests clairs et les tests en boîte noire peuvent également être appelés tests opaques.

## Points forts

- Les tests de la boîte grise sont essentiellement un mélange de méthodologies de la boîte blanche (connaissance complète) et de la boîte noire (aucune connaissance).

- Le test de la boîte grise est une technique permettant de découvrir des bogues logiciels ou de trouver des exploits, où certaines connaissances limitées sur le logiciel sous-jacent sont connues à l'avance.

- Cette forme de "piratage éthique" permet aux développeurs de logiciels de créer des correctifs et des correctifs pour empêcher les attaquants malveillants d'utiliser ces exploits.

