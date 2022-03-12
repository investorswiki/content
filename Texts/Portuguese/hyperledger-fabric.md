---
keywords: Investing,Cryptocurrency,Blockchain
title: Tecido do Hyperledger
description: O Hyperledger Fabric é uma plataforma para criar vários produtos, soluções e aplicativos baseados em blockchain para uso comercial.
---

# Tecido do Hyperledger
## O que é tecido Hyperledger?

O Hyperledger Fabric é uma estrutura modular de [blockchain](/blockchain) que atua como base para o desenvolvimento de produtos, soluções e aplicativos baseados em blockchain usando componentes plug-and-play destinados ao uso em empresas privadas.

O Hyperledger Fabric foi iniciado pela Digital Asset e pela IBM e agora surgiu como um empreendimento colaborativo entre setores, que atualmente está sendo hospedado pela Linux Foundation. Entre os vários projetos do Hyperledger, o Fabric foi o primeiro a sair do estágio de “incubação” e atingir o estágio “ativo” em março de 2017.

## Como o Hyperledger Fabric funciona

As redes blockchain tradicionais não podem suportar transações privadas e contratos confidenciais que são de extrema importância para as empresas. O Hyperledger Fabric foi projetado em resposta a isso como uma base modular, escalável e segura para oferecer soluções de blockchain industriais.

O Hyperledger Fabric é o mecanismo de código aberto para blockchain e cuida dos recursos mais importantes para avaliar e usar blockchain para casos de uso de negócios.

Dentro de redes industriais privadas, a identidade verificável de um participante é um requisito primário. O Hyperledger Fabric oferece suporte a associações com base na permissão; todos os participantes da rede devem ter identidades conhecidas. Muitos setores de negócios, como saúde e finanças, estão vinculados a regulamentos de proteção de dados que exigem a manutenção de dados sobre os vários participantes e seus respectivos acessos a vários pontos de dados. O Fabric dá suporte a essa associação baseada em permissão.

### Arquitetura modular

A arquitetura modular do Hyperledger Fabric separa o fluxo de trabalho de processamento de transações em três estágios diferentes: [contratos inteligentes](/smart-contracts) chamados chaincode que compreendem o processamento lógico distribuído e o acordo do sistema, pedido de transação e validação e compromisso de transação. Essa segregação oferece vários benefícios:

- Um número reduzido de níveis de confiança e verificação que mantém a rede e o processamento livres de desordem

- Escalabilidade de rede aprimorada

- Melhor desempenho geral

Além disso, o suporte do Hyperledger Fabric para plug-and-play de vários componentes permite a fácil reutilização de recursos existentes e a integração pronta de vários módulos. Por exemplo, se já existe uma função que verifica a identidade do participante, uma rede de nível empresarial simplesmente precisa conectar e reutilizar esse módulo existente em vez de construir a mesma função do zero.

Os participantes da rede têm três papéis distintos:

- Endossante

- Comissariado

- Consoante

Em poucas palavras, a proposta de transação é submetida ao peer endossante de acordo com a política de endosso pré-definida sobre o número de endossantes necessários. Após endossos suficientes pelo(s) endossante(s), um lote ou bloco de transações é entregue ao(s) comitente(s). Os committers validam que a política de endosso foi seguida e que não há transações conflitantes. Uma vez que ambas as verificações são feitas, as transações são confirmadas no livro-razão.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Fonte da imagem: IBM

Como apenas instruções de confirmação – como assinaturas e conjunto de leitura/gravação – são enviadas pela rede, a escalabilidade e o desempenho da rede são aprimorados. Apenas endossantes e committers têm acesso à transação, e a segurança é aprimorada com um número menor de participantes tendo acesso aos principais pontos de dados.

## Exemplo de tecido Hyperledger

Suponha que haja um fabricante que queira enviar chocolates para um varejista ou mercado específico de varejistas (ou seja, todos os varejistas dos EUA) a um preço específico, mas não queira revelar esse preço em outros mercados (ou seja, varejistas chineses).

Como a movimentação do produto pode envolver outras partes, como alfândega, empresa de transporte e banco financiador, o preço privado pode ser revelado a todas as partes envolvidas se uma versão básica da tecnologia blockchain for usada para suportar essa transação.

