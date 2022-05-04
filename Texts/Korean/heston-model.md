---
keywords: Trading,Options and Derivatives Trading,Advanced Options Trading Concepts,Options and Derivatives,Advanced Concepts
title: 헤스톤 모델
description: Steve Heston의 이름을 딴 Heston 모델은 금융 전문가가 유럽 옵션의 가격을 책정하는 데 사용하는 일종의 확률적 변동성 모델입니다.
---

# 헤스톤 모델
## 헤스톤 모델이란?

Steve Heston의 이름을 딴 Heston 모델은 [유럽 옵션 의 가격을 책정하는 데 사용되는 일종의 확률적 변동성 모델](/europeanoption) 입니다.

## 헤스톤 모델 이해하기

1993년 재무 부교수 Steven Heston이 개발한 Heston 모델은 다양한 증권에 대한 [옵션 가격 책정에 사용할 수 있는 옵션 가격 책정 모델입니다.](/option) 이는 더 인기 있는 [Black-Scholes 옵션 가격 책정 모델 과 비슷합니다](/blackscholes).

전반적으로 옵션 가격 책정 모델은 고급 투자자가 금융 시장의 기본 증권을 거래하는 특정 옵션의 가격을 추정하고 측정하는 데 사용됩니다. 옵션은 기본 증권과 마찬가지로 거래일 내내 가격이 변경됩니다. 옵션가격결정모형은 최적의 옵션가격을 파악하기 위해 옵션가격의 변동을 유발하는 변수를 분석하고 통합하고자 한다.

[확률적 변동성](/stochastic-volatility) 모델인 Heston 모델은 변동성이 임의적이라는 가정 하에 통계적 방법을 사용하여 옵션 가격을 계산하고 예측합니다 . 변동성이 일정하지 않고 임의적이라는 가정은 확률적 변동성 모델을 고유하게 만드는 핵심 요소입니다. 다른 유형의 확률적 변동성 모델에는 SABR 모델, Chen 모델 및 [GARCH](/generalalizedautogregressiveconditionalheteroskedasticity) 모델이 있습니다.

## 주요 차이점

Heston 모델은 다른 확률적 변동성 모델과 구별되는 다음과 같은 특징이 있습니다.

- 주식 가격과 변동성 간의 가능한 상관 관계를 고려합니다.

- 평균으로 회귀하면서 변동성을 전달합니다.

- 닫힌 형식의 솔루션을 제공합니다. 즉, 답변이 허용되는 수학 연산 집합에서 파생됩니다.

- 주가가 로그 정규 확률 분포를 따를 필요는 없습니다.

[변동성 스마일 모델](/volatilitysmile) 의 일종이기도 합니다 . "스마일"은 옵션이 더 [내](/inthemoney) 가격(ITM) 또는 [외 가격(](/outofthemoney) [OTM )](/outofthemoney) 이 될수록 변동성이 증가하는 동일한 만료 날짜를 가진 여러 옵션의 그래픽 표현인 변동성 스마일을 나타냅니다 . 스마일 모델의 이름은 미소를 닮은 그래프의 오목한 모양에서 파생됩니다.

## 헤스톤 모델 방법론

Heston 모델은 Black-Scholes 옵션 가격 책정 모델에 나타난 몇 가지 단점을 극복하고자 하는 가격 책정 옵션에 대한 폐쇄형 솔루션입니다. Heston 모델은 고급 투자자를 위한 도구입니다.

