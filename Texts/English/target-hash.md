---
keywords: Investing,Cryptocurrency,Altcoins
title: Target Hash
description: A target hash sets the difficulty for cryptocurrency mining utilizing a proof-of-work (PoW) blockchain system.
---

# Target Hash
## What Is a Target Hash?

In cryptocurrency mining, a target hash is a numeric value that a hashed [block header](/block-header-cryptocurrency) must be not exactly or equivalent to for another block to be granted to a miner. Block headers distinguish individual blocks in a blockchain.

Cryptocurrency mining alludes to the most common way of social occasion cryptocurrency as a reward for work that you complete. The idea of this work is to check the authenticity of a given cryptocurrency's transactions. Along these lines, cryptocurrency miners are basically auditors. At the point when you mine, you can earn cryptocurrency without putting down money for it.

The target hash is utilized in determining the difficulty of the input and can be adjusted to guarantee that blocks are handled productively. For instance, target hashes are utilized in digital currencies that utilization a proof-of-work (PoW) system to set the current [mining difficulty](/difficulty-cryptographic forms of money) (counting Bitcoin). On the off chance that a cryptocurrency involves an alternate system for mining, it may not need a target hash.

## How a Target Hash Works

[Cryptocurrencies](/cryptocurrency) depend on the utilization of [blockchains](/blockchain) that contain the history of all that cryptocurrency's transactions. These transactions are [hashed](/hash), or cryptographically encoded, into a series of alphanumeric characters. Hashing includes taking a string of data of any length and running it through an algorithm to create an output with a fixed length. The output will constantly be a similar length, paying little mind to how big or small the input is (albeit the number of changes of a hash is cosmically large). Each block will contain the hash of the previous block header.

Approving and encoding the blockchain is alluded to as [mining](/bitcoin-mining). Mining includes the utilization of computers to run hashing algorithms to deal with the latest block; the data that a client needs to mine is found in the block's header. The cryptocurrency network sets a target value for this hash — called the target hash — and miners try to figure out what this value is by testing out every conceivable value.

The block header contains the block rendition number, a timestamp, the hash utilized in the previous block, the hash of the [Merkle Root](/merkle-root-cryptocurrency), [the nonce](/nonce), and the target hash. The block is created by taking the hash of the block contents, adding a random string of numbers (the nonce), and hashing the block once more.

In the event that the hash meets the requirement of the target, the block is added to the blockchain. Spinning through solutions to figure the nonce is alluded to as [proof of work](/proof-work) (PoW), and the miner who can find the value is granted the block and paid in cryptocurrency.

## Special Considerations
### Target Hash for Bitcoin

Bitcoin utilizes the SHA-256 hash algorithm. This algorithm produces evidently random numbers in a manner that requires a predictable amount of computer processing power.

Mining a block requires the miner to deliver a value (a nonce) that, in the wake of being hashed (cryptographically encoded), is not exactly or equivalent to the one utilized in the latest block accepted by the bitcoin network. This number is between 0-(the smallest option) and 256-bits (the largest option) however is probably not going to at any point be the maximum number.

Since the target hash could be a colossal number, the miner might need to test a large number of values before finding success. A fruitless miner needs to sit tight for the next block (which is the reason miners that find a hash solution are compared to champs of a race or the lottery).

The target hash is adjusted occasionally. The hash capabilities used to produce the new target have specific properties intended to make the blockchain (and its cryptocurrency) secure. This cycle is deterministic, implying that it will deliver a similar outcome each time a similar input is utilized. It is sufficiently fast to not take too long to return a hash for the input. It likewise makes determining the input extremely challenging, especially for large numbers, and rolls out small improvements to the input bring about an altogether different hash output.

## Features
- Target hashes are utilized in digital currencies that utilization a proof-of-work (PoW) system to set the current mining difficulty (counting Bitcoin); on the off chance that a cryptocurrency involves an alternate system for mining, it may not need a target hash.
- In cryptocurrency mining, a target hash is a numeric value that a hashed block header (which is utilized to recognize individual blocks in a blockchain) must be not exactly or equivalent to for another block to be granted to a miner.
- The Bitcoin network changes the difficulty of mining by raising or bringing down the target hash to protect an average 10-minute interval between new blocks.
