---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Criptomoneda)
description: Una raíz de Merkle contiene información sobre cada hash de transacción individual que alguna vez estuvo en un bloque particular en una cadena de bloques.
---

# Merkle Root (Criptomoneda)
## ¿Qué es una raíz de Merkle?

Una raíz de Merkle es el [hash](/hash) de todos los hash de todas las transacciones que forman parte de un bloque en una red [blockchain](/blockchain).

## Comprender una raíz de Merkle

Una cadena de bloques se compone de varios bloques que están vinculados entre sí (de ahí el nombre de cadena de bloques). Un árbol hash, o el [árbol Merkle](/merkle-tree),. codifica los datos de la cadena de bloques de manera eficiente y segura. Permite la verificación rápida de los datos de la cadena de bloques, así como el movimiento rápido de grandes cantidades de datos de un nodo de computadora a otro en la red de la cadena de bloques punto a punto.

Cada transacción que ocurre en la red blockchain tiene un hash asociado. Sin embargo, estos hash no se almacenan en un orden secuencial en el bloque, sino en forma de una estructura similar a un árbol, de modo que cada hash está vinculado a su padre siguiendo una relación similar a un árbol padre-hijo.

Dado que hay numerosas transacciones almacenadas en un bloque en particular, todos los hash de transacciones en el bloque también se codifican, lo que da como resultado una raíz de Merkle.

Por ejemplo, considere un bloque de siete transacciones. En el nivel más bajo (llamado nivel de hoja), habrá cuatro hashes de transacción. En el nivel uno por encima del nivel de hoja, habrá dos hashes de transacción, cada uno de los cuales se conectará a dos hashes que están debajo de ellos en el nivel de hoja. En la parte superior (nivel dos), estará el último hash de transacción llamado raíz, y se conectará a los dos hash debajo (en el nivel uno).

Efectivamente, obtienes un árbol binario al revés, con cada nodo del árbol conectado a solo dos nodos debajo de él (de ahí el nombre de "árbol binario"). Tiene un hash de raíz en la parte superior, que se conecta a dos hashes en el nivel uno, cada uno de los cuales se conecta nuevamente a los dos hash en el nivel tres (nivel de hoja), y la estructura continúa dependiendo de la cantidad de hashes de transacción.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

El hash comienza en los nodos del nivel más bajo (nivel de hoja), y los cuatro hash se incluyen en el hash de los nodos que están vinculados a él en el nivel uno. Del mismo modo, el hash continúa en el nivel uno, lo que lleva a hashes de hashes que alcanzan niveles más altos, hasta que alcanza el único hash raíz superior.

Este hash de raíz se denomina raíz de Merkle y, debido a la vinculación de hashes en forma de árbol, contiene toda la información sobre cada hash de transacción individual que existe en el bloque. Ofrece un valor hash de punto único que permite validar todo lo presente en ese bloque.

Por ejemplo, si uno tiene que verificar una transacción que afirma provenir del bloque n.º 137, solo necesita verificar el árbol de Merkle del bloque, sin preocuparse por verificar nada en ningún otro bloque de la cadena de bloques, como el bloque n.º 136 o el bloque n.º 138.

<!--4861E8697637B7236BF11AA57D958059-->

Ingrese la raíz de Merkle, lo que acelera aún más la verificación. Dado que lleva toda la información sobre todo el árbol, solo es necesario verificar ese hash de transacción, su nodo hermano (si existe), y luego continuar hacia arriba hasta llegar a la parte superior.

Esencialmente, el árbol de Merkle y el mecanismo raíz de Merkle reducen significativamente los niveles de hashing que se deben realizar, lo que permite una verificación y transacciones más rápidas.

## Reflejos

- Las raíces de Merkle son fundamentales para el cálculo necesario para mantener las criptomonedas como bitcoin y ether.

- Las raíces de Merkle se utilizan en criptomonedas para asegurarse de que los bloques de datos que se pasan entre pares en una red de igual a igual estén completos, sin daños ni alteraciones.

- Una raíz de Merkle es una forma matemática simple de verificar los datos en un árbol de Merkle.

