---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: Model Heston
description: Model Hestona, nazwany na cześć Steve&#39;a Hestona, jest rodzajem stochastycznego modelu zmienności stosowanego przez specjalistów finansowych do wyceny opcji europejskich.
---

# Model Heston
## Jaki jest model Hestona?

Model Hestona, nazwany na cześć Steve'a Hestona, jest rodzajem stochastycznego modelu zmienności stosowanego do wyceny [opcji europejskich](/europeanoption).

## Zrozumienie modelu Heston

Model Hestona, opracowany przez profesora nadzwyczajnego finansów Stevena Hestona w 1993 roku, jest modelem wyceny opcji, który można wykorzystać do wyceny [opcji](/option) na różne papiery wartościowe. Jest on porównywalny z bardziej popularnym [modelem wyceny opcji Black-Scholes](/blackscholes).

Ogólnie rzecz biorąc, modele wyceny opcji są używane przez zaawansowanych inwestorów do oszacowania i oceny ceny konkretnej opcji, handlując bazowym papierem wartościowym na rynku finansowym. Opcje, podobnie jak ich bazowe zabezpieczenia, będą miały ceny zmieniające się w ciągu dnia handlowego. Modele wyceny opcji mają na celu analizę i integrację zmiennych, które powodują wahania cen opcji w celu określenia najlepszej ceny opcji dla inwestycji.

Jako [stochastyczny model zmienności](/stochastic-volatility),. model Hestona wykorzystuje metody statystyczne do obliczania i prognozowania cen opcji przy założeniu, że zmienność jest arbitralna. Założenie, że zmienność jest arbitralna, a nie stała, jest kluczowym czynnikiem, który sprawia, że stochastyczne modele zmienności są wyjątkowe. Inne typy stochastycznych modeli zmienności obejmują model SABR, model Chen i model [GARCH](/generalalizedautogregressiveconditionalheteroskedasticity).

## Kluczowe różnice

Model Hestona posiada cechy odróżniające go od innych stochastycznych modeli zmienności, a mianowicie:

- Uwzględnia możliwą korelację między ceną akcji a jej zmiennością.

- Przekazuje zmienność jako powrót do średniej.

- Daje rozwiązanie w formie zamkniętej, co oznacza, że odpowiedź pochodzi z przyjętego zestawu operacji matematycznych.

- Nie wymaga, aby ceny akcji podążały za logarytmicznym rozkładem prawdopodobieństwa.

Model Hestona jest również rodzajem [modelu uśmiechu zmienności](/volatilitysmile). „Uśmiech” odnosi się do uśmiechu zmienności, graficznej reprezentacji kilku opcji z identycznymi datami wygaśnięcia, które wykazują rosnącą zmienność, gdy opcje stają się coraz bardziej [in-the-money](/inthemoney) (ITM) lub [out-of -the](/outofthemoney) [-money](/outofthemoney) (OTM). Nazwa modelu uśmiechu wywodzi się od wklęsłego kształtu wykresu, który przypomina uśmiech.

## Metodologia modelu Heston

Model Heston to zamknięte rozwiązanie do wyceny opcji, które ma na celu przezwyciężenie niektórych niedociągnięć przedstawionych w modelu wyceny opcji Blacka-Scholesa. Model Heston to narzędzie dla zaawansowanych inwestorów.

