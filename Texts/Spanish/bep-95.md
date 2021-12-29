---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 es una propuesta de evolución de Binance que introduce un mecanismo de grabación en tiempo real en Binance Smart Chain. Hace que la tokenómica de BNB sea más dinámica y descentralizada.
---

# BEP-95
BEP-95 es una propuesta de evolución de Binance que introduce un mecanismo de grabación en tiempo real en Binance Smart Chain. Se introdujo para hacer que la tokenómica de BNB sea aún más dinámica y descentralizar aún más la red.

Con BEP-95, la red quemará una proporción fija de las tarifas de gas de cada bloque que cobran los validadores. La proporción exacta se determinará a través de los mecanismos de gobierno de BSC. Las quemas se llevarán a cabo incluso después de que BSC haya alcanzado su objetivo de 100 millones de BNB. Al reducir la oferta de BNB, se ejerce una presión al alza sobre el precio de la moneda. El BEP también puede disminuir la cantidad de delegadores y validadores de BNB recibidos. Sin embargo, con la presión al alza de los precios, el valor fiduciario también podría aumentar, compensando cualquier reducción en las monedas.

Para implementar esto técnicamente, la red cobra las tarifas de gas de cada bloque y las divide entre dos contratos inteligentes:

**1. Contrato de Recompensa del Sistema.** 1/16 de las tarifas de gas ingresará al Contrato de Recompensa del Sistema hasta llegar a un máximo de 100 BNB. Estas monedas se utilizarán como subsidios de paquetes entre cadenas.

**2. Contrato de ValidatorSet.** Todas las demás tarifas de gas entrarán en el Contrato de ValidatorSet y se compartirán diariamente con los delegantes y validadores a través de Binance Chain.

Para realizar una quema, el contrato ValidatorSet tiene una variable burnRatio. Al finalizar cada bloque, un validador firmará una transacción transfiriendo sus tarifas de gas a los contratos inteligentes. La función de depósito contiene una lógica de grabación que activa la fórmula simple: burnRatio * gasFee. Esta suma se transferirá a la dirección de grabación. El burnRatio se establecerá inicialmente en 10%.

Los validadores de BSC podrán votar a través de propuestas para cambiar la cantidad de burnRatio. Este mecanismo de gobierno ocurre en Binance Chain, y cualquier miembro de la comunidad puede enviar una propuesta para su revisión con un depósito mínimo de 2000 BNB. Todo el BNB apostado detrás de una propuesta y en una votación se devuelve después de que se haya tomado una decisión. El quórum se alcanza al 50 % y el cambio se implementará de inmediato a través de la comunicación entre cadenas.