### 계산은 다음과 같습니다.

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><의미론><mtable rowspacing="0.2499999999999992em " columnalign="오른쪽 왼쪽" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi><msub><mi>S</mi><mi>t</mi> </msub><mo>=</mo><mi>r</mi><msub><mi>S</mi><mi>t</mi></msub><mi>d</mi ><mi>t</mi><mo>+</mo><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><msub> <mi>S</mi><mi>t</mi></msub><mi>d</mi><msub><mi>W</mi><mrow><mn>1</mn> <mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true" ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <msub><mi>V</mi><mi>t</mi></msub><mo>=</mo><mi>k</mi><mo stretchy="false">(</ mo><mi>θ</mi><mo>−</mo><msub><mi>V</mi><mi>t</mi></msub><mo stretchy="false">) </mo><mi>d</mi><mi>t</mi><mo>+</mo><mi> σ</mi><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mi>d</mi><msub><mi>W </mi><mrow><mn>2</mn><mi>t</mi></mrow></msub></mrow></mstyle></mtd></mtr><mtr> <mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow> <mrow></mrow><mtext mathvariant="bold">여기서:</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub> <mi>S</mi><mi>t</mi></msub><mo>=</mo><mtext>시간의 자산 가격 </mtext><mi>t</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>r</mi><mo>=</mo><mtext>무위험 이자율 – 이론상 이자율 </mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></ mstyle></mtd><mtd><mstyle 스크립트 레벨= "0" displaystyle="true"><mrow><mrow></mrow><mtext>위험이 없는 자산</mtext></mrow></mstyle></mtd></mtr><mtr>< mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow>< mrow></mrow><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt><mo>=</mo><mtext>변동성(표준 편차) 자산 가격</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>σ</mi><mo>=</ mo><mtext>변동성 </mtext><msqrt><msub><mi>V</mi><mi>t</mi></msub></msqrt></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><mi>θ</mi><mo>=</mo><mtext>장기 가격 변동</mtext></mrow> </mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle ></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>k</mi><mo>=</mo><mtext> </mtext><mi>θ</mi></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"로의 복귀 비율 ><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><mi>d</mi> <mi>t</mi><mo>=</mo><mtext>무한하게 작은 양수 시간 증가</mtext></mrow></mstyle></mtd></mtr><mtr><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow> </mrow><msub><mi>W</mi><mrow><mn>1</mn><mi>t</mi></mrow></msub><mo>=</mo> <mtext>자산 가격의 브라운 모션</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow ></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>W</mi> <mrow><mn>2</mn><mi>t</mi></mrow></msub><mo>=</mo><mtext>자산 가격 변동의 브라운 운동</mte xt></mrow></mstyle></mtd></mtr></mtable><annotation encoding="application/x-tex">\begin{aligned} &amp;dS_t = rS_tdt + \sqrt{ V_t } S_tdW_{1t} \\ &amp;dV_t = k ( \theta - V_t ) dt+ \sigma \sqrt{ V_t } dW_{2t} \\ &amp;\textbf{여기서:} \\ &amp;S_t = \text{자산 가격 at time } t \\ &amp;r = \text{무위험 이자율 -- 이론적 이자율} \\ &amp;\text{무위험 자산} \\ &\sqrt{ V_t } = \text{ 자산 가격의 변동성(표준 편차)} \\ &amp;\sigma = \text{변동성 } \sqrt{ V_t } \\ &amp;\theta = \text{장기 가격 변동} \\ &k = \text{복귀율 } \theta \\ &amp;dt = \text{무한하게 작은 양수 시간 증가} \\ &amp;W_{1t} = \text{자산 가격의 브라운 운동} \\ &amp;W_ {2t} = \text{자산 가격 변동의 브라운 운동} \\ \end{aligned}</annotation></semantics></math></span><span class="katex-html " aria-hidden="true"><span class="base"><span class="strut" style="height:20.14216em;vertical-align:-9.82107 9999999998em;"></span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2">< span class="vlist-r"><span class="vlist" style="height:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="높이 :3.00054em;"></span><span class="mord"></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="높이 :3.00054em;"></span><span class="mord"></span></span><span style="top:-9.160540000000001em;"><span class="pstrut" style="높이 :3.00054em;"></span><span class="mord"></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="높이 :3.00054em;"></span><span class="mord"></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="높이 :3.00054em;"></span><span class="mord"></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="높이 :3.00054em;"></span><span class="mord"></span></span><span style="top:-3.0000000000000018em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:-1.3394600000000008em ;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:0.16053999999999924em; "><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:1.6605399999999992em;" ><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:3.1605399999999992em;"> <span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span><span style="top:4.660539999999998em;">< 스팬 클래스="pstrut" 스타일="높이:3.00054em;"></span><span class="mord"></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:9.821079999999998em;"><span></span></span></span ></span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " 스타일="높이:10.321080000000002em;"><span style="top:-12.321080000000002em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"><span class="mord mathnormal" style="margin- right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" 스타일="높이: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight"></span></span></span></span>< span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></ 스팬></span></span></span></span></span><span class="mspace" style="margin-right:0.27777777777 77778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.02778em;">r</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em;">S</ 스팬><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이:0.280555999999999em;"> <span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span>< span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight"></span></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span> </span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style=" margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" 스타일 le="margin-right:0.2222222222222222em;"></span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="pstrut" 스타일="높이:3.2em; "></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord mathnormal" style="margin-right:0.22222em; ">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이: 0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight"></span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="그 ight:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg 너비='400em' 높이='1.28em' viewBox='0 0 400000 1296' 보존AspectRatio='xMinYMin 슬라이스'><경로 d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.05764em;">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;" ><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</span> </span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" 스타일= "높이:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">d</span>< span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist- t2"> <span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight"></span></span></span></span></span><span class="vlist- s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span> </span></span></span></span></span></span><span style="top:-10.660540000000001em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span><span class="mord"> <span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= "vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margi n-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight" ><span class="mord mathnormal mtight"></span></span></span></span><span class="vlist-s">​</span></span><span 클래스 ="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right :0.2777777777777778em;"></span><span class="mord mathnormal" style="margin-right:0.03148em;">k</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class= "mbin">−</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><span class="mord 수학 일반" 스타일= "margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"> <span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right: 0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t </span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class=" vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mclose">)</ span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right:0.2222222222222222em;">< /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord mathnormal" style=" margin-right:0.03588em;">σ</span><span class="mord sqrt"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class= "vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;"><span class="p strut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><span class="mord 수학 일반" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight"></span></span></span> </span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"> <span></span></span></span></span></span></span></span></span><span style="top:-2.96054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;"><svg 너비=' 400em' 높이='1.28em' viewBox='0 0 400000 1296' reservedAspectRatio='xMinYMin 슬라이스'><경로 d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mord 수학정규" >d</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><스팬 클래스 = "vlist-t vlist-t2"> <span class = "vlist-r"> <span class = "vlist"style = "높이 : 0.30110799999993em;"> <span style = "상단 : -2.550000000000003em; 마진- 왼쪽:-0.13889em;여백-오른쪽:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mtight"><span class="mord mtight">2</span><span class="mord mathnormal mtight"></span></span></span></span>< /span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;">< 스팬></span></span></span></span></span></span></span></span><span style="top:-9.160540000000001em;"><스팬 클래스 ="프스트럿" 스타일="높이:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord 텍스트"><span class="mord textbf ">위치:</span></span></span></span><span style="top:-7.660540000000001em;"><span class="pstrut" style="height:3.00054em;"> </span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05764em; ">S</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이: 0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.05764em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"> </span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight"></span></span></span></span><span class="vlist -s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span ></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span 클래스 s="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord 텍스트"><span class="mord" >당시 자산 가격 </span></span><span class="mord mathnormal"></span></span></span><span style="top:-6.160540000000001em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord 수학 일반" 스타일=" margin-right:0.02778em;">r</span><span class="mspace" style="margin-right:0.277777777777778em;"></span><span class="mrel">=</span> <span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">무위험 이자율 – 이론상 이자율 </span></span></span></span><span style="top:-4.660540000000001em;"><span class="pstrut" style="height:3.00054em;"></span> <span class="mord"><span class="mord"></span><span class="mord text"><span class="mord">위험이 없는 자산</span></span>< /span></span><span style="top:-3.0000000000000018em;"><span class=" pstrut" 스타일="높이:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord sqrt"><span class=" vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:- 3.2em;"><span class="pstrut" style="height:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord "><span class="mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em ;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">t</ 스팬></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" 스타일="높이:0.15em;"><span></span></span></span></span></span></span></span></span><span 스타일=" 상단:-2.9 6054em;"><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;" ><svg 너비='400em' 높이='1.28em' viewBox='0 0 400000 1296' reservedAspectRatio='xMinYMin 슬라이스'><경로 d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span><span class="mspace" 스타일 ="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mord text"><span class="mord">자산 가격의 변동성(표준 편차)</span></span></span></span><span style="top: -1.3394600000000008em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span 클래스 ="mord mathnormal" style="margin-right:0.03588em;">σ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class=" mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">변동성 </span></span><span class="mord sqrt"><span class="vlist-t vlist-t2 "><span class="vlist-r"><span class="vlist" style="height:1.00054em;"><span class="svg-align" style="top:-3.2em;">< 스팬 클래스="pstrut" 스타일="높이:3.2em;"></span><span class="mord" style="padding-left:1em;"><span class="mord"><스팬 클래스= "mord mathnormal" style="margin-right:0.22222em;">V</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r "><span class="vlist" style="height:0.2805559999999999em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class ="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight"></span></span> </span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" 스타일="높이:0.15 em;"><span></span></span></span></span></span></span></span></span><span style="top:-2.96054em; "><span class="pstrut" style="height:3.2em;"></span><span class="hide-tail" style="min-width:1.02em;height:1.28em;">< svg 너비 = '400e m' 높이='1.28em' viewBox='0 0 400000 1296'preserveAspectRatio='xMinYMin 슬라이스'><경로 d='M263,681c0.7,0,18,39.7,52,119

