---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Cabecera de bloque (criptomoneda)
description: Encabezado de bloque. Una sección en un bloque que contiene metadatos y un resumen de las transacciones del bloque. Esta es la información cifrada al minar.
---

# Cabecera de bloque (criptomoneda)
El encabezado del bloque es una sección de un [bloque](/block) que sirve como resumen del resto del bloque. Se compone de todos los [metadatos](/metadata),. como el tiempo y la [dificultad cuando se](/difficulty) [extrajo](/mining) el bloque , la [raíz de Merkle](/merkle-tree) de las transacciones incluidas y el [nonce](/nonce). También está presente el [hash](/hash) del bloque anterior , que es el que nos permite crear la “cadena” de bloques. En esencia, el encabezado del bloque contiene cualquier dato que no sea la lista de transacciones sin procesar en sí.

Un encabezado de bloque es lo que los mineros procesan para intentar que el bloque sea válido. Esto es mucho más eficiente que codificar la totalidad del bloque, que puede estar compuesto por miles de transacciones. Sería mucho más engorroso para un minero cambiar el nonce y repetir un bloque completo de 2 MB para cada intento. Compare esto con los encabezados de bloque de Bitcoin, por ejemplo, que tienen una longitud fija de 80 bytes.

Los encabezados de bloque son excelentes desde el punto de vista de la minería, pero debido a su pequeño tamaño, también son ideales para clientes ligeros. La cadena de bloques de Bitcoin es demasiado grande para que la almacenen dispositivos como los teléfonos inteligentes. Si la cadena tuviera 100 000 bloques de 1 MB, consumiría 100 GB de espacio. Pero con solo los encabezados de bloque para esos mismos bloques, solo ocuparía 0.008 GB u 8 MB.

De esta forma, los dispositivos con menos ancho de banda o espacio de almacenamiento aún pueden realizar algún grado de validación. Debido a que la raíz de Merkle encapsula todas las transacciones, luego pueden verificar si una transacción se incluyó en un bloque en particular. Esto tiene un costo: el usuario aún debe confiar en un tercero para que le proporcione la información necesaria. Dicho esto, los clientes ligeros son preferibles a un sistema en el que los usuarios no realizan ninguna verificación.

## Reflejos

- Se codifican para crear una prueba de trabajo para las recompensas mineras.

- Los encabezados de bloque identifican bloques individuales en una cadena de bloques.

- Los bloques se superponen verticalmente, comenzando con el "bloque de génesis".

- El número de versión de Bitcoin lo ayuda a realizar un seguimiento de los cambios en el protocolo.

- Cada encabezado de bloque contiene tres conjuntos de metadatos de bloque y múltiples componentes individuales.

