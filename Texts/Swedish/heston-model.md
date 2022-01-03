---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: Heston modell
description: Heston-modellen, uppkallad efter Steve Heston, är en typ av stokastisk volatilitetsmodell som används av finansexperter för att prissätta europeiska optioner.
---

# Heston modell
## Vad är Heston-modellen?

Heston-modellen, uppkallad efter Steve Heston, är en typ av stokastisk volatilitetsmodell som används för att prissätta [europeiska optioner](/europeanoption).

## Förstå Heston-modellen

Heston-modellen, utvecklad av docent Steven Heston 1993, är en optionsprismodell som kan användas för prissättning av [optioner](/option) på olika värdepapper. Den är jämförbar med den mer populära [Black-Scholes alternativprismodell](/blackscholes).

Sammantaget används optionsprismodeller av avancerade investerare för att uppskatta och mäta priset på ett visst alternativ, som handlas på ett underliggande värdepapper på den finansiella marknaden. Optioner, precis som deras underliggande säkerhet, kommer att ha priser som ändras under hela handelsdagen. Optionsprissättningsmodeller försöker analysera och integrera de variabler som orsakar fluktuationer i optionspriserna för att identifiera det bästa optionspriset för investeringar.

Som en [stokastisk volatilitetsmodell](/stochastic-volatility) använder Heston-modellen statistiska metoder för att beräkna och prognostisera optionsprissättning med antagandet att volatiliteten är godtycklig. Antagandet att volatiliteten är godtycklig, snarare än konstant, är nyckelfaktorn som gör stokastiska volatilitetsmodeller unika. Andra typer av stokastiska volatilitetsmodeller inkluderar SABR-modellen, Chen-modellen och [GARCH-](/generalalizedautogregressiveconditionalheteroskedasticity) modellen.

## Nyckelskillnader

Heston-modellen har egenskaper som skiljer den från andra stokastiska volatilitetsmodeller, nämligen:

- Det tar hänsyn till en möjlig korrelation mellan en akties pris och dess volatilitet.

– Det förmedlar volatilitet som att återgå till medelvärdet.

– Det ger en lösning i sluten form, vilket innebär att svaret härleds från en accepterad uppsättning matematiska operationer.

– Det kräver inte att aktiekurserna följer en lognormal sannolikhetsfördelning.

Heston-modellen är också en typ av leendemodell med [volatilitet](/volatilitysmile). "Smile" syftar på volatilitetsleendet, en grafisk representation av flera alternativ med identiska utgångsdatum som visar ökande volatilitet i takt med att alternativen blir mer [in-the-money](/inthemoney) (ITM) eller [out-of-](/outofthemoney) [the-money](/outofthemoney) (OTM). Leendemodellens namn kommer från den konkava formen på grafen, som liknar ett leende.

## Heston Model Methodology

Heston-modellen är en sluten lösning för prissättningsalternativ som försöker övervinna några av de brister som presenteras i Black-Scholes optionsprismodell. Heston-modellen är ett verktyg för avancerade investerare.

### Beräkningen är som följer:

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mtable rowspacing="0.24999999999999992em " columnalign="right left" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo stretchy="false">(</ mo><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo stretchy="false">) </mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">där:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>tillgångspris vid tidpunkten </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>riskfri ränta – teoretisk ränta på en</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle scriptlevel= "0" displaystyle="true"><mrow><mrow></mrow><mtext>tillgång utan risk</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>volatilitet (standard avvikelse) av tillgångspriset</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo>=</ mo><mtext>volatiliteten för </mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>långsiktig prisvariation</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> återgångshastighet till </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <mi>t</mi><mo>=</mo><mtext>obestämt litet positivt tidssteg</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> </mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> <mtext>Brownisk rörelse av tillgångspriset</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow ></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> <mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>Brownisk rörelse av tillgångens prisvariation</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{där:} \\ &amp;S_t = \text{tillgångspris vid tidpunkten } t \\ &amp;r = \text{riskfri ränta -- teoretisk ränta på en} \\ &amp;\text{tillgång utan risk} \\ &amp;\sqrt{ V_t } = \text{ volatilitet (standardavvikelse) för tillgångspriset} \\ &amp;\sigma = \text{volatilitet för } \sqrt{ V_t } \\ &amp;\theta = \text{långsiktig prisvariation} \\ &amp;k = \text{återgångshastighet till } \theta \\ &amp;dt = \text{obestämt litet positivt tidssteg} \\ &amp;W_{1t} = \text{Brownisk rörelse av tillgångspriset} \\ &amp;W_ {2t} = \text{Brownisk rörelse av tillgångens prisvariation} \\ \end{aligned}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="strut" style="height:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">>< span class="vlist-r"><span class="vlist" style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.00000000000000018em ;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.660539999999998em;">< span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:6.160539999999998em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.82107999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="psrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span>< span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></ span></span></span></span></span></span><span class="mspace" style="margin-right:0.27777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"> <span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" margin-right:0.22222222222222222em;"></span><span class="mbin">+</span><span class="mspace" sty le="margin-right:0.2222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="psrut" style="height:3.2em; "></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="psrut" style="he ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;" ><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style= "height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2"> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.550000000000000003em;margin-left:-0.13889em;margin-right: 0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist- s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="psrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​</span></span><span class ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right :0.27777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class= "mbin">−</span><span class="mspace" style="margin-right:0.22222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style= "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class=" vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</span> span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.22222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.22222222222222222em;"></span><span class="mord mathnormal" style=" margin-right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class= "vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p strut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span> </span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> <span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width=' 400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord mathnormal" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000003em;margin- left:-0.13889em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight">t</span></span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span></span></span></span></span></span></span></span></span><span style="top:-9.160540000000001em;"><span class ="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord text"><span class="mord textbf ">där:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="psrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span clas s="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord" >tillgångspris vid tidpunkten </span></span><span class="mord mathnormal">t</span></span></span><span style="top:-6.160540000000001em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">riskfri ränta – teoretisk ränta på en </span></span></span></span><span style="top:-4.660540000000001em;"><span class="psrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">tillgång utan risk</span></span>< /span></span><span style="top:-3.00000000000000018em;"><span class=" pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:- 3.2em;"><span class="psrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span><span style=" topp: -2,9 6054em;"><span class="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mspace" stil ="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mord text"><span class="mord">volatilitet (standardavvikelse) för tillgångspriset</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">volatilitet för den </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< span class="psrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class ="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em;"><span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; "><span class="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< svg width='400e m' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704,7,510,7,-1060,3,512,-1067

