---
keywords: Investing,Cryptocurrency,Blockchain
title: 区块（比特币区块）
description: 块是数据库中永久记录加密货币交易数据的数据结构；一经写入，不得更改或删除。
---

# 区块（比特币区块）
## 什么是区块（Blockchain Block）？

块是区块链数据库中的数据结构，其中永久记录加密货币区块链中的交易数据。一个块记录了一些或所有尚未被网络验证的最新交易。验证数据后，将关闭块。然后，为要输入和验证的新交易创建一个新块。

因此，块是记录的永久存储，一旦写入，就无法更改或删除。

## 区块（区块链区块）如何运作

[区块链](/blockchain)网络见证了大量的交易活动。当用于加密货币时，维护这些交易的记录有助于系统跟踪使用或未使用的数量以及涉及的各方。在给定时期内进行的交易被记录到一个称为块的文件中，这是区块链网络的基础。

块存储信息。一个块中包含的信息很多，但不会占用大量的存储空间。块通常包括这些元素，但它可能因不同类型而异：

- **幻数**：一个包含特定值的数字，用于将该块标识为特定加密货币网络的一部分。

- **Blocksize**：设置块的大小限制，以便只能在其中写入特定数量的信息。

- **区块头**：包含有关区块的信息。

- **交易计数器**：表示区块中存储了多少交易的数字。

- **交易**：一个区块内所有交易的列表。

交易元素是最大的，因为它包含的信息最多。在存储大小之后是块头，它包括以下子元素：

- **版本**：正在使用的加密货币版本。

- **Previous block hash**：包含前一个区块头的哈希（加密数字）。

- **Hash Merkle root**：当前区块的[Merkle 树中交易的哈希。](/merkle-tree)

- **时间**：将区块放入区块链的时间戳。

- **Bits**：目标哈希的难度等级，表示解决随机数的难度。

- **Nonce**：矿工必须解决的加密数字，以验证区块并关闭它。

标头中的一个 32 位数字称为随机数——挖掘程序使用随机数“猜测”[散列中的随机数](/hash)。当一个随机数被验证时，当随机数或小于它的数字被猜测时，哈希就被解决了。然后，网络关闭该块，生成一个带有标头的新块，然后重复该过程。

采用不同的机制达成共识；最流行的加密货币是[工作量证明](/proof-work)(PoW)，由于与 PoW 相比降低了能源消耗，权益证明 (PoS) 变得越来越流行。

## 挖矿与区块的关系

挖矿是用于解决随机数的术语，这是块头中唯一可以更改的数字。如果在协议中使用工作量证明，这也是加密货币网络使用的过程。

加密货币挖掘通常被认为是一个复杂的数学问题；它实际上是通过散列生成的随机数。散列是使用加密货币使用的加密方法对信息进行加密的过程。例如，比特币使用 SHA256 作为其加密算法。为了让矿工生成“获胜”数字，挖矿程序必须使用 SHA 256 对随机数进行哈希处理，并将它们放入随机数中以查看它是否匹配。

> 在工作量证明协议下解决随机数散列需要耗费大量精力和计算能力。需要一个广泛的矿工网络和足够的能源来为一个小国供电以保持其运转。

>

困难在于所有之前的区块头都是随机加密的。因此，当前块头是基于先前块的随机生成的加密数和来自当前块的信息的随机生成的加密数。

## 其他区块和区块链用途

因为大多数区块链定义都提到比特币，因为它是第一个使用比特币的加密货币，所以许多人将区块和区块链与比特币联系起来。然而，其他加密货币也使用区块和区块链。值得注意的是，以太坊的网络有一种名为以太的加密货币，它也使用区块和区块链。

然而，以太坊及其区块链是为多种用途而设计的，其用途远不止加密货币。例如，不可替代的代币、智能合约、去中心化金融应用程序等已经使用以太坊开发。

＃＃ 强调

- 区块和区块链不仅仅由加密货币使用。它们还有许多其他用途。

- 区块由长数字标识，包括来自先前区块的加密交易信息和新交易信息。

- 在创建新块之前，必须通过网络验证块及其中的信息。

- 区块是区块链中存储和加密信息的地方。

＃＃ 常问问题

### 简单来说什么是区块链？

区块链是一个以链接方式存储和加密信息的数据库，因此以前的信息不能被更改，并且一个小组在通过共识（即数据正确的协议）最终确定之前验证任何条目。

### 区块链有什么用途？

区块链用于加密货币、去中心化金融应用程序、不可替代的代币，更多用途正在不断开发中。

### 区块链区块是如何创建的？

当矿工或区块验证者成功验证区块头中的加密信息时，就会创建区块，这会提示创建新区块。

