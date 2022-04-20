---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: Heston Modeli
description: Adını Steve Heston&#39;dan alan Heston Modeli, finansal profesyoneller tarafından Avrupa opsiyonlarını fiyatlandırmak için kullanılan bir tür stokastik oynaklık modelidir.
---

# Heston Modeli
## Heston Modeli Nedir?

Adını Steve Heston'dan alan Heston Modeli, [Avrupa opsiyonlarını fiyatlandırmak için kullanılan bir tür stokastik oynaklık modelidir](/europeanoption).

## Heston Modelini Anlamak

çeşitli menkul kıymetler üzerindeki [opsiyonların](/option) fiyatlandırılması için kullanılabilecek bir opsiyon fiyatlama modelidir . Daha popüler olan [Black-Scholes opsiyon fiyatlandırma modeliyle karşılaştırılabilir](/blackscholes).

Genel olarak, opsiyon fiyatlandırma modelleri, ileri düzey yatırımcılar tarafından, finansal piyasada temel bir menkul kıymet üzerinde ticaret yaparak belirli bir opsiyonun fiyatını tahmin etmek ve ölçmek için kullanılır. Seçenekler, tıpkı temel güvenlikleri gibi, işlem günü boyunca değişen fiyatlara sahip olacaktır. Opsiyon fiyatlandırma modelleri, yatırım için en iyi opsiyon fiyatını belirlemek için opsiyon fiyatlarında dalgalanmaya neden olan değişkenleri analiz etmeye ve entegre etmeye çalışır.

[Stokastik](/stochastic-volatility) bir oynaklık modeli olarak Heston Modeli, oynaklığın keyfi olduğu varsayımıyla opsiyon fiyatlandırmasını hesaplamak ve tahmin etmek için istatistiksel yöntemler kullanır. Oynaklığın sabit değil keyfi olduğu varsayımı, stokastik oynaklık modellerini benzersiz kılan temel faktördür. Diğer stokastik oynaklık modelleri arasında SABR modeli, Chen modeli ve [GARCH](/generalalizedautogregressiveconditionalheteroskedasticity) modeli bulunur.

## Temel Farklılıklar

Heston Modeli, onu diğer stokastik oynaklık modellerinden ayıran özelliklere sahiptir:

- Bir hisse senedinin fiyatı ile oynaklığı arasında olası bir korelasyonu hesaba katar.

- Ortalamaya dönerek oynaklığı ifade eder.

- Kapalı formlu bir çözüm verir, yani cevabın kabul edilen bir matematiksel işlemler kümesinden türetildiği anlamına gelir.

- Hisse senedi fiyatlarının lognormal bir olasılık dağılımı izlemesini gerektirmez.

Heston Modeli de bir tür [volatilite gülümseme modelidir](/volatilitysmile). "Gülümseme", aynı sona erme tarihlerine sahip çeşitli seçeneklerin grafiksel bir temsili olan ve seçenekler daha fazla [parada](/inthemoney) (ITM) veya [parasız](/outofthemoney) [(](/outofthemoney) OTM) hale geldikçe artan oynaklık gösteren oynaklık gülümsemesini ifade eder . Gülümseme modelinin adı, grafiğin bir gülümsemeyi andıran içbükey şeklinden gelmektedir.

## Heston Model Metodolojisi

Heston Modeli, Black-Scholes opsiyon fiyatlandırma modelinde sunulan bazı eksikliklerin üstesinden gelmeyi amaçlayan fiyatlandırma seçenekleri için kapalı biçimli bir çözümdür. Heston Modeli, ileri düzey yatırımcılar için bir araçtır.

