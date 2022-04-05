---
keywords: Crypto
title: Mineração
description: Mineração. A verificação de transações em uma rede blockchain, na qual as transações são adicionadas como entradas no livro blockchain.
---

# Mineração
A mineração é o processo pelo qual as transações de [criptomoedas](/cryptocurrency) são reunidas, verificadas e registradas em um livro digital conhecido como [blockchain](/blockchain). O trabalho realizado pelos mineradores é essencial para manter a integridade da rede e também é responsável pela introdução de novas moedas no sistema.

Dentro do sistema bancário tradicional, a moeda fiduciária é impressa e distribuída por instituições financeiras e autoridades governamentais - mas para a maioria das criptomoedas, a emissão de novas moedas não está nas mãos de entidades centralizadas. Em vez disso, novas unidades de criptomoeda são geradas através do processo de mineração, que segue um conjunto predefinido de regras estabelecidas pelo protocolo subjacente. Enquanto o protocolo define quais são as regras primárias, os chamados algoritmos de consenso descrevem como essas regras serão seguidas (por exemplo, durante a validação de transações).

Tomando o Bitcoin como exemplo, os participantes envolvidos no processo de mineração são chamados de nós de mineração (ou apenas mineradores), e desempenham um papel fundamental na segurança da rede blockchain. O trabalho de um minerador é reunir transações não confirmadas do pool de memória e organizá-las em um [bloco candidato](/candidate-block) que eles tentarão validar.

Ao criar um bloco candidato, um minerador inclui uma transação em que envia a [recompensa do bloco](/block-reward) para si mesmo. Essa transação é conhecida como transação base de moedas e geralmente é a primeira a ser registrada em um bloco.

Depois que a lista de transações não confirmadas é formada, cada transação é hash e suas saídas são organizadas em pares. Esses pares são então hash, produzindo novas saídas que também são organizadas em pares e hash novamente. O processo é repetido até que um único hash seja produzido, conhecido como hash raiz ou raiz da [árvore Merkle](/merkle-tree).

O hash raiz é então combinado com o hash do bloco confirmado anteriormente, juntamente com um número pseudo-aleatório chamado [nonce](/nonce) (mais alguns outros parâmetros). Esses elementos são então hash, produzindo o hash de bloco para esse bloco candidato.

No entanto, o minerador só terá sucesso se a saída resultante (hash do bloco) para o bloco candidato estiver abaixo de um valor predeterminado (destino). consequentemente, o processo é baseado em tentativa e erro e eles precisam executar várias funções de hash com diferentes nonces para encontrar um resultado válido. O primeiro minerador a encontrar um hash válido valida seu bloco candidato e recebe a recompensa do bloco. Todo o processo leva dez minutos, em média.

Depois que um bloco é validado, ele é adicionado ao blockchain e os mineradores começam a trabalhar no próximo bloco. O hash válido produzido pelos mineradores funciona como prova de seu trabalho e é por isso que o algoritmo de consenso do Bitcoin é chamado de Prova de Trabalho. Cada bloco confirmado possui um hash de bloco exclusivo que atua como um identificador.

A [recompensa do bloco](/block-reward) é definida pelo protocolo Bitcoin e diminui a cada 210.000 blocos (cerca de quatro anos). Inicialmente, a recompensa do bloco era de 50 BTC e agora é de 12,5 BTC.

