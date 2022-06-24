---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Bloque Ommer
description: Los bloques Ommer son bloques no seleccionados por la red Ethereum para agregar a la cadena de bloques. Obtenga más información sobre ellos y lo que hacen por la red.
---

# Bloque Ommer
## ¿Qué es un bloque Ommer?

Es posible que una red cree dos bloques simultáneamente. Cuando esto suceda, un bloque quedará fuera. Este bloque sobrante se llama bloque ommer. En el pasado, se llamaban bloques tío, en referencia a las relaciones familiares que se usaban para describir las posiciones de los bloques dentro de una cadena de bloques.

## Comprender los bloques Ommer

En una cadena de bloques pública como Ethereum y Bitcoin, es esencial utilizar un método que garantice que los datos dentro de la cadena de bloques se verifiquen y se agreguen por consenso. Es igualmente importante evitar que se modifiquen los datos. Muchas cadenas de bloques usan una estructura de datos llamada árbol de Merkle para lograr esto.

Un árbol de Merkle establece relaciones ancestrales para bloques de datos. La información de bloques anteriores se incluye en bloques nuevos, de forma similar al ADN que se transmite entre generaciones. Esto crea el concepto de bloques padre, hermano del padre, hijo y hermano similar a una representación gráfica de un árbol genealógico.

Así es como funciona: el primer bloque en un árbol podría llamarse bloque A. El siguiente bloque creado a partir del bloque A se consideraría hijo del bloque A e incluiría la información de A más la propia.

> Ethereum está pasando de la prueba de trabajo al consenso de prueba de participación. Bajo el mecanismo de consenso de prueba de participación, aún se pueden producir bloques ommer y se recompensan las tarifas de transacción.

>

Este bloque podría llamarse bloque B pero podría representarse como B~a~. B es el nombre del nuevo bloque y "a" se refiere a los datos del bloque principal. Esta relación padre/hijo continúa a medida que se agregan más bloques con la información de cada bloque anterior. Esto crea un árbol genealógico y una cadena de bloques.

Ahora considere si dos bloques fueron validados y creados simultáneamente desde B~a. Son bloques~ C~ab~ y C~ab2,~ bloques hermanos del mismo bloque padre. Solo se puede agregar uno a la cadena de bloques, por lo que la red elige C~ab~. C~ab2~ es una bifurcación de la cadena de bloques original, pero no se agrega ni se valida. Finalmente, se extrae otro bloque en la cadena de bloques que mantuvo a C~ab.~ Este es el bloque D~cab.~ C~ab2 es el hermano del ~padre de~ D~cab~, por lo que~ C~ab2~ es un ommer bloquear.

## Consideraciones Especiales

Estos bloques huérfanos eran, en esencia, errores en el código, subproductos no deseados y accidentales del proceso de minería. Sin embargo, Ethereum incentivó a los mineros de bloques ommer por varias razones:

- Permitir la creación de más bloques ommer como subproducto de tiempos de bloque más cortos y acelerar la red.

- Disminuir la centralización de incentivos a los grandes pools mineros. Estos grupos emplean grandes granjas mineras y reclaman la mayoría de las recompensas de criptomonedas, dejando poco para los mineros individuales.

- Incrementar la seguridad de la red complementando el trabajo en la blockchain principal permitiendo incluir el trabajo realizado en los bloques ommer.

Los bloques Ommer se incorporan a propósito en la cadena de bloques de Ethereum utilizando el protocolo de validación de su mecanismo de consenso, Casper the Friendly GHOST (Árbol secundario de objetos más pesados codiciosos). Cuando se produce una bifurcación de blockchain a partir de bloques creados simultáneamente, una regla de consenso de dos tercios de los validadores de red selecciona qué bloque se usa.

<!--7D655E4B296C31937FEB1522C669FA07-->

## Reflejos

- Los bloques Ommer son similares a los huérfanos de Bitcoin pero tienen un uso integrado, a diferencia de sus contrapartes de Bitcoin.

- Los bloques Ommer se crean en la cadena de bloques de Ethereum cuando se crean dos bloques y se envían al libro mayor aproximadamente al mismo tiempo. Solo uno puede ingresar al libro mayor.

- Los mineros o validadores de Ethereum son recompensados por crear bloques ommer en el sistema Ethereum a través de tarifas de transacción para pagar su trabajo.

## PREGUNTAS MÁS FRECUENTES

### ¿Qué es un bloque Ommer (tío)?

Uncle block es el antiguo nombre de un bloque ommer. Los desarrolladores y la comunidad de Ethereum decidieron que no había razón para tener nombres específicos de género, por lo que optaron por ommer como el nuevo nombre.

### ¿Cuál es la tasa Ommer (tío) de Ethereum?

La tasa ommer (anteriormente, la tasa tío) es la tasa a la que la red produce bloques ommer. La tasa cambia diariamente y depende de la cantidad de transacciones que se realicen.

### ¿Qué es la recompensa Ommer (tío) de Ethereum?

Según el mecanismo de consenso de prueba de trabajo, las recompensas por los bloques de ommer eran un pequeño porcentaje de la recompensa del bloque, más las tarifas de transacción. Cuando Ethereum haga la transición a la prueba de participación, los bloques ommer recibirán tarifas de transacción.

