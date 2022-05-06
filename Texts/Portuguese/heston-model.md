---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: Modelo Heston
description: O Modelo Heston, em homenagem a Steve Heston, é um tipo de modelo de volatilidade estocástica usado por profissionais financeiros para precificar opções europeias.
---

# Modelo Heston
## Qual é o modelo Heston?

O Modelo Heston, em homenagem a Steve Heston, é um tipo de modelo de volatilidade estocástica usado para precificar [opções europeias](/europeanoption).

## Entendendo o Modelo Heston

O Modelo Heston, desenvolvido pelo professor associado de finanças Steven Heston em 1993, é um modelo de precificação de opções que pode ser usado para precificar [opções](/option) de vários títulos. É comparável ao [modelo de precificação de opções Black-Scholes mais popular](/blackscholes).

Em geral, os modelos de precificação de opções são usados por investidores avançados para estimar e avaliar o preço de uma determinada opção, negociando em um título subjacente no mercado financeiro. As opções, assim como seus títulos subjacentes, terão preços que mudam ao longo do dia de negociação. Os modelos de precificação de opções buscam analisar e integrar as variáveis que causam flutuação nos preços das opções, a fim de identificar o melhor preço de opção para investimento.

Como um modelo [de volatilidade estocástica](/stochastic-volatility),. o Modelo de Heston usa métodos estatísticos para calcular e prever a precificação de opções com a suposição de que a volatilidade é arbitrária. A suposição de que a volatilidade é arbitrária, em vez de constante, é o fator chave que torna os modelos de volatilidade estocásticos únicos. Outros tipos de modelos de volatilidade estocástica incluem o modelo SABR, o modelo Chen e o modelo [GARCH](/generalalizedautogregressiveconditionalheteroskedasticity).

## Principais diferenças

O Modelo de Heston possui características que o distinguem de outros modelos de volatilidade estocástica, a saber:

- Considera uma possível correlação entre o preço de uma ação e sua volatilidade.

- Transmite a volatilidade como revertendo à média.

- Dá uma solução de forma fechada, o que significa que a resposta é derivada de um conjunto aceito de operações matemáticas.

- Não exige que os preços das ações sigam uma distribuição de probabilidade lognormal.

O Modelo de Heston também é um tipo de [modelo de sorriso de volatilidade](/volatilitysmile). "Sorriso" refere-se ao sorriso da volatilidade, uma representação gráfica de várias opções com datas de vencimento idênticas que mostram uma volatilidade crescente à medida que as opções se tornam mais [in-the-money](/inthemoney) (ITM) ou [out-of](/outofthemoney) [-the-money](/outofthemoney) (OTM). O nome do modelo de sorriso deriva da forma côncava do gráfico, que se assemelha a um sorriso.

## Metodologia do Modelo Heston

O Modelo Heston é uma solução de forma fechada para precificação de opções que busca superar algumas das deficiências apresentadas no modelo de precificação de opções Black-Scholes. O Modelo Heston é uma ferramenta para investidores avançados.

### O cálculo é o seguinte:

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mtable rowspacing="0.24999999999999992em " columnalign="right left" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo stretchy="false">(</ mo><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo stretchy="false">) </mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">onde:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>preço do ativo no momento </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>taxa de juros livre de risco – taxa teórica em um</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle scriptlevel= "0" displaystyle="true"><mrow><mrow></mrow><mtext>ativo sem risco</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>volatilidade (padrão desvio) do preço do ativo</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo>=</ mo><mtext>volatilidade do </mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>variação de preço de longo prazo</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> taxa de reversão para </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <mi>t</mi><mo>=</mo><mtext>incremento de tempo positivo indefinidamente pequeno</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> </mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> <mtext>Movimento browniano do preço do ativo</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow ></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> <mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>Movimento browniano da variação de preço do ativo</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{onde:} \\ &amp;S_t = \text{preço do ativo no momento } t \\ &amp;r = \text{taxa de juros livre de risco -- taxa teórica sobre um} \\ &amp;\text{ativo sem risco} \\ &amp;\sqrt{ V_t } = \text{ volatilidade (desvio padrão) do preço do ativo} \\ &amp;\sigma = \text{volatilidade do } \sqrt{ V_t } \\ &amp;\theta = \text{variância de preço de longo prazo} \\ &amp;k = \text{taxa de reversão para } \theta \\ &amp;dt = \text{incremento de tempo positivo indefinidamente pequeno} \\ &amp;W_{1t} = \text{movimento browniano do preço do ativo} \\ &amp;W_ {2t} = \text{Movimento browniano da variação de preço do ativo} \\ \end{aligned}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="strut" style="altura:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">< span class="vlist-r"><span class="vlist" style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.0000000000000018em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.660539999999998em;">< span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.821079999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span>< span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></ span></span></span></span></span></span><span class="mspace" style="margin-right:0.27777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"> <span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" sty le="margin-right:0.2222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="altura:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="pstrut" style="altura:3.2em; "></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="he ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34.79.3.68.167.158.7.102.5.238c34.3.79.3.51.8.119.3.52.5.120

