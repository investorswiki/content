---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Criptomoeda)
description: Uma raiz Merkle contém informações sobre cada hash de transação que já esteve em um bloco específico em uma blockchain.
---

# Merkle Root (Criptomoeda)
## O que é uma raiz de Merkle?

Uma raiz Merkle é o [hash](/hash) de todos os hashes de todas as transações que fazem parte de um bloco em uma rede [blockchain](/blockchain).

## Entendendo uma Raiz de Merkle

Um blockchain é composto por vários blocos que estão ligados uns aos outros (daí o nome blockchain). Uma árvore de hash, ou a [árvore de Merkle](/merkle-tree),. codifica os dados do blockchain de maneira eficiente e segura. Ele permite a verificação rápida de dados do blockchain, bem como o movimento rápido de grandes quantidades de dados de um nó de computador para outro na rede blockchain peer-to-peer.

Cada transação que ocorre na rede blockchain tem um hash associado a ela. No entanto, esses hashes não são armazenados em uma ordem sequencial no bloco, mas na forma de uma estrutura semelhante a uma árvore, de modo que cada hash seja vinculado ao seu pai seguindo uma relação semelhante a uma árvore pai-filho.

Como existem inúmeras transações armazenadas em um bloco específico, todos os hashes de transação no bloco também são hash, o que resulta em uma raiz Merkle.

Por exemplo, considere um bloco de sete transações. No nível mais baixo (chamado de nível folha), haverá quatro hashes de transação. No nível um acima do nível folha, haverá dois hashes de transação, cada um dos quais se conectará a dois hashes que estão abaixo deles no nível folha. No topo (nível dois), haverá o último hash de transação chamado root, e ele se conectará aos dois hashes abaixo dele (no nível um).

Efetivamente, você obtém uma árvore binária de cabeça para baixo, com cada nó da árvore conectando-se a apenas dois nós abaixo dela (daí o nome "árvore binária"). Ele tem um hash raiz no topo, que se conecta a dois hashes no nível um, cada um dos quais se conecta novamente aos dois hashes no nível três (nível folha), e a estrutura continua dependendo do número de hashes de transação.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

O hashing começa nos nós de nível mais baixo (nível de folha) e todos os quatro hashes são incluídos no hash de nós que estão vinculados a ele no nível um. Da mesma forma, o hash continua no nível um, o que leva os hashes de hashes a atingir níveis mais altos, até atingir o único hash raiz superior.

Esse hash raiz é chamado de raiz Merkle e, devido à ligação de hashes em forma de árvore, ele contém todas as informações sobre cada hash de transação que existe no bloco. Ele oferece um valor de hash de ponto único que permite validar tudo o que está presente nesse bloco.

Por exemplo, se alguém tiver que verificar uma transação que afirma ter vindo do bloco #137, basta verificar a árvore Merkle do bloco, sem se preocupar em verificar qualquer coisa em qualquer outro bloco da blockchain, como o bloco #136 ou o bloco # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Digite a raiz Merkle, que agiliza ainda mais a verificação. Como ele carrega todas as informações sobre a árvore inteira, basta verificar esse hash de transação, seu nó-irmão (se existir), e depois prosseguir para cima até chegar ao topo.

Essencialmente, a árvore Merkle e o mecanismo raiz Merkle reduzem significativamente os níveis de hash a serem executados, permitindo verificações e transações mais rápidas.

##Destaques

- As raízes Merkle são fundamentais para a computação necessária para manter criptomoedas como bitcoin e ether.

- As raízes Merkle são usadas em criptomoedas para garantir que os blocos de dados transmitidos entre pares em uma rede ponto a ponto estejam inteiros, intactos e inalterados.

- Uma raiz de Merkle é uma maneira matemática simples de verificar os dados em uma árvore de Merkle.