### Kalkulacja wygląda następująco:

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mtable rowspacing="0.24999999999999992em " columnalign="prawy lewy" columnpacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo stretchy="false">(</ mo><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo stretchy="false">) </mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">gdzie:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>cena aktywów w czasie </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>stopa procentowa wolna od ryzyka – stopa teoretyczna na</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle scriptlevel= „0” displaystyle="true"><mrow><mrow></mrow><mtext>zasób bez ryzyka</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>zmienność (standard odchylenie) ceny aktywów</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo>=</ mo><mtext>zmienność </mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>długoterminowa zmienność cen</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> wskaźnik powrotu do </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <mi>t</mi><mo>=</mo><mtext>nieskończenie mały dodatni przyrost czasu</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> </mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> <mtext>Ruch Browna ceny aktywów</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow ></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> <mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>Ruch Browna wariancji ceny aktywa</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{gdzie:} \\ &amp;S_t = \text{cena aktywów w czasie } t \\ &amp;r = \text{stopa procentowa wolna od ryzyka -- teoretyczna stopa dla} \\ &amp;\text{aktywa bez ryzyka} \\ &amp;\sqrt{ V_t } = \text{ zmienność (odchylenie standardowe) ceny aktywów} \\ &amp;\sigma = \text{zmienność } \sqrt{ V_t } \\ &amp;\theta = \text{długoterminowa zmienność ceny} \\ &amp;k = \text{szybkość powrotu do } \theta \\ &amp;dt = \text{nieskończenie mały dodatni przyrost czasu} \\ &amp;W_{1t} = \text{ruch Browna ceny aktywów} \\ &amp;W_ {2t} = \text{Ruch Browna wariancji ceny aktywów} \\ \end{aligned}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="rozpórka" style="height:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">< span class="vlist-r"><span class="vlist" style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.0000000000000018em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.660539999999998em;">< span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.8210799999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- po prawej:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span>< span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></ span></span></span></span></span></span><span class="mspace" style="margin-right:0.277777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"> <span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" sty le="margin-right:0.2222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="pstrut" style="height:3.2em; ></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0,2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0,22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="he ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' zachowajAspectRatio='xMinYMin wycinek'><ścieżka d='M263,681c0.7,0,18,39,7,52,119

c34,79,3,68.167,158,7,102,5,238c34,3,79,3,51,8,119,3,52,5,120

c340,-704,7,510,7,-1060,3512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3567,-271.3567c-38.7.80.7,-84.175,-136.283c-52.108,-89.167,185,3,-111.5,232

c-22.3.46,7,-33.8,70,3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109,3,-252,-110,-252c-10.7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;" ><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style= "height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2"> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist- s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​</span></span><span class ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span ><span class="mspace" style="margin-right:0.277777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right :0.27777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class= "mbin">−</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style= "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class=" vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</ span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord mathnormal" style=" margin-right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class= "vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p rozpórka" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span> </span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> <span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width=' 400em' height='1,28em' viewBox='0 0 400000 1296' zachowajAspectRatio='xMinYMin wycinek'><ścieżka d='M263,681c0,7,0,18,39,7,52,119

c34,79,3,68.167,158,7,102,5,238c34,3,79,3,51,8,119,3,52,5,120

c340,-704,7,510,7,-1060,3512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3567,-271.3567c-38.7.80.7,-84.175,-136.283c-52.108,-89.167,185,3,-111.5,232

c-22.3.46,7,-33.8,70,3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109,3,-252,-110,-252c-10.7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord mathnormal" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;marża- left:-0.13889em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight">t</span></span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span></span></span></span></span></span></span></span></span><span style="top:-9.16054000000001em;"><span class ="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord text"><span class="mord textbf ">gdzie:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0,2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span clas s="mrel">=</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord" >cena aktywów w czasie </span></span><span class="mord mathnormal">t</span></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">stopa procentowa wolna od ryzyka – teoretyczna stopa </span></span></span></span><span style="top:-4.6605400000000001em;"><span class="pstrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">zasób bez ryzyka</span></span>< /span></span><span style="top:-3.0000000000000018em;"><span class=" pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:- 3.2em;"><span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span><span style=" góra:-2,9 6054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg width='400em' height='1,28em' viewBox='0 0 400000 1296' zachowajAspectRatio='xMinYMin wycinek'><path d='M263,681c0,7,0,18,39,7,52,119

c34,79,3,68.167,158,7,102,5,238c34,3,79,3,51,8,119,3,52,5,120

c340,-704,7,510,7,-1060,3512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3567,-271.3567c-38.7.80.7,-84.175,-136.283c-52.108,-89.167,185,3,-111.5,232

c-22.3.46,7,-33.8,70,3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109,3,-252,-110,-252c-10.7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r Styl „><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mspace" ="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span ><span class="mord text"><span class="mord">zmienność (odchylenie standardowe) ceny aktywów</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">zmienność </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class ="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em;"><span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; "><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< szerokość svg='400e m' height='1,28em' viewBox='0 0 400000 1296' zachowajAspectRatio='xMinYMin wycinek'><ścieżka d='M263,681c0,7,0,18,39,7,52,119

c34,79,3,68.167,158,7,102,5,238c34,3,79,3,51,8,119,3,52,5,120

