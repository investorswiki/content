---
keywords: Investing,Cryptocurrency,Bitcoin
title: Prova de Trabalho (PoW)
description: A prova de trabalho descreve o processo que permite que a rede bitcoin permaneça robusta, dificultando o processo de mineração ou registro de transações.
---

# Prova de Trabalho (PoW)
## O que é Prova de Trabalho (PoW)?

A prova de trabalho (PoW) descreve um sistema que requer um esforço não insignificante, mas viável, para impedir usos frívolos ou maliciosos do poder de computação, como enviar e-mails de spam ou lançar ataques de negação de serviço. O conceito foi posteriormente adaptado para proteger o dinheiro digital por Hal Finney em 2004 através da ideia de "prova de trabalho reutilizável" usando o algoritmo de hash SHA-256.

Após sua introdução em 2009, o Bitcoin se tornou a primeira aplicação amplamente adotada da ideia PoW de Finney (Finney também foi o destinatário da primeira transação de bitcoin). A prova de trabalho também forma a base de muitas outras [ocorrências de](/cryptocurrency) [cripta](/cryptocurrency),. permitindo um consenso seguro e descentralizado.

## Entendendo a Prova de Trabalho

Esta explicação se concentrará na prova de trabalho como funciona na rede [bitcoin](/bitcoin). Bitcoin é uma moeda digital que é sustentada por uma espécie de livro- [razão distribuído](/distributed-ledger-technology-dlt) conhecido como " [blockchain](/blockchain) ". Este livro contém um registro de todas as transações de bitcoin, organizadas em "blocos" sequenciais, para que nenhum usuário tenha permissão para gastar duas vezes suas participações. Para evitar adulterações, o livro-razão é público ou "distribuído"; uma versão alterada seria rapidamente rejeitada por outros usuários.

A maneira como os usuários detectam adulteração na prática é por meio de [hashes](/hash),. longas sequências de números que servem como prova de trabalho. Coloque um determinado conjunto de dados por meio de uma função de hash (o bitcoin usa SHA-256) e ele gerará apenas um hash. Devido ao "efeito avalanche", no entanto, mesmo uma pequena alteração em qualquer parte dos dados originais resultará em um hash totalmente irreconhecível. Qualquer que seja o tamanho do conjunto de dados original, o hash gerado por uma determinada função terá o mesmo comprimento. O hash é uma função unidirecional: ele não pode ser usado para obter os dados originais, apenas para verificar se os dados que geraram o hash correspondem aos dados originais.

Gerar qualquer hash para um conjunto de transações bitcoin seria trivial para um computador moderno, portanto, para transformar o processo em “trabalho”, a rede bitcoin estabelece um certo nível de “dificuldade”. Essa configuração é ajustada para que um novo bloco seja " [extraído](/bitcoin-mining) " - adicionado ao blockchain gerando um hash válido - aproximadamente a cada 10 minutos. Definir a dificuldade é obtido estabelecendo um ["alvo" para o hash](/target-hash) : quanto menor o alvo, menor o conjunto de hashes válidos e mais difícil é gerar um. Na prática, isso significa um hash que começa com uma longa sequência de zeros.

> A prova de trabalho foi inicialmente criada como uma proposta de solução para o crescente problema do e-mail de spam.

>

## Considerações Especiais

Como um determinado conjunto de dados pode gerar apenas um hash, como os mineradores garantem que gerem um hash abaixo do destino? Eles alteram a entrada adicionando um inteiro, chamado de [nonce](/nonce) ("número usado uma vez"). Uma vez que um hash válido é encontrado, ele é transmitido para a rede e o bloco é adicionado ao blockchain.

A mineração é um processo competitivo, mas é mais uma loteria do que uma corrida. Em média, alguém gerará uma prova de trabalho aceitável a cada dez minutos, mas quem será é uma incógnita. Os mineradores se unem para aumentar suas chances de minerar blocos, o que gera taxas de transação e, por tempo limitado, uma recompensa de bitcoins recém-criados.

