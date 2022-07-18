---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: Heston model
description: Heston-modellen, opkaldt efter Steve Heston, er en type stokastisk volatilitetsmodel, der bruges af finansielle fagfolk til at prissætte europæiske optioner.
---

# Heston model
## Hvad er Heston-modellen?

Heston-modellen, opkaldt efter Steve Heston, er en type stokastisk volatilitetsmodel, der bruges til at prissætte [europæiske optioner](/europeanoption).

## Forståelse af Heston-modellen

Heston-modellen, udviklet af lektor Steven Heston i 1993, er en optionsprismodel, der kan bruges til prisfastsættelse af [optioner](/option) på forskellige værdipapirer. Den kan sammenlignes med den mere populære [Black-Scholes option prismodel](/blackscholes).

Overordnet set bruges option prissætningsmodeller af avancerede investorer til at estimere og måle prisen på en bestemt option, der handler på et underliggende værdipapir på den finansielle markedsplads. Optioner vil, ligesom deres underliggende sikkerhed, have priser, der ændrer sig gennem handelsdagen. Optionsprismodeller søger at analysere og integrere de variabler, der forårsager udsving i optionspriserne, for at identificere den bedste optionspris for investering.

Som en [stokastisk volatilitetsmodel](/stochastic-volatility) bruger Heston-modellen statistiske metoder til at beregne og forudsige optionspriser med den antagelse, at volatiliteten er vilkårlig. Antagelsen om, at volatilitet er vilkårlig, snarere end konstant, er nøglefaktoren, der gør stokastiske volatilitetsmodeller unikke. Andre typer af stokastiske volatilitetsmodeller omfatter SABR-modellen, Chen-modellen og [GARCH-](/generalalizedautogregressiveconditionalheteroskedasticity) modellen.

## Nøgleforskelle

Heston-modellen har egenskaber, der adskiller den fra andre stokastiske volatilitetsmodeller, nemlig:

- Det tager højde for en mulig sammenhæng mellem en akties pris og dens volatilitet.

- Det formidler volatilitet som at vende tilbage til middelværdien.

- Det giver en løsning i lukket form, hvilket betyder, at svaret er afledt af et accepteret sæt matematiske operationer.

- Det kræver ikke, at aktiekurserne følger en lognormal sandsynlighedsfordeling.

Heston-modellen er også en type [volatilitetssmilemodel](/volatilitysmile). "Smil" refererer til volatilitetssmilet, en grafisk repræsentation af flere optioner med identiske udløbsdatoer, der viser stigende volatilitet, efterhånden som optionerne bliver mere [in-the-money](/inthemoney) (ITM) eller [out-of](/outofthemoney) [-the-money](/outofthemoney) (OTM). Smilmodellens navn stammer fra grafens konkave form, som ligner et smil.

## Heston Model Metodologi

Heston-modellen er en lukket løsning til prisfastsættelsesmuligheder, der søger at overvinde nogle af de mangler, der præsenteres i Black-Scholes-optionsprismodellen. Heston-modellen er et værktøj for avancerede investorer.

