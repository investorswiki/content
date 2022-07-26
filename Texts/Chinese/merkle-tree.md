---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: 默克尔树
description: 默克尔树。一种组织和结构化大量数据以使其更易于处理的方法。基于哈希的数据结构。
---

# 默克尔树
Merkle 树是一种组织和结构化大量数据以使其更易于处理的方法。在加密货币和[区块链的情况下](/blockchain)，默克尔树用于以对资源要求较低的方式构建交易数据。

当在 Merkle 树结构中进行加密货币交易时，会对其进行哈希处理，然后给出等效的哈希值。在 Merkle 树中对每笔交易进行哈希处理后，产生的哈希值与另一个哈希值配对，然后再次进行哈希处理。例如，将哈希值“AB”和“AC”组合起来创建“ABC”。

重复这个配对哈希值的过程，直到产生最终的哈希值。最终的哈希值 Merkle 根提供了它包含的所有交易的摘要。然后将 Merkle 根摘要插入到块头中。

＃＃＃＃ 数据安全

Merkle 树结构提供了一个易于访问的[块中交易记录](/block)。因此，检查块中的数据是否已被更改或篡改非常简单。这是正确的，因为对 Merkle 树中交易（或任何其他相关数据）的任何更改都会导致完全不同的相应 Merkle 根。

#### 高效利用资源

如果加密货币不使用 Merkle 树，则每个验证请求都将涉及通过网络发送的大量信息。在 Merkle 树中构建交易数据是对资源的更有效利用。验证交易不需要账本的完整副本，因为哈希交易数据可以在 Merkle 根中验证，需要在节点之间发送的信息少得多，因此分析整体数据完整性的计算能力也更少。

换句话说，默克尔树结构使用户能够验证单个交易是否已包含在区块中，而无需经历下载整个区块链的过程。该技术是加密货币组织交易数据和高效运行的重要工具。如果没有 Merkle 树，对资源的更大需求可能会导致参与网络的[节点减少。](/node)

