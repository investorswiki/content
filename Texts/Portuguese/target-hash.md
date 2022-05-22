---
keywords: Investing,Cryptocurrency,Altcoins
title: Hash de destino
description: Um hash de destino define a dificuldade para mineração de criptomoeda usando um sistema blockchain de prova de trabalho (PoW).
---

# Hash de destino
## O que é um hash de destino?

Na mineração de criptomoeda, um hash de destino é um valor numérico que um [cabeçalho de bloco com hash](/block-header-cryptocurrency) deve ser menor ou igual para que um novo bloco seja concedido a um minerador. Os cabeçalhos de bloco identificam blocos individuais em uma blockchain.

A mineração de criptomoeda refere-se ao processo de coleta de criptomoeda como recompensa pelo trabalho que você conclui. A natureza deste trabalho é verificar a legitimidade das transações de uma determinada criptomoeda. Dessa forma, os mineradores de criptomoedas são essencialmente auditores. Quando você minera, você pode ganhar criptomoedas sem ter que gastar dinheiro por isso.

O hash de destino é usado para determinar a dificuldade da entrada e pode ser ajustado para garantir que os blocos sejam processados com eficiência. Por exemplo, hashes de destino são usados em criptomoedas que usam um sistema de prova de trabalho (PoW) para definir a [dificuldade](/difficulty-cryptocurrencies) [atual](/difficulty-cryptocurrencies) (incluindo mineração de Bitcoin). Se uma criptomoeda usa um sistema diferente para mineração, pode não exigir um hash de destino.

## Como funciona um hash de destino

[As criptomoedas](/cryptocurrency) contam com o uso de [blockchains](/blockchain) que contêm o histórico de todas as transações dessa criptomoeda. Essas transações são codificadas por [hash](/hash),. ou codificadas criptograficamente, em uma série de caracteres alfanuméricos. Hashing envolve pegar uma string de dados de qualquer tamanho e executá-la por meio de um algoritmo para produzir uma saída com um tamanho fixo. A saída sempre terá o mesmo comprimento, independentemente de quão grande ou pequena seja a entrada (embora o número de permutações de um hash seja astronomicamente grande). Cada bloco conterá o hash do cabeçalho do bloco anterior.

Validar e codificar o blockchain é chamado de [mineração](/bitcoin-mining). A mineração envolve o uso de computadores para executar algoritmos de hash para processar o bloco mais recente; a informação que um usuário precisa para minerar é encontrada no cabeçalho do bloco. A rede de criptomoedas define um valor de destino para esse hash - chamado hash de destino - e os mineradores tentam determinar qual é esse valor testando todos os valores possíveis.

O cabeçalho do bloco contém o número da versão do bloco, um carimbo de data/hora, o hash usado no bloco anterior, o hash do [Merkle Root](/merkle-root-cryptocurrency) [,](/merkle-root-cryptocurrency) o [nonce](/nonce) e o hash de destino. O bloco é gerado pegando o hash do conteúdo do bloco, adicionando uma string aleatória de números (o nonce) e fazendo o hash do bloco novamente.

Se o hash atender ao requisito do destino, o bloco será adicionado ao blockchain. Percorrer as soluções para adivinhar o nonce é chamado de [prova de trabalho](/proof-work) (PoW), e o minerador que consegue encontrar o valor recebe o bloco e é pago em criptomoeda.

## Considerações Especiais

### Hash de destino para Bitcoin

Bitcoin usa o algoritmo de hash SHA-256. Esse algoritmo gera números aleatórios verificáveis de uma maneira que requer uma quantidade previsível de poder de processamento do computador.

A mineração de um bloco exige que o minerador produza um valor (um nonce) que, após ser hash (codificado criptograficamente), seja menor ou igual ao usado no bloco mais recente aceito pela rede bitcoin. Esse número está entre 0- (a menor opção) e 256 bits (a maior opção), mas é improvável que seja o número máximo.

Como o hash de destino pode ser um número enorme, o minerador pode ter que testar um grande número de valores antes de ter sucesso. Um minerador malsucedido precisa esperar pelo próximo bloco (e é por isso que os mineradores que encontram uma solução de hash são comparados aos vencedores de uma corrida ou da loteria).

O hash de destino é ajustado periodicamente. As funções de hash usadas para gerar o novo destino têm propriedades específicas projetadas para tornar o blockchain (e sua criptomoeda) seguro. Esse processo é determinístico, o que significa que produzirá o mesmo resultado toda vez que a mesma entrada for usada. É rápido o suficiente para não demorar muito para retornar um hash para a entrada. Também dificulta muito a determinação da entrada, especialmente para números grandes, e faz com que pequenas alterações na entrada resultem em uma saída de hash muito diferente.

##Destaques

- Hashes de destino são usados em criptomoedas que usam um sistema de prova de trabalho (PoW) para definir a dificuldade de mineração atual (incluindo Bitcoin); se uma criptomoeda usa um sistema diferente para mineração, pode não exigir um hash de destino.

- Na mineração de criptomoeda, um hash de destino é um valor numérico que um cabeçalho de bloco com hash (que é usado para identificar blocos individuais em uma blockchain) deve ser menor ou igual para que um novo bloco seja concedido a um minerador.

- A rede Bitcoin ajusta a dificuldade de mineração aumentando ou diminuindo o hash alvo para preservar um intervalo médio de 10 minutos entre novos blocos.

