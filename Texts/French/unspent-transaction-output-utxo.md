---
keywords: Crypto
title: Sortie de transaction non dépensée (UTXO)
description: Sortie de transaction non dépensée (UTXO). Une sortie créée dans une transaction, qui doit être référencée dans une future transaction pour dépenser des fonds.
---

# Sortie de transaction non dépensée (UTXO)
Une sortie de transaction non dépensée (UTXO) fait référence à une sortie de transaction qui peut être utilisée comme entrée dans une nouvelle transaction. Essentiellement, les UTXO définissent où chaque transaction blockchain commence et se termine. Le modèle UTXO est un élément fondamental de Bitcoin et de nombreuses autres crypto-monnaies.

En d'autres termes, les transactions de crypto-monnaie sont constituées d'entrées et de sorties. Chaque fois qu'une transaction est effectuée, un utilisateur prend un ou plusieurs UTXO pour servir d'entrée (s). Ensuite, l'utilisateur fournit sa signature numérique pour confirmer la propriété des entrées, qui se traduisent finalement par des sorties. Les UTXO consommés sont désormais considérés comme "dépensés" et ne peuvent plus être utilisés. Pendant ce temps, les sorties de la transaction deviennent de nouveaux UTXO - qui peuvent être dépensés dans une nouvelle transaction plus tard.

Ceci est probablement mieux expliqué avec un exemple. Alice a 0,45 BTC dans son portefeuille. Ce n'est pas une fraction de pièce comme nous pourrions le conceptualiser. C'est plutôt une collection d'UTXO. Plus précisément, deux UTXO d'une valeur de 0,4 BTC et 0,05 BTC - sorties de transactions passées. Imaginons maintenant qu'Alice doive effectuer un paiement à Bob de 0,3 BTC.

Sa seule option ici est de briser l'unité 0,4 BTC et d'envoyer 0,3 BTC à Bob et 0,1 BTC à elle-même. Elle récupérerait normalement moins de 0,1 BTC en raison des frais miniers, mais simplifions et laissons le mineur de côté.

Alice crée une transaction qui dit essentiellement au réseau : prenez mon UTXO 0,4 BTC comme entrée, décomposez-le, envoyez-en 0,3 BTC à l'adresse de Bob et renvoyez le 0,1 BTC à mon adresse. Le 0,4 BTC est maintenant une sortie épuisée et ne peut pas être réutilisé. Entre-temps, deux nouveaux UTXO ont été créés (0,3 BTC et 0,1 BTC).

Notez que nous avons cassé un UTXO dans cet exemple, mais si Alice avait dû payer 0,42 BTC, elle aurait tout aussi bien pu combiner ses 0,4 BTC avec un autre 0,05 BTC pour produire un UTXO d'une valeur de 0,42 BTC, tout en se rendant 0,03 BTC.

En résumé, le modèle UTXO sert de mécanisme de protocole pour garder une trace de l'endroit où se trouvent les pièces à un moment donné. En un sens, ils fonctionnent un peu comme des chèques : ils sont adressés à des utilisateurs spécifiques (ou plutôt, leurs [adresses publiques](/address) ). Les UTXO ne peuvent pas être dépensés en partie - à la place, de nouveaux chèques doivent être créés à partir de l'ancien et transmis en conséquence.

