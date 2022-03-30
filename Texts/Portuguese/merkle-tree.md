---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: árvore merkle
description: árvore merkle. Uma maneira de organizar e estruturar grandes quantidades de dados para torná-lo mais simples de processar. Uma estrutura de dados baseada em hash.
---

# árvore merkle
Uma árvore Merkle é uma forma de organizar e estruturar grandes quantidades de dados para torná-los mais simples de processar. No caso de criptomoedas e [blockchain](/blockchain),. a árvore Merkle é usada para estruturar os dados das transações de uma forma menos exigente em recursos.

Quando uma transação de criptomoeda é feita em uma estrutura de árvore Merkle, ela recebe um hash e recebe um valor de hash equivalente. Depois que cada transação é hash na árvore Merkle, os valores de hash que são produzidos são emparelhados com outro valor de hash e, em seguida, hash novamente. Por exemplo, os valores de hash 'AB' e 'AC' são combinados para criar 'ABC'.

Esse processo de emparelhamento de valores de hash é repetido até que um valor de hash final seja produzido. O valor de hash final, a raiz de Merkle, fornece um resumo de todas as transações que ele contém. O resumo da raiz Merkle é então inserido no cabeçalho do bloco.

####Segurança de dados

Uma estrutura de árvore Merkle fornece um registro de fácil acesso das transações em um [bloco](/block). Portanto, é muito simples verificar se os dados de um bloco foram alterados ou adulterados. Isso é verdade porque qualquer alteração em uma transação (ou qualquer outro dado relacionado) na árvore Merkle levaria a uma raiz Merkle correspondente totalmente diferente.

#### Uso eficiente de recursos

Se as criptomoedas não usassem árvores Merkle, cada solicitação de verificação envolveria enormes quantidades de informações enviadas pela rede. Estruturar dados de transações em uma árvore Merkle é um uso muito mais eficiente de recursos. A validação de uma transação não requer uma cópia completa do ledger, pois os dados da transação com hash podem ser verificados em uma raiz Merkle, exigindo muito menos informações enviadas pelos nós e, portanto, menos poder de computação para analisar a integridade geral dos dados.

Em outras palavras, uma estrutura de árvore Merkle permite que os usuários verifiquem se uma transação individual foi incluída em um bloco sem precisar passar pelo processo de download de todo o blockchain. A tecnologia é uma ferramenta importante para as criptomoedas organizarem os dados das transações e funcionarem com a mesma eficiência. Sem as árvores Merkle, é provável que a maior demanda por recursos resulte em menos [nós](/node) participando da rede.