c340,-704,7,510,7,-1060,3512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3567,-271.3567c-38.7.80.7,-84.175,-136.283c-52.108,-89.167,185,3,-111.5,232

c-22.3.46,7,-33.8,70,3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109,3,-252,-110,-252c-10.7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span> <span style="top:0.16053999999999924em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777777778em;"></span><span class="mord text"><span class= "mord">długoterminowa zmienność cen</span></span></span></span><span style="top:1.6605399999999992em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.277777777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.277777777777777778em;"></span><span class="mord text"><span class="mord">współczynnik powrotu do </span></span ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.277777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">nieskończenie mały dodatni przyrost czasu</span> </span></span></span><span style="top:4.6605399999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em ;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span ></span></span></span></span></span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mrel ">=</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">Ruch Browna cena aktywów</span></span></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></ span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></ span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></ span></span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mrel">=</span><span class="mspace" styl ="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">Ruch Browna wariancji ceny aktywa</span></span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r">< span class="vlist" style="height:9.82107999999998em;"><span></span></span></span></span></span></span></span></span ></span></span>

## Model Heston kontra Black-Scholes

Model Blacka-Scholesa do wyceny opcji został wprowadzony w latach 70. XX wieku i służył jako jeden z pierwszych modeli pomagających inwestorom w określeniu ceny związanej z opcją na papier [wartościowy](/security). Ogólnie pomogło to w promowaniu inwestowania w opcje, ponieważ stworzyło model analizy cen opcji na różne papiery wartościowe.

Zarówno model Blacka-Scholesa, jak i model Hestona opierają się na podstawowych obliczeniach, które można zakodować i zaprogramować za pomocą zaawansowanego programu Excel lub innych systemów ilościowych. Formuła opcji kupna Blacka-Scholesa jest obliczana poprzez pomnożenie ceny akcji przez skumulowaną funkcję standardowego rozkładu normalnego prawdopodobieństwa.

Następnie [wartość bieżąca netto](/npv) (NPV) ceny wykonania pomnożona przez skumulowany standardowy rozkład normalny jest odejmowana od wartości wynikowej z poprzedniego obliczenia.

W notacji matematycznej

>

> Połączenie = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

Odwrotnie, wartość opcji sprzedaży można obliczyć za pomocą wzoru:

>

> Put = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

W obu formułach S to cena akcji, K to cena wykonania, r to wolna od ryzyka stopa procentowa, a T to czas do zapadalności.

Wzór na d~1~ to:

>

> (ln(S/K) + (r + (Zmienność roczna)^2^/2) * T)/(Zmienność roczna * (T^0,5^))

>

Wzór na d~2~ to:

>

> d1 – (Zmienność roczna) * (T^0,5^)

>

## Uwagi specjalne

Model Hestona jest godny uwagi, ponieważ stara się zapewnić jedno z głównych ograniczeń modelu Blacka-Scholesa, który utrzymuje stałą zmienność. Użycie zmiennych stochastycznych w modelu Hestona zakłada, że zmienność nie jest stała, ale arbitralna.

Zarówno podstawowy model Blacka-Scholesa, jak i model Hestona nadal dostarczają jedynie szacunkowych wycen opcji dla opcji europejskiej, która jest opcją, którą można zrealizować dopiero w dniu jej wygaśnięcia. Przeprowadzono różne badania i modele wyceny opcji amerykańskich za pomocą zarówno modelu Blacka-Scholesa, jak i modelu Hestona. Zmiany te dostarczają oszacowań opcji, które można zrealizować w dowolnym dniu poprzedzającym datę wygaśnięcia, tak jak ma to miejsce w przypadku opcji amerykańskich.

## Przegląd najważniejszych wydarzeń

- Oznacza to, że model zakłada, że zmienność jest arbitralna, w przeciwieństwie do modelu Blacka-Scholesa, który utrzymuje stałą zmienność.

- Model Hestona to model wyceny opcji, który wykorzystuje zmienność stochastyczną.

- Model Hestona jest rodzajem modelu uśmiechu zmienności, który jest graficzną reprezentacją kilku opcji z identycznymi datami wygaśnięcia, które wykazują rosnącą zmienność, gdy opcje stają się coraz bardziej ITM lub OTM.

