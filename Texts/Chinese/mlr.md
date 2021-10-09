---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: 多元线性回归 (MLR)
description: 多元线性回归 (MLR) 是一种统计技术，它使用多个解释变量来预测响应变量的结果。
---

# 多元线性回归 (MLR)
## 什么是多元线性回归 (MLR)？

多元线性回归 (MLR)，也简称为多元回归，是一种统计技术，它使用多个解释变量来预测响应变量的结果。多元线性回归的目标是对解释（独立）变量和响应（因）变量之间的[线性关系进行建模。](/linearrelationship)本质上，多元回归是普通最小二乘 (OLS)[回归的扩展，](/regression)因为它涉及多个解释变量。

##多元线性回归的公式和计算

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mtable rowspacing="0.24999999999999992em " columnalign="right left" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>y</mi><mi>i</mi></msub><mo>= </mo><msub><mi>β</mi><mn>0</mn></msub><mo>+</mo><msub><mi>β</mi><mn>1 </mn></msub><msub><mi>x</mi><mrow><mi>i</mi><mn>1</mn></mrow></msub><mo>+ </mo><msub><mi>β</mi><mn>2</mn></msub><msub><mi>x</mi><mrow><mi>i</mi>< mn>2</mn></mrow></msub><mo>+</mo><mi mathvariant="normal">.</mi><mi mathvariant="normal">.</mi>< mi mathvariant="normal">.</mi><mo>+</mo><msub><mi>β</mi><mi>p</mi></msub><msub><mi>x </mi><mrow><mi>i</mi><mi>p</mi></mrow></msub><mo>+</mo><mi>ϵ</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"> <mrow><mrow></mrow><mrow><mtext mathvariant="bold">哪里，</mtext><mtext> </mtext><mtext mathvariant="bold">for</mtext><mtext> </mtext></mrow><mi>i</mi><mo>=</mo><mi>n</mi><mrow><mtext> </mtext><mtext mathvariant="bold">观察：</mtext></mrow></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>y</mi><mi> i</mi></msub><mo>=</mo><mtext>因变量</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></ mrow><msub><mi>x</mi><mi>i</mi></msub><mo>=</mo><mtext>解释变量</mtext></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><msub><mi>β</mi><mn>0</mn></msub><mo>=</mo>< mtext>y 截距 (c即时术语）</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow>< /mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>β</mi><mi>p</ mi></msub><mo>=</mo><mtext>每个解释变量的斜率系数</mtext></mrow></mstyle></mtd></mtr><mtr><mtd>< mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow>< /mrow><mi>ϵ</mi><mo>=</mo><mtext>模型的误差项（也称为残差）</mtext></mrow></mstyle></mtd>< /mtr></mtable><annotation encoding="application/x-tex">\begin{aligned}&amp;y_i = \beta_0 + \beta _1 x_{i1} + \beta _2 x_{i2} + ... + \beta _p x_{ip} + \epsilon\\&amp;\textbf{其中，对于 } i = n \textbf{ 观察结果：}\\&amp;y_i=\text{因变量}\\&amp;x_i=\ text{解释变量}\\&amp;\beta_0=\text{y-截距（常数项）}\\&amp;\beta_p=\text{每个解释变量的斜率系数le}\\&amp;\epsilon=\text{模型的误差项（也称为残差）}\end{aligned}</annotation></semantics></math></span>< span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:10.500000000000004em;vertical-align:-5.000000000000002em;">< /span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2"><span class="vlist -r"><span class="vlist" style="height:5.500000000000001em;"><span style="top:-7.5000000000000001em;"><span class="pstrut" style="height:2.84em;" ></span><span class="mord"></span></span><span style="top:-6em;"><span class="psstrut" style="height:2.84em;"> </span><span class="mord"></span></span><span style="top:-4.499999999999999em;"><span class="psstrut" style="height:2.84em;"> </span><span class="mord"></span></span><span style="top:-2.999999999999999em;"><span class="psstrut" style="height:2.84em;"> </span><span class="mord"></span></span><span style="top:-1.4999999999999991em;"><span class="pstrut" style="height:2.84em;"></span><span class="mord"></span></span><span style="top:1.7763568394002505e-15em;">< span class="pstrut" style="height:2.84em;"></span><span class="mord"></span></span><span style="top:1.5000000000000018em;"><span class="pstrut" style="height:2.84em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:5.000000000000002em;"><span></span></span></span> </span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:5.500000000000001em;"><span style="top:-7.660000000000001em;"><span class="pstrut" style="height:3em;"></span><span class="mord" ><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class= "msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.31166399999999994em;"><span style="top ： -2.5500000000000003em;margin-left:-0.03588em;margin-right:0.05em;"><span class="psstrut" style="height:2.7em;"></span><span class="sizing reset- size6 size3 mtight"><span class="mord mathnormal mtight">i</span></span></span></span><span class="vlist-s">​</span></span ><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span ></span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace" style= "margin-right:0.2777777777777778em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05278em;">β</span><span class ="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="顶部：-2.5500000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="psstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></ span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span ></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span></span></span></span></span></span></span><span class="mord"><span class="mord mathnormal">x</span><span类= "msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.31166399999999994em;"><span style="top :-2.5500000000000003em;margin-left:0em;margin-right:0.05em;"><span class="psstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathnormal mtight">i</span><span class="mord mtight">1</span></span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2222222222222222em;"> </span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist -r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.550000000000 0003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="psstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></ span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class=" vlist-r"><span class="vlist" style="height:0.31166399999999994em;"><span style="top:-2.5500000000000003em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathnormal mtight" >i</span><span class="mord mtight">2</span></span></span></span></span><span class="vlist-s">​</span ></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span ></span></span>< span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222 em;"></span><span class="mord">.</span><span class="mord">.</span><span class="mord">.</span><span class ="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em; "></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05278em;">β</span><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.15139200000000003em;"><span style="top:-2.5500000000000003em;margin- left:-0.05278em;margin-right:0.05em;"><span class="psstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mathnormal mtight">p</span></span></span></span><span class="vlist-s">​</span></span><span class=" vlist-r"><span class="vlist" style="height:0.286108em;"><span></ span></span></span></span></span></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub "><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.311664em;"><span style="top:- 2.5500000000000003em;margin-left:0em;margin-right:0.05em;"><span class="psstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight "><span class="mord mtight"><span class="mord mathnormal mtight">i</span><span class="mord mathnormal mtight">p</span></span></span>< /span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.286108em ;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord mathnormal">ϵ< /span></span></span><span style="top:-6.16em;"><span class="psstrut" style="height:3em;"></span><span class="m ord"><span class="mord"></span><span class="mord text"><span class="mord textbf">哪里，对于</span></span><span class="mord mathnormal">i</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace " style="margin-right:0.277777777777778em;"></span><span class="mord mathnormal">n</span><span class="mord text"><span class="mord textbf">观察:</span></span></span></span><span style="top:-4.659999999999999em;"><span class="pstrut" style="height:3em;"></span> <span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y< /span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.31166399999999994em;" ><span style="top:-2.5500000000000003em;margin-left:-0.03588em;margin-right:0.05em;"><span class="psstrut" style="height:2.7em;"></span> <span class="sizing reset-size6 size3 mtight"><span class="mord math正常 mtight">i</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"> <span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace " style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;">< /span><span class="mord text"><span class="mord">因变量</span></span></span></span><span style="top:-3.1599999999999993em;" ><span class="pstrut" style="height:3em;"></span><span class="mord"><span class="mord"></span><span class="mord">< span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:0.31166399999999994em;"><span style="top:-2.5500000000000003em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7 em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">i</span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;" ></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"> <span class="mord">解释变量</span></span></span></span><span style="top:-1.6599999999999993em;"><span class="psstrut" style="height :3em;"></span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-右：0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></sp an></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height :0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em; "></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text" ><span class="mord">y 截距（常数项）</span></span></span></span><span style="top:-0.159999999999999837em;"><span class=" pstrut" style="height:3em;"></span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal " style="margin-right:0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r">< span class="vlist" style="height:0.15139200000000003em;"><span style="top:-2.5500000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut " style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">p</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r">< span class="vlist" style="height:0.286108em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></ span><span class="mord text"><span class="mord">每个解释变量的斜率系数</span></span></span></span><span style="top:1.3400000000000016em ;"><span class="pstrut" style="height:3em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal ">ϵ</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">模型的误差项（也称为残差）</span></span></ span></span></span></span><span class="vlist-s">​</span></span><span class="v list-r"><span class="vlist" style="height:5.000000000000002em;"><span></span></span></span></span></span></span>< /span></span></span></span>



