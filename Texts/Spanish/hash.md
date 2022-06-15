---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Picadillo
description: Picadillo. La salida producida por una función hash después de mapear un dato. También puede denominarse valor hash, código hash o resumen.
---

# Picadillo
En [criptografía](/cryptography),. la palabra hash se refiere a la salida producida por una función hash después de que se envía (asigna) una parte de los datos a través de ella. Además de simplemente hash, la salida producida por las funciones hash también puede denominarse valor hash, código hash o resumen.

Para comprender mejor qué es un hash, vale la pena analizar qué son las funciones hash y cómo funcionan.

Las funciones hash son [algoritmos matemáticos](/algorithm) que convierten un valor de entrada de cualquier tamaño en una salida (hash) de tamaño fijo. En la mayoría de los casos, la salida consiste en un número hexadecimal. Esto significa que el hash a menudo se denota como una combinación de números (0 a 9) y letras (a a f).

Por ejemplo, si usamos la palabra "Binance" como valor de entrada y la asignamos a través de una función hash SHA-256, el valor de salida (o hash) devuelto será:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Tenga en cuenta que no importa cuántas veces realicemos esta acción, la salida siempre será la misma (siempre que la entrada no cambie).

Por otro lado, cualquier cambio menor en la entrada hará que la función hash devuelva un hash completamente diferente a la salida. Por ejemplo, si enviamos la palabra "binance" en lugar de "Binance", tendríamos como resultado el siguiente hash:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Los hashes son útiles para verificar la validez de cierta información, sin revelar cuál es la información. En la práctica, las funciones hash se pueden aplicar a varios escenarios. Algunos casos de uso incluyen búsquedas en bases de datos, análisis de archivos grandes y gestión de datos.

Cuando se combinan con técnicas criptográficas, tenemos las llamadas funciones hash criptográficas. Estos se utilizan ampliamente en la seguridad de la información y son una parte esencial de la mayoría de las redes blockchain.

Por ejemplo, la cadena de bloques de Bitcoin tiene muchas operaciones que involucran hash, y estas son cruciales en el proceso de minería.

## Reflejos

- Un hash es una función que cumple con las demandas cifradas necesarias para resolver un cálculo de blockchain.

- Un hash, como un nonce o una solución, es la columna vertebral de la red blockchain.

- Se desarrolla un hash basado en la información presente en el encabezado del bloque.

- Los hashes tienen una longitud fija, ya que hace que sea casi imposible adivinar la longitud del hash si alguien intenta descifrar la cadena de bloques.

- Los mismos datos siempre producirán el mismo valor hash.

## PREGUNTAS MÁS FRECUENTES

### ¿Cómo se calcula un valor hash?

Una función hash utiliza algoritmos matemáticos complejos que convierten datos de longitud arbitraria en datos de longitud fija (por ejemplo, 256 caracteres). Si cambia un bit en cualquier parte de los datos originales, el valor hash completo cambia, lo que lo hace útil para verificar la fidelidad de los archivos digitales y otros datos.

### ¿Para qué se usan los hashes en las cadenas de bloques?

Los hashes se utilizan en varias partes de un sistema blockchain. En primer lugar, cada bloque contiene el hash del [encabezado](/block-header-cryptocurrency) del bloque anterior, lo que garantiza que no se haya manipulado nada a medida que se agregan nuevos bloques. Además, la minería de criptomonedas mediante [prueba de trabajo](/proof-work) (PoW) utiliza el hash de números generados aleatoriamente para llegar a un valor hash específico que contiene una serie de ceros a la izquierda. Esta función arbitraria consume muchos recursos, lo que dificulta que un mal actor se apodere de la red.

### ¿Qué es una función hash?

Las funciones hash son funciones matemáticas que transforman o "asignan" un conjunto dado de datos en una cadena de bits de tamaño fijo, también conocido como "valor hash".

