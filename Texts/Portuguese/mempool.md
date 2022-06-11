---
keywords: Crypto
title: Mempool
description: Mempool. O mecanismo de um nó para acompanhar transações não confirmadas que o nó viu (mas ainda não foram adicionadas a um bloco).
---

# Mempool
Um mempool (uma contração de memória e pool) é o mecanismo de um nó de criptomoeda para armazenar informações sobre transações não confirmadas. Funciona como uma espécie de sala de espera para transações que ainda não foram incluídas em um [bloco](/block).

Quando uma transação é transmitida, ela é enviada de um nó para seus pares, que a repassam para seus pares. Isso continua até que a transação tenha sido amplamente propagada, pronta para os mineradores a adicionarem a um bloco. É vital que essa zona de buffer exista, pois as transações não são adicionadas ao blockchain imediatamente.

Os nós executarão uma série de verificações para garantir que a transação seja válida – ou seja, verificando se as assinaturas estão corretas, as saídas não excedem as entradas e os fundos ainda não foram gastos. Se não atender a essas condições, é rejeitado.

Muitas vezes falamos do mempool, mas deve-se notar que não há um pool universal compartilhado por todos os nós. Cada um é configurado de forma diferente e recebe transações em momentos diferentes. Dispositivos de baixo custo com recursos limitados podem dedicar apenas pequenas quantidades de memória para registrar transações, enquanto os de ponta podem dedicar consideravelmente mais.

Como os mineradores são motivados principalmente pelos lucros, as transações com taxas mais altas associadas são aquelas com maior probabilidade de serem descartadas do mempool primeiro quando forem confirmadas. Estimar as taxas com precisão é difícil, principalmente quando o espaço do bloco é limitado e a demanda é alta, mas o mempool fornece um ponto de partida.

Para estimar as taxas, pode-se olhar para as transações não confirmadas atuais. É lógico que os usuários não devem pagar a mais em tempos de baixa taxa de transferência. Eles também não devem pagar menos por transações sensíveis ao tempo nos horários de pico, pois pode demorar um pouco até que seja confirmado. Ao levar em consideração o spread das taxas em um determinado momento, eles podem adivinhar a rapidez com que sua transação será incluída.

