---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Média Móvel Integrada Autoregressiva (ARIMA)
description: Uma média móvel integrada autorregressiva (ARIMA) é um modelo de análise estatística que aproveita dados de séries temporais para prever tendências futuras.
---

# Média Móvel Integrada Autoregressiva (ARIMA)
## O que é uma média móvel integrada autorregressiva (ARIMA)?

Uma média móvel integrada autoregressiva, ou ARIMA, é um modelo de análise estatística que usa dados de [séries temporais](/timeseries) para entender melhor o conjunto de dados ou prever tendências futuras.

Um modelo estatístico é autorregressivo se prevê valores futuros com base em valores passados. Por exemplo, um modelo ARIMA pode procurar prever os preços futuros de uma ação com base em seu desempenho passado ou prever os ganhos de uma empresa com base em períodos passados.

## Entendendo a Média Móvel Integrada Autoregressiva (ARIMA)

Um modelo de média móvel integrado autorregressivo é uma forma de [análise de regressão](/regression) que mede a força de uma variável dependente em relação a outras variáveis variáveis. O objetivo do modelo é prever futuros títulos ou movimentos do mercado financeiro examinando as diferenças entre os valores da série em vez de através de valores reais.

Um modelo ARIMA pode ser entendido delineando cada um de seus componentes da seguinte forma:

- [Autoregressão (AR)](/autoregressive) : refere-se a um modelo que mostra uma variável variável que regride em seus próprios valores defasados ou anteriores.

- **Integrado (I):** representa a diferenciação das observações brutas para permitir que a série temporal se torne estacionária (ou seja, os valores dos dados são substituídos pela diferença entre os valores dos dados e os valores anteriores).

- [Média móvel (MA)](/movingaverage) : incorpora a dependência entre uma observação e um erro residual de um modelo de média móvel aplicado a observações defasadas.

## Parâmetros ARIMA

Cada componente do ARIMA funciona como um parâmetro com uma notação padrão. Para modelos ARIMA, uma notação padrão seria ARIMA com p, d e q, onde valores inteiros substituem os parâmetros para indicar o tipo de modelo ARIMA utilizado. Os parâmetros podem ser definidos como:

- **p**: o número de observações defasadas no modelo; também conhecida como ordem de atraso.

- **d**: o número de vezes que as observações brutas são diferenciadas; também conhecido como o grau de diferenciação.

- q: o tamanho da janela de média móvel; também conhecida como a ordem da média móvel.

Em um modelo de [regressão linear](/nonlinear-regression),. por exemplo, o número e o tipo de termos são incluídos. Um valor 0, que pode ser usado como parâmetro, significaria que um determinado componente não deveria ser usado no modelo. Desta forma, o modelo ARIMA pode ser construído para desempenhar a função de um modelo ARMA, ou mesmo modelos simples AR, I ou MA.

> Como os modelos ARIMA são complicados e funcionam melhor em conjuntos de dados muito grandes, algoritmos de computador e técnicas de aprendizado de máquina são usados para calculá-los.

>

## Média Móvel Integrada Autoregressiva (ARIMA) e Estacionaridade

Em um modelo de média móvel integrado autorregressivo, os dados são diferenciados para torná-lo estacionário. Um modelo que mostra estacionariedade é aquele que mostra que há constância nos dados ao longo do tempo. A maioria dos dados econômicos e de mercado mostra tendências, portanto, o objetivo da diferenciação é remover quaisquer tendências ou estruturas sazonais.

[A sazonalidade](/seasonality),. ou quando os dados mostram padrões regulares e previsíveis que se repetem ao longo de um ano civil, pode afetar negativamente o modelo de regressão. Se aparecer uma tendência e a estacionaridade não for evidente, muitos dos cálculos ao longo do processo não podem ser feitos com grande eficácia.

> Um choque único afetará os valores subsequentes de um modelo ARIMA infinitamente no futuro. Portanto, o legado da crise financeira continua vivo nos modelos autorregressivos atuais.

>

## Considerações Especiais

Os modelos ARIMA são baseados na suposição de que os valores passados têm algum efeito residual nos valores atuais ou futuros. Por exemplo, um investidor usando um modelo ARIMA para prever os preços das ações suporia que novos compradores e vendedores daquela ação são influenciados por transações recentes de mercado ao decidir quanto oferecer ou aceitar pelo título.

Embora essa suposição seja válida em muitas circunstâncias, nem sempre é esse o caso. Por exemplo, nos anos anteriores à crise financeira de 2008, a maioria dos investidores não estava ciente dos riscos representados pelas grandes carteiras de [títulos garantidos por hipotecas](/mbs) (MBS) detidas por muitas empresas financeiras.

Naquela época, um investidor que usasse um modelo autorregressivo para prever o desempenho das ações financeiras dos EUA teria boas razões para prever uma tendência contínua de preços estáveis ou crescentes das ações nesse setor. No entanto, uma vez que se tornou de conhecimento público que muitas instituições financeiras estavam em risco de colapso iminente, os investidores de repente ficaram menos preocupados com os preços recentes dessas ações e muito mais preocupados com sua exposição ao risco subjacente. Portanto, o mercado está rapidamente reavaliando as ações financeiras para um nível muito mais baixo, um movimento que teria confundido totalmente um modelo autoregressivo.

## Perguntas frequentes

### Para que serve o ARIMA?

ARIMA é um método para prever ou prever resultados futuros com base em uma série histórica. Baseia-se no conceito estatístico de correlação serial, onde os pontos de dados passados influenciam os pontos de dados futuros.

### Quais são as diferenças entre os modelos autorregressivo e de média móvel?

ARIMA combina características autorregressivas com as de médias móveis. Um processo autoregressivo AR(1), por exemplo, é aquele em que o valor atual é baseado no valor imediatamente anterior, enquanto um processo AR(2) é aquele em que o valor atual é baseado nos dois valores anteriores. Uma média móvel é um cálculo usado para analisar pontos de dados criando uma série de médias de diferentes subconjuntos do conjunto de dados completo para suavizar a influência de valores discrepantes. Como resultado dessa combinação de técnicas, os modelos ARIMA podem levar em consideração tendências, ciclos, sazonalidade e outros tipos de dados não estáticos ao fazer previsões.

### Como funciona a previsão ARIMA?

A previsão ARIMA é obtida conectando-se dados de séries temporais para a variável de interesse. O software estatístico identificará o número apropriado de atrasos ou quantidade de diferenciação a ser aplicada aos dados e verificará a estacionariedade. Em seguida, ele produzirá os resultados, que geralmente são interpretados de maneira semelhante a um modelo de regressão linear múltipla.

##Destaques

- Modelos de média móvel integrada autorregressiva (ARIMA) preveem valores futuros com base em valores passados.

- ARIMA faz uso de médias móveis defasadas para suavizar dados de séries temporais.

- São amplamente utilizados em análises técnicas para prever preços futuros de títulos.

- Os modelos autorregressivos assumem implicitamente que o futuro será semelhante ao passado.

- Portanto, eles podem ser imprecisos sob certas condições de mercado, como crises financeiras ou períodos de rápida mudança tecnológica.

