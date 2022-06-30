---
keywords: Economy,Economics,Behavioral Economics
title: Inducción hacia atrás
description: En la teoría de juegos, la inducción hacia atrás es el proceso de deducir hacia atrás desde el final de un problema o escenario para inferir una secuencia de acciones óptimas.
---

# Inducción hacia atrás
## ¿Qué es la inducción hacia atrás?

La inducción hacia atrás en [la teoría de juegos](/gametheory) es un proceso iterativo de razonamiento hacia atrás en el tiempo, desde el final de un problema o situación, para resolver juegos secuenciales y de forma extensiva finita, e inferir una secuencia de acciones óptimas.

## Explicación de la inducción hacia atrás

La inducción hacia atrás se ha utilizado para resolver juegos desde que John von Neumann y Oskar Morgenstern establecieron la teoría de juegos como materia académica cuando publicaron su libro **Teoría de juegos y comportamiento económico** en 1944.

En cada etapa del juego, la inducción hacia atrás determina la estrategia óptima del jugador que hace el último movimiento en el juego. Luego, se determina la acción óptima del penúltimo jugador en movimiento, tomando como dada la acción del último jugador. Este proceso continúa hacia atrás hasta que se determina la mejor acción para cada punto en el tiempo. Efectivamente, se está determinando el equilibrio de [Nash](/nash-equilibrium) de cada subjuego del juego original.

Sin embargo, los resultados inferidos de la inducción hacia atrás a menudo no logran predecir el juego humano real. Los estudios experimentales han demostrado que el comportamiento "racional" (como lo predice la teoría de juegos) rara vez se exhibe en la vida real. Los jugadores irracionales en realidad pueden terminar obteniendo pagos más altos que los predichos por la inducción hacia atrás, como se ilustra en el [juego del ciempiés](/centipede-game).

En el juego del ciempiés, dos jugadores tienen alternativamente la oportunidad de tomar una mayor parte de un bote de dinero que va en aumento o de pasar el bote al otro jugador. Los pagos se organizan de modo que si el bote se pasa al oponente y el oponente se lleva el bote en la siguiente ronda, uno recibe un poco menos que si se hubiera llevado el bote en esta ronda. El juego concluye tan pronto como un jugador toma el alijo, ese jugador obtiene la porción más grande y el otro jugador obtiene la porción más pequeña.

## Ejemplo de inducción hacia atrás

Como ejemplo, supongamos que Izaz va primero y tiene que decidir si debe "tomar" o "pasar" el alijo, que actualmente asciende a $2. Si toman, entonces Izaz y Jian reciben $1 cada uno, pero si Izaz pasa, la decisión de tomar o pasar ahora debe ser tomada por Jian. Si Jian toma, obtienen $3 (es decir, el alijo anterior de $2 + $1) e Izaz obtiene $0. Pero si Jian pasa, Izaz ahora puede decidir si toma o pasa, y así sucesivamente. Si ambos jugadores eligen siempre pasar, cada uno recibe un pago de $100 al final del juego.

El punto del juego es que si Izaz y Jian cooperan y continúan pasando hasta el final del juego, obtienen el pago máximo de $100 cada uno. Pero si desconfían del otro jugador y esperan que "tomen" en la primera oportunidad, el equilibrio de Nash predice que los jugadores tomarán el reclamo más bajo posible ($ 1 en este caso).

El equilibrio de Nash de este juego, donde ningún jugador tiene un incentivo para desviarse de la estrategia elegida después de considerar la elección de un oponente, sugiere que el primer jugador se llevaría el bote en la primera ronda del juego. Sin embargo, en realidad, relativamente pocos jugadores lo hacen. Como resultado, obtienen un pago mayor que el pago previsto por el análisis de equilibrio.

## Resolver juegos secuenciales usando inducción hacia atrás

A continuación se muestra un juego secuencial simple entre dos jugadores. Las etiquetas con Jugador 1 y Jugador 2 dentro de ellas son los conjuntos de información para los jugadores uno o dos, respectivamente. Los números entre paréntesis en la parte inferior del árbol son los pagos en cada punto respectivo. El juego también es secuencial, por lo que el jugador 1 toma la primera decisión (izquierda o derecha) y el jugador 2 toma su decisión después del jugador 1 (arriba o abajo).

<!--360C571136D68BDF7B1BE984014B1A1C-->

La inducción hacia atrás, como toda teoría de juegos, utiliza los supuestos de racionalidad y maximización, lo que significa que el jugador 2 maximizará su pago en cualquier situación dada. En cualquier conjunto de información tenemos dos opciones, cuatro en total. Al eliminar las opciones que el jugador 2 no elegirá, podemos reducir nuestro árbol. De esta forma, marcaremos las líneas en azul que maximizan el pago del jugador en el conjunto de información dado.

<!--E78C02A07C982A1B447ED0D16A9FCE40-->

Después de esta reducción, el Jugador 1 puede maximizar sus ganancias ahora que se conocen las elecciones del Jugador 2. El resultado es un equilibrio encontrado por inducción hacia atrás del jugador 1 que elige "derecha" y el jugador 2 que elige "arriba". A continuación se muestra la solución del juego con la ruta de equilibrio en negrita.

<!--4DEC4364358F0D1CB7D219006F74D652-->

Por ejemplo, uno podría configurar fácilmente un juego similar al anterior utilizando empresas como jugadores. Este juego podría incluir escenarios [de lanzamiento de productos .](/rollout) Si la Compañía 1 quisiera lanzar un producto, ¿qué podría hacer la Compañía 2 en respuesta? ¿Compañía 2 lanzará un producto competidor similar? Al [pronosticar](/forecasting) las ventas de este nuevo producto en diferentes escenarios, podemos configurar un juego para predecir cómo se desarrollarán los eventos. A continuación se muestra un ejemplo de cómo se podría modelar un juego de este tipo.

<!--D102F649421403ABDBD56A5C1B29CF03-->

