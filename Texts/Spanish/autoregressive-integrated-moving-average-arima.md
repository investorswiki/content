---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Media móvil integrada autorregresiva (ARIMA)
description: Un promedio móvil integrado autorregresivo (ARIMA) es un modelo de análisis estadístico que aprovecha los datos de series temporales para pronosticar tendencias futuras.
---

# Media móvil integrada autorregresiva (ARIMA)
## ¿Qué es una media móvil integrada autorregresiva (ARIMA)?

Un promedio móvil integrado autorregresivo, o ARIMA, es un modelo de análisis estadístico que utiliza [datos de series de tiempo](/timeseries) para comprender mejor el conjunto de datos o para predecir tendencias futuras.

Un modelo estadístico es autorregresivo si predice valores futuros basados en valores pasados. Por ejemplo, un modelo ARIMA podría intentar predecir los precios futuros de una acción en función de su desempeño anterior o pronosticar las ganancias de una empresa en función de períodos anteriores.

## Comprender la media móvil integrada autorregresiva (ARIMA)

Un modelo de promedio móvil integrado autorregresivo es una forma de [análisis de regresión](/regression) que mide la fuerza de una variable dependiente en relación con otras variables cambiantes. El objetivo del modelo es predecir futuros valores o movimientos del mercado financiero mediante el examen de las diferencias entre los valores de la serie en lugar de los valores reales.

Un modelo ARIMA se puede entender delineando cada uno de sus componentes de la siguiente manera:

- [Autorregresión (AR)](/autoregressive) : se refiere a un modelo que muestra una variable cambiante que retrocede sobre sus propios valores retrasados o previos.

- **Integrado (I):** representa la diferenciación de las observaciones sin procesar para permitir que la serie temporal se vuelva estacionaria (es decir, los valores de los datos se reemplazan por la diferencia entre los valores de los datos y los valores anteriores).

- [Media móvil (MA)](/movingaverage) : incorpora la dependencia entre una observación y un error residual de un modelo de media móvil aplicado a observaciones retrasadas.

## Parámetros ARIMA

Cada componente en ARIMA funciona como un parámetro con una notación estándar. Para los modelos ARIMA, una notación estándar sería ARIMA con p, d y q, donde los valores enteros sustituyen a los parámetros para indicar el tipo de modelo ARIMA utilizado. Los parámetros se pueden definir como:

- **p**: el número de observaciones de retraso en el modelo; también conocido como el orden de retardo.

- **d**: el número de veces que se diferencian las observaciones sin procesar; también conocido como el grado de diferenciación.

- q: el tamaño de la ventana de media móvil; también conocido como el orden de la media móvil.

En un modelo de [regresión lineal](/nonlinear-regression),. por ejemplo, se incluyen el número y tipo de términos. Un valor 0, que se puede usar como parámetro, significaría que ese componente en particular no se debe usar en el modelo. De esta forma, el modelo ARIMA se puede construir para realizar la función de un modelo ARMA, o incluso modelos AR, I o MA simples.

> Debido a que los modelos ARIMA son complicados y funcionan mejor en conjuntos de datos muy grandes, se utilizan algoritmos informáticos y técnicas de aprendizaje automático para calcularlos.

>

## Media móvil integrada autorregresiva (ARIMA) y estacionariedad

En un modelo de promedio móvil integrado autorregresivo, los datos se diferencian para hacerlo estacionario. Un modelo que muestra estacionariedad es aquel que muestra que hay constancia en los datos a lo largo del tiempo. La mayoría de los datos económicos y de mercado muestran tendencias, por lo que el propósito de la diferenciación es eliminar cualquier tendencia o estructura estacional.

[La estacionalidad](/seasonality),. o cuando los datos muestran patrones regulares y predecibles que se repiten durante un año calendario, podría afectar negativamente al modelo de regresión. Si aparece una tendencia y la estacionariedad no es evidente, muchos de los cálculos a lo largo del proceso no se pueden realizar con gran eficacia.

> Un impacto único afectará los valores subsiguientes de un modelo ARIMA infinitamente en el futuro. Por lo tanto, el legado de la crisis financiera sigue vivo en los modelos autorregresivos actuales.

>

## Consideraciones Especiales

Los modelos ARIMA se basan en la suposición de que los valores pasados tienen algún efecto residual sobre los valores actuales o futuros. Por ejemplo, un inversionista que usa un modelo ARIMA para pronosticar los precios de las acciones supondría que los nuevos compradores y vendedores de esa acción están influenciados por las transacciones recientes del mercado cuando deciden cuánto ofrecer o aceptar por el valor.

Aunque esta suposición se mantendrá en muchas circunstancias, no siempre es así. Por ejemplo, en los años previos a la crisis financiera de 2008, la mayoría de los inversionistas no eran conscientes de los riesgos que planteaban las grandes carteras de [valores respaldados por hipotecas](/mbs) (MBS) de muchas empresas financieras.

Durante esos tiempos, un inversionista que usara un modelo autorregresivo para predecir el desempeño de las acciones financieras de EE. UU. habría tenido buenas razones para predecir una tendencia continua de precios de acciones estables o al alza en ese sector. Sin embargo, una vez que se hizo público que muchas instituciones financieras corrían el riesgo de un colapso inminente, los inversores de repente se preocuparon menos por los precios recientes de estas acciones y mucho más por su exposición al riesgo subyacente. Por lo tanto, el mercado reevaluó rápidamente las acciones financieras a un nivel mucho más bajo, un movimiento que habría confundido por completo a un modelo autorregresivo.

## Preguntas frecuentes

### ¿Para qué se utiliza ARIMA?

ARIMA es un método para pronosticar o predecir resultados futuros basados en una serie de tiempo histórica. Se basa en el concepto estadístico de correlación serial, donde los puntos de datos pasados influyen en los puntos de datos futuros.

### ¿Cuáles son las diferencias entre los modelos autorregresivos y de promedio móvil?

ARIMA combina características autorregresivas con las de los promedios móviles. Un proceso autorregresivo AR(1), por ejemplo, es aquel en el que el valor actual se basa en el valor inmediatamente anterior, mientras que un proceso AR(2) es aquel en el que el valor actual se basa en los dos valores anteriores. Un promedio móvil es un cálculo que se utiliza para analizar puntos de datos mediante la creación de una serie de promedios de diferentes subconjuntos del conjunto de datos completo para suavizar la influencia de los valores atípicos. Como resultado de esta combinación de técnicas, los modelos ARIMA pueden tener en cuenta tendencias, ciclos, estacionalidad y otros tipos de datos no estáticos al realizar pronósticos.

### ¿Cómo funciona la previsión ARIMA?

El pronóstico ARIMA se logra conectando datos de series de tiempo para la variable de interés. El software estadístico identificará el número apropiado de retrasos o la cantidad de diferenciación que se aplicará a los datos y verificará la estacionariedad. Luego generará los resultados, que a menudo se interpretan de manera similar a los de un modelo de regresión lineal múltiple.

## Reflejos

- Los modelos de promedio móvil integrado autorregresivo (ARIMA) predicen valores futuros basados en valores pasados.

- ARIMA utiliza promedios móviles rezagados para suavizar los datos de series de tiempo.

- Son ampliamente utilizados en el análisis técnico para pronosticar los precios futuros de los valores.

- Los modelos autorregresivos asumen implícitamente que el futuro se parecerá al pasado.

- Por lo tanto, pueden resultar inexactos en determinadas condiciones del mercado, como crisis financieras o períodos de rápido cambio tecnológico.

