---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: Modelo Box-Jenkins
description: O Modelo Box-Jenkins é um modelo matemático projetado para prever dados de uma série temporal especificada.
---

# Modelo Box-Jenkins
## Qual é o modelo Box-Jenkins?

O Modelo Box-Jenkins é um modelo matemático projetado para prever intervalos de dados com base em entradas de uma [série temporal especificada](/timeseries). O modelo Box-Jenkins pode analisar vários tipos diferentes de dados de séries temporais para fins de previsão.

Sua metodologia usa diferenças entre os pontos de dados para determinar os resultados. A metodologia permite que o modelo identifique tendências usando autorregressão, médias móveis e diferenciação sazonal para gerar previsões.

[modelos de média móvel integrada autorregressiva (ARIMA)](/autoregressive-integrated-moving-average-arima) são uma forma de modelo Box-Jenkins. Os termos ARIMA e Box-Jenkins às vezes são usados de forma intercambiável.

## Entendendo o modelo Box-Jenkins

Os modelos Box-Jenkins são usados para [prever](/forecasting) uma variedade de pontos de dados antecipados ou intervalos de dados, incluindo dados de negócios e preços futuros de títulos.

O Modelo Box-Jenkins foi criado por dois matemáticos: George Box e Gwilym Jenkins. Os dois matemáticos discutiram os conceitos que compõem esse modelo em uma publicação de 1970 chamada "Análise de Séries Temporais: Previsão e Controle".

As estimativas dos parâmetros do Modelo Box-Jenkins podem ser muito complicadas. Portanto, semelhante a outros modelos de regressão de séries temporais, os melhores resultados normalmente serão alcançados com o uso de software programável. O modelo Box-Jenkins também é geralmente mais adequado para previsões de curto prazo de 18 meses ou menos.

##Metodologia Box-Jenkins

O Modelo Box-Jenkins pode ser um dos vários modelos de análise de séries temporais que um previsor encontrará ao usar um software de previsão programado. Em muitos casos, o software será programado para usar automaticamente a metodologia de previsão de melhor ajuste com base nos dados da [série temporal](/timeseries) a ser prevista. Box-Jenkins é relatado como a melhor escolha para conjuntos de dados que são em sua maioria estáveis e têm baixa [volatilidade](/volatility).

O modelo Box-Jenkins prevê dados usando três princípios: autorregressão, diferenciação e média móvel. Esses três princípios são conhecidos como p, d e q, respectivamente. cada princípio é usado na análise de Box-Jenkins; juntos, eles são mostrados coletivamente como ARIMA (p, d, q).

O processo de autorregressão (p) testa os dados quanto ao seu nível de estacionariedade. Se os dados usados forem estacionários, isso pode simplificar o processo de previsão. Se os dados usados não forem estacionários, eles precisarão ser diferenciados (d). Os dados também são testados quanto ao seu ajuste de média móvel (que é feito na parte q do processo de análise). Em geral, a análise inicial dos dados os prepara para a previsão, determinando os parâmetros (p, d e q), que são aplicados para desenvolver uma previsão.

> Um choque único afetará os valores subsequentes de um modelo Box-Jenkins infinitamente no futuro. Portanto, o legado da crise financeira continua vivo nos modelos autorregressivos atuais.

>

## Média Móvel Integrada Autoregressiva (ARIMA)

Box-Jenkins é um tipo de modelo de média móvel integrada autorregressiva (ARIMA) que mede a força de uma variável dependente em relação a outras variáveis variáveis. O objetivo do modelo é prever futuros títulos ou movimentos do mercado financeiro examinando as diferenças entre os valores da série em vez de através de valores reais.

Um modelo ARIMA pode ser entendido delineando cada um de seus componentes da seguinte forma:

- [Autoregressão (AR)](/autoregressive) : refere-se a um modelo que mostra uma variável variável que regride em seus próprios valores defasados ou anteriores.

- Integrado (I): representa a diferenciação das observações brutas para permitir que a série temporal se torne estacionária, ou seja, os valores dos dados são substituídos pela diferença entre os valores dos dados e os valores anteriores.

- [Média móvel (MA)](/movingaverage) : incorpora a dependência entre uma observação e um erro residual de um modelo de média móvel aplicado a observações defasadas.

## Previsão de preços de ações

Um uso para a análise do Modelo Box-Jenkins é prever os preços das [ações .](/stock) Essa análise geralmente é construída e codificada por meio do software R. A análise dos resultados em um resultado logarítmico, que pode ser aplicado ao conjunto de dados para gerar os preços previstos para um determinado período de tempo no futuro.

Os modelos ARIMA são baseados na suposição de que os valores passados têm algum efeito residual nos valores atuais ou futuros. Por exemplo, um investidor usando um modelo ARIMA para prever os preços das ações suporia que novos compradores e vendedores daquela ação são influenciados por transações recentes de mercado ao decidir quanto oferecer ou aceitar pelo título.

Embora essa suposição seja válida em muitas circunstâncias diferentes, nem sempre é verdade. Por exemplo, nos anos anteriores à crise financeira de 2008, a maioria dos investidores não estava ciente dos riscos representados pelas grandes carteiras de [títulos garantidos por hipotecas](/mbs) (MBS) detidas por muitas empresas financeiras.

Naquela época, um investidor que usasse um modelo autorregressivo para prever o desempenho das ações financeiras dos EUA teria boas razões para prever uma tendência contínua de preços estáveis ou crescentes das ações nesse setor. No entanto, uma vez que se tornou de conhecimento público que muitas instituições financeiras estavam em risco de colapso iminente, os investidores de repente ficaram menos preocupados com os preços recentes dessas ações e muito mais preocupados com sua exposição ao risco subjacente.

Portanto, o mercado está rapidamente reavaliando as ações financeiras para um nível muito mais baixo, um movimento que teria confundido totalmente um modelo autoregressivo.

##Destaques

- Os modelos de média móvel integrada autorregressiva (ARIMA) são uma forma de modelo Box-Jenkins.

- O modelo Box-Jenkins é mais adequado para previsão dentro de prazos de 18 meses ou menos.

- A metodologia baseia-se no pressuposto de que as ocorrências passadas influenciam as futuras.

- O Modelo Box-Jenkins é uma metodologia de previsão usando estudos de regressão em dados de séries temporais.

