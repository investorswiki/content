---
keywords: Crypto
title: Metade
description: Metade. Quando a recompensa em bloco de um criptoativo cai para metade do que era antes; isso é usado para criar uma taxa de emissão decadente.
---

# Metade
No espaço das criptomoedas, o termo halving refere-se a um processo que reduz a taxa de emissão de novas moedas. Mais precisamente, o halving é a redução periódica do subsídio do bloco fornecido aos mineradores. O halving garante que um criptoativo seguirá uma taxa de emissão constante até que sua [oferta máxima](/maximum-supply) seja atingida.

Quando se trata de Bitcoin, novas moedas estão sendo geradas continuamente como parte da [recompensa do bloco](/block-reward) (que é composta pelo subsídio do bloco mais taxas de transação). Portanto, toda vez que um minerador “descobre” e valida com sucesso um novo [bloco](/block),. ele ganha moedas recém-criadas como compensação por seu trabalho.

Portanto, o processo de [mineração](/mining) é o que introduz novos [Bitcoins](/bitcoin) no sistema, e isso é feito em um ritmo previsível e controlado. Novos blocos de Bitcoin são extraídos, em média, a cada 10 minutos, e o subsídio do bloco segue uma taxa de declínio controlada. Assim, o halving é o que garante que o subsídio por bloco diminua em 50% a cada 210.000 blocos (aproximadamente a cada quatro anos).

Começando no bloco de [gênese](/genesis-block),. o subsídio de bloco do Bitcoin foi inicialmente definido como 50 BTC. Em seguida, foi reduzido para 25 BTC em 2012 e para 12,5 BTC em 2016. O próximo halving deve ocorrer por volta de maio de 2020, reduzindo o subsídio do bloco para 6,25 BTC. Após 32 halvings, o processo é interrompido e não serão criados mais Bitcoins. Neste ponto, a oferta máxima de 21 milhões de BTC será atingida.

[Acompanhe o Halving do Bitcoin](/halving)

O halving é uma parte importante do protocolo Bitcoin e, como o código é de código aberto, qualquer pessoa pode vê-lo. Por exemplo, a implementação do Bitcoin Core está disponível no [GitHub](/github) e uma das seções de código que define o subsídio do bloco se parece com isso:

CAmount GetBlockSubsidy(int nHeight, const Consenso::Params& consensoParams)

{

int halvings = nHeight / consensoParams.nSubsidyHalvingInterval;

// Força a recompensa do bloco para zero quando o deslocamento para a direita é indefinido.

se (metades >= 64)

retornar 0;

CAmount nSubsídio = 50 * MOEDA;

// O subsídio é cortado pela metade a cada 210.000 blocos, o que ocorrerá aproximadamente a cada 4 anos.

nSubsídio >>= metades;

retornar nSubsídio;

}