### Hesaplama şu şekildedir:

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mtable rowspacing="0.24999999999999992em " columnalign="sağ sol" columnpacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo Stretchy="false">(</mo><mi> mo><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo Stretchy="false">) </mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">burada:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>zamandaki varlık fiyatı </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>risksiz faiz oranı – teorik oran bir</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle scriptlevel= "0" displaystyle="true"><mrow><mrow></mrow><mtext>risk taşımayan varlık</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>volatilite (standart varlık fiyatının sapması)</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo>=</mi mo><mtext></mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> değişkenliği </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>uzun vadeli fiyat farkı</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" konumuna geri dönme oranı ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <mi>t</mi><mo>=</mo><mtext>süresiz küçük pozitif zaman artışı</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> </mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> <mtext>Varlık fiyatının Brown hareketi</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow ></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> <mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>Varlığın fiyat farkının Brown hareketi</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{nerede:} \\ &amp;S_t = \text{varlık fiyatı anda } t \\ &amp;r = \text{risksiz faiz oranı -- bir} \\ &amp;\text{risksiz varlık üzerindeki teorik oran} \\ &amp;\sqrt{ V_t } = \text{ varlık fiyatının oynaklığı (standart sapması) \\ &amp;\sigma = \text{volatilite } \sqrt{ V_t } \\ &amp;\theta = \text{uzun vadeli fiyat farkı} \\ &amp;k = \text{dönüş oranı } \theta \\ &amp;dt = \text{süresiz küçük pozitif zaman artışı} \\ &amp;W_{1t} = \text{Varlık fiyatının Brown hareketi} \\ &amp;W_ {2t} = \text{Varlığın fiyat farkının Brown hareketi} \\ \end{hizalanmış}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="strut" style="height:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">< span class="vlist-r"><span class="vlist" style="height:10.3210800000000002em;"><span style="top:-12.3210800000000002em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.0000000000000018em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.6605399999999998em;">< span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:6.1605399999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.8210799999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:10.321080000000002em;"><span style="üst:-12.3210800000000002em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="üst:-2.550000000000003em;sol kenar boşluğu:-0.05764em;sağ kenar boşluğu:0.05em;"><span class="pstrut" style="yükseklik: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span>< span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> span></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"> <span style="top:-2.5500000000000003em;sol kenar boşluğu:-0.05764em;sağ kenar boşluğu:0.05em;"><span class="pstrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" kenar-sağ:0.222222222222222em;"></span><span class="mbin">+</span><span class="mspace" sty le="margin-right:0.222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="pstrut" style="height:3.2em; "></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="üst:-2.55000000000000003em;sol kenar boşluğu:-0.22222em;sağ kenar boşluğu:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="he ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' korumaAspectRatio='xMinYMin dilim'><path d='M263.681c0.7,0,18,39.7,52.119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52,5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3.567,-271.3.567c-38.7.80.7,-84,175,-136.283c-52.108,-89.167.185.3,-111.5.232

c-22.3.46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="üst:-2.5500000000000003em;sol kenar boşluğu:-0.05764em;sağ kenar boşluğu:0.05em;" ><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style= "height:0.15em;"><span></span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2"> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;sol kenar boşluğu:-0.13889em;sağ kenar boşluğu: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist- s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="üst:-2.550000000000000em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​</span></span><span class ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span ><span class="mspace" style="margin-right:0.27777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right :0.27777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.222222222222222em;"></span><span class= "mbin">−</span><span class="mspace" style="margin-right:0.222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style= "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;sol kenar boşluğu:-0.22222em;sağ kenar boşluğu: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class=" vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</ span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.222222222222222em;"></span><span class="mord mathnormal" style=" margin-right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class= "vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p strut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="üst:-2.55000000000000003em;sol kenar boşluğu:-0.22222em;sağ kenar boşluğu:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span> </span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> <span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width=' 400em' yükseklik='1.28em' viewBox='0 0 400000 1296' koruAspectRatio='xMinYMin dilim'><yol d='M263.681c0.7,0,18,39.7,52.119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52,5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3.567,-271.3.567c-38.7.80.7,-84,175,-136.283c-52.108,-89.167.185.3,-111.5.232

c-22.3.46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span><span class="mord matematik normal" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin- left:-0.13889em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight">t</span></span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span></span></span></span></span></span></span></span></span><span style="top:-9.160540000000001em;"><span class ="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord text"><span class="mord textbf ">nerede:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="üst:-2.55000000000000003em;sol kenar boşluğu:-0.05764em;sağ kenar boşluğu:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.277777777777777em;"></span><span clas s="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class="mord" >zamandaki varlık fiyatı </span></span><span class="mord mathnormal">t</span></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.27777777777778em;"></span><span class="mord text"><span class="mord">risksiz faiz oranı – teorik faiz oranı </span></span></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">risk taşımayan varlık</span></span>< /span></span><span style="top:-3.00000000000000018em;"><span class=" pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="üst:- 3.2em;"><span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="üst:-2.5500000000000003em;sol kenar boşluğu:-0.22222em;sağ kenar boşluğu:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span><span style=" üst:-2.9 6054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' korumaAspectRatio='xMinYMin dilim'><path d='M263.681c0.7,0,18,39.7,52.119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52,5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3.567,-271.3.567c-38.7.80.7,-84,175,-136.283c-52.108,-89.167.185.3,-111.5.232

c-22.3.46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mspace" stili ="margin-right:0.277777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777777em;"></span ><span class="mord text"><span class="mord">varlık fiyatının oynaklığı (standart sapma)</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.277777777777777em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">volatilitesi </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="üst:-2.5500000000000003em;sol kenar boşluğu:-0.22222em;sağ kenar boşluğu:0.05em;"><span sınıfı ="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em;"><span></span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; "><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< svg genişliği='400e m' height='1.28em' viewBox='0 0 400000 1296' koruAspectRatio='xMinYMin dilim'><path d='M263.681c0.7,0,18,39.7,52.119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52,5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3.567,-271.3.567c-38.7.80.7,-84,175,-136.283c-52.108,-89.167.185.3,-111.5.232

c-22.3.46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span></span> <span style="top:0.160539999999924em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.27777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777777em;"></span><span class="mord text"><span class= "mord">uzun vadeli fiyat farkı</span></span></span></span><span style="top:1.6605399999999992em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class="mord"> </span></span'a geri dönme oranı ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.27777777777778em;"></span><span class="mord text"><span class="mord">süresiz küçük pozitif zaman artışı</span> </span></span></span><span style="top:4.6605399999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">G</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000003em;sol kenar boşluğu:-0.13889em ;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span ></span></span></span></span></span><span class="mspace" style="margin-right:0.277777777777777em;"></span><span class="mrel ">=</span><span class="mspace" style="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">Brown hareketi varlık fiyatı</span></span></span></span><span style="top:6.1605399999999998em;"><span class="pstrut" style="height:3.00054em;"></span span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.55000000000000003em;sol kenar boşluğu:-0.13889em;sağ kenar boşluğu:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span></span></span></span> span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></ span></span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace" stili ="margin-right:0.27777777777777778em;"></span><span class="mord text"><span class="mord">Varlığın fiyat farkının Brown hareketi</span></span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r">< span class="vlist" style="height:9.8210799999999998em;"><span></span></span></span></span></span></span></span></span></span ></span></span>

## Heston Modeli ve Black-Scholes

Opsiyon fiyatlandırması için Black-Scholes modeli 1970'lerde tanıtıldı ve yatırımcıların [menkul kıymet üzerindeki bir opsiyonla ilişkili bir fiyat elde etmelerine yardımcı olan ilk modellerden biri olarak hizmet etti](/security). Genel olarak, çeşitli menkul kıymetler üzerindeki seçeneklerin fiyatını analiz etmek için bir model oluşturduğundan, opsiyon yatırımını teşvik etmeye yardımcı oldu.

Hem Black-Scholes hem de Heston Modeli, gelişmiş Excel veya diğer nicel sistemler aracılığıyla kodlanabilen ve programlanabilen temel hesaplamalara dayanmaktadır. Black-Scholes alım opsiyonu formülü, hisse senedi fiyatının kümülatif standart normal olasılık dağılım fonksiyonu ile çarpılmasıyla hesaplanır.

Daha sonra, kullanım fiyatının [net bugünkü değeri](/npv) (NPV), kümülatif standart normal dağılım ile çarpılır ve önceki hesaplamanın sonuç değerinden çıkarılır.

Matematiksel gösterimde,

>

> Çağrı = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

Tersine, bir satım opsiyonunun değeri aşağıdaki formül kullanılarak hesaplanabilir:

>

> Koy = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

Her iki formülde de S hisse senedi fiyatı, K kullanım fiyatı, r risksiz faiz oranı ve T vadeye kalan zamandır.

d~1~ formülü:

>

> (ln(S/K) + (r + (Yıllık Oynaklık)^2^/2) * T)/(Yıllık Oynaklık * (T^0.5^))

>

d~2~ formülü:

>

> d1 – (Yıllıklandırılmış Oynaklık) * (T^0.5^)

>

## Özel Hususlar

Heston Modeli dikkat çekicidir çünkü Black-Scholes modelinin oynaklığı sabit tutan ana sınırlamalarından birini sağlamaya çalışmaktadır. Heston Modelinde stokastik değişkenlerin kullanımı, oynaklığın sabit değil keyfi olduğu fikrini sağlar.

Hem temel Black-Scholes modeli hem de Heston Modeli, yalnızca sona erme tarihinde uygulanabilen bir Avrupa seçeneği için yalnızca seçenek fiyatlandırma tahminleri sağlar. Hem Black-Scholes hem de Heston Modeli aracılığıyla Amerikan seçeneklerinin fiyatlandırılması için çeşitli araştırmalar ve modeller incelenmiştir. Bu varyasyonlar, Amerikan opsiyonlarında olduğu gibi, vade tarihine kadar herhangi bir tarihte uygulanabilecek opsiyonlar için tahminler sağlar.

## Öne Çıkanlar

- Bu, oynaklığı sabit tutan Black-Scholes modelinin aksine, modelin oynaklığın keyfi olduğunu varsaydığı anlamına gelir.

- Heston Modeli, stokastik oynaklığı kullanan bir opsiyon fiyatlandırma modelidir.

- Heston Modeli, seçenekler daha fazla ITM veya OTM haline geldikçe artan oynaklık gösteren aynı son kullanma tarihlerine sahip birkaç seçeneğin grafiksel bir temsili olan bir tür oynaklık gülümseme modelidir.

