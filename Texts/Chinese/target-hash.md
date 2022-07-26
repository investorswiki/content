---
keywords: Investing,Cryptocurrency,Altcoins
title: 目标哈希
description: 目标哈希设置使用工作量证明 (PoW) 区块链系统进行加密货币挖掘的难度。
---

# 目标哈希
## 什么是目标哈希？

在加密货币挖掘中，目标哈希是哈希[块头](/block-header-cryptocurrency)必须小于或等于才能将新块授予矿工的数值。区块头标识区块链中的各个区块。

加密货币挖掘是指收集加密货币作为您完成工作的奖励的过程。这项工作的本质是验证给定加密货币交易的合法性。通过这种方式，加密货币矿工本质上是审计员。当你挖矿时，你可以赚取加密货币，而无需为此投入资金。

目标哈希用于确定输入的难度，并且可以进行调整以确保有效地处理块。例如，目标哈希用于使用工作量证明 (PoW) 系统设置当前[采矿难度](/difficulty-cryptocurrencies)[y](/difficulty-cryptocurrencies) （包括比特币）的加密货币。如果加密货币使用不同的系统进行挖掘，它可能不需要目标哈希。

## 目标哈希是如何工作的

[加密货币](/cryptocurrency)依赖于使用包含所有加密货币交易历史的[区块链。](/blockchain)这些交易被[散列](/hash)或加密编码成一系列字母数字字符。散列涉及获取任意长度的数据字符串并通过算法运行它以产生具有固定长度的输出。无论输入有多大或多小，输出总是相同的长度（尽管散列的排列数量是天文数字）。每个块将包含前一个块头的哈希。

验证和编码区块链被称为[挖掘](/bitcoin-mining)。挖矿涉及使用计算机运行散列算法来处理最近的区块；用户需要挖掘的信息可以在区块的头部找到。加密货币网络为此散列设置了一个目标值——称为目标散列——矿工试图通过测试所有可能的值来确定这个值是什么。

区块头包含区块版本号、时间戳、前一个区块中使用的哈希、[默克尔根的](/merkle-root-cryptocurrency)[哈希](/merkle-root-cryptocurrency)、[随机数](/nonce)和目标哈希。通过获取块内容的散列，添加随机数字串（nonce）并再次对块进行散列来生成块。

如果哈希满足目标的要求，则将该块添加到区块链中。循环通过解决方案以猜测随机数被称为[工作证明](/proof-work)（PoW），能够找到价值的矿工将获得区块并以加密货币支付。

## 特别注意事项

### 比特币的目标哈希

比特币使用 SHA-256 哈希算法。该算法以需要可预测数量的计算机处理能力的方式生成可验证的随机数。

挖掘一个区块需要矿工产生一个值（一个随机数），经过散列（加密编码）后，该值小于或等于比特币网络接受的最新块中使用的值。这个数字介于 0-（最小选项）和 256 位（最大选项）之间，但不太可能是最大数字。

因为目标哈希可能是一个巨大的数字，矿工在成功之前可能必须测试大量的值。不成功的矿工必须等待下一个区块（这就是为什么找到哈希解决方案的矿工被比作比赛或彩票的赢家）。

目标哈希会定期调整。用于生成新目标的散列函数具有旨在使区块链（及其加密货币）安全的特定属性。这个过程是确定性的，这意味着每次使用相同的输入时都会产生相同的结果。它足够快，不会花费太长时间来返回输入的哈希值。这也使得确定输入变得非常困难，尤其是对于大数字，并且对输入进行小的更改会导致非常不同的哈希输出。

＃＃ 强调

- 目标哈希用于使用工作量证明 (PoW) 系统设置当前挖矿难度的加密货币（包括比特币）；如果加密货币使用不同的系统进行挖掘，它可能不需要目标哈希。

- 在加密货币挖掘中，目标哈希是一个数字值，哈希块头（用于识别区块链中的单个块）必须小于或等于才能将新块授予矿工。

- 比特币网络通过提高或降低目标哈希来调整挖矿难度，以保持新区块之间的平均 10 分钟间隔。

