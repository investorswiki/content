---
keywords: Investing,Cryptocurrency,Blockchain
title: Bloco (Bloco Bitcoin)
description: Blocos são estruturas de dados dentro de um banco de dados onde os dados de transações de criptomoedas são registrados permanentemente; uma vez escrito, não pode ser alterado ou removido.
---

# Bloco (Bloco Bitcoin)
## O que é um bloco (Blockchain Block)?

Blocos são estruturas de dados dentro do banco de dados blockchain, onde os dados de transação em um blockchain de criptomoeda são registrados permanentemente. Um bloco registra algumas ou todas as transações mais recentes ainda não validadas pela rede. Uma vez que os dados são validados, o bloco é fechado. Em seguida, é criado um novo bloco para que novas transações sejam inseridas e validadas.

Um bloco é, portanto, um armazenamento permanente de registros que, uma vez gravados, não podem ser alterados ou removidos.

## Como funciona um bloco (Blockchain Block)

Uma rede [blockchain](/blockchain) está testemunhando uma grande atividade de transações. Quando usado em criptomoeda, manter um registro dessas transações ajuda o sistema a rastrear quanto foi ou não usado e quais partes estavam envolvidas. As transações realizadas durante um determinado período são registradas em um arquivo chamado bloco, que é a base da rede blockchain.

Um bloco armazena informações. Há muitas informações incluídas em um bloco, mas elas não ocupam muito espaço de armazenamento. Os blocos geralmente incluem esses elementos, mas podem variar entre os diferentes tipos:

- **Número mágico**: Um número contendo valores específicos que identificam aquele bloco como parte da rede de uma determinada criptomoeda.

- **Blocksize**: Define o limite de tamanho do bloco para que apenas uma quantidade específica de informação possa ser escrita nele.

- **Cabeçalho do bloco**: Contém informações sobre o bloco.

- **Contador de transações**: Um número que representa quantas transações estão armazenadas no bloco.

- **Transações**: Uma lista de todas as transações dentro de um bloco.

O elemento de transação é o maior porque contém mais informações. Ele é seguido em tamanho de armazenamento pelo cabeçalho do bloco, que inclui estes subelementos:

- **Versão**: A versão da criptomoeda que está sendo usada.

- **Hash do bloco anterior**: Contém um hash (número criptografado) do cabeçalho do bloco anterior.

- **Hash Merkle root**: Hash das transações na [árvore Merkle](/merkle-tree) do bloco atual.

- **Hora**: Um carimbo de data/hora para colocar o bloco no blockchain.

- **Bits**: A classificação de dificuldade do hash alvo, significando a dificuldade em resolver o nonce.

- **Nonce**: O número criptografado que um minerador deve resolver para verificar o bloco e fechá-lo.

Um número de 32 bits no cabeçalho é chamado de nonce - o programa de mineração usa números aleatórios para "adivinhar" o nonce no [hash](/hash). Quando um nonce é verificado, o hash é resolvido quando o nonce, ou um número menor que ele, é adivinhado. Em seguida, a rede fecha esse bloco, gera um novo com um cabeçalho e o processo se repete.

diferentes mecanismos são usados para chegar a um consenso; o mais popular para criptomoeda é [o proof-of-work](/proof-work) (PoW), com o proof-of-stake (PoS) se tornando mais devido ao consumo de energia reduzido em comparação ao PoW.

## Relação da Mineração com os Blocos

Mineração é o termo usado para resolver o número que é o nonce, o único número que pode ser alterado em um cabeçalho de bloco. É também o processo que a rede da criptomoeda usa se a prova de trabalho for usada no protocolo.

A mineração de criptomoedas é comumente considerada um problema matemático complexo; na verdade, é um número aleatório gerado por meio de hash. Hashing é o processo de criptografar informações usando o método de criptografia que uma criptomoeda usa. Por exemplo, o Bitcoin usa SHA256 para seu algoritmo de criptografia. Para um minerador gerar o número "vencedor", o programa de mineração deve usar o SHA 256 para fazer hash de números aleatórios e colocá-los no nonce para ver se é uma correspondência.

> Resolver o hash de número aleatório sob o protocolo de prova de trabalho é o que consome tanta energia e poder computacional. Uma extensa rede de mineradores e energia suficiente para abastecer um pequeno país é necessária para mantê-lo funcionando.

>

A dificuldade está em que todos os cabeçalhos de bloco anteriores são criptografados aleatoriamente. Portanto, o cabeçalho do bloco atual é um número criptografado gerado aleatoriamente com base nos números criptografados gerados aleatoriamente de blocos anteriores e informações do bloco atual.

## Outros usos de blocos e blockchains

Como a maioria das definições de blockchain se refere ao Bitcoin porque foi a primeira criptomoeda a usar uma, muitas pessoas associam blocos e blockchains ao Bitcoin. No entanto, outras criptomoedas também usam blocos e blockchains. É importante notar que a rede da Ethereum possui uma criptomoeda chamada ether que também usa blocos e blockchain.

No entanto, o Ethereum e seu blockchain foram projetados para usos múltiplos que se estendem a muito mais do que criptomoedas. Por exemplo, tokens não fungíveis, contratos inteligentes, aplicativos financeiros descentralizados e muito mais foram desenvolvidos usando o Ethereum.

##Destaques

- Blocos e blockchains não são usados apenas por criptomoedas. Eles também têm muitos outros usos.

- Os blocos são identificados por números longos que incluem informações de transações criptografadas de blocos anteriores e novas informações de transações.

- Os blocos e as informações dentro deles devem ser verificados por uma rede antes que novos blocos possam ser criados.

- Um bloco é um lugar em uma blockchain onde as informações são armazenadas e criptografadas.

##PERGUNTAS FREQUENTES

### O que é Blockchain em palavras simples?

Um blockchain é um banco de dados que armazena e criptografa informações de forma vinculada, para que as informações anteriores não possam ser alteradas, e um grupo verifica todas as entradas antes de serem finalizadas por meio de um consenso - um acordo de que os dados estão corretos.

### Para que servem os Blockchains?

Blockchains são usados em criptomoedas, aplicativos financeiros descentralizados, tokens não fungíveis, com mais usos constantemente em desenvolvimento.

### Como é criado um bloco Blockchain?

Os blocos são criados quando os mineradores ou validadores de bloco validam com sucesso as informações criptografadas no blockheader, o que solicita a criação de um novo bloco.

