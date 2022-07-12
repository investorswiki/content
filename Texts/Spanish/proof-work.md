---
keywords: Investing,Cryptocurrency,Bitcoin
title: Prueba de trabajo (PoW)
description: La prueba de trabajo describe el proceso que permite que la red de bitcoin se mantenga sólida al dificultar el proceso de extracción o registro de transacciones.
---

# Prueba de trabajo (PoW)
## ¿Qué es la prueba de trabajo (PoW)?

La prueba de trabajo (PoW) describe un sistema que requiere una cantidad de esfuerzo no insignificante pero factible para impedir usos frívolos o maliciosos de la potencia informática, como enviar correos electrónicos no deseados o lanzar ataques de denegación de servicio. Posteriormente, Hal Finney adaptó el concepto para asegurar el dinero digital en 2004 a través de la idea de una "prueba de trabajo reutilizable" utilizando el algoritmo hash SHA-256.

Tras su introducción en 2009, Bitcoin se convirtió en la primera aplicación ampliamente adoptada de la idea PoW de Finney (Finney también fue el destinatario de la primera transacción de bitcoin). La prueba de trabajo también forma la base de muchas otras [ocurrencias de](/cryptocurrency) [criptas](/cryptocurrency),. lo que permite un consenso seguro y descentralizado.

## Comprender la prueba de trabajo

Esta explicación se centrará en la prueba de trabajo tal como funciona en la red [bitcoin](/bitcoin). Bitcoin es una moneda digital que está respaldada por una especie de [libro mayor distribuido](/distributed-ledger-technology-dlt) conocido como " [blockchain](/blockchain) ". Este libro contiene un registro de todas las transacciones de bitcoin, organizadas en "bloques" secuenciales, de modo que ningún usuario puede gastar dos veces ninguna de sus existencias. Para evitar la manipulación, el libro mayor es público o "distribuido"; una versión alterada sería rápidamente rechazada por otros usuarios.

La forma en que los usuarios detectan la manipulación en la práctica es a través de [hashes](/hash),. largas cadenas de números que sirven como prueba de trabajo. Ponga un conjunto dado de datos a través de una función hash (bitcoin usa SHA-256), y solo generará un hash. Sin embargo, debido al "efecto de avalancha", incluso un pequeño cambio en cualquier parte de los datos originales dará como resultado un hash totalmente irreconocible. Cualquiera que sea el tamaño del conjunto de datos original, el hash generado por una función determinada tendrá la misma longitud. El hash es una función unidireccional: no se puede utilizar para obtener los datos originales, solo para comprobar que los datos que generaron el hash coinciden con los datos originales.

Generar cualquier hash para un conjunto de transacciones de bitcoin sería trivial para una computadora moderna, por lo que para convertir el proceso en "trabajo", la red de bitcoin establece un cierto nivel de "dificultad". Esta configuración se ajusta para que se " [mine](/bitcoin-mining) " un nuevo bloque, que se agrega a la cadena de bloques generando un hash válido, aproximadamente cada 10 minutos. La dificultad de configuración se logra estableciendo un ["objetivo" para el hash](/target-hash) : cuanto menor sea el objetivo, menor será el conjunto de hashes válidos y más difícil será generar uno. En la práctica, esto significa un hash que comienza con una cadena muy larga de ceros.

> La prueba de trabajo se creó inicialmente como una propuesta de solución al creciente problema del correo electrónico no deseado.

>

## Consideraciones Especiales

Dado que un conjunto dado de datos solo puede generar un hash, ¿cómo se aseguran los mineros de generar un hash por debajo del objetivo? Alteran la entrada agregando un número entero, llamado [nonce](/nonce) ("número usado una vez"). Una vez que se encuentra un hash válido, se transmite a la red y el bloque se agrega a la cadena de bloques.

La minería es un proceso competitivo, pero es más una lotería que una carrera. En promedio, alguien generará una prueba de trabajo aceptable cada diez minutos, pero nadie sabe quién será. Los mineros se agrupan para aumentar sus posibilidades de minar bloques, lo que genera tarifas de transacción y, por un tiempo limitado, una recompensa de bitcoins recién creados.

