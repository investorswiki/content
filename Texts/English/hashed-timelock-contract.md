---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Hashed Timelock Contract (HTLC)
description: Hashed TimeLock Contract (HTLC). Alludes to a special feature that is utilized to make smart contracts that are able to change payment channels.
---

# Hashed Timelock Contract (HTLC)
The term Hashed TimeLock Contract (HTLC) alludes to a special feature that is utilized to make [smart contracts](/smart-contract) that are able to change payment channels. Technically, the HTLC feature enables the implementation of time-bound transactions between two users. In practice, the beneficiary of a HTLC transaction needs to recognize the payment by presenting a cryptographic proof inside a predefined timeframe (number of blocks). Assuming the beneficiary forfeits or neglects to claim the payment, the funds will be returned to the original shipper.
The HTLC feature is applied in both bidirectional and directed payment channels to permit the secure transfers of funds over different channels, without requiring trust on any of the intermediaries.
There are two key components which recognize HTLC from standard cryptocurrency transactions, which are:
- Hashlock: a function that limits the spending of funds until a certain piece of data is publicly revealed (as a cryptographic proof). Such proof may likewise be alluded to as the pre-picture of the hashlock. The pre-picture is essentially the snippet of data that is utilized to produce the hashlock, and to later open its funds.
- Timelock: is a function that limits the spending of funds until a specific time (or block level) from now on. It tends to be accomplished in Bitcoin, for instance, utilizing functions like CheckLockTimeVerify or CheckSequenceVerify.

The Bitcoin Lightning Network is among the most famous use instances of Hashed Timelocked Contracts. By carrying out HTLC into payment channels, funds can be executed from one client to another through interconnected payment channels, without requiring any level of trust. This interaction is known as network routing. It permits Alice to exchange funds with Carol even on the off chance that they are not straightforwardly associated through a payment channel. HTLC's enable Alice to send her funds to Carol through different participants of the network (e.g., Bob) - and the hashlock and timelock features guarantee that Bob can't capture the funds.
Other than being utilized on the Lightning Network, HTLCs can likewise be valuable in different settings, for example, cross-chain [atomic swaps](/atomic-swaps), financial smart contracts and escrow, and substantially more.

## Features
- Payments utilizing HTLCs are conditional thus have effectiveness benefits for blockchain transactions. This property makes HTLCs a fundamental device utilized by the lightning network.
- This type of smart contract requires the receiver of a payment to recognize it inside a certain period of time or relinquish it.
- A hashed timelock contract (HTLC) lessens counterparty risk in decentralized smart contracts by really making a time-based escrow that uses a cryptographic passphrase.
## FAQ
### The amount Does a Smart Contract Cost?
On the Ethereum blockchain, a smart contract sending takes gas, which costs Gwei (a lower denomination of ether). Contingent upon the complexity of the contract, it can cost billions of Gwei to convey a smart contract. Less complex contracts like a simple exchange are a lot less expensive.
### What Is a Smart Contract?
A smart contract is a program stored on a blockchain that executes when specific conditions are met.
### What Is a Timelock Contract?
A timelock contract is a smart contract embedded in a blockchain that executes a transaction at a specific time. They are utilized in hashed timelock contracts and payment channels where specific payment times are required.
### Does Bitcoin Have Smart Contracts?
Initially, Bitcoin's blockchain couldn't execute smart contracts. Nonetheless, the Taproot upgrade in 2021 permitted the blockchain to involve smart contracts in transactions.
