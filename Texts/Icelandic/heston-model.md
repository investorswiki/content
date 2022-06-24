---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: Heston fyrirmynd
description: Heston líkanið, nefnt eftir Steve Heston, er tegund af stokastískri sveiflulíkan sem fjármálasérfræðingar nota til að verðleggja evrópska valkosti.
---

# Heston fyrirmynd
## Hvað er Heston fyrirmyndin?

Heston líkanið, nefnt eftir Steve Heston, er tegund af stochastic flöktunarlíkani sem notað er til að verðleggja [evrópska valkosti](/europeanoption).

## Að skilja Heston líkanið

Heston líkanið, þróað af dósent Steven Heston í fjármálum árið 1993, er valréttarverðlagningarlíkan sem hægt er að nota til að verðleggja [valkosti](/option) á ýmsum verðbréfum. Það er sambærilegt við vinsælli [Black-Scholes valréttarverðslíkanið](/blackscholes).

Á heildina litið eru valréttarverðlagningarlíkön notuð af háþróuðum fjárfestum til að áætla og meta verð tiltekins valréttar, sem eiga viðskipti með undirliggjandi verðbréf á fjármálamarkaði. Valkostir, rétt eins og undirliggjandi öryggi þeirra, munu hafa verð sem breytast allan viðskiptadaginn. Valréttarverðlagningarlíkön leitast við að greina og samþætta þær breytur sem valda sveiflum í verði valréttar til að finna besta valréttarverðið fyrir fjárfestingu.

Sem [stokastískt](/stochastic-volatility) flöktslíkan notar Heston líkanið tölfræðilegar aðferðir til að reikna út og spá fyrir um verðlagningu valréttar með þeirri forsendu að flökt sé handahófskennt. Forsenda þess að flökt sé handahófskennt, frekar en stöðugt, er lykilatriðið sem gerir stochastic flöktunarlíkön einstök. Aðrar gerðir af stokastískum sveiflulíkönum eru SABR líkanið, Chen líkanið og [GARCH](/generalalizedautogregressiveconditionalheteroskedasticity) líkanið.

## Lykilmunur

Heston líkanið hefur eiginleika sem aðgreina það frá öðrum stokastískum sveiflulíkönum, þ.e.

- Það tekur þátt í mögulegri fylgni milli verðs hlutabréfa og flökts þess.

- Það miðlar óstöðugleika sem að hverfa aftur til meðaltalsins.

- Það gefur lausn á lokuðu formi, sem þýðir að svarið er dregið af viðurkenndu mengi stærðfræðilegra aðgerða.

- Það krefst þess ekki að hlutabréfaverð fylgi logeðlilegri líkindadreifingu.

Heston líkanið er líka tegund [flöktsbroslíkans](/volatilitysmile). "Smile" vísar til sveiflubrossins, myndræna framsetningu á nokkrum valkostum með sömu gildistíma sem sýna vaxandi sveiflur eftir því sem valmöguleikarnir verða meira [í peningunum](/inthemoney) (ITM) eða [out-of](/outofthemoney) [-the-money](/outofthemoney) (OTM). Nafn brosmódelsins er dregið af íhvolfu lögun línuritsins, sem líkist brosi.

## Heston Model Aðferðafræði

Heston líkanið er lokuð lausn fyrir verðlagningarvalkosti sem leitast við að vinna bug á sumum göllunum sem fram koma í Black-Scholes valréttarverðlagningarlíkani. Heston líkanið er tæki fyrir háþróaða fjárfesta.

