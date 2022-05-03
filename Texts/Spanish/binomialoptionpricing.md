---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Modelo de fijación de precios de opciones binomiales
description: Un modelo binomial de valoración de opciones es un método de valoración de opciones que utiliza un procedimiento iterativo y permite la especificación de nodos en un período determinado.
---

# Modelo de fijación de precios de opciones binomiales
## ¿Qué es el modelo de precios de opciones binomiales?

El modelo de valoración de opciones binomial es un método de [valoración de opciones](/valuation) desarrollado en 1979. El modelo de valoración de opciones binomial utiliza un procedimiento iterativo, lo que permite la especificación de nodos, o puntos en el tiempo, durante el lapso de tiempo entre la fecha de valoración y la [fecha de](/expiration-date) [vencimiento de la opción](/expiration-date).

El modelo reduce las posibilidades de cambios de precios y elimina la posibilidad de [arbitraje](/arbitrage). Un ejemplo simplificado de un [árbol binomial](/binomial_tree) podría verse así:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Conceptos básicos del modelo de fijación de precios de opciones binomiales

Con los modelos de precios de opciones binomiales, se supone que hay dos resultados posibles, por lo tanto, la parte binomial del modelo. Con un modelo de precios, los dos resultados son un movimiento hacia arriba o hacia abajo. La principal ventaja de un modelo de valoración de opciones binomial es que son matemáticamente simples. Sin embargo, estos modelos pueden volverse complejos en un modelo de varios períodos.

A diferencia del [modelo Black-Scholes](/blackscholes),. que proporciona un resultado numérico basado en entradas, el modelo binomial permite el cálculo del activo y la opción para múltiples períodos junto con el rango de resultados posibles para cada período (ver más abajo).

La ventaja de esta vista de varios períodos es que el usuario puede visualizar el cambio en el precio del activo de un período a otro y evaluar la opción en función de las decisiones tomadas en diferentes momentos. Para una [opción basada en EE. UU.](/americanoption),. que se puede ejercer en cualquier momento antes de la fecha de [vencimiento](/expirationdate),. el modelo binomial puede proporcionar información sobre cuándo puede ser recomendable ejercer la opción y cuándo se debe mantener por períodos más largos.

Al observar el [árbol binomial de valores, un comerciante puede determinar de antemano cuándo](/binomial_tree) puede ocurrir una decisión sobre un [ejercicio .](/exercise) Si la opción tiene un valor positivo, existe la posibilidad de ejercicio mientras que, si la opción tiene un valor inferior a cero, debe mantenerse por períodos más largos.

## Cálculo del precio con el modelo binomial

El método básico para calcular el modelo de opción binomial es usar la misma probabilidad en cada período de éxito y fracaso hasta que venza la opción. Sin embargo, un comerciante puede incorporar diferentes probabilidades para cada período en función de la nueva información obtenida a medida que pasa el tiempo.

Un árbol binomial es una herramienta útil cuando se valoran [opciones americanas](/americanoption) y opciones [integradas](/embeddedoption). Su simplicidad es su ventaja y desventaja al mismo tiempo. El árbol es fácil de modelar mecánicamente, pero el problema radica en los posibles valores que puede tomar el activo subyacente en un período de tiempo. En un modelo de árbol binomial, el activo subyacente solo puede valer exactamente uno de dos valores posibles, lo cual no es realista, ya que los activos pueden valer cualquier cantidad de valores dentro de un rango determinado.

Por ejemplo, puede haber una probabilidad de 50/50 de que el precio del activo subyacente pueda aumentar o disminuir en un 30 por ciento en un período. Sin embargo, para el segundo período, la probabilidad de que el precio del activo subyacente aumente puede aumentar a 70/30.

Por ejemplo, si un inversionista está evaluando un [pozo de petróleo](/exploratory-well),. ese inversionista no está seguro de cuál es el valor de ese pozo de petróleo, pero existe una probabilidad del 50/50 de que el precio suba. Si los precios del petróleo aumentan en el Período 1, lo que hace que el pozo de petróleo sea más valioso y los [fundamentos del mercado](/fundamentals) ahora apuntan a aumentos continuos en los precios del petróleo, la probabilidad de una mayor apreciación del precio ahora puede ser del 70 por ciento. El modelo binomial permite esta flexibilidad; el modelo Black-Scholes no lo hace.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Ejemplo del mundo real del modelo de fijación de precios de opciones binomiales

Un ejemplo simplificado de un [árbol binomial](/binomial_tree) tiene solo un paso. Suponga que hay una acción cuyo precio es de $100 por acción. En un mes, el precio de esta acción subirá $10 o bajará $10, creando esta situación:

- **Precio de las acciones** = $100

- **Precio de las acciones en un mes (estado arriba)** = $110

- **Precio de las acciones en un mes (estado bajo)** = $90

A continuación, suponga que hay una opción de compra disponible sobre esta acción que vence en un mes y tiene un precio de ejercicio de $100. En el estado alto, esta opción de compra vale $10, y en el estado bajo, vale $0. El modelo binomial puede calcular cuál debería ser el precio de la opción de compra hoy.

Para simplificar, suponga que un inversionista compra la mitad de las acciones y escribe o vende una opción de compra. La inversión total hoy es el precio de media acción menos el precio de la opción, y los posibles pagos al final del mes son:

- **Costo hoy** = $50 - precio de la opción

- **Valor de la cartera** (estado arriba) = $55 - máx ($110 - $100, 0) = $45

- **Valor de la cartera** (estado a la baja) = $45 - máx ($90 - $100, 0) = $45

El pago de la cartera es igual sin importar cómo se mueva el precio de las acciones. Dado este resultado, suponiendo que no haya oportunidades de arbitraje, un inversor debería ganar la tasa libre de riesgo en el transcurso del mes. El costo de hoy debe ser igual al pago descontado a la tasa libre de riesgo durante un mes. La ecuación a resolver es así:

- **Precio de la opción** = $50 - $45 xe ^ (-tasa libre de riesgo x T), donde e es la constante matemática 2.7183.

Suponiendo que la tasa libre de riesgo es del 3 % anual y T es igual a 0,0833 (uno dividido por 12), entonces el precio de la opción de compra hoy es de $5,11.

El modelo binomial de fijación de precios de opciones presenta dos ventajas para los vendedores de opciones sobre el modelo Black-Scholes. El primero es su sencillez, que permite menos errores en la aplicación comercial. El segundo es su operación iterativa, que ajusta los precios de manera oportuna para reducir la oportunidad de que los compradores ejecuten estrategias de arbitraje.

Por ejemplo, dado que proporciona un flujo de valoraciones de un [derivado](/derivative) para cada nodo en un lapso de tiempo, es útil para valorar derivados como las opciones americanas, que se pueden ejecutar en cualquier momento entre la fecha de compra y la fecha de vencimiento. También es mucho más simple que otros modelos de precios, como el modelo Black-Scholes.

## Reflejos

- El modelo es intuitivo y se utiliza con más frecuencia en la práctica que el conocido modelo de Black-Scholes.

- Con el modelo, hay dos resultados posibles con cada iteración: un movimiento hacia arriba o hacia abajo que sigue un árbol binomial.

- El modelo binomial de fijación de precios de opciones valora las opciones utilizando un enfoque iterativo que utiliza múltiples períodos para valorar las opciones americanas.