c34,79.3,68.167,158.7,102.5,238c34.3,79.3,51.8,119.3,52.5,120

c340,-704.7,510.7,-1060.3,512,-1067

l0 -0

c4.7,-7.3,11,-11,19,-11

H40000v40H1012.3

s-271.3,567,-271.3,567c-38.7,80.7,-84,175,-136,283c-52,108,-89.167,185.3,-111.5,232

c-22.3,46.7,-33.8,70.3,-34.5,71c-4.7,4.7,-12.3,7,-23,7s-12,-1,-12,-1

s-109,-253,-109,-253c-72.7,-168,-109.3,-252,-110,-252c-10.7,8,-22,16.7,-34,26

c-22,17.3,-33.3,26,-34,26s-26,-26,-26,-26s76,-59,76,-59s76,-60,76,-60z

M1001 80h400000v40h-400000z'/></svg></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r "><span class="vlist" style="height:0.23946em;"><span></span></span></span></span></span></span></span> <span style="top:0.16053999999999924em;"><span class="pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord">< /span><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span ><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class= "mord">장기 가격 변동</span></span></span></span><span style="top:1.6605399999999992em;"><span class="pstrut" style="height:3.00054 em;"></span><span class="mord"><span class="mord"></span><span class="mord Mathnormal" style="margin-right:0.03148em;">k< /span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><s pan class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">복귀율 </span></span ><span class="mord mathnormal" style="margin-right:0.02778em;">θ</span></span></span><span style="top:3.1605399999999992em;"><span class= "pstrut" style="height:3.00054em;"></span><span class="mord"><span class="mord"></span><span class="mord mathnormal">d</span ><span class="mord mathnormal"></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span ><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">무한하게 작은 양의 시간 증분</span> </span></span></span><span style="top:4.660539999999998em;"><span class="pstrut" style="height:3.00054em;"></span><span class=" mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vl ist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em ;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">1</span><span class="mord mathnormal mtight">t</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span ></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel ">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">브라운 운동 자산 가격</span></span></span></span><span style="top:6.160539999999998em;"><span class="pstrut" style="height:3.00054em;"></ 스팬><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"> <span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.13889em;margin-right:0.05em;"><span class=" pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">2</ span><span class="mord mathnormal mtight"></span></span></span></span></span><span class="vlist-s">​</span></ 스팬><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></ 스팬></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" 스타일 ="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">자산 가격 변동의 브라운 운동</span></span></span ></span></span><span class="vlist-s">​</span></span><span class="vlist-r">< 스팬 클래스="vlist" 스타일="높이:9.821079999999998em;"><span></span></span></span></span></span></span></span></span ></span></span>

