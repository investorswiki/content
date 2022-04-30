---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Contrato de bloqueio de tempo com hash (HTLC)
description: Contrato de bloqueio de tempo com hash (HTLC). Refere-se a um recurso especial usado para criar contratos inteligentes que podem modificar os canais de pagamento.
---

# Contrato de bloqueio de tempo com hash (HTLC)
O termo Hashed TimeLock Contract (HTLC) refere-se a um recurso especial que é usado para criar [contratos inteligentes](/smart-contract) capazes de modificar os canais de pagamento. Tecnicamente, o recurso HTLC permite a implementação de transações com limite de tempo entre dois usuários. Na prática, o destinatário de uma transação HTLC deve reconhecer o pagamento enviando uma prova criptográfica dentro de um prazo especificado (número de blocos). Se o destinatário perder ou não reivindicar o pagamento, os fundos serão devolvidos ao remetente original.

O recurso HTLC é aplicado em canais de pagamento bidirecionais e roteados para permitir transferências seguras de fundos em vários canais, sem exigir confiança em nenhum dos intermediários.

Existem dois elementos-chave que distinguem o HTLC das transações de criptomoeda padrão, que são:

- Hashlock: função que restringe o gasto de recursos até que determinado dado seja divulgado publicamente (como prova criptográfica). Essa prova também pode ser chamada de pré-imagem do hashlock. A pré-imagem é simplesmente a informação que é usada para gerar o hashlock e, posteriormente, desbloquear seus fundos.

- Timelock: é uma função que restringe o gasto de fundos até um determinado momento (ou altura do bloco) no futuro. Isso pode ser alcançado no Bitcoin, por exemplo, usando funções como CheckLockTimeVerify ou CheckSequenceVerify.

A Bitcoin Lightning Network está entre os casos de uso mais populares de contratos com bloqueio de tempo com hash. Ao implementar o HTLC nos canais de pagamento, os fundos podem ser transacionados de usuário para usuário por meio de canais de pagamento interconectados, sem exigir nenhum nível de confiança. Esse processo é conhecido como roteamento de rede. Ele permite que Alice troque fundos com Carol mesmo que não estejam diretamente conectadas por meio de um canal de pagamento. Os HTLCs permitem que Alice envie seus fundos para Carol por meio de outros participantes da rede (por exemplo, Bob) - e os recursos de hashlock e timelock garantem que Bob não possa interceptar os fundos.

Além de serem usados na Lightning Network, os HTLCs também podem ser úteis em outros contextos, como [trocas atômicas de cadeia cruzada](/atomic-swaps),. contratos inteligentes financeiros e custódia e muito mais.

## Destaques

- Os pagamentos usando HTLCs são condicionais e, portanto, têm benefícios de eficiência para transações de blockchain. Essa propriedade torna os HTLCs uma ferramenta fundamental usada pela rede de raios.

- Esse tipo de contrato inteligente exige que o destinatário de um pagamento o reconheça dentro de um determinado período de tempo ou o perca.

- Um contrato de timelock com hash (HTLC) reduz o risco de contraparte em contratos inteligentes descentralizados, criando efetivamente um depósito baseado em tempo que utiliza uma senha criptográfica.

## PERGUNTAS FREQUENTES

### Quanto custa um contrato inteligente?

Na blockchain Ethereum, uma implantação de contrato inteligente consome gás, que custa Gwei (uma denominação mais baixa de éter). Dependendo da complexidade do contrato, pode custar bilhões de Gwei para implantar um contrato inteligente. Contratos menos complexos, como uma simples troca, são muito mais baratos.

### O que é um contrato inteligente?

Um contrato inteligente é um programa armazenado em um blockchain que é executado quando condições específicas são atendidas.

### O que é um contrato de timelock?

Um contrato de timelock é um contrato inteligente embutido em um blockchain que executa uma transação em um momento específico. Eles são usados em contratos de timelock com hash e canais de pagamento onde são necessários tempos de pagamento específicos.

### O Bitcoin tem contratos inteligentes?

Inicialmente, o blockchain do Bitcoin não era capaz de executar contratos inteligentes. No entanto, a atualização do Taproot em 2021 permitiu que o blockchain usasse contratos inteligentes nas transações.

