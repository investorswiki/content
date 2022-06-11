---
keywords: Investing,Cryptocurrency,Blockchain
title: Bloque (Bloque Bitcoin)
description: Los bloques son estructuras de datos dentro de una base de datos donde los datos de transacciones de criptomonedas se registran permanentemente; una vez escrito, no puede ser alterado o eliminado.
---

# Bloque (Bloque Bitcoin)
## ¿Qué es un bloque (Blockchain Block)?

Los bloques son estructuras de datos dentro de la base de datos de la cadena de bloques, donde los datos de transacciones en una cadena de bloques de criptomonedas se registran de forma permanente. Un bloque registra algunas o todas las transacciones más recientes aún no validadas por la red. Una vez validados los datos, se cierra el bloque. Luego, se crea un nuevo bloque para ingresar y validar nuevas transacciones.

Por lo tanto, un bloque es un almacén permanente de registros que, una vez escritos, no se pueden modificar ni eliminar.

## Cómo funciona un bloque (Blockchain Block)

Una red [blockchain](/blockchain) es testigo de una gran cantidad de actividad de transacciones. Cuando se usa en criptomonedas, mantener un registro de estas transacciones ayuda al sistema a rastrear cuánto se usó o no y qué partes estuvieron involucradas. Las transacciones realizadas durante un período determinado se registran en un archivo llamado bloque, que es la base de la red blockchain.

Un bloque almacena información. Hay muchas piezas de información incluidas dentro de un bloque, pero no ocupa una gran cantidad de espacio de almacenamiento. Los bloques generalmente incluyen estos elementos, pero pueden variar entre diferentes tipos:

- **Número mágico**: un número que contiene valores específicos que identifican ese bloque como parte de la red de una criptomoneda en particular.

- **Tamaño de bloque**: establece el límite de tamaño en el bloque para que solo se pueda escribir una cantidad específica de información en él.

- **Encabezado del bloque**: Contiene información sobre el bloque.

- **Contador de transacciones**: Un número que representa cuántas transacciones se almacenan en el bloque.

- **Transacciones**: Una lista de todas las transacciones dentro de un bloque.

El elemento transacción es el más grande porque contiene la mayor cantidad de información. Le sigue en tamaño de almacenamiento el encabezado del bloque, que incluye estos subelementos:

- **Versión**: La versión de criptomoneda que se está utilizando.

- **Hash de bloque anterior**: Contiene un hash (número encriptado) del encabezado del bloque anterior.

- **Hash Merkle root**: Hash de transacciones en el [árbol Merkle](/merkle-tree) del bloque actual.

- **Tiempo**: Una marca de tiempo para colocar el bloque en la cadena de bloques.

- **Bits**: la calificación de dificultad del hash de destino, lo que significa la dificultad para resolver el nonce.

- **Nonce**: El número encriptado que debe resolver un minero para verificar el bloque y cerrarlo.

Un número de 32 bits en el encabezado se llama nonce: el programa de minería usa números aleatorios para "adivinar" el nonce en el [hash](/hash). Cuando se verifica un nonce, el hash se resuelve cuando se adivina el nonce, o un número menor que él. Luego, la red cierra ese bloque, genera uno nuevo con un encabezado y el proceso se repite.

Se utilizan diferentes mecanismos para llegar a un consenso; la más popular para las criptomonedas es [la prueba de trabajo](/proof-work) (PoW), y la prueba de participación (PoS) se vuelve cada vez más debido al consumo reducido de energía en comparación con PoW.

## Relación de la minería con los bloques

Minería es el término utilizado para resolver el número que es el nonce, el único número que se puede cambiar en un encabezado de bloque. También es el proceso que usa la red de criptomonedas si se usa prueba de trabajo en el protocolo.

Se piensa comúnmente que la minería de criptomonedas es un problema matemático complejo; en realidad es un número aleatorio generado mediante hash. Hashing es el proceso de encriptar información usando el método de encriptación que usa una criptomoneda. Por ejemplo, Bitcoin usa SHA256 para su algoritmo de cifrado. Para que un minero genere el número "ganador", el programa de minería debe usar SHA 256 para codificar números aleatorios y colocarlos en el nonce para ver si coinciden.

> Resolver el hash de números aleatorios bajo el protocolo de prueba de trabajo es lo que requiere tanta energía y poder computacional. Se necesita una extensa red de mineros y suficiente energía para alimentar a un país pequeño para que siga funcionando.

>

La dificultad radica en que todos los encabezados de bloque anteriores se cifran aleatoriamente. Por lo tanto, el encabezado del bloque actual es un número encriptado generado aleatoriamente basado en los números encriptados generados aleatoriamente de bloques anteriores y la información del bloque actual.

## Otros usos de Block y Blockchain

Debido a que la mayoría de las definiciones de blockchain se refieren a Bitcoin porque fue la primera criptomoneda en usar una, muchas personas asocian bloques y blockchains con Bitcoin. Sin embargo, otras criptomonedas también usan bloques y cadenas de bloques. Es importante tener en cuenta que la red de Ethereum tiene una criptomoneda llamada ether que también usa bloques y blockchain.

Sin embargo, Ethereum y su cadena de bloques fueron diseñados para múltiples usos que van mucho más allá de las criptomonedas. Por ejemplo, se han desarrollado tokens no fungibles, contratos inteligentes, aplicaciones financieras descentralizadas y más utilizando Ethereum.

## Reflejos

- Los bloques y las cadenas de bloques no son utilizados únicamente por las criptomonedas. También tienen muchos otros usos.

- Los bloques se identifican con números largos que incluyen información de transacciones cifradas de bloques anteriores e información de transacciones nuevas.

- Los bloques y la información dentro de ellos deben ser verificados por una red antes de que se puedan crear nuevos bloques.

- Un bloque es un lugar en una cadena de bloques donde la información se almacena y cifra.

## PREGUNTAS MÁS FRECUENTES

### ¿Qué es Blockchain en palabras simples?

Una cadena de bloques es una base de datos que almacena y encripta información de manera vinculada, de modo que la información anterior no se puede modificar, y un grupo verifica las entradas antes de que se finalicen a través de un consenso, un acuerdo de que los datos son correctos.

### ¿Para qué se utilizan las cadenas de bloques?

Las cadenas de bloques se utilizan en criptomonedas, aplicaciones financieras descentralizadas, tokens no fungibles, con más usos constantemente en desarrollo.

### ¿Cómo se crea un bloque Blockchain?

Los bloques se crean cuando los mineros o los validadores de bloques validan con éxito la información cifrada en el encabezado del bloque, lo que provoca la creación de un nuevo bloque.

