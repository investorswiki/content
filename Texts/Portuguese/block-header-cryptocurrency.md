---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Cabeçalho do bloco (criptomoeda)
description: cabeçalho do bloco. Uma seção em um bloco contendo metadados e um resumo das transações do bloco. Esta é a informação hash durante a mineração.
---

# Cabeçalho do bloco (criptomoeda)
O cabeçalho do bloco é uma seção em um [bloco](/block) que serve como um resumo do restante do bloco. Ele é composto de todos os [metadados](/metadata) – como a hora e a [dificuldade](/difficulty) em que o bloco foi [minerado](/mining),. a [raiz Merkle](/merkle-tree) das transações incluídas e o [nonce](/nonce). Também está presente o [hash](/hash) do bloco anterior , que é o que nos permite criar a “cadeia” de blocos. Em essência, o cabeçalho do bloco contém quaisquer dados que não sejam a própria lista de transações brutas.

Um cabeçalho de bloco é o hash dos mineradores para tentar tornar o bloco válido. Isso é muito mais eficiente do que fazer o hash de todo o bloco, que pode ser composto de milhares de transações. Seria muito mais complicado para um minerador alterar o nonce e refazer um bloco inteiro de 2 MB para cada tentativa. Compare isso com os cabeçalhos de bloco do Bitcoin, por exemplo, que têm um comprimento fixo de 80 bytes.

Os cabeçalhos de bloco são ótimos do ponto de vista da mineração, mas devido ao seu tamanho pequeno, também são ideais para clientes leves. O blockchain do Bitcoin é muito grande para dispositivos como smartphones armazenarem. Se a cadeia tivesse 100.000 blocos de 1 MB, você consumiria 100 GB de espaço. Mas com apenas os cabeçalhos de bloco para esses mesmos blocos, você ocuparia apenas 0,008 GB ou 8 MB.

Dessa forma, dispositivos com menos largura de banda ou espaço de armazenamento ainda podem realizar algum grau de validação. Como a raiz Merkle encapsula todas as transações, eles podem verificar posteriormente se uma transação foi incluída em um bloco específico. Isso tem um custo – o usuário ainda deve confiar em terceiros para fornecer as informações necessárias. Com isso dito, os clientes leves são preferíveis a um sistema em que os usuários não realizam nenhuma verificação.

##Destaques

- Eles são criptografados para criar uma prova de trabalho para recompensas de mineração.

- Cabeçalhos de bloco identificam blocos individuais em uma blockchain.

- Os blocos são colocados em camadas verticalmente, começando com o “bloco de gênese”.

- O número da versão do bitcoin ajuda você a acompanhar as alterações no protocolo.

- Cada cabeçalho de bloco contém três conjuntos de metadados de bloco e vários componentes individuais.

