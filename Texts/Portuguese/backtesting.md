---
keywords: Trading,Technical Analysis,Technical Analysis Basic Education
title: backtesting
description: O backtesting avalia a eficácia de uma estratégia de negociação, executando-a em relação a dados históricos para ver como ela teria se saído.
---

# backtesting
## O que é backtesting?

O backtesting é o método geral para ver o desempenho de uma estratégia ou modelo [ex-post](/expost). O backtesting avalia a viabilidade de uma [estratégia de negociação](/trading-strategy) descobrindo como ela se sairia usando dados históricos. Se o backtesting funcionar, traders e analistas podem ter confiança para empregá-lo daqui para frente.

## Entendendo o backtesting

O backtesting permite que um trader simule uma estratégia de negociação usando [dados históricos](/historical-returns) para gerar resultados e analisar risco e lucratividade antes de arriscar qualquer capital real.

Um backtest bem conduzido que produz resultados positivos garante [aos traders](/trader) que a estratégia é fundamentalmente sólida e provavelmente gerará lucros quando implementada na realidade. Em contraste, um backtest bem conduzido que produz resultados abaixo do ideal levará os traders a alterar ou rejeitar a estratégia.

> Estratégias de negociação particularmente complicadas, como estratégias implementadas por sistemas de negociação automatizados, dependem muito de backtesting para provar seu valor, pois são muito misteriosas para avaliar de outra forma.

>

Contanto que uma ideia de negociação possa ser quantificada, ela pode ser testada novamente. Alguns traders e investidores podem buscar a experiência de um programador qualificado para desenvolver a ideia em uma forma testável. Normalmente, isso envolve um programador que codifica a ideia na linguagem proprietária hospedada pela [plataforma de](/trading-platform) [negociação](/trading-platform).

O programador pode incorporar variáveis de entrada definidas pelo usuário que permitem ao trader "ajustar" o sistema. Um exemplo disso seria o sistema de cruzamento [de média móvel simples](/sma) (SMA). O trader poderá inserir (ou alterar) os comprimentos das duas médias móveis usadas no sistema. O trader poderia então fazer um backtest para determinar quais comprimentos de médias móveis teriam o melhor desempenho nos dados históricos.

## O cenário ideal de backtesting

O backtest ideal escolhe dados de amostra de um período de tempo relevante de duração que reflete uma variedade de condições de mercado. Dessa forma, pode-se julgar melhor se os resultados do backtest representam um acaso ou uma negociação sólida.

O conjunto de dados históricos deve incluir uma [amostra verdadeiramente representativa](/representative-sample) de ações, incluindo aquelas de empresas que eventualmente [faliram](/bankruptcy) ou foram vendidas ou liquidadas. A alternativa, incluindo apenas dados de ações históricas que ainda existem hoje, produzirá retornos artificialmente altos no backtesting.

Um backtest deve considerar todos os custos de negociação, por mais insignificantes que sejam, pois eles podem se somar ao longo do período de backtesting e afetar drasticamente a aparência da lucratividade de uma estratégia. Os comerciantes devem garantir que seu software de backtesting seja responsável por esses custos.

Testes fora da amostra e testes de desempenho antecipados fornecem confirmação adicional sobre a eficácia de um sistema e podem mostrar as verdadeiras cores de um sistema antes que o dinheiro real esteja em jogo. Uma forte [correlação](/correlation) entre os resultados dos testes de desempenho backtesting, out-of-sample e forward é vital para determinar a viabilidade de um sistema de negociação.

## Backtesting vs. Teste de desempenho avançado

O teste de desempenho futuro, também conhecido como [negociação de papel](/papertrade),. fornece aos traders outro conjunto de dados fora da amostra para avaliar um sistema. O teste de desempenho futuro é uma simulação de negociação real e envolve seguir a lógica do sistema em um mercado ao vivo. Também é chamado de negociação em papel, pois todos os negócios são executados apenas em papel; ou seja, as entradas e saídas de negociação são documentadas juntamente com qualquer lucro ou perda para o sistema, mas nenhuma negociação real é executada.

Um aspecto importante do teste de desempenho avançado é seguir exatamente a lógica do sistema; caso contrário, torna-se difícil, senão impossível, avaliar com precisão esta etapa do processo. Os comerciantes devem ser honestos sobre quaisquer entradas e saídas de comércio e evitar comportamentos como [escolher a](/cherrypicking) dedo ou não incluir um comércio no papel, racionalizando que "eu nunca teria feito esse comércio". Caso a negociação tenha ocorrido seguindo a lógica do sistema, ela deve ser documentada e avaliada.

## Backtesting vs. Análise de cenário

Enquanto o backtesting usa dados históricos reais para testar o ajuste ou o sucesso, a [análise de cenário](/scenario_analysis) faz uso de dados hipotéticos que simulam vários resultados possíveis. Por exemplo, a análise de cenários simulará mudanças específicas nos valores dos títulos da carteira ou fatores-chave que ocorrem, como uma mudança na [taxa de juros](/interestrate).

análise de cenário é comumente usada para estimar mudanças no valor de uma [carteira](/portfolio) em resposta a um evento desfavorável e pode ser usada para examinar um cenário teórico de pior caso.

## Algumas armadilhas do backtesting

Para que o backtesting forneça resultados significativos, os traders devem desenvolver suas estratégias e testá-las de boa fé, evitando o máximo possível de viés. Isso significa que a estratégia deve ser desenvolvida sem depender dos dados usados no backtesting.

Isso é mais difícil do que parece. Os comerciantes geralmente constroem estratégias com base em dados históricos. Eles devem ser rigorosos ao testar com conjuntos de dados diferentes daqueles em que treinam seus modelos. Caso contrário, o backtest produzirá resultados brilhantes que não significam nada.

Da mesma forma, os traders devem evitar a dragagem de dados, na qual testam uma ampla gama de estratégias hipotéticas contra o mesmo conjunto de dados, o que também produzirá sucessos que falharão em mercados [em tempo real](/real_time),. porque existem muitas estratégias inválidas que venceriam o mercado por um período de tempo. período de tempo específico por acaso.

Uma maneira de compensar a tendência de dragagem ou seleção de dados é usar uma estratégia que tenha sucesso no período de tempo relevante ou dentro da amostra e testá-la com dados de um período de tempo diferente ou fora da amostra . Se backtests dentro e fora da amostra produzirem resultados semelhantes, é mais provável que eles sejam válidos.

##Destaques

- A teoria subjacente é que qualquer estratégia que funcionou bem no passado provavelmente funcionará bem no futuro e, inversamente, qualquer estratégia que funcionou mal no passado provavelmente terá um desempenho ruim no futuro.

- Backtesting avalia a viabilidade de uma estratégia de negociação ou modelo de precificação, descobrindo como ela teria se comportado retrospectivamente usando dados históricos.

- Ao testar uma ideia em dados históricos, é benéfico reservar um período de tempo de dados históricos para fins de teste. Se for bem-sucedido, testá-lo em períodos de tempo alternativos ou dados fora da amostra pode ajudar a confirmar sua viabilidade potencial.

