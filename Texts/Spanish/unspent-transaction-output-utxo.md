---
keywords: Crypto
title: Salida de transacciones no gastadas (UTXO)
description: Salida de transacciones no gastadas (UTXO). Una salida creada en una transacción, a la que se debe hacer referencia en una transacción futura para gastar fondos.
---

# Salida de transacciones no gastadas (UTXO)
Una salida de transacción no gastada (UTXO) se refiere a una salida de transacción que se puede usar como entrada en una nueva transacción. En esencia, los UTXO definen dónde comienza y termina cada transacción de blockchain. El modelo UTXO es un elemento fundamental de Bitcoin y muchas otras criptomonedas.

En otras palabras, las transacciones de criptomonedas están hechas de entradas y salidas. Cada vez que se realiza una transacción, un usuario toma uno o más UTXO para que sirvan como entrada (s). A continuación, el usuario proporciona su firma digital para confirmar la propiedad de las entradas, que finalmente se traducen en salidas. Los UTXO consumidos ahora se consideran "gastados" y ya no se pueden usar. Mientras tanto, los resultados de la transacción se convierten en nuevos UTXO, que se pueden gastar en una nueva transacción más adelante.

Probablemente esto se explique mejor con un ejemplo. Alice tiene 0,45 BTC en su billetera. Esto no es una fracción de una moneda como podríamos conceptualizarlo. Es más bien una colección de UTXO. Específicamente, dos UTXO por valor de 0,4 BTC y 0,05 BTC: salidas de transacciones pasadas. Ahora imaginemos que Alice necesita hacer un pago a Bob de 0.3 BTC.

Su única opción aquí es dividir la unidad de 0,4 BTC y enviar 0,3 BTC a Bob y 0,1 BTC a ella misma. Normalmente reclamaría menos de 0,1 BTC debido a las tarifas de minería, pero simplifiquemos y dejemos al minero fuera.

Alice crea una transacción que esencialmente le dice a la red: tome mi UTXO de 0,4 BTC como entrada, divídalo, envíe 0,3 BTC a la dirección de Bob y devuelva los 0,1 BTC a mi dirección. Los 0,4 BTC ahora son una salida gastada y no se pueden reutilizar. Mientras tanto, se han creado dos nuevos UTXO (0,3 BTC y 0,1 BTC).

Tenga en cuenta que dividimos un UTXO en este ejemplo, pero si Alice tuvo que pagar 0,42 BTC, podría haber combinado fácilmente sus 0,4 BTC con otros 0,05 BTC para producir un UTXO por valor de 0,42 BTC, mientras se devolvía 0,03 BTC.

En resumen, el modelo UTXO sirve como mecanismo del protocolo para realizar un seguimiento de dónde están las monedas en un momento dado. En cierto sentido, funcionan como cheques: están dirigidos a usuarios específicos (o más bien, a sus [direcciones públicas](/address) ). Los UTXO no se pueden gastar en parte; en su lugar, se deben crear nuevos cheques a partir del anterior y transferirlos en consecuencia.

