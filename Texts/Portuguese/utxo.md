---
keywords: Investing,Cryptocurrency,Bitcoin
title: Modelo UTXO
description: UTXOs são a saída não gasta nas transações no nível do banco de dados em algumas criptomoedas. Saiba mais sobre UTXOs e como eles funcionam.
---

# Modelo UTXO
## Qual é o modelo UTXO?

Uma saída de transação não gasta (UTXO) é o termo técnico para a quantidade de [moeda digital](/currency) que permanece após uma transação de criptomoeda. Você pode pensar nisso como o troco que você recebe depois de comprar um item, mas não é uma denominação mais baixa da moeda – é uma saída de transação no banco de dados gerado pela rede para permitir transações de troco não exatas.

A parte de toda a criptomoeda não gasta em uma transação é usada como medida contábil. Como a contabilidade de dupla entrada, cada transação tem uma entrada e uma saída.

Por exemplo, imagine que 1 BTC é um balde cheio de moedas. Cada moeda representa um UTXO. Se você comprar algo de Bob por 0,5 BTC, a rede dará a Bob todo o balde de moedas e devolverá os 0,5 BTC que você deve em "troco". Agora você tem um UTXO no valor de 0,5 BTC que não pode ser dividido em quantidades menores.

## Entendendo o modelo UTXO

UTXO é um protocolo para distribuir os bits de dados dos quais a criptomoeda é feita e pode ser difícil de entender inicialmente. Uma rede ou desenvolvedor de criptomoeda vê o UTXO de uma maneira muito diferente do que um usuário de criptomoeda do dia-a-dia.

### O que a rede vê

Uma transação de criptomoeda é uma transferência de informações dentro de um banco de dados. A criptomoeda é dividida em pequenos pedaços, que são armazenados em todo o banco de dados e chamados de saídas de transação não gastas. Quase todas as transações criam UTXO porque a maioria não está em incrementos de números inteiros.

Isso significa que o gasto não ocorre usando um único byte de dados. Em vez disso, várias frações de criptomoeda são recuperadas para atender a uma solicitação de gastos.

> UTXOs não são denominações de criptomoedas, como satoshi para Bitcoin (BTC) ou gwei para ether (ETH); no entanto, UTXOs podem ser medidos nessas denominações.

>

Quando você inicia uma transação por meio de sua carteira, os UTXOs com suas informações são localizados, desbloqueados e as informações do novo proprietário são associadas ao UTXO que você transferiu para eles. Eles são bloqueados mais uma vez, e esse usuário pode usá-los em transações pelo mesmo processo.

À medida que as transações continuam, o banco de dados é preenchido com registros de alterações de propriedade. As saídas são frações de criptomoeda que você enviou para alguém que não foi gasta. Eles são registrados no banco de dados como entradas em frações de criptomoeda.

### O que um usuário vê

Quando você decide gastar seu Bitcoin, você vê apenas o valor que gastou deduzido e o valor restante em sua carteira. Para você, é semelhante a usar uma nota de US$ 1 em um item de US$ 0,50 - você recebe o troco, coloca-o no bolso e segue seu dia.

## Objetivos do Modelo UTXO

O modelo UTXO é usado em muitas criptomoedas porque permite que os usuários rastreiem a propriedade de todas as partes dessa criptomoeda. Como as criptomoedas foram criadas com o anonimato em mente, os UTXOs são associados aos endereços públicos visíveis para toda a rede.

Os usuários não podem ser identificados a partir de sua propriedade, a menos que anunciem seu endereço, mas o modelo permite transparência por meio dos endereços.

> Uma transação codifica a transferência de valor da fonte do fundo (sua entrada) para o destino (a saída ou o destinatário).

>

### Quedas do modelo UTXO

A profusão de pequenas moedas dentro da rede de uma criptomoeda torna certas transações antieconômicas. Isso ocorre porque a transação pode custar mais do que o custo real do produto que está sendo comprado com criptomoeda. Por exemplo, não faz sentido comprar uma xícara de café de US$ 2 se a [taxa de transação](/fee) na rede do bitcoin for maior que o preço do café.

##Destaques

- Quando uma transação é concluída, quaisquer saídas não gastas são registradas em um banco de dados como entradas que podem ser usadas posteriormente para uma nova transação.

- UTXOs são processados continuamente e fazem parte do início e fim de cada transação.

- Um UTXO é a quantidade de moeda digital restante após a execução de uma transação de criptomoeda.

##PERGUNTAS FREQUENTES

### O que é UTXO em Blockchain?

UTXOs são pequenos pedaços não gastos de criptomoedas que sobraram de transações em certas criptomoedas. Eles são registrados no banco de dados UTXO e usados em transações posteriores.

### Ethereum é um UTXO?

Ethereum é uma criptomoeda, portanto não é um UTXO. Além disso, o Ethereum usa uma abordagem baseada em contas com saldos de contas, portanto, não há UTXOs na Máquina Virtual Ethereum.

### Bitcoin é um UTXO?

As saídas de transações não gastas fazem parte da tecnologia de banco de dados distribuído por trás do Bitcoin e outras criptomoedas. Bitcoin usa UTXOs, mas não é um UTXO.