### Útreikningurinn er sem hér segir:

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mtable rowspacing="0.24999999999999992em " columnalign="right left" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo stretchy="false">(</ mo><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo stretchy="false">) </mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">þar sem:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>eignaverð á tíma </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>áhættulausir vextir – fræðilegir vextir á</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle scriptlevel= "0" displaystyle="true"><mrow><mrow></mrow><mtext>eign án áhættu</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>sveiflur (staðall frávik) eignaverðs</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo></ mo><mtext>sveiflur </mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>langtíma verðfrávik</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> hlutfall afturhvarfs í </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <mi>t</mi><mo>=</mo><mtext>endanlega lítil jákvæð tímaaukning</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> </mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> <mtext>Brownísk hreyfing eignaverðs</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow ></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> <mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>Brownísk hreyfing á verðfráviki eignarinnar</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{þar:} \\ &amp;S_t = \text{eignaverð á tíma } t \\ &amp;r = \text{áhættulausir vextir -- fræðilegir vextir á} \\ &amp;\text{eign sem ber enga áhættu} \\ &amp;\sqrt{ V_t } = \text{ óstöðugleiki (staðalfrávik) eignaverðs} \\ &amp;\sigma = \text{sveiflur } \sqrt{ V_t } \\ &amp;\theta = \text{langtímaverðsfrávik} \\ &amp;k = \text{hraði afturhvarfs í } \theta \\ &amp;dt = \text{óákveðinn lítill jákvæður tími} \\ &amp;W_{1t} = \text{Brúnhreyfing eignaverðs} \\ &amp;W_ {2t} = \text{Brownísk hreyfing á verðfráviki eignarinnar} \\ \end{aligned}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="strut" style="height:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">>< span class="vlist-r"><span class="vlist" style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="psrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.00000000000000018em ;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.660539999999998em;">< span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:6.160539999999998em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.821079999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="psrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span>< span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></ span></span></span></span></span></span><span class="mspace" style="margin-right:0.27777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"> <span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" sty le="margin-right:0.2222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="pstrut" style="height:3.2em; "></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="psrut" style="hann ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin sneið'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3.512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;" ><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style= "height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2"> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.550000000000000003em;margin-left:-0.13889em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist- s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="psrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-s">​</span></span><span class ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right :0.27777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class= "mbin">−</span><span class="mspace" style="margin-right:0.22222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style= "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class=" vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</span> span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.22222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.22222222222222222em;"></span><span class="mord mathnormal" style=" margin-right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class= "vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p strut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span> </span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> <span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width=' 400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin sneið'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3.512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord mathnormal" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000003em;margin- left:-0.13889em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight">t</span></span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span></span></span></span></span></span></span></span></span><span style="top:-9.160540000000001em;"><span class ="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord text"><span class="mord textbf ">þar:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="psrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span clas s="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord" >eignaverð á sínum tíma </span></span><span class="mord mathnormal">t</span></span></span><span style="top:-6.160540000000001em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">áhættulausir vextir – fræðilegir vextir á </span></span></span></span><span style="top:-4.660540000000001em;"><span class="psrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">eign án áhættu</span></span>< /span></span><span style="top:-3.00000000000000018em;"><span class=" pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:- 3.2em;"><span class="psrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span><span style=" efst: -2,9 6054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin sneið'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3.512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mspace" stíll ="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mord text"><span class="mord">sveiflur (staðalfrávik) eignaverðs</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord"></span><span class ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">sveiflur í </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< span class="psrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.55000000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class ="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em;"><span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; "><span class="psrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< svg width='400e m' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin sneið'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3.512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271,3,567,-271,3,567c-38,7,80,7,-84,175,-136,283c-52,108,-89,167,185,3,-111,5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72,7,-168,-109,3,-252,-110,-252c-10,7,8,-22,16,7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span> <span style="top:0.16053999999999924em;"><span class="psrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">>< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class= "mord">langtíma verðfrávik</span></span></span></span><span style="top:1.6605399999999992em;"><span class="psrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">hraði afturhvarfs í </span></span ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">endanlega lítil jákvæð tímaaukning</span> </span></span></span><span style="top:4.660539999999998em;"><span class="psrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000003em;margin-left:-0.13889em ;margin-right:0.05em;"><span class="psrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span ></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel ">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">brúnísk hreyfing á eignaverðið</span></span></span></span><span style="top:6.160539999999998em;"><span class="psrut" style="height:3.00054em;"></ span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></ span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></ span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" stíll ="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">Brownísk hreyfing á verðfráviki eignarinnar</span></span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r">​ span class="vlist" style="height:9.821079999999998em;"><span></span></span></span></span></span></span></span></span ></span></span>

## Heston Model gegn Black-Scholes

Black-Scholes líkanið fyrir verðlagningu valréttar var kynnt á áttunda áratugnum og þjónaði sem ein af fyrstu gerðum til að hjálpa fjárfestum að fá verð sem tengist valrétti á [verðbréfi](/security). Almennt hjálpaði það til við að efla valréttarfjárfestingu þar sem það skapaði líkan til að greina verð á valréttum á ýmsum verðbréfum.

Bæði Black-Scholes og Heston líkanið byggjast á undirliggjandi útreikningum sem hægt er að kóða og forrita í gegnum háþróað Excel eða önnur magnkerfi. Black-Scholes kaupréttarformúlan er reiknuð út með því að margfalda hlutabréfaverðið með uppsöfnuðu venjulegu líkindadreifingarfalli.

Síðan er [nettó núvirði](/npv) (NPV) verkfallsverðs margfaldað með uppsafnaðri staðlaðri normaldreifingu dregin frá verðmæti fyrri útreiknings.

Í stærðfræðilegri nótnaskrift,

>

> Kalla = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

Hins vegar væri hægt að reikna út verðmæti söluréttar með formúlunni:

>

> Setja = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

Í báðum formúlunum er S hlutabréfaverð, K er verkfallsgengi, r er áhættulausir vextir og T er tími til gjalddaga.

Formúlan fyrir d~1~ er:

>

> (ln(S/K) + (r + (Annualized Volatility)^2^/2) * T)/(Annualized Volatility * (T^0.5^))

>

Formúlan fyrir d~2~ er:

>

> d1 – (Annualized Volatility) * (T^0,5^)

>

## Sérstök atriði

Heston líkanið er athyglisvert vegna þess að það leitast við að sjá fyrir einni af helstu takmörkunum Black-Scholes líkansins sem heldur stöðugu óstöðugleika. Notkun stochastískra breyta í Heston líkaninu gerir ráð fyrir þeirri hugmynd að sveiflur séu ekki stöðugar heldur handahófskenndar.

Bæði grunn Black-Scholes líkanið og Heston líkanið gefa enn aðeins upp áætlanir um verðlagningu valréttar fyrir evrópskan valrétt, sem er valréttur sem aðeins er hægt að nýta á gildistíma hans. Ýmsar rannsóknir og líkön hafa verið rannsökuð til að verðleggja bandaríska valkosti í gegnum bæði Black-Scholes og Heston líkanið. Þessar breytingar gefa áætlanir um valrétti sem hægt er að nýta á hvaða dagsetningu sem er fram að gjalddaga, eins og raunin er fyrir bandaríska valkosti.

## Hápunktar

- Þetta þýðir að líkanið gerir ráð fyrir að sveiflur séu handahófskenndar, öfugt við Black-Scholes líkanið sem heldur stöðugu sveiflum.

- Heston líkanið er valréttarverðlagningarlíkan sem notar stokastískt flökt.

- Heston líkanið er tegund flöktsbroslíkans, sem er myndræn framsetning á nokkrum valkostum með sömu fyrningardagsetningar sem sýna vaxandi sveiflur eftir því sem valkostirnir verða fleiri ITM eða OTM.

