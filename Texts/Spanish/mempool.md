---
keywords: Crypto
title: Mempool
description: Mempool. El mecanismo de un nodo para realizar un seguimiento de las transacciones no confirmadas que el nodo ha visto (pero que aún no se han agregado a un bloque).
---

# Mempool
Un mempool (una contracción de memoria y grupo) es un mecanismo de nodo de criptomonedas para almacenar información sobre transacciones no confirmadas. Actúa como una especie de sala de espera para las transacciones que aún no han sido incluidas en un [bloque](/block).

Cuando se transmite una transacción, se envía desde un nodo a sus pares, quienes luego la pasarán a sus pares. Esto continúa hasta que la transacción se ha propagado ampliamente, lista para que los mineros la agreguen a un bloque. Es vital que exista esta zona de amortiguamiento, ya que las transacciones no se agregan a la cadena de bloques de inmediato.

Los nodos ejecutarán una serie de comprobaciones para garantizar que la transacción sea válida, es decir, verificar que las firmas sean correctas, que las salidas no excedan las entradas y que los fondos no se hayan gastado. Si no cumple con estas condiciones, se rechaza.

A menudo hablamos de mempool, pero debe tenerse en cuenta que no existe un grupo universal compartido por todos los nodos. Cada uno está configurado de manera diferente y recibe transacciones en diferentes momentos. Es posible que los dispositivos de gama baja con recursos limitados solo dediquen pequeñas cantidades de memoria para registrar transacciones, mientras que los de gama alta pueden dedicar una cantidad considerablemente mayor.

Como los mineros están motivados principalmente por las ganancias, las transacciones con tarifas más altas son las que tienen más probabilidades de descartarse del mempool primero cuando se confirman. Calcular las tarifas con precisión es difícil, especialmente cuando el espacio de bloques es limitado y la demanda es alta, pero el mempool proporciona un punto de partida.

Para estimar las tarifas, uno puede mirar las transacciones actuales no confirmadas. Es lógico que los usuarios no paguen de más en tiempos de bajo rendimiento. Tampoco deberían pagar menos por las transacciones sensibles al tiempo en las horas pico, ya que puede pasar un tiempo antes de que se confirme. Al tener en cuenta la distribución de las tarifas en un momento dado, pueden hacer una suposición informada sobre la rapidez con la que se incluirá su transacción.

