---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Prueba de Capacidad (Criptomoneda)
description: La prueba de capacidad es un mecanismo de consenso que utiliza el espacio del disco duro de un nodo de minería para decidir los derechos de minería en la red de la cadena de bloques.
---

# Prueba de Capacidad (Criptomoneda)
## ¿Qué es la prueba de capacidad (PoC) para las criptomonedas?

La prueba de capacidad (PoC) es un algoritmo de [mecanismo de consenso](/consensus-mechanism-cryptocurrency) utilizado en blockchains que permite que los dispositivos de [minería](/bitcoin-mining) en la red usen su espacio disponible en el disco duro para decidir los derechos de minería y validar las transacciones. Esto contrasta con el uso de la potencia computacional del dispositivo de minería (como en el algoritmo [de prueba de trabajo](/proof-work) ) o la participación del minero en las criptomonedas (como en el algoritmo [de prueba de participación ).](/proof-stake-pos)

## Comprender la prueba de capacidad

La prueba de capacidad surgió como una de las muchas soluciones alternativas al problema del alto consumo de energía en los sistemas de prueba de trabajo (PoW) y el acaparamiento de criptomonedas en los sistemas de prueba de participación (PoS).

La prueba de capacidad permite que los dispositivos de minería, también conocidos como nodos, en la red de la cadena de [bloques](/blockchain) utilicen el espacio vacío en su disco duro para extraer las [criptomonedas disponibles](/cryptocurrency).

En lugar de alterar repetidamente los números en el encabezado del bloque y el hash repetido para el valor de la solución como en un sistema PoW, PoC funciona almacenando una lista de posibles soluciones en el disco duro del dispositivo de minería incluso antes de que comience la actividad minera.

Cuanto más grande sea el disco duro, más valores de solución posibles se pueden almacenar en el disco duro, más posibilidades tiene un minero de igualar el valor hash requerido de su lista, lo que da como resultado más posibilidades de ganar la recompensa minera.

Para dibujar una analogía, si las recompensas de la lotería se basan en acertar la mayor cantidad de números en el boleto ganador, entonces un jugador con una lista más larga de posibles soluciones tendrá mejores posibilidades de ganar. Además, el jugador puede seguir usando los números de bloque de boletos de lotería una y otra vez.

[Burstcoin](/burstcoin) es una criptomoneda que utiliza un sistema de prueba de capacidad. Otras monedas que lo usan son Storj, Chia y SpaceMint.

## Cómo funciona PoC: trazado y minería

El protocolo de prueba de capacidad implica un proceso de dos pasos que implica el trazado y la minería.

En primer lugar, se traza el disco duro: la lista de todos los valores [nonce posibles](/nonce) se crea mediante el hashing repetido de datos, incluida la cuenta de un minero. Cada nonce contiene 8192 hashes, que están numerados del 0 al 8191. Todos los hashes se emparejan en "cucharadas", lo que significa que los hashes adyacentes se combinan para formar un par de dos. Por ejemplo, los hash 0 y 1 constituyen la primicia 0, los hash 2 y 3 constituyen el hash 1, y así sucesivamente.

El segundo paso implica el ejercicio de minería real, durante el cual un minero calcula un número de pala. Por ejemplo, si un minero comienza la actividad minera y genera una primicia número 38, el minero entonces iría a la primicia número 38 del nonce 1 y usaría los datos de esa primicia para calcular un valor de fecha límite.

El proceso se repite para calcular la fecha límite para cada nonce retenido en el disco duro del minero. Tras el cálculo de todos los plazos, el minero selecciona el que tiene el plazo mínimo.

Una fecha límite representa la duración del tiempo en segundos que debe transcurrir desde que se falsificó el último bloque antes de que un minero pueda falsificar un nuevo bloque. Si nadie más ha forjado un bloque dentro de este tiempo, el minero puede forjar un bloque y reclamar la recompensa del bloque.

Por ejemplo, si al minero X se le ocurre un plazo mínimo de 36 segundos y ningún otro minero puede falsificar el bloque en los próximos 36 segundos, X asegurará la oportunidad de falsificar el siguiente bloque y será recompensado.

## Ventajas y desventajas de la prueba de capacidad

PoC tiene varias ventajas sobre los sistemas PoW y PoS, así como algunas desventajas importantes que incluyen:

<h5><a href="">TTT</a></h5>

## Reflejos

- El principal beneficio de un sistema PoC es su eficiencia en comparación con los sistemas de prueba de trabajo (PoW) y prueba de participación (PoS).

- Las cadenas de bloques que se ejecutan con prueba de capacidad incluyen Storj, Burst, Chia y SpaceMint.

- Los sistemas de autenticación de prueba de capacidad (PoC) emplean espacio libre en el disco duro de un dispositivo para almacenar soluciones a un problema de hashing de criptomonedas.