## 多元线性回归可以告诉你什么

简单线性回归是一种函数，它允许分析师或统计学家根据已知的关于另一个变量的信息对一个变量进行预测。只有当一个变量有两个连续变量——一个自变量和一个因变量时，才能使用线性回归。自变量是用于计算因变量或结果的参数。多元回归模型扩展到几个解释变量。

多元回归模型基于以下假设：

-因变量和自变量之间存在[线性关系](/linearrelationship)

[相关性](/correlation)不是太高

- y~i~ 观察是从总体中独立随机选择的

- 残差应服从均值为 0 且[方差为](/variance)**σ**的[正态分布](/normaldistribution)

确定[系数](/coefficient-of-determination)[(](/coefficient-of-determination) R-squared) 是一种统计指标，用于衡量结果的变化有多少可以用自变量的变化来解释。 R^2^ 总是随着更多预测变量添加到 MLR 模型而增加，即使预测变量可能与结果变量无关。

因此，R^2^ 本身不能用于识别哪些预测变量应该包含在模型中，哪些应该被排除。 R^2^ 只能介于 0 和 1 之间，其中 0 表示任何一个自变量都无法预测结果，1 表示可以从自变量预测结果而没有误差。

在解释多元回归的结果时，beta 系数是有效的，同时保持所有其他变量不变（“所有其他条件都相同”）。多元回归的输出可以水平显示为方程，也可以垂直显示为表格。