O Hyperledger Fabric resolve esse problema mantendo as transações privadas privadas na rede; apenas os participantes que precisam saber estão cientes dos detalhes necessários. O particionamento de dados no blockchain permite que pontos de dados específicos sejam acessíveis apenas para as partes que precisam saber.

## Críticas ao Hyperledger Fabric

A marca d'água do entusiasmo criptográfico quebrou em 2018 após o colapso do preço do bitcoin (que atingiu seu pico em 17 de dezembro de 2017). Afirmações excessivamente otimistas sobre o valor da nova tecnologia foram substituídas por ceticismo, e tecnologias relacionadas, incluindo o Hyperledger, também sofreram com esse ceticismo.

### Concorrentes do Hyperledger Fabric

O Hyperledger Fabric compete com outros projetos do Hyperledger, como Iroha, Indy e Sawtooth. Ele também compete com o Corda da R3, que também é um DLT privado baseado em permissão.

A empresa de serviços Blockchain Chainstack publicou um artigo em janeiro de 2020 que mostra que o desenvolvimento no Corda tem sido historicamente maior do que o desenvolvimento no Fabric, embora o desenvolvimento do Fabric tenha passado pelo Corda no terceiro trimestre de 2019, quando o Fabric mudou para o GitHub.

O relatório do Chainstack mostra que, embora haja três vezes mais desenvolvedores trabalhando no Fabric, os desenvolvedores do Corda fizeram mais de duas vezes mais contribuições de código, e os desenvolvedores do Fabric enviam muito menos código por desenvolvedor do que os desenvolvedores do Corda.

### Hyperledger Fabric não é Blockchain e não é eficiente

Várias críticas ao Hyperledger Fabric apontam que um blockchain privado baseado em permissão com os recursos do Hyperledger Fabric não é um blockchain, e as tecnologias atuais não blockchain são muito mais baratas e oferecem a mesma quantidade de segurança. Stuart Popejoy, do Cointelegraph, colocou o caso assim:

>

> A arquitetura do Fabric é muito mais complexa do que qualquer plataforma blockchain, além de ser menos segura contra adulterações e ataques. Você pensaria que um blockchain “privado” ofereceria pelo menos escalabilidade e desempenho, mas o Fabric também falha aqui. Simplificando, os pilotos criados no Fabric enfrentarão uma implantação complexa e insegura que não poderá ser dimensionada com seus negócios .

>

O Hyperledger Fabric também foi criticado por falta de resiliência. Uma equipe de pesquisadores da Sorbonne em Paris e CSIRO - Data61, agência nacional de ciências da Austrália, descobriu que atrasos significativos na rede reduziram a confiabilidade do Fabric: "[B] ao atrasar a propagação do bloco, demonstramos que o Hyperledger Fabric não fornece garantias de consistência suficientes para ser implantado em ambientes críticos. "

## Hyperledger Fabric 2.0 lançado em janeiro de 2020

Em janeiro de 2020, o Hyperledger Fabric 2.0 foi lançado para resolver algumas das críticas existentes. De acordo com Ron Miller, do Techcrunch, “as maiores atualizações envolvem forçar um acordo entre as partes antes que qualquer novo dado possa ser adicionado ao livro-razão, conhecido como governança descentralizada dos contratos inteligentes”.

Embora a atualização não seja uma mudança radical na simplicidade ou aplicabilidade do Fabric, ela demonstra que o progresso continua a ser feito no setor de criptomoedas além da mania de criptomoedas que ocorreu em 2018. Nos próximos cinco a dez anos, é esperava que o blockchain corporativo sem dúvida encontre seu uso adequado.

## Destaques

- Hyperledger é uma estrutura de contabilidade distribuída de código aberto e de nível empresarial lançada pela Linux Foundation em dezembro de 2015.

- Como o Hyperledger Fabric é privado e requer permissão para acessar, as empresas podem segregar informações (como preços), além de que as transações podem ser aceleradas porque o número de nós na rede é reduzido.

- O Fabric 2.0 foi lançado em janeiro de 2020. Os principais recursos desta versão são transações mais rápidas, tecnologia de contrato inteligente atualizada e compartilhamento de dados simplificado.

- Fabric é uma plataforma de tecnologia de contabilidade descentralizada (DLT) altamente modular que foi projetada pela IBM para uso em empresas industriais.

