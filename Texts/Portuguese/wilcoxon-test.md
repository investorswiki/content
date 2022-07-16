---
keywords: Investing,Fundamental Analysis,Tools for Fundamental Analysis,Tools
title: Teste de Wilcoxon
description: O teste de Wilcoxon, que se refere ao teste de soma de ranks ou ao teste de ranks sinalizados, é um teste não paramétrico que compara dois grupos pareados.
---

# Teste de Wilcoxon
## O que é o teste de Wilcoxon?

O teste de Wilcoxon, que pode se referir tanto ao teste de soma de ranks quanto à versão do teste de ranks sinalizados, é um teste estatístico não paramétrico que compara dois grupos pareados. Os testes essencialmente calculam a diferença entre conjuntos de pares e analisam essas diferenças para estabelecer se elas são [estatisticamente](/statistical-significance) [significativamente](/statistical-significance) diferentes umas das outras.

## Entendendo o teste de Wilcoxon

A soma de classificação e os testes de classificação sinalizada foram propostos pelo estatístico americano Frank Wilcoxon em um trabalho de pesquisa inovador publicado em 1945. Os testes lançaram as bases para o teste de [hipóteses de](/hypothesistesting) [estatísticas não paramétricas](/nonparametric-statistics),. que são usadas para dados populacionais que podem ser classificados, mas não têm valores numéricos, como satisfação do cliente ou críticas musicais. As distribuições não paramétricas não têm parâmetros e não podem ser definidas por uma equação como as distribuições paramétricas.

Os tipos de perguntas que o teste de Wilcoxon pode ajudar a responder incluem coisas como:

- As notas dos testes são diferentes do 5º ao 6º ano para os mesmos alunos?

- Um determinado medicamento tem efeito sobre a saúde quando testado nos mesmos indivíduos?

Esses modelos assumem que os dados vêm de duas populações correspondentes ou dependentes, seguindo a mesma pessoa ou estoque ao longo do tempo ou lugar. Os dados também são considerados contínuos em oposição a discretos. Por ser um teste não paramétrico, não requer uma distribuição de probabilidade particular da variável dependente na análise.

## Tipos de teste de Wilcoxon

- O teste de soma de postos de Wilcoxon pode ser usado para testar a [hipótese nula de](/null_hypothesis) que duas populações têm a mesma distribuição contínua. Uma hipótese nula é um teste estatístico que diz que não há diferença significativa entre duas populações ou variáveis. As suposições básicas necessárias para empregar o teste de soma de postos são que os dados são da mesma população e são pareados, os dados podem ser medidos em pelo menos uma escala de intervalo e os dados foram escolhidos de forma aleatória e independente.

- O teste de postos sinalizados de Wilcoxon assume que há informação nas magnitudes e sinais das diferenças entre observações pareadas. Como o equivalente não paramétrico do teste t de Student pareado, o posto sinalizado pode ser usado como alternativa ao [teste t](/t-test) quando os dados populacionais não seguem uma [distribuição normal](/normaldistribution).

## Calculando uma estatística de teste de Wilcoxon

As etapas para chegar a uma estatística de teste de classificação sinalizada de Wilcoxon, **W,** são as seguintes:

1. Para cada item em uma amostra de **n** itens, obtenha uma pontuação de diferença, D~i~, entre duas medidas (ou seja, subtraia uma da outra).

1. Despreze então os sinais positivos ou negativos e obtenha um conjunto de **n** diferenças absolutas |D~i~|.

1. Omita pontuações de diferença zero, dando a você um conjunto de pontuações de diferença absolutas **n** diferentes de zero, onde **n' ≤ n**. Assim, **n'** torna-se o tamanho real da amostra.

1. Em seguida, atribua ranks R~i~ de 1 a **n** a cada um dos |D~i~| de tal forma que a menor pontuação de diferença absoluta recebe a classificação 1 e a maior recebe a classificação **n**. Se dois ou mais |D~i~| são iguais, cada um recebe a classificação média das classificações que teriam sido atribuídas individualmente se não houvesse empates nos dados.

1. Agora reatribua o símbolo "+" ou "–" a cada uma das classificações **n** R~i~, dependendo se D~i~ era originalmente positivo ou negativo.

1. A estatística do teste de Wilcoxon **W** é subsequentemente obtida como a soma das classificações positivas.

Na prática, esse teste é realizado por meio de um software de análise estatística ou de uma planilha.

##Destaques

- Ambas as versões do modelo assumem que os pares nos dados provêm de populações dependentes, ou seja, seguindo a mesma pessoa ou preço de ação no tempo ou lugar.

- O objetivo do teste é determinar se dois ou mais conjuntos de pares são diferentes um do outro de maneira estatisticamente significativa.

- O teste de Wilcoxon compara dois grupos pareados e vem em duas versões, o teste de soma de ranks e o teste de ranks sinalizados.

