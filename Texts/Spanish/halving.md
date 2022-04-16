---
keywords: Crypto
title: Reducir a la mitad
description: Reducir a la mitad. Cuando la recompensa por bloque de un criptoactivo cae a la mitad de lo que era antes; esto se utiliza para crear una tasa de emisión decreciente.
---

# Reducir a la mitad
En el espacio de las criptomonedas, el término reducción a la mitad se refiere a un proceso que reduce la tasa de emisión de nuevas monedas. Más precisamente, la reducción a la mitad es la reducción periódica del subsidio en bloque proporcionado a los mineros. La reducción a la mitad garantiza que un activo criptográfico seguirá una tasa de emisión constante hasta que finalmente se alcance su [suministro máximo .](/maximum-supply)

Cuando se trata de Bitcoin, las nuevas monedas se generan continuamente como parte de la [recompensa del bloque](/block-reward) (que se compone del subsidio del bloque más las tarifas de transacción). Entonces, cada vez que un minero "descubre" y valida con éxito un nuevo [bloque](/block),. gana monedas recién creadas como compensación por su trabajo.

Entonces, el proceso de [minería](/mining) es lo que introduce nuevos [Bitcoins](/bitcoin) en el sistema, y esto se hace a un ritmo predecible y controlado. Se extraen nuevos bloques de Bitcoin, en promedio, cada 10 minutos, y el subsidio del bloque sigue una tasa de descomposición controlada. En consecuencia, la reducción a la mitad es lo que asegura que el subsidio por bloque se reducirá en un 50% cada 210.000 bloques (aproximadamente cada cuatro años).

A partir del bloque de [génesis](/genesis-block),. el subsidio de bloque de Bitcoin se fijó inicialmente en 50 BTC. Luego, se redujo a 25 BTC en 2012 y a 12,5 BTC en 2016. Se espera que la siguiente reducción a la mitad ocurra alrededor de mayo de 2020, reduciendo el subsidio por bloque a 6,25 BTC. Una vez que se han producido 32 mitades, el proceso se detiene y no se crearán más Bitcoins. En este punto, se alcanzará el suministro máximo de 21 millones de BTC.

[Siga junto con la reducción a la mitad de Bitcoin](/halving)

La reducción a la mitad es una parte importante del protocolo de Bitcoin y, dado que el código es de código abierto, cualquiera puede verlo. Por ejemplo, la implementación de Bitcoin Core está disponible en [GitHub](/github),. y una de las secciones de código que define el subsidio en bloque se ve así:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensoParams)

{

int mitades = nHeight / consensoParams.nSubsidyHalvingInterval;

// Fuerza la recompensa del bloque a cero cuando el desplazamiento a la derecha no está definido.

si (reducciones a la mitad >= 64)

devolver 0;

CAmonto nSubsidio = 50 * MONEDA;

// El subsidio se reduce a la mitad cada 210.000 bloques, lo que ocurrirá aproximadamente cada 4 años.

nSubsidio >>= mitades;

volver nSubsidio;

}