La prueba de trabajo hace que sea extremadamente difícil alterar cualquier aspecto de la cadena de bloques, ya que dicha alteración requeriría volver a minar todos los bloques posteriores. También dificulta que un usuario o grupo de usuarios monopolicen el poder de cómputo de la red, ya que la maquinaria y el poder necesarios para completar las funciones hash son costosos.

> Si parte de una red minera comienza a aceptar una prueba de trabajo alternativa, se conoce como [bifurcación dura](/hard-fork).

>

## Ejemplo de prueba de trabajo

La prueba de trabajo requiere que una computadora participe aleatoriamente en funciones hash hasta que llegue a una salida con la cantidad mínima correcta de ceros a la izquierda. Por ejemplo, el hash para el bloque #660000, extraído el 4 de diciembre de 2020 es 000000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. La recompensa en bloque por ese hash exitoso fue de 6,25 BTC.

Ese bloque siempre contendrá 745 transacciones que implican poco más de 1.666 bitcoins, así como el encabezado del bloque anterior. Si alguien intentara cambiar el monto de una transacción incluso en 0.000001 bitcoin, el hash resultante sería irreconocible y la red rechazaría el intento de fraude.

## Preguntas frecuentes sobre la prueba de trabajo

### ¿Qué significa Prueba de trabajo?

PoW requiere que los nodos en una red brinden evidencia de que han gastado poder computacional (es decir, trabajo) para lograr un consenso de manera descentralizada y evitar que los malos actores se apoderen de la red.

### ¿Cómo valida la prueba de trabajo una transacción criptográfica?

El trabajo en sí es arbitrario. Para Bitcoin, implica iteraciones de algoritmos hash SHA-256. Sin embargo, el "ganador" de una ronda de hash agrega y registra las transacciones del mempool en el siguiente bloque. Debido a que el "ganador" se elige al azar en proporción al trabajo realizado, incentiva a todos en la red a actuar con honestidad y registrar solo transacciones verdaderas.

### ¿Por qué las criptomonedas necesitan prueba de trabajo?

Debido a que son descentralizadas y de igual a igual por diseño, las cadenas de bloques, como las redes de criptomonedas, requieren alguna forma de lograr tanto el consenso como la seguridad. La prueba de trabajo es uno de esos métodos que hace que sea demasiado intensivo en recursos para tratar de superar la red. También existen otros mecanismos de prueba que requieren menos recursos, pero que tienen otros inconvenientes o fallas, como la [prueba](/proof-stake-pos) [de participación (PoS)](/proof-stake-pos) y [la prueba de quema](/proof-burn-cryptocurrency). Sin un mecanismo de prueba, la red y los datos almacenados en ella serían vulnerables a ataques o robos.

### ¿Bitcoin usa prueba de trabajo?

Sí. Utiliza un algoritmo PoW basado en la función hash SHA-256 para validar y confirmar transacciones, así como para poner en circulación nuevos bitcoins.

### ¿En qué se diferencia la prueba de participación (PoS) de PoW?

PoS es un mecanismo de consenso que asigna aleatoriamente el nodo que extraerá o validará transacciones en bloque de acuerdo con la cantidad de monedas que tenga ese nodo. Cuantos más tokens se mantengan en una billetera, más poder de minería se le otorgará efectivamente. Si bien PoS requiere muchos menos recursos, tiene varios otros defectos, incluida una mayor probabilidad de un [ataque del 51%](/51-attack) en altcoins más pequeños e incentivos para acumular tokens y no usarlos.

## Reflejos

- La prueba de participación (POS) fue uno de varios mecanismos de consenso novedosos creados como alternativa a la prueba de trabajo.

- La prueba de trabajo (PoW) es un mecanismo de consenso descentralizado que requiere que los miembros de una red se esfuercen en resolver un rompecabezas matemático arbitrario para evitar que alguien juegue con el sistema.

- La prueba de trabajo a escala requiere enormes cantidades de energía, que solo aumenta a medida que más mineros se unen a la red.

- Debido a la prueba de trabajo, las transacciones de Bitcoin y otras criptomonedas se pueden procesar entre pares de manera segura sin la necesidad de un tercero de confianza.

- La prueba de trabajo se usa ampliamente en la minería de criptomonedas, para validar transacciones y extraer nuevos tokens.

