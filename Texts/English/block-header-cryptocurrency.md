---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Block Header (Cryptocurrency)
description: Block header. A section in a block containing metadata and a summary of the block&#39;s transactions. This is the data hashed while mining.
---

# Block Header (Cryptocurrency)
The block header is a section in a [block](/block) that fills in as a summary of the remainder of the block. It's comprised of all the [metadata](/metadata) - like the time and [difficulty](/difficulty) when the block was [mined](/mining), the [Merkle root](/merkle-tree) of the included transactions, and the [nonce](/nonce). Additionally present is the previous block's [hash](/hash), which permits us to make the "chain" of blocks. Fundamentally, the block header contains any data that isn't the rundown of raw transactions itself.
A block header is what the miners hash to try and make the block legitimate. This is significantly more efficient than hashing the entirety of the block, which can be comprised of thousands of transactions. It would be immeasurably more lumbering for a miner to change the nonce and to rehash a whole 2MB block for each endeavor. Compare this with hashing Bitcoin's block headers, for example, which have a fixed length of 80 bytes.
Block headers are great according to a mining point of view, but since of their small size, they're likewise great for light clients. The Bitcoin blockchain is too large for gadgets like cell phones to store. Assuming the chain had 100,000 1MB blocks, you'd consume 100GB of space. In any case, with just the block headers for those equivalent blocks, you'd just take up 0.008GB, or 8MB.
Along these lines, gadgets with less bandwidth or storage space can in any case perform some degree of validation. Since the Merkle root epitomizes the entirety of the transactions, they can later check whether a transaction was remembered for a specific block. This includes some major disadvantages - the client must in any case depend on an outsider to give them fundamental data. So, light clients are desirable over a system where the users perform no verification by any means.

## Features
- They're hashed to make a proof of work for mining rewards.
- Block headers distinguish individual blocks in a blockchain.
- The blocks are layered upward, starting with the "beginning block."
- The Bitcoin variant number assists you with keeping track of changes in the protocol.
- Each block header contains three arrangements of block metadata and numerous individual parts.