## 如何使用多元线性回归的示例

例如，分析师可能想知道市场走势如何影响埃克森美孚 (XOM) 的价格。在这种情况下，他们的线性方程将以标准普尔 500 指数的值作为自变量或预测变量，并将 XOM 的价格作为因变量。

实际上，多个因素可以预测事件的结果。例如，埃克森美孚的价格走势不仅仅取决于整体市场的表现。石油价格、利率和石油[期货价格变动等其他预测因素](/futures)可能会影响 XOM 的价格和其他石油公司的股票价格。为了理解存在两个以上变量的关系，使用多元线性回归。

多元线性回归 (MLR) 用于确定几个随机变量之间的数学关系。换句话说，MLR 检查多个自变量如何与一个因变量相关。一旦确定了每个独立因素来预测因变量，就可以使用多个变量的信息来准确预测它们对结果变量的影响水平。该模型以最接近所有单个数据点的直线（线性）的形式创建关系。

参考上面的 MLR 方程，在我们的示例中：

- y~i~ = 因变量——XOM 的价格

- x~i1~ = 利率

- x~i2~ = 油价

- x~i3~ = 标准普尔 500 指数的价值

- x~i4~= 石油期货价格

- B~0~ = 零时间的 y 轴截距

- B~1~ =当 x~i1~ 变化时测量因变量单位变化的[回归系数](/regression)- 利率变化时 XOM 价格的变化

- B~2~ = 当 x~i2~ 变化时衡量因变量单位变化的系数值——当油价变化时 XOM 价格的变化

最小二乘估计——B~0~、B~1~、B~2~…B~p~——通常由统计软件计算。回归模型中可以包含尽可能多的变量，其中每个自变量都用一个数字来区分——1,2,3,4...p。多元回归模型允许分析师根据提供的关于多个解释变量的信息来预测结果。

尽管如此，该模型并不总是完全准确，因为每个数据点都可能与模型预测的结果略有不同。残值 E 是实际结果和预测结果之间的差异，包含在模型中以解释这种微小的变化。

假设我们通过统计计算软件运行我们的 XOM 价格回归模型，它会返回以下输出：

<!--193B494081C84A1BDB50F6709905B87F-->

分析师会将此输出解释为如果其他变量保持不变，如果市场上的石油价格上涨 1%，XOM 的价格将上涨 7.8%。该模型还显示，随着利率上升 1%，XOM 的价格将下降 1.5%。 R^2^ 表明，埃克森美孚股票价格的 86.5% 的变化可以用利率、油价、石油期货和标准普尔 500 指数的变化来解释。

## 线性回归和多元回归的区别

[普通线性平方](/least-squares-method)(OLS) 回归比较了在某些解释变量发生变化的情况下因变量的响应。然而，一个因变量很少只用一个变量来解释。在这种情况下，分析师使用多元回归，它试图使用多个自变量来解释因变量。多元回归可以是线性的也可以是非线性的。

多元回归基于在因变量和自变量之间存在线性关系的假设。它还假设自变量之间没有主要相关性。

＃＃ 强调

- 多元回归是线性 (OLS) 回归的扩展，仅使用一个解释变量。

- 多元线性回归 (MLR)，也简称为多元回归，是一种统计技术，它使用多个解释变量来预测响应变量的结果。

- MLR 广泛用于计量经济学和金融推理。

＃＃ 常问问题

### 多元回归是线性的意味着什么？

在多元线性回归中，模型计算[最佳拟合线，以](/line-of-best-fit)最小化包含的每个变量与因变量相关的方差。因为它适合一条线，所以它是一个线性模型。还有涉及多个变量的非线性回归模型，例如逻辑回归、二次回归和概率模型。

### 如何在金融中使用多元回归模型？

任何关注多个变量的计量经济模型都可能是倍数。[因子模型](/multifactor-model)比较两个或多个因子以分析变量之间的关系和结果性能。 [Fama and French 三因子](/famaandfrenchthreefactormodel)模型就是这样一个模型，它通过在CAPM 中的市场风险因子（它本身是一个回归模型）中添加规模风险和价值风险因子来扩展[资本资产定价模型(CAPM)。](/capm)通过包括这两个额外的因素，该模型针对这种表现优异的趋势进行了调整，这被认为使其成为评估经理绩效的更好工具。

### 我可以手动进行多元回归吗？

这不太可能，因为多元回归模型很复杂，当模型中包含更多变量或要分析的数据量增加时，情况会变得更加复杂。要运行多元回归，您可能需要在 Excel 等程序中使用专门的统计软件或函数。

### 是什么让多元回归成为倍数？

多元回归考虑了多个解释变量对某些感兴趣的结果的影响。当模型中的所有其他变量保持不变时，它评估这些解释性或独立变量对因变量的相对影响。

### 为什么要使用多元回归而不是简单的 OLS 回归？

一个因变量很少只用一个变量来解释。在这种情况下，分析师使用多元回归，它试图使用多个自变量来解释因变量。然而，该模型假设自变量之间没有主要的相关性。

