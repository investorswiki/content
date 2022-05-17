---
keywords: Investing,Cryptocurrency,Blockchain
title: Consenso de hashgraph
description: El consenso de Hashgraph funciona de manera diferente a los mecanismos de consenso de blockchain más conocidos. Obtenga más información sobre él y cómo funciona.
---

# Consenso de hashgraph
## ¿Qué es el consenso de Hashgraph?

El consenso de Hashgraph es una alternativa a, o la próxima generación de, la tecnología detrás de los mecanismos de consenso de blockchain. En lugar de usar el poder computacional de grandes redes para verificar transacciones, las transacciones se registran y confirman a través de un protocolo que usa comunicación de nodos.

Un hashgraph es un libro mayor descentralizado de la misma manera que lo es una cadena de bloques. Almacena información, la protege con criptografía, limita el acceso y utiliza los datos almacenados como verificación. Sin embargo, una red de hashgraph alcanza el consenso de una manera muy diferente a como lo hace una cadena de bloques.

El consenso de Hashgraph se alcanza utilizando conceptos llamados "chismes", "chismes sobre chismes" y votación virtual. Los diseñadores del sistema informan que resuelve los problemas inherentes a los [algoritmos](/algorithm) de creación de consenso , como la [prueba de trabajo](/proof-work) (PoW), en términos de mejor velocidad y mayor eficiencia.

> El consenso de Hashgraph (chismes, chismes sobre chismes y votación virtual) es el mecanismo que utiliza el libro mayor distribuido de Hedera para validar y confirmar transacciones.

>

## Comprender el consenso de Hashgraph

Hashgraph es una alternativa a blockchain. Similar a una cadena de bloques, almacena datos y los encripta. Se genera un hash para la información de la transacción, y se agregan y construyen nuevas transacciones o datos. Sin embargo, una cadena de bloques es un libro mayor que consta de bloques de datos. Cada bloque está vinculado al bloque anterior utilizando sus datos, verificados por una red de validadores para crear el siguiente bloque. Este proceso crea una cadena. Un hashgraph no es una cadena: toda la información se guarda en un libro de contabilidad encriptado y todos los usuarios participan en el proceso de validación, no solo los validadores.

Por ejemplo, Alice crea una transacción con Bob y toda la información que conoce se le entrega a él. Bob luego hace una transacción con Kris. Toda la información que tiene Bob se comunica a Kris. Kris realiza transacciones con Eli y todo lo que sabe se transfiere. Esto continúa en toda la red, con la cadena esencialmente cotilleando sobre los eventos que están ocurriendo. Cada nodo sabe lo que saben todos los demás nodos, por lo que no hay necesidad de validación computacional.

A medida que los chismes se propagan de un usuario a otro, la red utiliza algoritmos y automatización para garantizar que el estado del libro mayor de hashgraph se actualice y sea el mismo.

### Chisme

La información sobre los datos se llama "chismes". La estructura de datos contenida en una transacción son:

- Una marca de tiempo

- Más transacciones o ceros

- Dos hashes de los contenedores principales

- Una firma encriptada.

Los dos hashes son los últimos eventos de dos nodos de sincronización que comparan su información. Los nodos crean eventos y se sincronizan continuamente.

> Hashgraph, el libro mayor, es más eficiente que blockchain porque no se desperdicia energía en bloques que no se aceptan. Toda la información se conserva en un hashgraph.

>

### Chismes sobre chismes

La información sobre los datos de transacciones se denomina "chismes sobre chismes". La información se sincroniza en la red hashgraph mediante un evento llamado "sincronización de chismes". Una sincronización de chismes es un historial colaborativo de "eventos de chismes" en todo el hashgraph. De esta forma, los datos no pueden ser alterados ni manipulados y hay consenso.

### Votación Virtual

