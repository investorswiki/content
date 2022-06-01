---
keywords: Crypto
title: Bloco Candidato
description: Bloco Candidato. Um bloco temporário criado por um nó de mineração (minerador) para adicionar ao blockchain para receber as recompensas do bloco.
---

# Bloco Candidato
Em poucas palavras, um bloco candidato é um bloco que um nó de mineração (minerador) está tentando minerar para receber a recompensa do bloco. Assim, um bloco candidato pode ser descrito como um bloco temporário que será validado ou descartado pela rede. Os mineradores competem entre si para validar o próximo bloco e adicioná-lo ao blockchain, mas primeiro eles precisam criar um bloco candidato para participar da competição de mineração.

Os blocos candidatos são criados por mineradores coletando e organizando várias transações não confirmadas do pool de memória. As transações são então hash para formar uma estrutura de [árvore Merkle](/merkle-tree),. que eventualmente produzirá uma raiz Merkle (ou hash raiz). A raiz Merkle é um único hash que representa todos os hashes anteriores dessa árvore e, portanto, todas as transações que foram incluídas nesse bloco específico.

O hash raiz - junto com o hash do bloco anterior e um número aleatório chamado [nonce](/nonce) - é então colocado no cabeçalho do bloco. O cabeçalho do bloco é então hash pelo minerador, gerando uma saída com base nesses componentes (hash raiz, hash do bloco anterior e nonce) mais alguns outros elementos. A saída resultante é o hash do bloco e servirá como identificador exclusivo do bloco recém-gerado (bloco candidato).

Para ser considerada válida, a saída (hash de bloco) deve começar com um certo número de zeros (menos que um valor alvo definido pelo protocolo). Isso significa que o processo de mineração é baseado em várias tentativas (tentativa e erro), pois os nós de mineração precisam executar uma infinidade de funções de hash com diferentes valores de nonce até que um hash de bloco válido seja produzido. O hash do bloco produzido é o que prova que o minerador fez seu trabalho (daí a Prova de Trabalho).

Depois que um minerador encontra um hash de bloco válido, seu bloco candidato será transmitido para o restante dos nós da rede, que verificarão a autenticidade do hash. Se tudo estiver bem, o bloco candidato será registrado no blockchain. Neste ponto, cada nó de validação atualiza sua cópia dos dados do blockchain para refletir o bloco minerado recente, e o minerador receberá a recompensa do bloco.