## 헤스톤 모델 vs. 블랙숄즈

옵션 가격 책정을 위한 블랙숄즈 모델은 1970년대에 도입되었으며 투자자들이 유가 증권 옵션과 관련된 가격을 도출하는 데 도움이 되는 최초의 모델 중 하나 [였습니다](/security). 일반적으로 다양한 유가 증권의 옵션 가격을 분석하는 모델을 만들어 옵션 투자를 촉진하는 데 도움이되었습니다.

Black-Scholes와 Heston 모델은 모두 고급 Excel 또는 기타 정량 시스템을 통해 코딩 및 프로그래밍할 수 있는 기본 계산을 기반으로 합니다. Black-Scholes 콜옵션 공식은 주가에 누적 표준 정규 확률 분포 함수를 곱하여 계산됩니다.

이후 행사가격의 [순현재가치](/npv) (NPV)에 누적표준정규분포를 곱한 값을 이전 계산의 결과값에서 뺀다.

수학 표기법에서,

>

> 호출 = S * N(d~1~) – K~e~^(-r * T) * N(d^~2~^)^

>

반대로 풋옵션의 가치는 다음 공식을 사용하여 계산할 수 있습니다.

>

> Put = K~e~^(-r * T) * N(-d2)^ – S * N(-d~1~)

