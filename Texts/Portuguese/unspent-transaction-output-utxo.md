---
keywords: Crypto
title: Saída de transação não gasta (UTXO)
description: Saída de transação não gasta (UTXO). Uma saída criada em uma transação, que deve ser referenciada em uma transação futura para gastar fundos.
---

# Saída de transação não gasta (UTXO)
Uma saída de transação não gasta (UTXO) refere-se a uma saída de transação que pode ser usada como entrada em uma nova transação. Em essência, os UTXOs definem onde cada transação de blockchain começa e termina. O modelo UTXO é um elemento fundamental do Bitcoin e de muitas outras criptomoedas.

Em outras palavras, as transações de criptomoedas são feitas de entradas e saídas. Sempre que uma transação é feita, um usuário usa um ou mais UTXOs para servir como entrada(s). Em seguida, o usuário fornece sua assinatura digital para confirmar a propriedade sobre as entradas, que finalmente resultam em saídas. Os UTXOs consumidos agora são considerados "gastos" e não podem mais ser usados. Enquanto isso, as saídas da transação se tornam novos UTXOs – que podem ser gastos em uma nova transação posteriormente.

Isso provavelmente é melhor explicado com um exemplo. Alice tem 0,45 BTC em sua carteira. Esta não é uma fração de uma moeda como poderíamos conceituar. É mais uma coleção de UTXOs. Especificamente, dois UTXOs no valor de 0,4 BTC e 0,05 BTC – saídas de transações anteriores. Agora vamos imaginar que Alice precisa fazer um pagamento para Bob de 0,3 BTC.

Sua única opção aqui é quebrar a unidade de 0,4 BTC e enviar 0,3 BTC para Bob e 0,1 BTC de volta para ela. Ela normalmente recuperaria menos de 0,1 BTC devido às taxas de mineração, mas vamos simplificar e deixar o minerador de fora.

Alice cria uma transação que essencialmente diz à rede: pegue meu UTXO de 0,4 BTC como entrada, divida-o, envie 0,3 BTC dele para o endereço de Bob e devolva o 0,1 BTC para meu endereço. O 0,4 BTC agora é uma saída gasta e não pode ser reutilizada. Enquanto isso, dois novos UTXOs foram criados (0,3 BTC e 0,1 BTC).

Observe que separamos um UTXO neste exemplo, mas se Alice tivesse que pagar 0,42 BTC, ela poderia facilmente combinar seus 0,4 BTC com outros 0,05 BTC para produzir um UTXO no valor de 0,42 BTC, enquanto retornava 0,03 BTC para si mesma.

Resumindo, o modelo UTXO serve como mecanismo do protocolo para acompanhar as moedas onde estão em um determinado momento. De certa forma, eles funcionam como cheques: são endereçados a usuários específicos (ou melhor, seus [endereços públicos](/address) ). UTXOs não podem ser gastos em parte – em vez disso, novos cheques devem ser criados a partir do antigo e repassados de acordo.