A prova de trabalho torna extremamente difícil alterar qualquer aspecto do blockchain, pois tal alteração exigiria a re-mineração de todos os blocos subsequentes. Também torna difícil para um usuário ou grupo de usuários monopolizar o poder de computação da rede, uma vez que o maquinário e o poder necessários para completar as funções de hash são caros.

> Se parte de uma rede de mineração começar a aceitar uma prova de trabalho alternativa, ela é conhecida como [hard fork](/hard-fork).

>

## Exemplo de Prova de Trabalho

A prova de trabalho requer que um computador se envolva aleatoriamente em funções de hash até chegar a uma saída com a quantidade mínima correta de zeros à esquerda. Por exemplo, o hash para o bloco nº 660000, extraído em 4 de dezembro de 2020, é 00000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. A recompensa do bloco por esse hash bem-sucedido foi de 6,25 BTC.

Esse bloco sempre conterá 745 transações envolvendo pouco mais de 1.666 bitcoins, assim como o cabeçalho do bloco anterior. Se alguém tentasse alterar o valor de uma transação em até 0,000001 bitcoin, o hash resultante seria irreconhecível e a rede rejeitaria a tentativa de fraude.

## Perguntas frequentes sobre a prova de trabalho

### O que significa Prova de Trabalho?

O PoW exige que os nós em uma rede forneçam evidências de que eles gastaram poder computacional (ou seja, trabalho) para obter consenso de maneira descentralizada e impedir que atores mal-intencionados ultrapassem a rede.

### Como a prova de trabalho valida uma transação de criptografia?

O trabalho em si é arbitrário. Para Bitcoin, envolve iterações de algoritmos de hash SHA-256. O "vencedor" de uma rodada de hash, no entanto, agrega e registra as transações do mempool no próximo bloco. Como o "vencedor" é escolhido aleatoriamente e proporcional ao trabalho realizado, incentiva todos na rede a agir com honestidade e registrar apenas transações verdadeiras.

### Por que as criptomoedas precisam de prova de trabalho?

Por serem descentralizados e peer-to-peer por design, blockchains, como redes de criptomoedas, exigem alguma maneira de alcançar consenso e segurança. A prova de trabalho é um desses métodos que consome muitos recursos para tentar ultrapassar a rede. Também existem outros mecanismos de prova que consomem menos recursos, mas que têm outras desvantagens ou falhas, como [prova](/proof-stake-pos) [de participação (PoS)](/proof-stake-pos) e [prova de queima](/proof-burn-cryptocurrency). Sem um mecanismo de prova, a rede e os dados armazenados nela estariam vulneráveis a ataques ou roubos.

### O Bitcoin usa Prova de Trabalho?

Sim. Ele usa um algoritmo PoW baseado na função de hash SHA-256 para validar e confirmar transações, bem como para emitir novos bitcoins em circulação.

### Como o Proof of Stake (PoS) difere do PoW?

PoS é um mecanismo de consenso que atribui aleatoriamente o nó que irá minerar ou validar transações de bloco de acordo com quantas moedas esse nó possui. Quanto mais tokens forem mantidos em uma carteira, mais poder de mineração será efetivamente concedido a ela. Embora o PoS seja muito menos intensivo em recursos, ele tem várias outras falhas, incluindo uma chance maior de um [ataque de 51%](/51-attack) em altcoins menores e incentivos para acumular tokens e não usá-los.

## Destaques

- Proof of Stake (POS) foi um dos vários novos mecanismos de consenso criados como uma alternativa à prova de trabalho.

- Proof of work (PoW) é um mecanismo de consenso descentralizado que exige que os membros de uma rede se esforcem para resolver um quebra-cabeça matemático arbitrário para impedir que alguém jogue no sistema.

- A prova de trabalho em escala requer enormes quantidades de energia, o que só aumenta à medida que mais mineradores se juntam à rede.

- Devido à prova de trabalho, Bitcoin e outras transações de criptomoeda podem ser processadas ponto a ponto de maneira segura, sem a necessidade de um terceiro confiável.

- A prova de trabalho é amplamente utilizada na mineração de criptomoedas, para validar transações e minerar novos tokens.

