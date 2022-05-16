---
keywords: Investing,Cryptocurrency,Altcoins
title: Hachís de destino
description: Un hash de destino establece la dificultad para la minería de criptomonedas utilizando un sistema de cadena de bloques de prueba de trabajo (PoW).
---

# Hachís de destino
## ¿Qué es un hash objetivo?

En la minería de criptomonedas, un hash de destino es un valor numérico que [el encabezado de un bloque con hash](/block-header-cryptocurrency) debe ser menor o igual para que se le otorgue un nuevo bloque a un minero. Los encabezados de bloque identifican bloques individuales en una cadena de bloques.

La minería de criptomonedas se refiere al proceso de recopilación de criptomonedas como recompensa por el trabajo que completa. La naturaleza de este trabajo es verificar la legitimidad de las transacciones de una criptomoneda determinada. De esta manera, los mineros de criptomonedas son esencialmente auditores. Cuando mina, puede ganar criptomonedas sin tener que poner dinero para ello.

El hash de destino se usa para determinar la dificultad de la entrada y se puede ajustar para garantizar que los bloques se procesen de manera eficiente. Por ejemplo, los hashes de destino se utilizan en criptomonedas que utilizan un sistema de prueba de trabajo (PoW) para establecer la [dificultad de minería actual](/difficulty-cryptocurrencies) (incluido Bitcoin) [.](/difficulty-cryptocurrencies) Si una criptomoneda utiliza un sistema diferente para la minería, es posible que no requiera un hash de destino.

## Cómo funciona un hash de destino

[Las criptomonedas](/cryptocurrency) se basan en el uso de cadenas de [bloques](/blockchain) que contienen el historial de todas las transacciones de esa criptomoneda. Estas transacciones se [cifran](/hash) o codifican criptográficamente en una serie de caracteres alfanuméricos. Hashing implica tomar una cadena de datos de cualquier longitud y ejecutarla a través de un algoritmo para producir una salida con una longitud fija. La salida siempre tendrá la misma longitud, independientemente de cuán grande o pequeña sea la entrada (aunque la cantidad de permutaciones de un hash es astronómicamente grande). Cada bloque contendrá el hash del encabezado del bloque anterior.

La validación y codificación de la cadena de bloques se conoce como [minería](/bitcoin-mining). La minería implica el uso de computadoras para ejecutar algoritmos hash para procesar el bloque más reciente; la información que un usuario necesita extraer se encuentra en el encabezado del bloque. La red de criptomonedas establece un valor objetivo para este hash, llamado hash objetivo, y los mineros intentan determinar cuál es este valor probando todos los valores posibles.

El encabezado del bloque contiene el número de versión del bloque, una marca de tiempo, el hash utilizado en el bloque anterior, el hash de [Merkle Root](/merkle-root-cryptocurrency) [,](/merkle-root-cryptocurrency) el [nonce](/nonce) y el hash de destino. El bloque se genera tomando el hash del contenido del bloque, agregando una cadena aleatoria de números (el nonce) y procesando el bloque nuevamente.

Si el hash cumple con los requisitos del objetivo, el bloque se agrega a la cadena de bloques. Recorrer las soluciones para adivinar el nonce se conoce como [prueba de trabajo](/proof-work) (PoW), y el minero que puede encontrar el valor recibe el bloque y se le paga en criptomoneda.

## Consideraciones Especiales

### Hash de destino para Bitcoin

Bitcoin utiliza el algoritmo hash SHA-256. Este algoritmo genera números aleatorios verificables de una manera que requiere una cantidad predecible de potencia de procesamiento informático.

La extracción de un bloque requiere que el minero produzca un valor (un nonce) que, después de ser procesado (codificado criptográficamente), sea menor o igual que el utilizado en el bloque más reciente aceptado por la red bitcoin. Este número está entre 0 (la opción más pequeña) y 256 bits (la opción más grande), pero es poco probable que alguna vez sea el número máximo.

Debido a que el hash objetivo podría ser un número enorme, es posible que el minero deba probar una gran cantidad de valores antes de tener éxito. Un minero que no tiene éxito tiene que esperar al siguiente bloque (razón por la cual los mineros que encuentran una solución hash se comparan con los ganadores de una carrera o de la lotería).

El hash de destino se ajusta periódicamente. Las funciones hash utilizadas para generar el nuevo objetivo tienen propiedades específicas diseñadas para hacer que la cadena de bloques (y su criptomoneda) sea segura. Este proceso es determinista, lo que significa que producirá el mismo resultado cada vez que se utilice la misma entrada. Es lo suficientemente rápido como para no tardar demasiado en devolver un hash para la entrada. También hace que sea muy difícil determinar la entrada, especialmente para números grandes, y hace que pequeños cambios en la entrada den como resultado una salida hash muy diferente.

## Reflejos

- Los hashes de destino se utilizan en criptomonedas que utilizan un sistema de prueba de trabajo (PoW) para establecer la dificultad de minería actual (incluido Bitcoin); si una criptomoneda utiliza un sistema diferente para la minería, es posible que no requiera un hash de destino.

- En la minería de criptomonedas, un hash objetivo es un valor numérico que un encabezado de bloque con hash (que se usa para identificar bloques individuales en una cadena de bloques) debe ser menor o igual para que se le otorgue un nuevo bloque a un minero.

- La red Bitcoin ajusta la dificultad de la minería aumentando o disminuyendo el hash objetivo para preservar un intervalo promedio de 10 minutos entre nuevos bloques.