c340,-704.7.510.7,-1060.3.512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17,3,-33,3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;" ><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style= "altura:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2"> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist- s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="altura:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​</span></span><span class ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right :0.2777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class= "mbin">−</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style= "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class=" vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</ span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord mathnormal" style=" margin-right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class= "vlist" style="altura:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p strut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span> </span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> <span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width=' 400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34.79.3.68.167.158.7.102.5.238c34.3.79.3.51.8.119.3.52.5.120

c340,-704.7.510.7,-1060.3.512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17,3,-33,3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord mathnormal" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin- left:-0.13889em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight">t</span></span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span></span></span></span></span></span></span></span></span><span style="top:-9.160540000000001em;"><span class ="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord text"><span class="mord textbf ">onde:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span clas s="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class="mord" >preço do ativo no momento </span></span><span class="mord mathnormal">t</span></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">taxa de juros livre de risco – taxa teórica em um </span></span></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">ativo sem risco</span></span>< /span></span><span style="top:-3.0000000000000018em;"><span class=" pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:- 3.2em;"><span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span><span style=" topo:-2,9 6054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34.79.3.68.167.158.7.102.5.238c34.3.79.3.51.8.119.3.52.5.120

c340,-704.7.510.7,-1060.3.512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17,3,-33,3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r Estilo "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mspace" ="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span ><span class="mord text"><span class="mord">volatilidade (desvio padrão) do preço do ativo</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">volatilidade de o </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class ="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em;"><span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; "><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< largura svg='400e m' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34.79.3.68.167.158.7.102.5.238c34.3.79.3.51.8.119.3.52.5.120

c340,-704.7.510.7,-1060.3.512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17,3,-33,3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span> <span style="top:0.16053999999999924em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class= "mord">variação de preço de longo prazo</span></span></span></span><span style="top:1.6605399999999992em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">taxa de reversão para </span></span ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">incremento de tempo positivo indefinidamente pequeno</span> </span></span></span><span style="top:4.660539999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em ;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span ></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel ">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class="mord">Movimento browniano de o preço do ativo</span></span></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></ span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord" mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></ span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></ span></span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace" style ="margin-right:0.277777777777778em;"></span><span class="mord text"><span class="mord">Movimento browniano da variação de preço do ativo</span></span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r">< span class="vlist" style="height:9.821079999999998em;"><span></span></span></span></span></span></span></span></span ></span></span>

## Modelo Heston vs. Black-Scholes

O modelo Black-Scholes para precificação de opções foi introduzido na década de 1970 e serviu como um dos primeiros modelos para ajudar os investidores a obter um preço associado a uma opção sobre um [título](/security). Em geral, ajudou a promover o investimento em opções, pois criou um modelo para analisar o preço das opções sobre vários títulos.

Tanto o modelo de Black-Scholes quanto o de Heston são baseados em cálculos subjacentes que podem ser codificados e programados por meio de Excel avançado ou outros sistemas quantitativos. A fórmula de opção de compra de Black-Scholes é calculada multiplicando o preço das ações pela função de distribuição de probabilidade normal padrão cumulativa.

Em seguida, o [valor presente líquido](/npv) (VPL) do preço de exercício multiplicado pela distribuição normal padrão acumulada é subtraído do valor resultante do cálculo anterior.

Em notação matemática,

>

> Chamada = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

Por outro lado, o valor de uma opção de venda pode ser calculado usando a fórmula:

>

> Colocar = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

Em ambas as fórmulas, S é o preço da ação, K é o preço de exercício, r é a taxa de juros livre de risco e T é o tempo até o vencimento.

A fórmula para d~1~ é:

>

> (ln(S/K) + (r + (Volatilidade Anual)^2^/2) * T)/(Volatilidade Anualizada * (T^0,5^))

>

A fórmula para d~2~ é:

>

> d1 – (Volatilidade Anualizada) * (T^0,5^)

>

## Considerações Especiais

O Modelo de Heston é digno de nota porque busca suprir uma das principais limitações do modelo de Black-Scholes que mantém a volatilidade constante. O uso de variáveis estocásticas no Modelo de Heston fornece a noção de que a volatilidade não é constante, mas arbitrária.

Tanto o modelo básico de Black-Scholes quanto o modelo de Heston ainda fornecem apenas estimativas de precificação de opções para uma opção europeia, que é uma opção que só pode ser exercida na data de vencimento. Várias pesquisas e modelos foram estudados para precificar opções americanas por meio de Black-Scholes e do modelo Heston. Essas variações fornecem estimativas de opções que podem ser exercidas em qualquer data até a data de vencimento, como é o caso das opções americanas.

## Destaques

- Isso significa que o modelo assume que a volatilidade é arbitrária, ao contrário do modelo Black-Scholes que mantém a volatilidade constante.

- O Modelo Heston é um modelo de precificação de opções que utiliza volatilidade estocástica.

- O Modelo Heston é um tipo de modelo de sorriso de volatilidade, que é uma representação gráfica de várias opções com datas de vencimento idênticas que mostram volatilidade crescente à medida que as opções se tornam mais ITM ou OTM.

