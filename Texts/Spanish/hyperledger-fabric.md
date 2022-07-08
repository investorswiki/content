---
keywords: Investing,Cryptocurrency,Blockchain
title: Tela de hiperlibro
description: Hyperledger Fabric es una plataforma para crear varios productos, soluciones y aplicaciones basados en blockchain para uso comercial.
---

# Tela de hiperlibro
## ¿Qué es Hyperledger Fabric?

Hyperledger Fabric es un marco de [blockchain modular](/blockchain) que actúa como base para desarrollar productos, soluciones y aplicaciones basados en blockchain utilizando componentes plug-and-play que están destinados para su uso en empresas privadas.

Hyperledger Fabric fue iniciado por Digital Asset e IBM y ahora ha surgido como una empresa de colaboración entre industrias, que actualmente está siendo alojada por la Fundación Linux. Entre los varios proyectos de Hyperledger, Fabric fue el primero en salir de la etapa de "incubación" y alcanzar la etapa "activa" en marzo de 2017.

## Cómo funciona Hyperledger Fabric

Las redes blockchain tradicionales no pueden soportar transacciones privadas y contratos confidenciales que son de suma importancia para las empresas. Hyperledger Fabric se diseñó en respuesta a esto como una base modular, escalable y segura para ofrecer soluciones industriales de cadena de bloques.

Hyperledger Fabric es el motor de código abierto para blockchain y se ocupa de las características más importantes para evaluar y usar blockchain para casos de uso empresarial.

Dentro de las redes industriales privadas, la identidad verificable de un participante es un requisito principal. Hyperledger Fabric admite membresías basadas en permisos; todos los participantes de la red deben tener identidades conocidas. Muchos sectores comerciales, como la atención médica y las finanzas, están sujetos a normas de protección de datos que exigen el mantenimiento de datos sobre los distintos participantes y su acceso respectivo a varios puntos de datos. Fabric admite dicha membresía basada en permisos.

### Arquitectura modular

La arquitectura modular de Hyperledger Fabric separa el flujo de trabajo del procesamiento de transacciones en tres etapas diferentes: [contratos inteligentes](/smart-contracts) llamados chaincode que comprenden el procesamiento lógico distribuido y el acuerdo del sistema, el pedido de transacciones y la validación y compromiso de transacciones. Esta segregación ofrece múltiples beneficios:

- Un número reducido de niveles de confianza y verificación que mantiene la red y el procesamiento ordenados

- Escalabilidad de red mejorada

- Mejor rendimiento general

Además, el soporte de Hyperledger Fabric para plug-and-play de varios componentes permite una fácil reutilización de las funciones existentes y la integración lista para usar de varios módulos. Por ejemplo, si ya existe una función que verifica la identidad del participante, una red de nivel empresarial simplemente necesita conectar y reutilizar este módulo existente en lugar de crear la misma función desde cero.

Los participantes en la red tienen tres roles distintos:

- Endosante

- Comitente

- Consentimiento

En pocas palabras, la propuesta de transacción se envía al par endorsante de acuerdo con la política de endoso predefinida sobre el número de endosantes necesarios. Después de suficientes endosos por parte de los endosantes, se entrega un lote o bloque de transacciones a los emisores. Los remitentes validan que se siguió la política de respaldo y que no hay transacciones en conflicto. Una vez que se realizan ambas comprobaciones, las transacciones se consignan en el libro mayor.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Fuente de la imagen: IBM

Dado que solo se envían instrucciones de confirmación, como firmas y conjunto de lectura/escritura, a través de la red, se mejora la escalabilidad y el rendimiento de la red. Solo los patrocinadores y los que se comprometen tienen acceso a la transacción, y la seguridad mejora con una menor cantidad de participantes que tienen acceso a puntos de datos clave.

## Ejemplo de Hyperledger Fabric

Supongamos que hay un fabricante que quiere enviar chocolates a un minorista específico o mercado de minoristas (es decir, todos los minoristas de EE. UU.) a un precio específico pero no quiere revelar ese precio en otros mercados (es decir, minoristas chinos).

Dado que el movimiento del producto puede involucrar a otras partes, como la aduana, una empresa de transporte y un banco financiero, el precio privado puede revelarse a todas las partes involucradas si se utiliza una versión básica de la tecnología blockchain para respaldar esta transacción.

