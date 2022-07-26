---
keywords: Crypto
title: 布隆过滤器
description: 布隆过滤器。一种数据结构，可用于通知用户特定项目是否是一组项目的一部分
---

# 布隆过滤器
布隆过滤器是一种数据结构，可用于通知用户特定项目是否是集合的一部分。虽然它不能肯定地说一个元素是否在集合中，但它可以肯定地说这个元素是否不在集合中。

布隆过滤器由伯顿霍华德布卢姆于 1970 年创建，由于其空间使用效率高，因此对于一系列应用来说是一种有吸引力的产品。在某些加密货币（尤其是比特币）中，它们在简化支付验证或 SPV 中发挥着不可或缺的作用。

在使用 SPV 客户端时，用户可以在不运行完整节点的情况下与比特币网络进行交互。全节点具有一定的存储和计算要求，这使得它们难以在智能手机等低功耗设备上运行。另一方面，SPV 客户端只需向完整节点查询与用户钱包相关的信息。

将这些数据传递给用户的最直接的解决方案是让全节点知道客户端的密钥，这样只有相关的交易才会发送给它们。显然，这是一个低于标准的解决方案，因为会牺牲客户的隐私。另一方面，仅下载所有交易以丢弃大部分交易将浪费带宽。输入布隆过滤器。

让我们来说明一下。假设客户 Alice 有一笔高价值交易，她不想让运行全节点的 Bob 知道。她构建了一个布隆过滤器，我们将其说明为 10x1 网格：

她通过两个不同的哈希函数传递她感兴趣的交易数据，这两个函数输出 0 到 9 之间的两个数字。我们称它们为 4 和 7。她将过滤器发送给 Bob。

查看此网格，您不知道 Alice 传递给过滤器的数据是什么。如果您有一个包含数据的集合，您将能够对其进行哈希处理并将其与过滤器进行比较——如果匹配，则可能是 Alice 请求的信息。

同时，可能有很多输入会映射到 4 和 7，因此 Bob 无法确定 Alice 对数据的哪一部分感兴趣。他只是返回所有匹配项，然后 Alice 将它们过滤掉。

当然，这过于简单化了，但它证明了这个概念：布隆过滤器混淆了客户的真正利益。这不是一个完美的方法（仍然存在对其隐私的担忧），但它是对节点的非屏蔽请求的改进。

