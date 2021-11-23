---
keywords: Investing,Cryptocurrency,Blockchain
title: Consenso de Hashgraph
description: O consenso de hashgraph funciona de maneira diferente dos mecanismos de consenso de blockchain mais conhecidos. Saiba mais sobre ele e como funciona.
---

# Consenso de Hashgraph
## O que é Consenso de Hashgraph?

O consenso de hashgraph é uma alternativa – ou a próxima geração – da tecnologia por trás dos mecanismos de consenso de blockchain. Em vez de usar o poder computacional de grandes redes para verificar transações, as transações são registradas e confirmadas por meio de um protocolo que usa comunicação de nó.

Um hashgraph é um livro-razão descentralizado da mesma forma que um blockchain. Ele armazena informações, protege-as com criptografia, limita o acesso e usa os dados armazenados como verificação. No entanto, uma rede de hashgraph atinge o consenso de uma maneira muito diferente da blockchain.

O consenso de hashgraph é alcançado usando conceitos chamados "fofocas", "fofocas sobre fofocas" e votação virtual. Os designers do sistema relatam que ele resolve os problemas inerentes aos [algoritmos de construção de consenso](/algorithm),. como [prova de trabalho](/proof-work) (PoW), em termos de melhor velocidade e maior eficiência.

> Consenso de hashgraph — fofocas, fofocas sobre fofocas e votação virtual — é o mecanismo que o livro-razão distribuído Hedera usa para validar e confirmar transações.

>

## Entendendo o Consenso do Hashgraph

Hashgraph é uma alternativa ao blockchain. Semelhante a um blockchain, ele armazena dados e os criptografa. Um hash é gerado para informações de transação e novas transações ou dados são adicionados e construídos. No entanto, um blockchain é um livro-razão que consiste em blocos de dados. Cada bloco é vinculado ao bloco anterior usando seus dados, verificados por uma rede de validadores para criar o próximo bloco. Este processo cria uma cadeia. Um hashgraph não é uma cadeia — todas as informações são mantidas em um livro-razão criptografado e todos os usuários participam do processo de validação, não apenas os validadores.

Por exemplo, Alice cria uma transação com Bob e todas as informações que ela conhece são fornecidas a ele. Bob então faz uma transação com Kris. Todas as informações que Bob tem são comunicadas a Kris. Kris faz transações com Eli e tudo o que ela sabe é transferido. Isso continua em toda a rede, com a cadeia essencialmente fofocando sobre os eventos que estão ocorrendo. Cada nó sabe o que todos os outros nós sabem, então não há necessidade de validação computacional.

À medida que a fofoca se espalha de usuário para usuário, a rede usa algoritmos e automação para garantir que o estado do livro de hashgraph seja atualizado e o mesmo.

### Fofoca

As informações sobre os dados são chamadas de "fofocas". As estruturas de dados contidas em uma transação são:

- Um carimbo de data/hora

- Mais transações ou zeros

- Dois hashes dos contêineres pai

- Uma assinatura criptografada.

Os dois hashes são os últimos eventos de dois nós de sincronização que comparam suas informações. Os nós estão continuamente criando eventos e sincronizando.

> Hashgraph—o livro-razão—é mais eficiente que blockchain porque nenhuma energia é desperdiçada em blocos que não são aceitos. Todas as informações são mantidas em um hashgraph.

>

### Fofocas Sobre Fofocas

As informações sobre dados de transações são chamadas de "fofocas sobre fofocas". As informações são sincronizadas na rede de hashgraph usando um evento chamado "sincronização de fofocas". Uma sincronização de fofocas é um histórico colaborativo de "eventos de fofocas" em todo o hashgraph. Dessa forma, os dados não podem ser alterados ou adulterados, e há consenso.

### Votação Virtual

A votação virtual ocorre quando os nós comparam eventos e chegam a um consenso por meio de um algoritmo de votação. Veja como funciona — uma transação recebe um carimbo de data/hora conforme um nó a recebe. À medida que passa para os outros nós da rede, é atribuído a ele um carimbo de data/hora que é uma mediana de todos os carimbos de data/hora dessa transação recebidos pelos nós da rede. A mediana atua como resultado da votação. Isso cria um sistema de transação mais justo do que um blockchain porque a rede decide, não um nó.

### Tolerância ao erro

Tal como acontece com a maioria dos livros e blockchain distribuídos, sempre há uma chance de que um participante da rede não seja honesto. Pode haver atrasos na comunicação ou latência da rede que fazem com que os nós não se comuniquem corretamente.

Mecanismos de consenso são projetados para lidar com essas falhas definindo critérios de tolerância a falhas. Os desenvolvedores precisam considerar e levar em conta os maus atores, conexões ruins, latência de rede e outros problemas de rede. O consenso de hashgraph pode tolerar um terço da rede agindo maliciosamente. É supostamente tolerante a falhas bizantinas assíncronas - o nível de segurança mais alto - o que significa que os nós honestos em uma rede continuam operando mesmo se houver agentes mal-intencionados.

## Como o Hashgraph é diferente do Blockchain?

Hashgraph é uma estrutura de dados que mantém os registros de quem disse a quem o quê e em que ordem eles o fizeram. É um histórico colaborativo de eventos de fofocas à medida que os participantes adicionam e compartilham informações, o que valida as transações muito mais rapidamente do que um blockchain.

Blockchain adiciona informações de transações anteriores a novas informações de transações e as criptografa. Um terceiro é necessário para validar as transações entre as partes. Hashgraph não precisa desse processo lento por causa do protocolo de fofocas.

> O consenso de hashgraph é muito mais rápido que os mecanismos de consenso de blockchain, com tempos médios de confirmação de transação em segundos em vez de minutos.

>

Bitcoin e muitas outras criptomoedas têm problemas com o tempo das mensagens. No entanto, a tolerância a falhas bizantinas assíncronas do hashgraph supera o problema do tempo das mensagens, assumindo que as mensagens perdidas ou atrasadas eventualmente chegarão aos seus destinos.

Por exemplo, se duas transações ocorrerem simultaneamente, uma rede blockchain escolhe em qual ordem as transações ocorreram. Em alguns blockchains, as taxas de transação priorizam a confirmação. Outras redes podem decidir qual transação é confirmada com base em quantos tokens um validador apostou. Nesses blockchains, um nó influencia o resultado.

O consenso de hashgraph elimina a influência que um nó ou um grupo de nós pode ter nas transações. Como há um carimbo de data/hora em cada transação e cada transação é comunicada a toda a rede, os problemas de tempo de transação são resolvidos.

## Destaques

- O sistema de contabilidade distribuído de hashgraph não recebeu ampla adoção pela comunidade de criptografia.

- O consenso de hashgraph usa informações sobre informações em vez do conteúdo em si para criar consenso.

- As informações primárias no hashgraph são chamadas de "fofocas" e as informações secundárias são chamadas de "fofocas sobre fofocas".

## PERGUNTAS FREQUENTES

### Como funciona o consenso de Hashgraph?

O consenso de hashgraph funciona usando carimbos de data e hora de consenso e "fofocas", em que cada nó comunica tudo o que sabe a nós aleatórios em "eventos de fofocas".

### O que é Consenso de Hashgraph?

O consenso de hashgraph é um mecanismo usado em um ledger distribuído de hashgraph para validar transações.

### O Hashgraph substituirá o Blockchain?

O Hashgraph foi projetado para ser – e comercializado como – uma melhoria na tecnologia blockchain, mas ainda não se sabe se irá substituí-lo. Ainda não tem tanto interesse e adoção do desenvolvedor quanto a tecnologia blockchain.

