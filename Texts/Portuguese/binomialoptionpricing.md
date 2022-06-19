---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Modelo de precificação de opções binomiais
description: Um modelo de precificação de opções binomial é um método de avaliação de opções que utiliza um procedimento iterativo e permite a especificação do nó em um determinado período.
---

# Modelo de precificação de opções binomiais
## O que é o modelo de precificação de opções binomiais?

O modelo de precificação de opções binomial é um método de [precificação de opções](/valuation) desenvolvido em 1979. O modelo de precificação de opções binomial utiliza um procedimento iterativo, permitindo a especificação de nós, ou pontos no tempo, durante o intervalo de tempo entre a data de avaliação e a [data de](/expiration-date) [vencimento da opção](/expiration-date).

O modelo reduz as possibilidades de variação de preços e elimina a possibilidade de [arbitragem](/arbitrage). Um exemplo simplificado de uma [árvore binomial](/binomial_tree) pode ser algo assim:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Noções básicas do modelo de precificação de opções binomiais

Com modelos de preços de opções binomiais, as suposições são de que existem dois resultados possíveis – portanto, a parte binomial do modelo. Com um modelo de precificação, os dois resultados são um movimento para cima ou um movimento para baixo. A principal vantagem de um modelo de precificação de opções binomial é que eles são matematicamente simples. No entanto, esses modelos podem se tornar complexos em um modelo multiperíodo.

Ao contrário do [modelo Black-Scholes](/blackscholes),. que fornece um resultado numérico baseado em entradas, o modelo binomial permite o cálculo do ativo e a opção para vários períodos juntamente com a faixa de resultados possíveis para cada período (veja abaixo).

A vantagem dessa visão multiperíodo é que o usuário pode visualizar a mudança no preço do ativo de um período para outro e avaliar a opção com base em decisões tomadas em diferentes momentos. Para uma [opção](/americanoption) baseada nos EUA , que pode ser exercida a qualquer momento antes da [data de vencimento](/expirationdate),. o modelo binomial pode fornecer informações sobre quando o exercício da opção pode ser aconselhável e quando deve ser mantido por períodos mais longos.

Ao olhar para a [árvore binomial](/binomial_tree) de valores, um trader pode determinar antecipadamente quando uma decisão sobre um [exercício](/exercise) pode ocorrer. Caso a opção tenha valor positivo, existe a possibilidade de exercício, enquanto, caso a opção tenha valor inferior a zero, deve ser mantida por períodos mais longos.

## Calculando Preço com o Modelo Binomial

O método básico de cálculo do modelo de opção binomial é usar a mesma probabilidade a cada período de sucesso e fracasso até que a opção expire. No entanto, um trader pode incorporar diferentes probabilidades para cada período com base em novas informações obtidas com o passar do tempo.

Uma árvore binomial é uma ferramenta útil ao precificar [opções americanas](/americanoption) e opções [incorporadas](/embeddedoption). Sua simplicidade é sua vantagem e desvantagem ao mesmo tempo. A árvore é fácil de modelar mecanicamente, mas o problema está nos valores possíveis que o ativo subjacente pode levar em um período de tempo. Em um modelo de árvore binomial, o ativo subjacente só pode valer exatamente um dos dois valores possíveis, o que não é realista, pois os ativos podem valer qualquer número de valores dentro de um determinado intervalo.

Por exemplo, pode haver uma chance de 50/50 de que o preço do ativo subjacente possa aumentar ou diminuir em 30% em um período. Para o segundo período, no entanto, a probabilidade de que o preço do ativo subjacente aumente pode aumentar para 70/30.

Por exemplo, se um investidor está avaliando um [poço de petróleo](/exploratory-well),. esse investidor não tem certeza de qual é o valor desse poço de petróleo, mas há uma chance de 50/50 de que o preço suba. Se os preços do petróleo subirem no Período 1, tornando o poço de petróleo mais valioso e os [fundamentos do mercado](/fundamentals) agora apontarem para aumentos contínuos nos preços do petróleo, a probabilidade de uma maior valorização do preço agora pode ser de 70%. O modelo binomial permite essa flexibilidade; o modelo Black-Scholes não.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Exemplo do mundo real de modelo de precificação de opção binomial

Um exemplo simplificado de uma [árvore binomial](/binomial_tree) tem apenas um passo. Suponha que há uma ação que está cotada a $ 100 por ação. Em um mês, o preço dessa ação aumentará $ 10 ou cairá $ 10, criando esta situação:

- **Preço das ações** = $ 100

- **Preço das ações em um mês (estado em alta)** = $ 110

- **Preço das ações em um mês (estado inativo)** = $ 90

Em seguida, suponha que haja uma opção de compra disponível sobre essa ação que expira em um mês e tem um preço de exercício de $ 100. No estado de alta, esta opção de compra vale $ 10 e, no estado de baixa, vale $ 0. O modelo binomial pode calcular qual deve ser o preço da opção de compra hoje.

Para fins de simplificação, suponha que um investidor compre metade das ações e subscreva ou venda uma opção de compra. O investimento total hoje é o preço de meia ação menos o preço da opção, e os possíveis retornos no final do mês são:

- **Custo hoje** = $ 50 - preço da opção

- **Valor do portfólio** (estado ativo) = $ 55 - máx. ($ 110 - $ 100, 0) = $ 45

- **Valor do portfólio** (estado inativo) = $ 45 - max($ 90 - $ 100, 0) = $ 45

O retorno do portfólio é igual, não importa como o preço das ações se mova. Dado este resultado, assumindo que não há oportunidades de arbitragem, um investidor deve ganhar a taxa livre de risco ao longo do mês. O custo hoje deve ser igual ao pagamento descontado à taxa livre de risco por um mês. A equação a resolver é assim:

- **Preço da opção** = $ 50 - $ 45 xe ^ (-taxa livre de risco x T), onde e é a constante matemática 2,7183.

Supondo que a taxa livre de risco seja de 3% ao ano e T igual a 0,0833 (um dividido por 12), então o preço da opção de compra hoje é de $ 5,11.

O modelo de precificação de opções binomial apresenta duas vantagens para os vendedores de opções em relação ao modelo Black-Scholes. A primeira é a sua simplicidade, que permite menos erros na aplicação comercial. A segunda é sua operação iterativa, que ajusta os preços em tempo hábil para reduzir a oportunidade de os compradores executarem estratégias de arbitragem.

Por exemplo, uma vez que fornece um fluxo de avaliações para um [derivativo](/derivative) para cada nó em um período de tempo, é útil para avaliar derivativos como opções americanas – que podem ser executadas a qualquer momento entre a data de compra e a data de vencimento. Também é muito mais simples do que outros modelos de preços, como o modelo Black-Scholes.

##Destaques

- O modelo é intuitivo e é mais utilizado na prática do que o conhecido modelo Black-Scholes.

- Com o modelo, há dois resultados possíveis com cada iteração - um movimento para cima ou um movimento para baixo que segue uma árvore binomial.

- O modelo de precificação de opções binomiais valoriza as opções usando uma abordagem iterativa utilizando vários períodos para avaliar as opções americanas.

