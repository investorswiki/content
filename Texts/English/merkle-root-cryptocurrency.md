---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (Cryptocurrency)
description: A Merkle root contains information about each and every transaction hash that at any point was on a particular block in a blockchain.
---

# Merkle Root (Cryptocurrency)
## What Is a Merkle Root?

A Merkle root is the [hash](/hash) of the multitude of hashes of the multitude of transactions that are part of a block in a [blockchain](/blockchain) network.

## Understanding a Merkle Root

A blockchain is involved different blocks that are linked with each other (thus the name blockchain). A hash tree, or the [Merkle tree](/merkle-tree), encodes the blockchain data in an efficient and secure way. It empowers the quick verification of blockchain data, as well as quick movement of large measures of data from one computer node to the next on the peer-to-peer blockchain network.

Each transaction happening on the blockchain network has a hash associated with it. Nonetheless, these hashes are not stored in a sequential order on the block, rather as a tree-like structure with the end goal that each hash is linked to its parent following a parent-youngster tree-like connection.

Since there are various transactions stored on a particular block, all the transaction hashes in the block are likewise hashed, which brings about a Merkle root.

For instance, consider a seven-transaction block. At the least level (called the leaf-level), there will be four transaction hashes. At the level one over the leaf-level, there will be two transaction hashes, every one of which will interface with two hashes that are below them at the leaf level. At the top (level two), there will be the last transaction hash called the root, and it will associate with the two hashes below it (at level one).

Successfully, you get a topsy turvy binary tree, with every node of the tree interfacing with just two nodes below it (consequently the name "binary tree"). It has one root hash at the top, which interfaces with two hashes at level one, every one of which again associates with the two hashes at level three (leaf-level), and the structure keeps relying on the number of transaction hashes.
<!--AAFEB15A7406E8DD3ABDD652D7C85823-->
The hashing begins at the most minimal level (leaf-level) nodes, and every one of the four hashes are remembered for the hash of nodes that are linked to it at level one. Essentially, hashing go on at level one, which prompts hashes of hashes coming to higher levels, until it arrives at the single top root hash.

This root hash is called the Merkle root, and due to the tree-like linkage of hashes, it contains all the information about each and every transaction hash that exists on the block. It offers a single-point hash value that empowers approving all that present on that block.

For instance, assuming that one needs to confirm a transaction that claims to have come from block #137, they just has to check the block's Merkle tree, without stressing over checking anything on some other blocks on the blockchain, similar to block #136 or block #138.
<!--4861E8697637B7236BF11AA57D958059-->
Enter the Merkle root, which further paces up verification. Since it conveys all the information about the whole tree, one just has to confirm that transaction hash, its kin node (in the event that it exists), and continue up until it arrives at the top.

Basically, the Merkle tree and Merkle root mechanism altogether lessen the levels of hashing to be performed, empowering quicker verification and transactions.

## Features
- Merkle roots are central to the calculation required to keep up with cryptocurrencies like bitcoin and ether.
- Merkle roots are utilized in cryptocurrency to ensure data blocks passed between peers on a peer-to-peer network are whole, unharmed, and unaltered.
- A Merkle root is a simple mathematical method for confirming the data on a Merkle tree.
