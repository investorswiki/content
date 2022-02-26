---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: 随机波动率
description: 随机波动假设资产的价格波动随时间变化而不是恒定的，这是 Black Scholes 模型错误地假设的。
---

# 随机波动率
## 什么是随机波动率？

随机波动率 (SV) 是指资产价格的[波动率](/volatility)是变化的而不是恒定的，正如[Black Scholes](/blackscholes)期权定价模型中所假设的那样。随机波动率模型试图通过允许波动率随时间波动来纠正 Black Scholes 的这个问题。

## 了解随机波动率

“随机”一词意味着某些变量是随机确定的，无法精确预测。然而，可以替代地确定概率分布。在金融建模的背景下，[随机建模迭代](/stochastic-modeling)[随机变量](/random-variable)的连续值，这些值彼此不独立。非独立的意思是虽然变量的值会随机变化，但其起点将取决于其先前的值，因此取决于其先前的值，依此类推；这描述了所谓的[随机游走](/randomwalktheory)。

随机模型的示例包括用于定价期权的[Heston 模型](/heston-model)和 SABR 模型，以及用于分析时间序列数据的[GARCH](/garch)模型，其中方差误差被认为是序列[自相关](/autocorrelation)的。

资产的波动性是期权定价的关键组成部分。随机波动率模型是出于对期权定价的 Black Scholes 模型进行修改的需要而开发的，该模型未能有效地考虑到[标的证券价格波动性](/underlying-security)可能发生变化的事实。 Black Scholes 模型反而做了简化假设，即基础证券的波动性是恒定的。随机波动率模型通过允许基础证券的价格波动率作为[随机变量波动来纠正这一点](/random-variable)。通过允许价格变化，随机波动率模型提高了计算和预测的准确性。

## 赫斯顿随机波动率模型

Heston 模型是由金融学者 Steven Heston 在 1993 年创建的随机波动率模型。该模型使用波动率或多或少是随机的假设，并具有以下区别于其他随机波动率模型的特征：

- 它考虑了资产价格与其波动性之间的相关性。

- 它将波动理解为[回归均值](/meanreversion)。

- 它给出了一个封闭形式的解决方案，这意味着答案是从一组公认的数学运算中得出的。

- 它不要求股票价格遵循[对数正态](/log-normal-distribution)概率分布。

Heston 模型还包含一个[波动率微笑](/volatilitysmile)，允许更多隐含波动率被加权到相对于上行打击的下行[打击](/strikeprice)。 “微笑”的名称是由于这些波动率差异在绘制时呈凹形。

＃＃ 强调

- 让波动率随机变化的随机模型，例如赫斯顿模型，试图纠正这个盲点。

- 许多基本期权定价模型（例如 Black Scholes）假设波动性恒定，从而导致定价效率低下和错误。

- 随机波动是一个概念，它考虑到资产价格波动随时间变化而不是恒定的事实。

