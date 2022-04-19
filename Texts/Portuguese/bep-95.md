---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 é uma proposta de evolução da Binance que introduz um mecanismo de gravação em tempo real para a Binance Smart Chain. Isso torna a tokenômica do BNB mais dinâmica e descentralizada.
---

# BEP-95
BEP-95 é uma proposta de evolução da Binance que introduz um mecanismo de gravação em tempo real para a Binance Smart Chain. Ele foi introduzido para tornar a tokenômica do BNB ainda mais dinâmica e descentralizar ainda mais a rede.

Com o BEP-95, a rede queimará uma proporção fixa das taxas de gás de cada bloco que os validadores coletam. A proporção exata será determinada por meio dos mecanismos de governança do BSC. As queimadas ocorrerão mesmo depois que o BSC atingir sua meta de 100 milhões de BNB. Ao reduzir a oferta de BNB, uma pressão ascendente é colocada no preço da moeda. O BEP também pode diminuir a quantidade de delegantes e validadores de BNB recebidos. No entanto, com a pressão ascendente dos preços, o valor fiduciário também pode aumentar, compensando qualquer redução nas moedas.

Para implementar isso tecnicamente, a rede coleta as taxas de gás de cada bloco e as divide entre dois contratos inteligentes:

**1. Contrato de Recompensa do Sistema.** 1/16 das taxas de gás entrarão no Contrato de Recompensa do Sistema até atingir um máximo de 100 BNB. Essas moedas serão usadas como subsídios para pacotes de cadeia cruzada.

**2. Contrato ValidatorSet.** Todas as outras taxas de gás entrarão no Contrato ValidatorSet e serão compartilhadas diariamente com delegantes e validadores via Binance Chain.

Para realizar uma gravação, o Contrato ValidatorSet possui uma variável burnRatio. Ao finalizar cada bloco, um validador assinará uma transação transferindo suas taxas de gás para os contratos inteligentes. A função de depósito contém uma lógica de queima que aciona a fórmula simples: burnRatio * gasFee. Esta soma será então transferida para o endereço de gravação. O burnRatio será inicialmente definido em 10%.

Os validadores do BSC poderão votar por meio de propostas para alterar o valor do burnRatio. Esse mecanismo de governança ocorre na Binance Chain, e qualquer membro da comunidade pode enviar uma proposta para análise com um depósito mínimo de 2.000 BNB. Todos os BNB apostados em uma proposta e em uma votação são devolvidos após a decisão ter sido tomada. O quórum é atingido em 50% e a mudança será implementada imediatamente por meio de comunicação entre cadeias.

