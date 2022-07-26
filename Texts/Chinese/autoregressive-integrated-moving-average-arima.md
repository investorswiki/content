---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: 自回归综合移动平均线 (ARIMA)
description: 自回归综合移动平均 (ARIMA) 是一种利用时间序列数据预测未来趋势的统计分析模型。
---

# 自回归综合移动平均线 (ARIMA)
## 什么是自回归综合移动平均线 (ARIMA)？

自回归综合移动平均线 (ARIMA) 是一种统计分析模型，它使用[时间序列数据](/timeseries)更好地理解数据集或预测未来趋势。

如果统计模型根据过去的值预测未来的值，那么它就是自回归的。例如，ARIMA 模型可能会根据过去的表现来预测股票的未来价格，或者根据过去的时期预测公司的收益。

## 了解自回归综合移动平均线 (ARIMA)

自回归综合移动平均模型是一种[回归分析形式，](/regression)用于衡量一个因变量相对于其他变化变量的强度。该模型的目标是通过检查序列中值之间的差异而不是通过实际值来预测未来的证券或金融市场走势。

一个 ARIMA 模型可以通过概述它的每个组件来理解，如下所示：

-[自回归 (AR)](/autoregressive) ：指一种模型，该模型显示一个不断变化的变量，该变量根据其自身的滞后或先验值进行回归。

- **Integrated (I):** 表示原始观测值的差异，以使时间序列变得平稳（即，数据值被数据值与先前值之间的差异替换）。

-[移动平均 (MA)](/movingaverage) ：结合了观测值与应用于滞后观测值的移动平均模型的残差之间的依赖关系。

## ARIMA 参数

ARIMA 中的每个组件都用作具有标准符号的参数。对于 ARIMA 模型，标准符号是带有 p、d 和 q 的 ARIMA，其中整数值替代参数以指示所使用的 ARIMA 模型的类型。参数可以定义为：

- **p**：模型中滞后观察的数量；也称为滞后顺序。

- **d**：原始观测值差异的次数；也称为差异度。

- q：移动平均窗口的大小；也称为移动平均线的顺序。

在线[性回归](/nonlinear-regression)模型中，包括项的数量和类型。可用作参数的 0 值意味着不应在模型中使用特定组件。这样，可以构建 ARIMA 模型来执行 ARMA 模型，甚至是简单的 AR、I 或 MA 模型的功能。

> 因为 ARIMA 模型很复杂，并且在非常大的数据集上效果最好，所以使用计算机算法和机器学习技术来计算它们。

>

## 自回归综合移动平均线 (ARIMA) 和平稳性

在自回归综合移动平均模型中，数据是不同的，以使其平稳。显示平稳性的模型是显示数据随时间推移具有恒定性的模型。大多数经济和市场数据都显示趋势，因此差异的目的是消除任何趋势或季节性结构。

[季节性](/seasonality)，或者当数据显示在一个日历年内重复的规律和可预测的模式时，可能会对回归模型产生负面影响。如果出现趋势且平稳性不明显，则整个过程中的许多计算都不能有效地进行。

> 一次性冲击将无限地影响 ARIMA 模型的后续值。因此，金融危机的遗留问题仍然存在于当今的自回归模型中。

>

## 特别注意事项

ARIMA 模型基于过去值对当前或未来值有一些残余影响的假设。例如，使用 ARIMA 模型预测股票价格的投资者会假设该股票的新买家和卖家在决定提供或接受多少证券时受到近期市场交易的影响。

尽管这种假设在许多情况下都成立，但情况并非总是如此。例如，在 2008 年金融危机之前的几年中，大多数投资者并未意识到许多金融公司持有的大型[抵押贷款支持证券(MBS) 投资组合所带来的风险。](/mbs)

在此期间，使用自回归模型预测美国金融股表现的投资者有充分的理由预测该行业股票价格持续稳定或上涨的趋势。然而，一旦公众知道许多金融机构面临即将倒闭的风险，投资者突然就不再关心这些股票的近期价格，而更关心它们的潜在风险敞口。因此，市场迅速将金融股重新估值到低得多的水平，这一举动完全会混淆自回归模型。

＃＃ 经常问的问题

### ARIMA 是做什么用的？

ARIMA 是一种基于历史时间序列预测或预测未来结果的方法。它基于序列相关的统计概念，其中过去的数据点影响未来的数据点。

### 自回归模型和移动平均模型有什么区别？

ARIMA 将自回归特征与移动平均线的特征相结合。例如，AR(1) 自回归过程是当前值基于前一个值的过程，而 AR(2) 过程是当前值基于前两个值的过程。移动平均值是一种用于分析数据点的计算，通过创建完整数据集的不同子集的一系列平均值以消除异常值的影响。作为这种技术组合的结果，ARIMA 模型可以在进行预测时考虑趋势、周期、季节性和其他非静态类型的数据。

### ARIMA 预测如何工作？

ARIMA 预测是通过插入感兴趣变量的时间序列数据来实现的。统计软件将识别适当的滞后数或差异量，以应用于数据并检查平稳性。然后它将输出结果，这些结果的解释通常类似于多元线性回归模型的解释。

＃＃ 强调

- 自回归综合移动平均 (ARIMA) 模型根据过去值预测未来值。

- ARIMA 利用滞后移动平均线来平滑时间序列数据。

- 它们被广泛用于技术分析以预测未来的证券价格。

- 自回归模型隐含地假设未来与过去相似。

- 因此，它们在某些市场条件下可能被证明是不准确的，例如金融危机或技术快速变革时期。

