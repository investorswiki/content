---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Prova de Capacidade (Criptomoeda)
description: A Prova de Capacidade é um mecanismo de consenso que usa o espaço do disco rígido de um nó de mineração para decidir os direitos de mineração na rede blockchain.
---

# Prova de Capacidade (Criptomoeda)
## O que é Prova de Capacidade (PoC) para Criptomoedas?

Prova de capacidade (PoC) é um algoritmo de [mecanismo de consenso](/consensus-mechanism-cryptocurrency) usado em blockchains que permite que dispositivos de [mineração](/bitcoin-mining) na rede usem seu espaço disponível no disco rígido para decidir direitos de mineração e validar transações. Isso contrasta com o uso do poder computacional do dispositivo de mineração (como no algoritmo [de prova de trabalho](/proof-work) ) ou a participação do minerador nas criptomoedas (como no algoritmo [de prova de participação](/proof-stake-pos) ).

## Compreensão da prova de capacidade

A prova de capacidade surgiu como uma das muitas soluções alternativas para o problema do alto consumo de energia em sistemas de prova de trabalho (PoW) e armazenamento de criptomoedas em sistemas de prova de participação (PoS).

A prova de capacidade permite que os dispositivos de mineração, também conhecidos como nós, na rede [blockchain](/blockchain) usem espaço vazio em seu disco rígido para minerar as [criptomoedas disponíveis](/cryptocurrency).

Em vez de alterar repetidamente os números no cabeçalho do bloco e repetir o hash para o valor da solução como em um sistema PoW, o PoC funciona armazenando uma lista de possíveis soluções no disco rígido do dispositivo de mineração antes mesmo do início da atividade de mineração.

Quanto maior o disco rígido, mais valores de solução possíveis podem ser armazenados no disco rígido, mais chances um minerador tem de corresponder ao valor de hash necessário de sua lista, resultando em mais chances de ganhar a recompensa de mineração.

Para fazer uma analogia, se as recompensas da loteria forem baseadas na correspondência do maior número de números no bilhete premiado, um jogador com uma lista maior de soluções possíveis terá melhores chances de ganhar. Além disso, o jogador pode continuar usando os números do bloco de bilhetes de loteria repetidamente.

[Burstcoin](/burstcoin) é uma criptomoeda que usa um sistema de prova de capacidade. Outras moedas que o usam são Storj, Chia e SpaceMint.

## Como funciona o PoC: plotagem e mineração

O protocolo de prova de capacidade envolve um processo de duas etapas que envolve plotagem e mineração.

Primeiro, o disco rígido é plotado: a lista de todos os valores [nonce possíveis](/nonce) é criada por meio de hashing repetido de dados, incluindo a conta de um minerador. Cada um desses nonce contém 8192 hashes, que são numerados de 0 a 8191. Todos os hashes são agrupados em "scoops", o que significa que os hashes adjacentes são combinados para formar um par de dois. Por exemplo, hash 0 e 1 constituem colher 0, hash 2 e 3 constituem hash 1 e assim por diante.

A segunda etapa envolve o exercício real de mineração, durante o qual um minerador calcula um número de colher. Por exemplo, se um minerador inicia a atividade de mineração e gera um furo número 38, o minerador então iria para o furo número 38 de nonce 1 e usaria os dados desse furo para calcular um valor de prazo.

O processo é repetido para calcular o prazo para cada nonce retido no disco rígido do minerador. Após o cálculo de todos os prazos, aquele com o prazo mínimo é selecionado pelo minerador.

Um prazo final representa a duração de tempo em segundos que deve decorrer desde que o último bloco foi forjado antes que um minerador possa forjar um novo bloco. Se ninguém mais forjou um bloco dentro desse período, o minerador pode forjar um bloco e reivindicar a recompensa do bloco.

Por exemplo, se o minerador X apresentar um prazo mínimo de 36 segundos e nenhum outro minerador puder forjar o bloco nos próximos 36 segundos, X garantirá a chance de forjar o próximo bloco e ser recompensado.

## Prós e Contras da Prova de Capacidade

PoC tem várias vantagens sobre os sistemas PoW e PoS, bem como algumas desvantagens importantes que incluem:

<h5><a href="">TT</a></h5>

## Destaques

- O principal benefício de um sistema PoC é sua eficiência em comparação com os sistemas de prova de trabalho (PoW) e prova de participação (PoS).

- Blockchains que funcionam com prova de capacidade incluem Storj, Burst, Chia e SpaceMint.

- Os sistemas de autenticação de prova de capacidade (PoC) empregam espaço livre no disco rígido de um dispositivo para armazenar soluções para um problema de hash de criptomoeda.

