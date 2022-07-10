---
keywords: Crypto
title: Halving
description: Halving. At the point when the block reward of a crypto asset, drops to one-half of what it was previously; this is utilized to make a rotting rate of issuance.
---

# Halving
In the cryptocurrency space, the term halving alludes to a cycle that lessens the issuance rate of new coins. All the more unequivocally, halving is the periodical reduction of the block subsidy gave to miners. The halving guarantees that a crypto asset will follow a consistent issuance rate until its [maximum supply](/maximum-supply) is in the long run reached.
With regards to Bitcoin, news coins are being generated constantly as part of the [block reward](/block-reward) (which is comprised of the block subsidy plus transaction fees). So every time a miner effectively "finds" and approves a new [block](/block), they earn recently made coins as compensation for their work.
So the [mining](/mining) process presents new [Bitcoins](/bitcoin) into the system, and this is finished at a predictable and controlled pace. New Bitcoin blocks are mined, on average, at regular intervals, and the block subsidy follows a controlled rotting rate. Appropriately, the halving guarantees that the block subsidy will diminish by half every 210,000 blocks (generally like clockwork).
Starting at the [genesis block](/genesis-block), Bitcoin's block subsidy was initially set as 50 BTC. Then, at that point, it was diminished to 25 BTC in 2012, and to 12.5 BTC in 2016. The following halving is expected to occur around May 2020, lessening the block subsidy to 6.25 BTC. When 32 halvings have happened, the interaction stops and no more Bitcoins will be made. As of now, the maximum supply of 21 million BTC will be reached.
[Follow alongside the Bitcoin Halving](/halving)
The halving is an important part of the Bitcoin protocol and, since the code is open-source, anybody can see it. For example, the Bitcoin Core implementation is available on [GitHub](/github), and one of the code segments that characterizes the block subsidy seems to be this:
CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensusParams)
{
 int halvings = nHeight/consensusParams.nSubsidyHalvingInterval;
 // Force block reward to zero when right shift is indistinct.
 if (halvings >= 64)
 return 0;

 CAmount nSubsidy = 50 * COIN;
 // Subsidy is cut in half every 210,000 blocks which will happen around like clockwork.
 nSubsidy >>= halvings;
 return nSubsidy;
}