Hyperledger Fabric aborda este problema al mantener privadas las transacciones privadas en la red; sólo los participantes que necesitan saber conocen los detalles necesarios. La partición de datos en la cadena de bloques permite que los puntos de datos específicos sean accesibles solo para las partes que necesitan saber.

## Críticas a Hyperledger Fabric

La marca de agua más alta del criptoentusiasmo se rompió en 2018 después del colapso del precio de bitcoin (que alcanzó su punto máximo el 17 de diciembre de 2017). Las afirmaciones demasiado optimistas sobre el valor de la nueva tecnología fueron reemplazadas por escepticismo, y las tecnologías relacionadas, incluido Hyperledger, también sufrieron este escepticismo.

### Competidores de Hyperledger Fabric

Hyperledger Fabric compite con otros proyectos de Hyperledger como Iroha, Indy y Sawtooth. También compite con Corda de R3, que también es una DLT privada basada en permisos.

La firma de servicios Blockchain Chainstack publicó un artículo en enero de 2020 que muestra que el desarrollo en Corda ha sido históricamente más alto que el desarrollo en Fabric, aunque el desarrollo de Fabric superó el de Corda en el tercer trimestre de 2019 cuando Fabric cambió a GitHub.

El informe de Chainstack muestra que, si bien hay tres veces más desarrolladores trabajando en Fabric, los desarrolladores de Corda hicieron más del doble de contribuciones de código, y los desarrolladores de Fabric impulsan mucho menos código por desarrollador que los desarrolladores de Corda.

### Hyperledger Fabric no es blockchain y no es eficiente

Varias críticas de Hyperledger Fabric señalan que una cadena de bloques privada basada en permisos con las características de Hyperledger Fabric no es una cadena de bloques, y las tecnologías actuales que no son cadenas de bloques son mucho menos costosas y brindan la misma cantidad de seguridad. Stuart Popejoy de Cointelegraph expuso el caso de esta manera:

>

> La arquitectura de Fabric es mucho más compleja que cualquier plataforma de cadena de bloques y, al mismo tiempo, es menos segura contra la manipulación y los ataques. Uno pensaría que una cadena de bloques "privada" al menos ofrecería escalabilidad y rendimiento, pero Fabric también falla aquí. En pocas palabras, los pilotos creados en Fabric se enfrentarán a una implementación compleja e insegura que no podrá escalar con sus negocios .

>

Hyperledger Fabric también ha sido criticado por su falta de resiliencia. Un equipo de investigadores de la Sorbona en París y CSIRO - Data61, la agencia científica nacional de Australia, descubrió que los retrasos significativos en la red reducían la confiabilidad de Fabric: "[Al] retrasar la propagación de bloques, demostramos que Hyperledger Fabric no brinda suficientes garantías de consistencia para ser desplegado en entornos críticos " .

## Hyperledger Fabric 2.0 lanzado en enero de 2020

En enero de 2020, se lanzó Hyperledger Fabric 2.0 para abordar algunas de las críticas existentes. Según Ron Miller de Techcrunch, "las actualizaciones más importantes implican forzar un acuerdo entre las partes antes de que se pueda agregar cualquier dato nuevo al libro mayor, lo que se conoce como gobierno descentralizado de los contratos inteligentes".

Aunque la actualización no es un cambio radical en la simplicidad o la aplicabilidad de Fabric, demuestra que se sigue progresando en la industria de las criptomonedas más allá de la criptomanía que ocurrió en 2018. Durante los próximos cinco a diez años, es Se esperaba que la cadena de bloques empresarial, sin duda, encontrara su uso adecuado.

## Reflejos

- Hyperledger es un marco de libro mayor distribuido de código abierto y de nivel empresarial lanzado por la Fundación Linux en diciembre de 2015.

- Debido a que Hyperledger Fabric es privado y requiere permiso para acceder, las empresas pueden segregar información (como precios), además de que las transacciones pueden acelerarse porque se reduce la cantidad de nodos en la red.

- Fabric 2.0 se lanzó en enero de 2020. Las características principales de esta versión son transacciones más rápidas, tecnología de contrato inteligente actualizada y uso compartido de datos simplificado.

- Fabric es una plataforma de tecnología de contabilidad descentralizada (DLT) altamente modular que fue diseñada por IBM para uso empresarial industrial.

