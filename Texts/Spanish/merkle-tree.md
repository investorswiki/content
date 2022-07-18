---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Árbol Merkle
description: Árbol Merkle. Una forma de organizar y estructurar grandes cantidades de datos para que sea más fácil de procesar. Una estructura de datos basada en hash.
---

# Árbol Merkle
Un árbol de Merkle es una forma de organizar y estructurar grandes cantidades de datos para que su procesamiento sea más sencillo. En el caso de las criptomonedas y la cadena de [bloques](/blockchain),. el árbol de Merkle se utiliza para estructurar los datos de las transacciones de una manera que exige menos recursos.

Cuando se realiza una transacción de criptomonedas en una estructura de árbol de Merkle, se le asigna un hash y luego se le asigna un valor de hash equivalente. Después de que se aplica el hash a cada transacción en el árbol de Merkle, los valores hash que se producen se emparejan con otro valor hash y luego se vuelven a aplicar el hash. Por ejemplo, los valores hash 'AB' y 'AC' se combinan para crear 'ABC'.

Este proceso de emparejamiento de valores hash se repite hasta que se produce un valor hash final. El valor hash final, la raíz de Merkle, proporciona un resumen de todas las transacciones que contiene. El resumen raíz de Merkle se inserta luego en el encabezado del bloque.

#### Seguridad de datos

Una estructura de árbol de Merkle proporciona un registro de fácil acceso de las transacciones en un [bloque](/block). Por lo tanto, es muy sencillo comprobar si los datos de un bloque han sido modificados o alterados. Esto es cierto porque cualquier cambio en una transacción (o cualquier otro dato relacionado) en el árbol de Merkle conduciría a una raíz de Merkle correspondiente completamente diferente.

#### Uso eficiente de los recursos

Si las criptomonedas no usaran árboles Merkle, cada solicitud de verificación implicaría el envío de enormes cantidades de información a través de la red. La estructuración de datos de transacciones en un árbol de Merkle es un uso mucho más eficiente de los recursos. La validación de una transacción no requiere una copia completa del libro mayor, ya que los datos de la transacción con hash se pueden verificar en una raíz de Merkle, lo que requiere que se envíe mucha menos información a través de los nodos y, por lo tanto, menos poder de cómputo para analizar la integridad general de los datos.

En otras palabras, una estructura de árbol de Merkle permite a los usuarios verificar que una transacción individual se ha incluido en un bloque sin tener que pasar por el proceso de descarga de toda la cadena de bloques. La tecnología es una herramienta importante para que las criptomonedas organicen los datos de las transacciones y funcionen tan eficientemente como lo hacen. Sin árboles Merkle, es probable que la mayor demanda de recursos resulte en menos [nodos](/node) participando en la red.