La votación virtual ocurre cuando los nodos comparan eventos y llegan a un consenso a través de un algoritmo de votación. Así es como funciona: a una transacción se le asigna una marca de tiempo cuando un nodo la recibe. A medida que pasa a los otros nodos de la red, se le asigna una marca de tiempo que es la mediana de todas las marcas de tiempo de esa transacción recibida por los nodos de la red. La mediana actúa como resultado de la votación. Esto crea un sistema de transacciones más justo que una cadena de bloques porque la red decide, no un nodo.

### Tolerancia a fallos

Al igual que con la mayoría de los libros de contabilidad distribuidos y blockchain, siempre existe la posibilidad de que un participante en la red no sea honesto. Puede haber retrasos en la comunicación o la latencia de la red que hace que los nodos no se comuniquen correctamente.

Los mecanismos de consenso están diseñados para tratar estas fallas mediante el establecimiento de criterios de tolerancia a fallas. Los desarrolladores deben considerar y dar cuenta de los malos actores, las malas conexiones, la latencia de la red y otros problemas de la red. El consenso de Hashgraph puede tolerar que un tercio de la red actúe de manera maliciosa. Según se informa, es tolerante a fallas bizantinas asincrónicas, el nivel de seguridad más alto, lo que significa que los nodos honestos en una red continúan operando incluso si hay malos actores.

## ¿En qué se diferencia Hashgraph de Blockchain?

Hashgraph es una estructura de datos que mantiene los registros de quién le dijo a quién qué y en qué orden lo hicieron. Es una historia colaborativa de eventos de chismes a medida que los participantes agregan y comparten información, lo que valida las transacciones mucho más rápido que una cadena de bloques.

Blockchain agrega información de transacciones anteriores a la información de transacciones nuevas y la encripta. Se necesita un tercero para validar las transacciones entre las partes. Hashgraph no necesita este proceso lento debido al protocolo de chismes.

> El consenso de Hashgraph es mucho más rápido que los mecanismos de consenso de blockchain, con tiempos promedio de confirmación de transacciones en segundos en lugar de minutos.

>

Bitcoin y muchas otras criptomonedas tienen problemas con el tiempo de los mensajes. Sin embargo, la tolerancia a fallas bizantinas asincrónicas de hashgraph supera el problema de la sincronización de los mensajes al suponer que los mensajes perdidos o retrasados eventualmente llegarán a sus destinos.

Por ejemplo, si dos transacciones ocurren simultáneamente, una red blockchain elige en qué orden ocurrieron las transacciones. En algunas cadenas de bloques, las tarifas de transacción priorizan la confirmación. Otras redes pueden decidir qué transacción se confirma en función de la cantidad de tokens que haya apostado un validador. En estas cadenas de bloques, un nodo influye en el resultado.

El consenso de Hashgraph elimina la influencia que un nodo o un grupo de nodos pueden tener en las transacciones. Debido a que hay una marca de tiempo en cada transacción y cada transacción se comunica a toda la red, se resuelven los problemas de sincronización de las transacciones.

## Reflejos

- El sistema de registro distribuido hashgraph no ha recibido una amplia adopción por parte de la comunidad criptográfica.

- El consenso de Hashgraph utiliza información sobre la información en lugar del contenido en sí mismo para crear consenso.

- La información primaria en el hashgraph se llama "chismes" y la información secundaria se llama "chismes sobre chismes".

## PREGUNTAS MÁS FRECUENTES

### ¿Cómo funciona el consenso de Hashgraph?

El consenso de Hashgraph funciona utilizando marcas de tiempo de consenso y "chismes", en los que cada nodo comunica todo lo que sabe a nodos aleatorios en "eventos de chismes".

### ¿Qué es el consenso de Hashgraph?

El consenso de Hashgraph es un mecanismo utilizado en un libro mayor distribuido de hashgraph para validar transacciones.

### ¿Hashgraph reemplazará a Blockchain?

Hashgraph está diseñado para ser, y comercializado como, una mejora en la tecnología blockchain, pero aún está por verse si la reemplazará. Todavía no tiene tanto interés y adopción por parte de los desarrolladores como la tecnología blockchain.

