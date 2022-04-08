---
keywords: Trading,Options and Derivatives Trading,Options Trading Strategy and Education,Options and Derivatives,Strategy and Education
title: Fugito
description: Fugit es la cantidad de tiempo que un inversor cree que le queda hasta que ya no sería beneficioso ejercer una opción anticipadamente.
---

# Fugito
## ¿Qué es Fugit?

Fugit, del latín **tempus fugit**, es la cantidad de tiempo que un inversionista cree que le queda hasta que ya no sería beneficioso ejercer una [opción](/option) anticipadamente, o la probabilidad de que una opción al estilo estadounidense se ejerza antes. caduca

El concepto fugit fue nombrado y creado por el economista Mark Garman, un profesor de Berkeley que estudió el momento óptimo para ejercer una opción estadounidense cotizada utilizando [árboles binomiales](/binomial_tree).

## Entendiendo a Fugit

Fugit es un término utilizado en el comercio de opciones, tomado del latín. Específicamente, tiene su origen en un verso del poema épico **Georgica**, que fue escrito por el poeta romano Virgilio: "**sed fugit interea fugit irreparabile tempus.**" En inglés, esto significa: “pero huye mientras tanto o "el tiempo irrecuperable huye". Se refiere a la función de ejercicio anticipado otorgada a los tenedores de opciones de estilo americano (y que está ausente en las opciones de [estilo](/europeanoption) [europeo](/europeanoption) ).

A menos que una opción esté [muy dentro del dinero,](/deepinthemoney) por lo general no debe ejercerse antes porque esto causa una pérdida de valor inherente. Sería más rentable mantener la opción en lugar de convertirla en una posición [larga](/long) o [corta](/short) en el valor subyacente. A algunos inversores les resulta rentable ejercer las opciones de compra anticipadamente cuando están en el dinero justo antes de una fecha [ex-dividendo](/ex-dividend),. o bien en las opciones de venta de dinero que tienen cerca de un [delta de 100](/delta).

Dada una opción que es candidata potencial para el ejercicio anticipado, el tenedor de la opción calculará su fugit para ver si realmente debe ejercerse o no. Fugit se calcula como el tiempo restante esperado para ejercer una opción estadounidense o, alternativamente, como la vida esperada neutral al riesgo de una opción durante la cual aún puede [cubrirse de manera efectiva](/hedge). El cálculo generalmente requiere un modelo de árbol binomial y es posible que no siempre llegue a un valor único.

## Consideraciones Especiales

Los cálculos de Fugit también se utilizan con opciones de [Bermudas](/bermuda),. contratos que solo se pueden ejercer en fechas predeterminadas, a menudo en un día cada mes. El concepto también se utiliza para determinar si se debe utilizar la función para convertir deuda en capital para [bonos convertibles y cuándo hacerlo](/convertiblebond).

Nassim Taleb, trader de opciones y autor del libro **The Black Swan: The Impact of the Highly Improbable**, propone una alternativa al cálculo de fugit, al que llama "rho fudge", o **Omega* de la opción * = **Duración nominal x (Rho2 de una opción americana / Rho2 de una opción europea).** Tenga en cuenta que Taleb emplea diferentes usos de las palabras rho (tradicionalmente relacionado con la sensibilidad a la tasa de interés) y omega (tradicionalmente relacionado con la sensibilidad al precio y también conocida como lambda). Aquí, el omega es similar a fugit, y el rho2 es la sensibilidad del precio de una opción al pago de dividendos .

### Calculando Fugit

El cálculo del fugit de una opción es el siguiente: donde **n** es el número de pasos de tiempo en el árbol binomial; **t** es el tiempo restante hasta el vencimiento de la opción, y **i** es el paso de tiempo actual en el árbol binomial.

Primero, establezca el valor de fugit de cada uno de los nodos al final del árbol binomial igual a **i = n.** Luego, trabajando hacia atrás: si la opción debe ejercerse en un nodo en particular, establezca el fugit en ese nodo igual a su período; o bien, si la opción no debe ejercerse en un nodo en particular, establezca el fugit en el fugit esperado neutral al riesgo durante el próximo período. El valor al que se llega de esta manera al comienzo del primer período (i = 0) es el fugit actual. Finalmente, para anualizar el fugit, multiplicar el valor resultante por **t/n**.

## Reflejos

- El concepto fue formalizado por Mark Garman, un economista de Berkeley, utilizando modelos de árboles binomiales para identificar las condiciones óptimas para el ejercicio temprano.

- Los cálculos de Fugit también se utilizan para programar las opciones de las Bermudas y los bonos convertibles.

- Fugit es el tiempo que le queda a una opción americana hasta que ya no es beneficiosa para el ejercicio anticipado.

- Fugit también puede interpretarse como la probabilidad de que la función de ejercicio de dicha opción se utilice antes de su vencimiento.

