---
keywords: Crypto
title: Filtro de floración
description: Filtro de floración. Una estructura de datos que se puede utilizar para informar al usuario si un artículo en particular es parte de un conjunto de artículos.
---

# Filtro de floración
Un filtro Bloom es una estructura de datos que se puede usar para informar al usuario si un elemento en particular es parte de un conjunto. Aunque no puede decir con certeza si un elemento está en el conjunto, puede decir con certeza si el elemento no lo está.

Creados por Burton Howard Bloom en 1970, los filtros Bloom son una oferta atractiva para una variedad de aplicaciones debido a su eficiencia en el uso del espacio. En algunas criptomonedas (sobre todo Bitcoin), juegan un papel integral en la Verificación de Pago Simplificada, o SPV.

Al usar un cliente SPV, los usuarios pueden interactuar con la red Bitcoin sin ejecutar un nodo completo. Los nodos completos vienen con ciertos requisitos computacionales y de almacenamiento que los hacen difíciles de manejar para ejecutarse en dispositivos de baja potencia como los teléfonos inteligentes. Los clientes de SPV, por otro lado, simplemente consultan los nodos completos para obtener información relevante para la(s) billetera(s) del usuario.

La solución más sencilla para transmitir estos datos al usuario sería hacer que los nodos completos conozcan las claves del cliente, de modo que solo se les envíen las transacciones pertinentes. Evidentemente, esta es una solución mediocre ya que se sacrificaría la privacidad del cliente. Por otro lado, descargar todas las transacciones solo para descartar la mayoría de ellas sería una pérdida de ancho de banda. Introduzca los filtros Bloom.

Ilustremos. Suponga que un cliente, Alice, tiene una transacción de alto valor que no quiere que Bob, que ejecuta un nodo completo, conozca. Ella construye un filtro Bloom, que ilustraremos como una cuadrícula de 10x1:

Pasa los datos de la transacción que le interesan a través de dos funciones hash diferentes, que generan dos números entre 0 y 9. Llamémoslos 4 y 7. Le envía el filtro a Bob.

Mirando esta cuadrícula, no tiene idea de qué datos ha pasado Alice al filtro. Si tuviera un conjunto en el que estuvieran contenidos los datos, podría analizarlos y compararlos con el filtro; si hay una coincidencia, existe la posibilidad de que fuera la información que solicitó Alice.

Al mismo tiempo, es probable que haya muchas entradas que se asignen a 4 y 7, por lo que Bob no puede determinar qué parte de los datos le interesa a Alice. Simplemente devuelve todas las coincidencias y Alice las filtra por su parte.

Esto es, por supuesto, una simplificación excesiva, pero demuestra el concepto: los filtros Bloom ofuscan los verdaderos intereses del cliente. No es un método perfecto (todavía hay preocupaciones sobre su privacidad), pero es una mejora con respecto a una solicitud sin blindaje a un nodo.

