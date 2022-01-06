---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: Model Heston
description: Model Heston, dinamakan sempena Steve Heston, ialah sejenis model turun naik stokastik yang digunakan oleh profesional kewangan untuk menetapkan harga pada pilihan Eropah.
---

# Model Heston
## Apakah Model Heston?

Model Heston, dinamakan sempena Steve Heston, ialah sejenis model turun naik stokastik yang digunakan untuk menetapkan harga [pilihan Eropah](/europeanoption).

## Memahami Model Heston

Model Heston, yang dibangunkan oleh profesor kewangan bersekutu Steven Heston pada tahun 1993, ialah model penentuan harga opsyen yang boleh digunakan untuk [pilihan penetapan harga](/option) pada pelbagai sekuriti. Ia setanding dengan [model harga pilihan Black-Scholes yang lebih popular](/blackscholes).

Secara keseluruhan, model penentuan harga opsyen digunakan oleh pelabur maju untuk menganggar dan mengukur harga pilihan tertentu, berdagang pada keselamatan asas dalam pasaran kewangan. Pilihan, sama seperti keselamatan asasnya, akan mempunyai harga yang berubah sepanjang hari dagangan. Model penentuan harga opsyen berusaha untuk menganalisis dan menyepadukan pembolehubah yang menyebabkan turun naik harga opsyen untuk mengenal pasti harga opsyen terbaik untuk pelaburan.

Sebagai model [turun naik stokastik](/stochastic-volatility),. Model Heston menggunakan kaedah statistik untuk mengira dan meramalkan harga opsyen dengan andaian bahawa turun naik adalah sewenang-wenangnya. Andaian bahawa turun naik adalah sewenang-wenangnya, bukannya tetap, adalah faktor utama yang menjadikan model turun naik stokastik unik. Jenis model turun naik stokastik lain termasuk model SABR, model Chen dan model [GARCH](/generalalizedautogregressiveconditionalheteroskedasticity).

## Perbezaan Utama

Model Heston mempunyai ciri-ciri yang membezakannya daripada model turun naik stokastik yang lain, iaitu:

- Ia memfaktorkan kemungkinan korelasi antara harga saham dan turun naiknya.

- Ia menyampaikan turun naik sebagai berbalik kepada min.

- Ia memberikan penyelesaian bentuk tertutup, bermakna jawapan diperoleh daripada set operasi matematik yang diterima.

- Ia tidak memerlukan harga saham mengikut taburan kebarangkalian lognormal.

Model Heston juga merupakan jenis [model senyuman turun naik](/volatilitysmile). "Senyuman" merujuk kepada senyuman turun naik, gambaran grafik beberapa pilihan dengan tarikh tamat tempoh yang sama yang menunjukkan turun naik yang semakin meningkat apabila pilihan menjadi lebih [dalam wang](/inthemoney) (ITM) atau [keluar](/outofthemoney) [wang](/outofthemoney) (OTM). Nama model senyuman berasal daripada bentuk graf cekung, yang menyerupai senyuman.

## Metodologi Model Heston

Model Heston ialah penyelesaian bentuk tertutup untuk pilihan penetapan harga yang berusaha untuk mengatasi beberapa kelemahan yang dibentangkan dalam model penentuan harga opsyen Black-Scholes. Model Heston ialah alat untuk pelabur maju.

