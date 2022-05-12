---
keywords: Crypto
title: Bloque de candidatos
description: Bloque de candidatos. Un bloque temporal creado por un nodo de minería (minero) para agregar a la cadena de bloques para recibir las recompensas del bloque.
---

# Bloque de candidatos
En pocas palabras, un bloque candidato es un bloque que un nodo de minería (miner) está tratando de extraer para recibir la recompensa del bloque. Por lo tanto, un bloque candidato puede describirse como un bloque temporal que la red validará o descartará. Los mineros compiten entre sí para validar el siguiente bloque y agregarlo a la cadena de bloques, pero primero deben crear un bloque candidato para participar en la competencia minera.

Los mineros crean bloques de candidatos recopilando y organizando múltiples transacciones no confirmadas del grupo de memoria. Luego, las transacciones se procesan para formar una estructura de [árbol de Merkle](/merkle-tree),. que eventualmente producirá una raíz de Merkle (o hash de raíz). La raíz de Merkle es un único hash que representa todos los hash anteriores de ese árbol y, por lo tanto, todas las transacciones que se incluyeron en ese bloque en particular.

El hash raíz, junto con el hash del bloque anterior y un número aleatorio llamado [nonce](/nonce),. se coloca en el encabezado del bloque. Luego, el minero procesa el encabezado del bloque, generando una salida basada en esos componentes (hash raíz, hash del bloque anterior y nonce) además de algunos otros elementos. El resultado resultante es el hash del bloque y servirá como un identificador único del bloque recién generado (bloque candidato).

Para que se considere válido, la salida (hash de bloque) debe comenzar con un cierto número de ceros (menos que un valor objetivo definido por el protocolo). Esto significa que el proceso de minería se basa en múltiples intentos (ensayo y error), ya que los nodos de minería tienen que realizar una gran cantidad de funciones hash con diferentes valores de nonce hasta que finalmente se produce un hash de bloque válido. El hash de bloque producido es lo que prueba que el minero hizo su trabajo (por lo tanto, Prueba de trabajo).

Después de que un minero encuentre un hash de bloque válido, su bloque candidato se transmitirá al resto de los nodos de la red, que verificarán la autenticidad del hash. Si todo está bien, el bloque candidato se registrará en la cadena de bloques. En este punto, cada nodo de validación actualiza su copia de los datos de la cadena de bloques para reflejar el bloque extraído recientemente, y el minero obtendrá la recompensa del bloque.

