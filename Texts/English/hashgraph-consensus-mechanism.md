---
keywords: Investing,Cryptocurrency,Blockchain
title: Hashgraph Consensus
description: Hashgraph consensus works uniquely in contrast to all the more notable blockchain consensus mechanisms. Study it and how it functions.
---

# Hashgraph Consensus
## What Is Hashgraph Consensus?

Hashgraph consensus is an alternative to — or the next generation of — the technology behind blockchain consensus mechanisms. Rather than utilizing the computational power of large networks to check transactions, transactions are recorded and confirmed through a protocol that utilizes node communication.

A hashgraph is a decentralized ledger similarly a blockchain is. It stores data, protects it with cryptography, limits access, and uses the stored data as verification. Nonetheless, a hashgraph network arrives at consensus in a very different manner than a blockchain does.

Hashgraph consensus is arrived at utilizing concepts called "gossip," "gossip about gossip," and virtual voting. Fashioners of the system report that it tackles the problems inherent to consensus-building [algorithms](/algorithm, for example, [proof of work](/proof-work) (PoW), in terms of better speed and higher effectiveness.

> Hashgraph consensus — gossip, gossip about gossip, and virtual voting — is the mechanism the Hedera distributed ledger utilizations to approve and affirm transactions.
>
## Figuring out Hashgraph Consensus

Hashgraph is an alternative to blockchain. Like a blockchain, it stores data and encodes it. A hash is produced for transaction data, and new transactions or data are added and based upon. Nonetheless, a blockchain is a ledger that comprises of blocks of data. Each block is linked to the previous block utilizing its data, confirmed by a network of validators to make the next block. This interaction makes one chain. A hashgraph isn't one chain — all data is kept in an encoded ledger, and each client partakes in the validation cycle, in addition to the validators.

For instance, Alice makes a transaction with Bob, and the data she knows is all given to him. Bob then makes a transaction with Kris. The data Bob has is all conveyed to Kris. Kris transacts with Eli, and all that she knows is moved. This go on all through the network, with the chain basically gossiping about the events occurring. Each node understands what any remaining nodes know, so there is no requirement for computational validation.

As the gossip spreads from one client to another, the network utilizes algorithms and automation to guarantee the state of the hashgraph ledger is refreshed and the equivalent.

### Gossip

Data about data is called "gossip." The data structure contained in a transaction are:

- A timestamp
- More transactions or zeros
- Two hashes from the parent compartments
- A scrambled signature.

The two hashes are the last events from two synchronizing nodes that compare their data. Nodes are constantly making events and adjusting.

> Hashgraph — the ledger — is more efficient than blockchain on the grounds that no energy is squandered on blocks that are not accepted. All data is retained in a hashgraph.
>
### Gossip About Gossip

Data about transaction data is called "gossip about gossip." Information is synchronized in the hashgraph network utilizing an event called a "gossip sync." A gossip sync is a collaborative history of "gossip events" all through the hashgraph. Along these lines, data can't be altered or messed with, and there is consensus.

### Virtual Voting

Virtual voting happens when the nodes compare events and arrive at a consensus by means of a voting algorithm. This is the secret — a transaction is assigned a timestamp as a node gets it. As it passes to different nodes in the network, it is assigned a timestamp that is a median of all of the timestamps for that transaction received by the nodes in the network. The median acts as the consequence of the vote. This makes a more fair transaction system than a blockchain in light of the fact that the network chooses, not one node.

### Adaptation to internal failure

Similarly as with most distributed ledgers and blockchain, there is generally a chance that a participant in the network isn't honest. There may be postpones in communication or network latency that causes nodes not to appropriately impart.

Consensus mechanisms are intended to deal with these flaws by setting adaptation to non-critical failure criteria. Designers need to consider and account for agitators, awful associations, network latency, and other network issues. Hashgraph consensus can endure one-third of the network acting noxiously. It is reportedly asynchronous Byzantine shortcoming lenient — the highest security level — and that means that honest nodes on a network keep operating even assuming there are troublemakers.

## How Is Hashgraph Different From Blockchain?

Hashgraph is a data structure that keeps up with the records of who let who know what and in what order they did as such. It is a collaborative history of gossip events as participants add and share data, which approves transactions a lot quicker than a blockchain.

Blockchain adds previous transaction data to new transaction data and encodes it. A third party is expected to approve the transactions between parties. Hashgraph needn't bother with this sluggish interaction due to the gossip protocol.

> Hashgraph consensus is a lot quicker than blockchain consensus mechanisms, with average transaction confirmation times in seconds as opposed to minutes.
>

Bitcoin and numerous other cryptocurrencies generally disapprove of message timing. In any case, hashgraph's asynchronous Byzantine adaptation to non-critical failure conquers the problem of message timing by expecting that lost or delayed messages will eventually come to their objections.

For instance, in the event that two transactions happen at the same time, a blockchain network picks which order the transactions happened. In some blockchains, transaction fees focus on confirmation. Different networks could conclude which transaction is confirmed in view of the number of tokens a validator has marked. In these blockchains, one node influences the outcome.

Hashgraph consensus kills the influence one node or a group of nodes can have on transactions. Since there is a timestamp on every transaction, and every transaction is imparted to the whole network, transaction timing issues are settled.

## Features
- The hashgraph distributed ledger system has not received wide adoption by the crypto community.
- Hashgraph consensus utilizes data about data instead of the substance itself to make consensus.
- Primary data in the hashgraph is called "gossip," and secondary data is called "gossip about gossip."
## FAQ
### How Does Hashgraph Consensus Work?
Hashgraph consensus works utilizing consensus timestamps and "gossip," in which every node conveys all that it knows to random nodes in "gossip events."
### What Is Hashgraph Consensus?
Hashgraph consensus is a mechanism utilized in a hashgraph distributed ledger to approve transactions.
### Will Hashgraph Replace Blockchain?
Hashgraph is intended to be — and showcased as — an improvement on blockchain technology, yet whether it will replace it is not yet clear. It doesn't yet have as much designer interest and adoption as blockchain technology.
