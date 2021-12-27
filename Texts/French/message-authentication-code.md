---
keywords: Personal Finance,Banking
title: Code d&#39;authentification de message (MAC)
description: Un code d&#39;authentification de message (MAC), ou balise, est un code de sécurité saisi par l&#39;utilisateur d&#39;un ordinateur pour accéder à des comptes ou à des portails.
---

# Code d'authentification de message (MAC)
## Qu'est-ce qu'un code d'authentification de message ?

Un code d'authentification de message (MAC), ou **tag,** est un code de sécurité saisi par l'utilisateur d'un ordinateur pour accéder à des comptes ou à des portails. Ce code est joint au message ou à la demande envoyé par l'utilisateur. Les codes d'authentification de message (MAC) attachés au message doivent être reconnus par le système récepteur afin d'accorder l'accès à l'utilisateur.

## Comprendre le code d'authentification de message (MAC)

Les codes d'authentification de message (MAC) sont couramment utilisés dans [les transferts électroniques de fonds](/electronic-funds-transfer-act) (TEF) pour maintenir l'intégrité des informations. Ils confirment qu'un message est authentique ; qu'il provient réellement, en d'autres termes, de l'expéditeur indiqué et qu'il n'a subi aucune modification en cours de route. Un vérificateur qui possède également la clé peut l'utiliser pour identifier les modifications du contenu du message en question.

Les codes d'authentification de message sont généralement nécessaires pour accéder à tout type de compte financier. Les banques, les sociétés de courtage, les sociétés de fiducie et toute autre société de dépôt, d'investissement ou d'assurance offrant un accès en ligne peuvent utiliser ces codes. Ils sont un élément essentiel de la cryptographie financière.

## Algorithmes utilisés pour générer des MAC

Trois algorithmes composent typiquement un MAC : un algorithme de génération de clé, un algorithme de signature et un algorithme de vérification. L'algorithme de génération de clé choisit une clé au hasard. L'algorithme de signature envoie une balise lorsqu'il reçoit la clé et le message. L'algorithme de vérification est utilisé pour vérifier l'authenticité du message lorsqu'on lui donne la clé et l'étiquette ; il renverra un message de **accepté** si le message et la balise sont authentiques et inchangés, mais sinon, il renverra un message de **rejeté.**

Par exemple, l'expéditeur envoie un message, tel qu'un EFT, via l'algorithme MAC, qui génère une clé et attache une balise de données MAC au message. Le destinataire reçoit le message, le réexécute via l'algorithme MAC avec la même clé et obtient une deuxième balise de données. Ils compareront ensuite cette étiquette de données MAC avec la première attachée au message lors de sa transmission. Si le code est le même aux deux extrémités, le destinataire peut supposer en toute sécurité que l'intégrité des données du message est intacte. Si ce n'est pas le cas, cela signifie que le message a été modifié, falsifié ou falsifié.

Cependant, le message lui-même doit contenir certaines données garantissant que ce message ne peut être envoyé qu'une seule fois. Par exemple, un MAC, un horodatage ou un numéro de séquence à usage unique peuvent être utilisés pour garantir que le message ne peut être envoyé qu'une seule fois. Sinon, le système pourrait être vulnérable à une attaque par relecture, dans laquelle un attaquant intercepte le message après qu'il a été décodé et le retransmet ultérieurement, reproduisant les résultats originaux et infiltrant le système.

## Codes d'intégrité des messages (MIC)

Parfois, le terme code d'intégrité de message (MIC) sera utilisé à la place de MAC. Cela se fait le plus souvent dans l'industrie des communications, où MAC signifie traditionnellement adresse de contrôle d'accès au support (adresse MAC). Cependant, MIC peut également être utilisé pour faire référence au **résumé de message,** qui n'utilise pas de clés secrètes de la même manière qu'un MAC, et ne peut pas offrir le même niveau de sécurité sans chiffrement supplémentaire.

