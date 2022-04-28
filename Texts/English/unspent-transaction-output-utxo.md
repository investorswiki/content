---
keywords: Crypto
title: Unspent Transaction Output (UTXO)
description: Unspent Transaction Output (UTXO). An output made in a transaction, which must be referred to in a future transaction to spend funds.
---

# Unspent Transaction Output (UTXO)
An unspent transaction output (UTXO) alludes to a transaction output that can be utilized as contribution to another transaction. Basically, UTXOs characterize where each blockchain transaction starts and wraps up. The UTXO model is a fundamental element of Bitcoin and numerous other digital forms of money.
All in all, cryptocurrency transactions are made of data sources and outputs. Whenever a transaction is made, a client takes at least one UTXOs to act as the input(s). Next, the client gives their digital signature to affirm ownership over the data sources, which at last outcome in outputs. The UTXOs consumed are currently thought of "spent," and can at this point not be utilized. In the mean time, the outputs from the transaction become new UTXOs - which can be spent in another transaction later.
This is presumably better made sense of with a model. Alice has 0.45 BTC in her wallet. This isn't a small portion of a coin as we would conceptualize it. It's fairly an assortment of UTXOs. Specifically, two UTXOs worth 0.4 BTC, and 0.05 BTC - outputs from past transactions. Presently we should envision that Alice needs to make a payment to Bob of 0.3 BTC.
Her main option here is to break up the 0.4 BTC unit and to send 0.3 BTC to Bob, and 0.1 BTC back to herself. She would ordinarily recover under 0.1 BTC due to mining fees, however we should rearrange and leave the miner out.
Alice makes a transaction that basically tells the network: take my 0.4 BTC UTXO as an info, break it up, send 0.3 BTC of it to Bob's address and return the 0.1 BTC to my address. The 0.4 BTC is currently a spent output, and can't be reused. In the interim, two new UTXOs have been made (0.3 BTC and 0.1 BTC).
Note that we separated an UTXO in this model, yet assuming Alice needed to pay 0.42 BTC, she could just as effectively have combined her 0.4 BTC with another 0.05 BTC to create an UTXO worth 0.42 BTC, while returning 0.03 BTC to herself.
Summarizing, the UTXO model fills in as the convention's mechanism for keeping track of where coins are at some random time. It might be said, they operate similar as checks: they're addressed to specific users (or rather, their public [addresses](/address)). UTXOs can't be spent in that frame of mind all things being equal, new checks must be made from the former one and passed along in like manner.
