---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Contrato de bloqueo de tiempo hash (HTLC)
description: Contrato TimeLock hash (HTLC). Se refiere a una función especial que se utiliza para crear contratos inteligentes que pueden modificar los canales de pago.
---

# Contrato de bloqueo de tiempo hash (HTLC)
El término Hashed TimeLock Contract (HTLC) se refiere a una función especial que se utiliza para crear [contratos inteligentes](/smart-contract) que pueden modificar los canales de pago. Técnicamente, la función HTLC permite la implementación de transacciones con límite de tiempo entre dos usuarios. En la práctica, el destinatario de una transacción HTLC debe acusar recibo del pago mediante la presentación de una prueba criptográfica dentro de un plazo específico (número de bloques). Si el destinatario pierde o no reclama el pago, los fondos se devolverán al remitente original.

La función HTLC se aplica tanto en canales de pago bidireccionales como enrutados para permitir transferencias seguras de fondos a través de varios canales, sin necesidad de confiar en ninguno de los intermediarios.

Hay dos elementos clave que distinguen a HTLC de las transacciones de criptomonedas estándar, que son:

- Hashlock: una función que restringe el gasto de fondos hasta que cierta información se divulgue públicamente (como prueba criptográfica). Tal prueba también puede denominarse preimagen del hashlock. La imagen previa es simplemente la información que se utiliza para generar el hashlock y luego desbloquear sus fondos.

- Timelock: es una función que restringe el gasto de fondos hasta un tiempo específico (o altura de bloque) en el futuro. Se puede lograr en Bitcoin, por ejemplo, usando funciones como CheckLockTimeVerify o CheckSequenceVerify.

Bitcoin Lightning Network se encuentra entre los casos de uso más populares de contratos Hashed Timelocked. Al implementar HTLC en los canales de pago, los fondos pueden transferirse de un usuario a otro a través de canales de pago interconectados, sin necesidad de ningún nivel de confianza. Este proceso se conoce como enrutamiento de red. Le permite a Alice intercambiar fondos con Carol incluso si no están conectados directamente a través de un canal de pago. Los HTLC le permiten a Alice enviar sus fondos a Carol a través de otros participantes de la red (por ejemplo, Bob), y las funciones de hashlock y timelock aseguran que Bob no pueda interceptar los fondos.

Además de usarse en Lightning Network, los HTLC también pueden ser útiles en otros contextos, como [intercambios atómicos entre cadenas](/atomic-swaps),. contratos financieros inteligentes y custodia, y mucho más.

## Reflejos

- Los pagos que utilizan HTLC son condicionales y, por lo tanto, tienen beneficios de eficiencia para las transacciones de blockchain. Esta propiedad convierte a los HTLC en una herramienta fundamental utilizada por la red lightning.

- Este tipo de contrato inteligente requiere que el receptor de un pago lo reconozca dentro de un cierto período de tiempo o lo pierda.

- Un contrato de bloqueo de tiempo hash (HTLC) reduce el riesgo de la contraparte en los contratos inteligentes descentralizados mediante la creación efectiva de un depósito en garantía basado en el tiempo que utiliza una frase de contraseña criptográfica.

## PREGUNTAS MÁS FRECUENTES

### ¿Cuánto cuesta un contrato inteligente?

En la cadena de bloques de Ethereum, la implementación de un contrato inteligente requiere gas, lo que cuesta Gwei (una denominación más baja de éter). Dependiendo de la complejidad del contrato, implementar un contrato inteligente puede costar miles de millones de Gwei. Los contratos menos complejos como un simple intercambio son mucho más baratos.

### ¿Qué es un contrato inteligente?

Un contrato inteligente es un programa almacenado en una cadena de bloques que se ejecuta cuando se cumplen condiciones específicas.

### ¿Qué es un contrato Timelock?

Un contrato de bloqueo de tiempo es un contrato inteligente integrado en una cadena de bloques que ejecuta una transacción en un momento específico. Se utilizan en contratos de bloqueo de tiempo hash y canales de pago donde se necesitan tiempos de pago específicos.

### ¿Bitcoin tiene contratos inteligentes?

Inicialmente, la cadena de bloques de Bitcoin no podía ejecutar contratos inteligentes. Sin embargo, la actualización de Taproot en 2021 permitió que la cadena de bloques usara contratos inteligentes en las transacciones.