### Beregningen er som følger:

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mtable rowspacing="0.24999999999999992em " columnalign="right left" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" <mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> < msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo stretchy="false">(</ mo ><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo stretchy="false">) < /mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">hvor:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>aktivpris på tidspunktet </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>risikofri rente – teoretisk rente på en</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle scriptlevel= "0" displaystyle="true"><mrow><mrow></mrow><mtext>aktiv uden risiko</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><mqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>volatilitet (standard afvigelse) af aktivprisen</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo>=</ mo><mtext>volatiliteten af ​​</mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>langsigtet prisafvigelse</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> hastighed for tilbagevenden til </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" <mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> < mi>t</mi><mo>=</mo><mtext>uendeligt lille positiv tidsstigning</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> < mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> < /mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> < mtext>Brownsk bevægelse af aktivprisen</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow > </mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> < mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>Brownsk bevægelse af aktivets prisvariation</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{hvor:} \\ &amp;S_t = \text{aktivpris på tidspunktet } t \\ &amp;r = \text{risikofri rente -- teoretisk rente på et} \\ &amp;\text{aktiv uden risiko} \\ &amp;\sqrt{ V_t } = \text{ volatilitet (standardafvigelse) af aktivprisen} \\ &amp;\sigma = \text{volatilitet af } \sqrt{ V_t } \\ &amp;\theta = \text{langsigtet prisafvigelse} \\ &amp;k = \text{tilbageførselshastighed til } \theta \\ &amp;dt = \text{ubegrænset lille positiv tidsstigning} \\ &amp;W_{1t} = \text{Brownsk bevægelse af aktivprisen} \\ &amp;W_ {2t} = \text{Brownsk bevægelse af aktivets prisafvigelse} \\ \end{aligned}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="strut" style="height:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">>< span class="vlist-r"><span class="vlist" style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="højde :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.00000000000000018em ;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.660539999999998em;">< span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:6.160539999999998em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.82107999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="psrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="psrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span>< span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></ span ></span></span></span></span></span><span class="mspace" style="margin-right:0.27777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.280555999999999em;"> <span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" margin-right:0.22222222222222222em;"></span><span class="mbin">+</span><span class="mspace" sty le="margin-right:0.2222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="psrut" style="height:3.2em; "></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="psrut" style="he ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10-0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84.175,-136.283c-52.108,-89.167,185.3,-111.5.232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23.7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7.8,-22.16.7,-34.26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59.76,-59s76,-60.76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;" ><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style= " height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2 "> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.550000000000000003em;margin-left:-0.13889em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist- s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="psrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s"></span></span><span class ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></ span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin- højre :0.2777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span>< span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class = "mbin">−</span><span class="mspace" style="margin-right:0.22222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style = "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class=" vlist " style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</ span ><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.22222222222222222em;">< / span><span class="mbin">+</span><span class="mspace" style="margin-right:0.22222222222222222em;"></span><span class="mord mathnormal" style=" margin -right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class=" vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p strut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span> </span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> < span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class ="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width=' 400em ' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10-0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84.175,-136.283c-52.108,-89.167,185.3,-111.5.232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23.7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7.8,-22.16.7,-34.26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59.76,-59s76,-60.76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord mathnormal" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000000000000003em;margin- left:-0.13889em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight">t</span></span></span></span>< /span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span ></span></span></span></span></span></span></span></span><span style="top:-9.160540000000001em;"><span class = "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord text"><span class="mord textbf ">hvor:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="psrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span clas s="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord" >aktivpris på tidspunktet </span></span><span class="mord mathnormal">t</span></span></span><span style="top:-6.160540000000001em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">risikofri rente – teoretisk rente på en </span></span></span></span><span style="top:-4.660540000000001em;"><span class="psrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">aktiv uden risiko</span></span>< /span></span><span style="top:-3.00000000000000018em;"><span class=" pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:- 3.2em;"><span class="psrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ span></span></span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" stil ="height:0.15em;"><span></span></span></span></span></span></span></span></span><span style=" top :-2,9 6054em;"><span class="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10-0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84.175,-136.283c-52.108,-89.167,185.3,-111.5.232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23.7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7.8,-22.16.7,-34.26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59.76,-59s76,-60.76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mspace" stil ="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mord text"><span class="mord">volatilitet (standardafvigelse) af aktivprisen</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">volatilitet af den </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< span class="psrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class ="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span> </span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em ;"><span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; " ><span class="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< svg bredde='400e m' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10-0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84.175,-136.283c-52.108,-89.167,185.3,-111.5.232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23.7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7.8,-22.16.7,-34.26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59.76,-59s76,-60.76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span> <span style="top:0.16053999999999924em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class= "mord">langsigtet prisafvigelse</span></span></span></span><span style="top:1.6605399999999992em;"><span class="psrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">hastighed for tilbagevenden til </span></span ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">ubegrænset lille positiv tidsstigning</span> </span></span></span><span style="top:4.660539999999998em;"><span class="psrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000003em;margin-left:-0.13889em ;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span > </span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel " >=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">brownsk bevægelse af aktivpris</span></span></span></span><span style="top:6.160539999999998em;"><span class="psrut" style="height:3.00054em;"></ span ><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s"><​</span>< / span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span>< / span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style ="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">Brownsk bevægelse af aktivets prisvariation</span></span></ span ></span></span><span class="vlist-s"></span></span><span class="vlist-r"></span> span class="vlist" style="height:9.821079999999998em;"><span></span></span></span></span></span></span></span></span ></span></span>

## Heston Model vs. Sorte Skoler

Black-Scholes-modellen for prisfastsættelse af optioner blev introduceret i 1970'erne og tjente som en af de første modeller til at hjælpe investorer med at udlede en pris forbundet med en option på et [værdipapir](/security). Generelt var det med til at fremme optionsinvestering, da det skabte en model til at analysere prisen på optioner på forskellige værdipapirer.

Både Black-Scholes- og Heston-modellen er baseret på underliggende beregninger, der kan kodes og programmeres gennem avancerede Excel eller andre kvantitative systemer. Black-Scholes call option-formlen beregnes ved at multiplicere aktiekursen med den kumulative standard normale sandsynlighedsfordelingsfunktion.

Derefter trækkes [nettonutidsværdien](/npv) (NPV) af strejkeprisen multipliceret med den kumulative standardnormalfordeling fra den resulterende værdi af den tidligere beregning.

i matematisk notation,

>

> Kald = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

Omvendt kan værdien af en put-option beregnes ved hjælp af formlen:

>

> Put = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

I begge formler er S aktiekursen, K er strikekursen, r er den risikofri rente, og T er tiden til udløb.

Formlen for d~1~ er:

>

> (ln(S/K) + (r + (Annualiseret Volatilitet)^2^/2) * T)/(Annualiseret Volatilitet * (T^0,5^))

>

Formlen for d~2~ er:

>

> d1 – (Annualiseret volatilitet) * (T^0,5^)

>

## Særlige overvejelser

Heston-modellen er bemærkelsesværdig, fordi den søger at sørge for en af de vigtigste begrænsninger af Black-Scholes-modellen, som holder volatiliteten konstant. Brugen af stokastiske variabler i Heston-modellen sørger for den opfattelse, at volatiliteten ikke er konstant, men vilkårlig.

Både den grundlæggende Black-Scholes-model og Heston-modellen giver stadig kun estimater for optionsprissætning for en europæisk option, som er en option, der kun kan udnyttes på dens udløbsdato. Forskellige undersøgelser og modeller er blevet undersøgt for prissætning af amerikanske muligheder gennem både Black-Scholes og Heston-modellen. Disse variationer giver estimater for optioner, der kan udnyttes på en hvilken som helst dato frem til udløbsdatoen, som det er tilfældet for amerikanske optioner.

##Højdepunkter

- Det betyder, at modellen antager, at volatiliteten er vilkårlig, i modsætning til Black-Scholes-modellen, der holder volatiliteten konstant.

- Heston-modellen er en optionsprismodel, der udnytter stokastisk volatilitet.

- Heston-modellen er en type volatilitetssmilemodel, som er en grafisk repræsentation af flere muligheder med identiske udløbsdatoer, der viser stigende volatilitet, efterhånden som mulighederne bliver mere ITM eller OTM.