>

두 공식에서 S는 주가, K는 행사 가격, r은 무위험 이자율, T는 만기까지의 시간입니다.

d~1~의 공식은 다음과 같습니다.

>

> (ln(S/K) + (r + (연간 변동성)^2^/2) * T)/(연간 변동성 * (T^0.5^))

>

d~2~의 공식은 다음과 같습니다.

>

> d1 – (연간 변동성) * (T^0.5^)

>

## 특별 고려 사항

Heston 모델은 변동성을 일정하게 유지하는 Black-Scholes 모델의 주요 한계 중 하나를 제공하려고 하기 때문에 주목할 만합니다. Heston 모델에서 확률적 변수의 사용은 변동성이 일정하지 않고 임의적이라는 개념을 제공합니다.

기본 Black-Scholes 모델과 Heston 모델은 모두 만기일에만 행사할 수 있는 옵션인 유럽 옵션에 대한 옵션 가격 추정만 제공합니다. Black-Scholes와 Heston 모델을 통해 미국식 옵션의 가격을 결정하기 위해 다양한 연구와 모델이 연구되었습니다. 이러한 변동은 미국 옵션의 경우와 같이 만기일까지 이어지는 모든 날짜에 행사할 수 있는 옵션에 대한 추정치를 제공합니다.

## 하이라이트

- 이는 변동성을 일정하게 유지하는 Black-Scholes 모델과 달리 변동성이 임의적이라고 가정함을 의미합니다.

- Heston 모델은 확률적 변동성을 활용한 옵션 가격 책정 모델입니다.

- Heston 모델은 변동성 스마일 모델의 일종으로, 옵션이 ITM 또는 OTM이 증가함에 따라 변동성이 증가하는 동일한 만료 날짜를 가진 여러 옵션을 그래픽으로 표현한 것입니다.

