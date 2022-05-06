---
keywords: Personal Finance,Banking
title: Código de autenticação de mensagem (MAC)
description: Um código de autenticação de mensagem (MAC), ou tag, é um código de segurança digitado pelo usuário de um computador para acessar contas ou portais.
---

# Código de autenticação de mensagem (MAC)
## O que é um código de autenticação de mensagem?

Um código de autenticação de mensagem (MAC), ou **tag,** é um código de segurança digitado pelo usuário de um computador para acessar contas ou portais. Este código é anexado à mensagem ou solicitação enviada pelo usuário. Os códigos de autenticação de mensagem (MACs) anexados à mensagem devem ser reconhecidos pelo sistema receptor para conceder acesso ao usuário.

## Entendendo o código de autenticação de mensagem (MAC)

Os códigos de autenticação de mensagem (MACs) são comumente usados em [transferências eletrônicas de fundos](/electronic-funds-transfer-act) (EFTs) para manter a integridade das informações. eles confirmam que uma mensagem é autêntica; que realmente vem, em outras palavras, do remetente declarado e não sofreu nenhuma alteração no caminho. Um verificador que também possui a chave pode usá-la para identificar alterações no conteúdo da mensagem em questão.

Os códigos de autenticação de mensagens geralmente são necessários para acessar qualquer tipo de conta financeira. Bancos, corretoras, sociedades fiduciárias e qualquer outro depósito, investimento ou companhia de seguros que ofereça acesso online podem empregar esses códigos. Eles são um componente vital da criptografia financeira.

## Algoritmos usados para gerar MACs

Três algoritmos normalmente compreendem um MAC: um algoritmo de geração de chave, um algoritmo de assinatura e um algoritmo de verificação. O algoritmo de geração de chave escolhe uma chave aleatoriamente. O algoritmo de assinatura envia uma tag quando recebe a chave e a mensagem. o algoritmo de verificação é usado para verificar a autenticidade da mensagem quando dada a chave e tag; ele retornará uma mensagem de **aceito** se a mensagem e a tag forem autênticas e inalteradas, mas, caso contrário, retornará uma mensagem de **rejeitado.**

Por exemplo, o remetente envia uma mensagem, como um EFT, por meio do algoritmo MAC, que gera uma chave e anexa uma etiqueta de dados MAC à mensagem. O destinatário recebe a mensagem, a executa de volta pelo algoritmo MAC com a mesma chave e obtém uma segunda etiqueta de dados. Eles então compararão esta etiqueta de dados MAC com a primeira anexada à mensagem quando ela foi transmitida. Se o código for o mesmo em ambas as extremidades, o destinatário pode assumir com segurança que a integridade dos dados da mensagem está intacta. Se não, no entanto, significa que a mensagem foi alterada, adulterada ou forjada.

No entanto, a própria mensagem deve conter alguns dados que garantam que esta mensagem só possa ser enviada uma vez. Por exemplo, um MAC, carimbo de data/hora ou número de sequência de uso único pode ser usado para garantir que a mensagem possa ser enviada apenas uma vez. Caso contrário, o sistema pode ficar vulnerável a um ataque de repetição, no qual um invasor intercepta a mensagem depois de decodificada e a retransmite posteriormente, replicando os resultados originais e se infiltrando no sistema.

## Códigos de integridade da mensagem (MICs)

Às vezes, o termo código de integridade da mensagem (MIC) será usado em vez de MAC. Isso é feito com mais frequência no setor de comunicações, onde MAC tradicionalmente significa endereço de controle de acesso à mídia (endereço MAC). No entanto, MIC também pode ser usado para se referir ao **digest da mensagem**, que não usa chaves secretas da mesma maneira que um MAC e não pode oferecer o mesmo nível de segurança sem criptografia adicional.