### Pengiraan adalah seperti berikut:

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantik><mtable rowspacing="0.24999999999999992em " columnalign="right left" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo stretchy="false">(</ mo><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo stretchy="false">) </mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">di mana:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>harga aset pada masa </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>kadar faedah tanpa risiko – kadar teori pada</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle scriptlevel= "0" displaystyle="true"><mrow><mrow></mrow><mtext>aset tidak membawa risiko</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>volatiliti (standard sisihan) harga aset</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo>=</ mo><mtext>kemeruapan </mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>varian harga jangka panjang</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> kadar pengembalian kepada </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <mi>t</mi><mo>=</mo><mtext>kenaikan masa positif yang kecil selama-lamanya</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> </mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> <mtext>Pergerakan coklat harga aset</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow ></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> <mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>Gerakan coklat bagi varians harga aset</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{di mana:} \\ &amp;S_t = \text{harga aset pada masa } t \\ &amp;r = \text{kadar faedah bebas risiko -- kadar teoretikal pada} \\ &amp;\text{aset tidak membawa risiko} \\ &amp;\sqrt{ V_t } = \text{ turun naik (sisihan piawai) harga aset} \\ &amp;\sigma = \text{volatiliti } \sqrt{ V_t } \\ &amp;\theta = \text{varian harga jangka panjang} \\ &amp;k = \text{kadar pengembalian kepada } \theta \\ &amp;dt = \text{kenaikan masa positif yang kecil selama-lamanya} \\ &amp;W_{1t} = \text{Pergerakan coklat harga aset} \\ &amp;W_ {2t} = \text{Gerakan coklat bagi varians harga aset} \\ \end{aligned}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="strut" style="height:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">< span class="vlist-r"><span class="vlist" style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.0000000000000018em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.660539999999998em;">< span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.821079999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- kanan:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span>< span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></ span></span></span></span></span></span><span class="mspace" style="margin-right:0.27777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"> <span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" sty le="margin-right:0.2222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="pstrut" style="height:3.2em; "></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:">2.7em; </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="dia ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;" ><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style= "height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2"> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist- s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist-s">​</span></span><span class ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right :0.277777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.222222222222222em;"></span><span class= "mbin">−</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><span class="mord mathnormal" style= "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class=" vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</ span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.222222222222222em;"></span><span class="mord mathnormal" style=" margin-right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class= "vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p strut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span> </span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> <span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg width=' 400em' ketinggian='1.28em' viewBox='0 0 400000 1296' preserveAspectNisbah='xMinYMin hirisan'><laluan d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord mathnormal" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin- kiri:-0.13889em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight">t</span></span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< span></span></span></span></span></span></span></span></span><span style="top:-9.160540000000001em;"><kelas span ="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord text"><span class="mord textbf ">di mana:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:">2.7em; </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span kelas s="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord" >harga aset pada masa </span></span><span class="mord mathnormal">t</span></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class="mord">kadar faedah tanpa risiko – kadar teori pada sesuatu </span></span></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">aset tidak membawa risiko</span></span>< /span></span><span style="top:-3.0000000000000018em;"><span class=" pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:- 3.2em;"><span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.550000000000003em;margin-left:-0.22222em;margin-right:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span><span style=" atas:-2.9 6054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg width='400em' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><path d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span><span class="mspace" style ="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mord text"><span class="mord">kemeruapan (sisihan piawai) harga aset</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">kemeruapan </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.550000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class ="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15 em;"><span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; "><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< lebar svg='400e m' height='1.28em' viewBox='0 0 400000 1296' preserveAspectRatio='xMinYMin slice'><laluan d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span></span> <span style="top:0.16053999999999924em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.277777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class= "mord">varian harga jangka panjang</span></span></span></span><span style="top:1.6605399999999992em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">kadar pengembalian kepada </span></span ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">kenaikan masa positif yang kecil selama-lamanya</span> </span></span></span><span style="top:4.660539999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em ;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span ></span></span></span></span></span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel ">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord text"><span class="mord">Gerakan coklat harga aset</span></span></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></ span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.550000000000003em;margin-left:-0.13889em;margin-right:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></ span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></ span></span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span><span class="mspace" gaya ="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">Gerakan coklat bagi varians harga aset</span></span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r">< span class="vlist" style="height:9.821079999999998em;"><span></span></span></span></span></span></span></span></span ></span></span>

## Model Heston lwn. Black-Scholes

Model Black-Scholes untuk penetapan harga opsyen telah diperkenalkan pada tahun 1970-an dan berfungsi sebagai salah satu model pertama untuk membantu pelabur memperoleh harga yang berkaitan dengan pilihan pada [sekuriti](/security). Secara umum, ia membantu mempromosikan pelaburan opsyen kerana ia mencipta model untuk menganalisis harga opsyen pada pelbagai sekuriti.

Kedua-dua Model Black-Scholes dan Heston adalah berdasarkan pengiraan asas yang boleh dikodkan dan diprogramkan melalui Excel lanjutan atau sistem kuantitatif lain. Formula opsyen panggilan Black-Scholes dikira dengan mendarabkan harga saham dengan fungsi taburan kebarangkalian normal standard kumulatif.

Selepas itu, [nilai kini bersih](/npv) (NPV) harga mogok didarab dengan taburan normal piawai kumulatif ditolak daripada nilai terhasil pengiraan sebelumnya.

Dalam tatatanda matematik,

>

> Panggilan = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

Sebaliknya, nilai opsyen jual boleh dikira menggunakan formula:

>

> Letakkan = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

Dalam kedua-dua formula, S ialah harga saham, K ialah harga mogok, r ialah kadar faedah bebas risiko, dan T ialah masa untuk matang.

Formula untuk d~1~ ialah:

>

> (ln(S/K) + (r + (Kemeruapan Tahunan)^2^/2) * T)/(Kemeruapan Tahunan * (T^0.5^))

>

Formula untuk d~2~ ialah:

>

> d1 – (Kemeruapan Tahunan) * (T^0.5^)

>

## Pertimbangan Khas

Model Heston patut diberi perhatian kerana ia bertujuan untuk menyediakan salah satu batasan utama model Black-Scholes yang mengekalkan kemeruapan yang tetap. Penggunaan pembolehubah stokastik dalam Model Heston memberikan tanggapan bahawa turun naik tidak tetap tetapi sewenang-wenangnya.

Kedua-dua model asas Black-Scholes dan Model Heston masih hanya menyediakan anggaran harga opsyen untuk pilihan Eropah, yang merupakan pilihan yang hanya boleh dilaksanakan pada tarikh tamat tempohnya. Pelbagai penyelidikan dan model telah dikaji untuk menetapkan harga pilihan Amerika melalui kedua-dua Black-Scholes dan Model Heston. Variasi ini memberikan anggaran untuk pilihan yang boleh dilaksanakan pada mana-mana tarikh yang membawa kepada tarikh tamat tempoh, seperti yang berlaku untuk pilihan Amerika.

## Sorotan

- Ini bermakna bahawa model menganggap bahawa turun naik adalah sewenang-wenangnya, berbeza dengan model Black-Scholes yang mengekalkan volatiliti tetap.

- Model Heston ialah model penentuan harga pilihan yang menggunakan turun naik stokastik.

- Model Heston ialah sejenis model senyuman turun naik, yang merupakan perwakilan grafik beberapa pilihan dengan tarikh tamat tempoh yang sama yang menunjukkan turun naik yang semakin meningkat apabila pilihan menjadi lebih ITM atau OTM.

