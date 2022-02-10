---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Modelo de caja-Jenkins
description: El modelo de Box-Jenkins es un modelo matemático diseñado para pronosticar datos de una serie de tiempo específica.
---

# Modelo de caja-Jenkins
## ¿Qué es el modelo Box-Jenkins?

El modelo de Box-Jenkins es un modelo matemático diseñado para pronosticar rangos de datos basados en entradas de una [serie de tiempo específica](/timeseries). El modelo de Box-Jenkins puede analizar varios tipos diferentes de datos de series de tiempo con fines de pronóstico.

Su metodología utiliza diferencias entre puntos de datos para determinar los resultados. La metodología permite que el modelo identifique tendencias usando autorregresión, promedios móviles y diferenciación estacional para generar pronósticos.

[modelos de promedio móvil integrado autorregresivo (ARIMA)](/autoregressive-integrated-moving-average-arima) son una forma de modelo de Box-Jenkins. Los términos ARIMA y Box-Jenkins a veces se usan indistintamente.

## Comprender el modelo de Box-Jenkins

Los modelos de Box-Jenkins se utilizan para [pronosticar](/forecasting) una variedad de puntos de datos anticipados o rangos de datos, incluidos datos comerciales y precios de valores futuros.

El modelo Box-Jenkins fue creado por dos matemáticos: George Box y Gwilym Jenkins. Los dos matemáticos discutieron los conceptos que componen este modelo en una publicación de 1970 llamada "Análisis de series de tiempo: pronóstico y control".

Las estimaciones de los parámetros del Modelo de Box-Jenkins pueden ser muy complicadas. Por lo tanto, de forma similar a otros modelos de regresión de series de tiempo, los mejores resultados generalmente se lograrán mediante el uso de software programable. El modelo Box-Jenkins también es generalmente más adecuado para pronósticos a corto plazo de 18 meses o menos.

## Metodología Box-Jenkins

El modelo de Box-Jenkins puede ser uno de varios modelos de análisis de series de tiempo con los que se encontrará un pronosticador cuando utilice un software de pronóstico programado. En muchos casos, el software se programará para usar automáticamente la metodología de pronóstico que mejor se ajuste en función de los datos de la [serie temporal](/timeseries) que se pronosticará. Se informa que Box-Jenkins es la mejor opción para conjuntos de datos que son en su mayoría estables y tienen baja [volatilidad](/volatility).

El modelo Box-Jenkins pronostica datos utilizando tres principios: autorregresión, diferenciación y promedio móvil. Estos tres principios se conocen como p, d y q, respectivamente. Cada principio se utiliza en el análisis de Box-Jenkins; juntos, se muestran colectivamente como ARIMA (p, d, q).

El proceso de autorregresión (p) prueba los datos para determinar su nivel de estacionariedad. Si los datos que se utilizan son estacionarios, puede simplificar el proceso de pronóstico. Si los datos que se utilizan no son estacionarios, será necesario diferenciarlos (d). Los datos también se prueban para determinar su ajuste de promedio móvil (que se realiza en la parte q del proceso de análisis). En general, el análisis inicial de los datos los prepara para el pronóstico mediante la determinación de los parámetros (p, d y q), que luego se aplican para desarrollar un pronóstico.

> Un impacto único afectará los valores subsiguientes de un modelo de Box-Jenkins infinitamente en el futuro. Por lo tanto, el legado de la crisis financiera sigue vivo en los modelos autorregresivos actuales.

>

## Media móvil integrada autorregresiva (ARIMA)

Box-Jenkins es un tipo de modelo de promedio móvil integrado autorregresivo (ARIMA) que mide la fuerza de una variable dependiente en relación con otras variables cambiantes. El objetivo del modelo es predecir futuros valores o movimientos del mercado financiero mediante el examen de las diferencias entre los valores de la serie en lugar de los valores reales.

Un modelo ARIMA se puede entender delineando cada uno de sus componentes de la siguiente manera:

- [Autorregresión (AR)](/autoregressive) : se refiere a un modelo que muestra una variable cambiante que retrocede sobre sus propios valores retrasados o previos.

- Integrado (I): representa la diferenciación de las observaciones brutas para permitir que la serie temporal se vuelva estacionaria, es decir, los valores de los datos se reemplazan por la diferencia entre los valores de los datos y los valores anteriores.

- [Media móvil (MA)](/movingaverage) : incorpora la dependencia entre una observación y un error residual de un modelo de media móvil aplicado a observaciones retrasadas.

## Pronóstico de precios de acciones

Uno de los usos del análisis del modelo Box-Jenkins es pronosticar los precios de las [acciones .](/stock) Este análisis generalmente se construye y codifica a través del software R. El análisis da como resultado un resultado logarítmico, que se puede aplicar al conjunto de datos para generar los precios pronosticados para un período de tiempo específico en el futuro.

Los modelos ARIMA se basan en la suposición de que los valores pasados tienen algún efecto residual sobre los valores actuales o futuros. Por ejemplo, un inversionista que usa un modelo ARIMA para pronosticar los precios de las acciones supondría que los nuevos compradores y vendedores de esa acción están influenciados por las transacciones recientes del mercado cuando deciden cuánto ofrecer o aceptar por el valor.

Aunque esta suposición se mantendrá en muchas circunstancias diferentes, no siempre es cierta. Por ejemplo, en los años previos a la crisis financiera de 2008, la mayoría de los inversionistas no eran conscientes de los riesgos que planteaban las grandes carteras de [valores respaldados por hipotecas](/mbs) (MBS) de muchas empresas financieras.

Durante esos tiempos, un inversionista que usara un modelo autorregresivo para predecir el desempeño de las acciones financieras de EE. UU. habría tenido buenas razones para predecir una tendencia continua de precios de acciones estables o al alza en ese sector. Sin embargo, una vez que se hizo público que muchas instituciones financieras corrían el riesgo de un colapso inminente, los inversores de repente se preocuparon menos por los precios recientes de estas acciones y mucho más por su exposición al riesgo subyacente.

Por lo tanto, el mercado reevaluó rápidamente las acciones financieras a un nivel mucho más bajo, un movimiento que habría confundido por completo a un modelo autorregresivo.

## Reflejos

- Los modelos de promedio móvil integrado autorregresivo (ARIMA) son una forma de modelo de Box-Jenkins.

- El modelo Box-Jenkins es el más adecuado para realizar pronósticos dentro de marcos de tiempo de 18 meses o menos.

- La metodología se basa en el supuesto de que los sucesos pasados influyen en los futuros.

- El modelo Box-Jenkins es una metodología de pronóstico que utiliza estudios de regresión sobre datos de series temporales.