10 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span> <span style="top:0.16053999999999924em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">>< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class= "mord">långsiktig prisvariation</span></span></span></span><span style="top:1.6605399999999992em;"><span class="psrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">hastighet för återgång till </span></span ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">oändligt litet positivt tidssteg</span> </span></span></span><span style="top:4.660539999999998em;"><span class="psrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000003em;marginal-left:-0.13889em ;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span ></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel ">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">brunisk rörelse av tillgångspriset</span></span></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></ span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></ span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></ span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" stil ="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">Brownisk rörelse av tillgångens prisvariation</span></span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r">​ span class="vlist" style="height:9.821079999999998em;"><span></span></span></span></span></span></span></span></span ></span></span>

## Heston Model vs. Black-Scholes

Black-Scholes-modellen för prissättning av optioner introducerades på 1970-talet och fungerade som en av de första modellerna för att hjälpa investerare att härleda ett pris associerat med en option på ett [värdepapper](/security). I allmänhet bidrog det till att främja optionsinvesteringar eftersom det skapade en modell för att analysera priset på optioner på olika värdepapper.

Både Black-Scholes- och Heston-modellen är baserade på underliggande beräkningar som kan kodas och programmeras genom avancerade Excel eller andra kvantitativa system. Black-Scholes köpoptionsformel beräknas genom att multiplicera aktiekursen med den kumulativa normala normala sannolikhetsfördelningsfunktionen.

Därefter subtraheras [nettonuvärdet](/npv) (NPV) av lösenpriset multiplicerat med den kumulativa standardnormalfördelningen från det resulterande värdet av den tidigare beräkningen.

I matematisk notation,

>

> Ring = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

Omvänt kan värdet av en säljoption beräknas med hjälp av formeln:

>

> Put = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

I båda formlerna är S aktiekursen, K är lösenpriset, r är den riskfria räntan och T är tiden till förfall.

Formeln för d~1~ är:

>

> (ln(S/K) + (r + (Annualized Volatility)^2^/2) * T)/(Annualized Volatility * (T^0,5^))

>

Formeln för d~2~ är:

>

> d1 – (Annualized Volatility) * (T^0,5^)

>

## Särskilda överväganden

Heston-modellen är anmärkningsvärd eftersom den försöker sörja för en av de viktigaste begränsningarna för Black-Scholes-modellen som håller volatiliteten konstant. Användningen av stokastiska variabler i Heston-modellen ger uppfattningen att volatiliteten inte är konstant utan godtycklig.

Både den grundläggande Black-Scholes-modellen och Heston-modellen ger fortfarande bara uppskattningar av optionsprissättningen för en europeisk option, som är en option som endast kan utnyttjas på dess utgångsdatum. Olika forskning och modeller har studerats för prissättning av amerikanska alternativ genom både Black-Scholes och Heston-modellen. Dessa variationer ger uppskattningar för optioner som kan utnyttjas på vilket datum som helst fram till förfallodagen, vilket är fallet för amerikanska optioner.

## Höjdpunkter

– Det betyder att modellen utgår från att volatiliteten är godtycklig, till skillnad från Black-Scholes-modellen som håller volatiliteten konstant.

- Heston-modellen är en optionsprismodell som använder stokastisk volatilitet.

– Heston-modellen är en typ av volatilitetssmile-modell, som är en grafisk representation av flera alternativ med identiska utgångsdatum som visar ökande volatilitet när alternativen blir mer ITM eller OTM.

