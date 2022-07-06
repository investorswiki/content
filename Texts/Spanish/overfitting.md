---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: sobreajuste
description: El sobreajuste es un error de modelado que ocurre cuando una función se ajusta demasiado a un conjunto limitado de puntos de datos.
---

# sobreajuste
## ¿Qué es el sobreajuste?

El sobreajuste es un error de modelado en estadísticas que ocurre cuando una función está demasiado alineada con un conjunto limitado de puntos de datos. Como resultado, el modelo es útil en referencia solo a su conjunto de datos inicial y no a ningún otro conjunto de datos.

El sobreajuste del modelo generalmente toma la forma de hacer un modelo demasiado complejo para explicar las idiosincrasias en los datos bajo estudio. En realidad, los datos que se estudian a menudo contienen cierto grado de error o ruido aleatorio. Por lo tanto, intentar hacer que el modelo se ajuste demasiado a datos ligeramente inexactos puede infectar el modelo con errores sustanciales y reducir su poder predictivo.

## Comprender el sobreajuste

Por ejemplo, un problema común es el uso de [algoritmos informáticos](/algorithm) para buscar en extensas bases de datos de datos históricos del mercado con el fin de encontrar patrones. Con suficiente estudio, a menudo es posible desarrollar teoremas elaborados que parecen predecir los rendimientos en el [mercado de valores](/stockmarket) con gran precisión.

Sin embargo, cuando se aplican a datos fuera de la muestra, es probable que tales teoremas resulten ser simplemente el ajuste excesivo de un modelo a lo que en realidad eran solo ocurrencias fortuitas. En todos los casos, es importante probar un modelo con datos que están fuera de la muestra utilizada para desarrollarlo.

## Cómo evitar el sobreajuste

Las formas de evitar el sobreajuste incluyen la validación cruzada, en la que los datos que se utilizan para entrenar el modelo se dividen en pliegues o particiones y el modelo se ejecuta para cada pliegue. Luego, se promedia la estimación del error general. Otros métodos incluyen el ensamblaje: las predicciones se combinan de al menos dos modelos separados, el aumento de datos, en el que el conjunto de datos disponible se hace para que parezca diverso, y la simplificación de datos, en la que el modelo se optimiza para evitar el sobreajuste.

> Los profesionales financieros siempre deben ser conscientes de los peligros de sobreajustar o desadaptar un modelo basado en datos limitados. El modelo ideal debe ser equilibrado.

>

## Sobreajuste en el aprendizaje automático

El sobreajuste también es un factor en el aprendizaje automático. Puede surgir cuando a una máquina se le ha enseñado a buscar datos específicos de una manera, pero cuando se aplica el mismo proceso a un nuevo conjunto de datos, los resultados son incorrectos. Esto se debe a errores en el modelo que se construyó, ya que probablemente muestra un sesgo bajo y una varianza alta. El modelo puede haber tenido características redundantes o superpuestas, lo que resultó en que se volviera innecesariamente complicado y, por lo tanto, ineficaz.

## Sobreadaptación vs. Falta de ajuste

Un modelo que está sobreajustado puede ser demasiado complicado, haciéndolo ineficaz. Pero un modelo también puede estar mal ajustado, lo que significa que es demasiado simple, con muy pocas características y muy pocos datos para construir un modelo efectivo. Un modelo sobreajustado tiene un sesgo bajo y una varianza alta, mientras que un modelo de ajuste insuficiente es lo contrario: tiene un sesgo alto y una varianza baja. Agregar más funciones a un modelo demasiado simple puede ayudar a limitar el sesgo.

## Ejemplo de sobreajuste

Por ejemplo, una universidad que está viendo una tasa de deserción universitaria más alta de lo que le gustaría, decide que quiere crear un modelo para predecir la probabilidad de que un solicitante llegue hasta la graduación.

Para ello, la universidad entrena un modelo a partir de un conjunto de datos de 5000 solicitantes y sus resultados. Luego ejecuta el modelo en el conjunto de datos original, el grupo de 5000 solicitantes, y el modelo predice el resultado con un 98 % de precisión. Pero para probar su precisión, también ejecutan el modelo en un segundo conjunto de datos: 5000 solicitantes más. Sin embargo, esta vez, el modelo solo tiene una precisión del 50 %, ya que el modelo se ajustaba demasiado a un subconjunto de datos estrecho, en este caso, las primeras 5000 solicitudes.

## Reflejos

- El sobreajuste es un error que ocurre en el modelado de datos como resultado de una función particular que se alinea demasiado cerca de un conjunto mínimo de puntos de datos.

- Cuando un modelo se ha visto comprometido por sobreajuste, el modelo puede perder su valor como herramienta predictiva para invertir.

- Un modelo de datos también puede estar mal ajustado, lo que significa que es demasiado simple, con muy pocos puntos de datos para ser efectivo.

- Los profesionales financieros corren el riesgo de sobreajustar un modelo basado en datos limitados y terminar con resultados defectuosos.

- El sobreajuste es un problema más frecuente que el desajuste y normalmente ocurre como resultado de tratar de evitar el sobreajuste.

