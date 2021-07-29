---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: 다중 선형 회귀(MLR)
description: 다중 선형 회귀(MLR)는 여러 설명 변수를 사용하여 응답 변수의 결과를 예측하는 통계 기법입니다.
---

# 다중 선형 회귀(MLR)
## 다중 선형 회귀(MLR)란 무엇입니까?

간단히 다중 회귀라고도 하는 다중 선형 회귀(MLR)는 여러 설명 변수를 사용하여 응답 변수의 결과를 예측하는 통계 기법입니다. 다중 선형 회귀의 목표는 설명(독립) 변수와 응답(종속) 변수 간의 [선형 관계 를 모델링하는 것입니다. 본질적으로 다중 회귀는](/linearrelationship) 하나 이상의 설명 변수를 포함하기 때문에 일반 최소 자승(OLS) [회귀 의 확장입니다.](/regression)

## 다중 선형 회귀의 공식 및 계산

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><의미론><mtable rowspacing="0.2499999999999992em " columnalign="오른쪽 왼쪽" columnspacing="0em"><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>y</mi><mi>i</mi></msub><mo>= </mo><msub><mi>β</mi><mn>0</mn></msub><mo>+</mo><msub><mi>β</mi><mn>1 </mn></msub><msub><mi>x</mi><mrow><mi>i</mi><mn>1</mn></mrow></msub><mo>+ </mo><msub><mi>β</mi><mn>2</mn></msub><msub><mi>x</mi><mrow><mi>i</mi>< mn>2</mn></mrow></msub><mo>+</mo><mi mathvariant="normal">.</mi><mi mathvariant="normal">.</mi>< mi mathvariant="normal">.</mi><mo>+</mo><msub><mi>β</mi><mi>p</mi></msub><msub><mi>x </mi><mrow><mi>i</mi><mi>p</mi></mrow></msub><mo>+</mo><mi>ϵ</mi></mrow ></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd> <mstyle scriptlevel="0" displaystyle="true"> <mrow><mrow></mrow><mrow><mtext mathvariant="bold">여기서,</mtext><mtext> </mtext><mtext mathvariant="bold">용</mtext><mtext> </mtext></mrow><mi>i</mi><mo>=</mo><mi>n</mi><mrow><mtext> </mtext><mtext mathvariant="bold"> 관찰:</mtext></mrow></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></ mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>y</mi><mi> i</mi></msub><mo>=</mo><mtext>종속 변수</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></ mrow><msub><mi>x</mi><mi>i</mi></msub><mo>=</mo><mtext>설명 변수</mtext></mrow></mstyle> </mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel=" 0" displaystyle="true"><mrow><mrow></mrow><msub><mi>β</mi><mn>0</mn></msub><mo>=</mo>< mtext>y 절편(c 즉시)</mtext></mrow></mstyle></mtd></mtr><mtr><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow></mrow>< /mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow></mrow><msub><mi>β</mi><mi>p</ mi></msub><mo>=</mo><mtext>각 설명 변수에 대한 기울기 계수</mtext></mrow></mstyle></mtd></mtr><mtr><mtd>< mstyle scriptlevel="0" displaystyle="true"><mrow></mrow></mstyle></mtd><mtd><mstyle scriptlevel="0" displaystyle="true"><mrow><mrow>< /mrow><mi>ϵ</mi><mo>=</mo><mtext>모델의 오차항(잔차라고도 함)</mtext></mrow></mstyle></mtd>< /mtr></mtable><annotation encoding="application/x-tex">\begin{정렬}&amp;y_i = \beta_0 + \beta _1 x_{i1} + \beta _2 x_{i2} + ... + \beta _p x_{ip} + \epsilon\\&amp;\textbf{여기서, for } i = n \textbf{ 관찰:}\\&amp;y_i=\text{종속 변수}\\&amp;x_i=\ text{설명 변수}\\&amp;\beta_0=\text{y절편(상수항)}\\&amp;\beta_p=\text{각 설명 변수에 대한 기울기 계수 le}\\&amp;\epsilon=\text{모델의 오류 항(잔차라고도 함)}\end{aligned}</annotation></semantics></math></span>< span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:10.500000000000004em;vertical-align:-5.000000000000002em;">< /span><span class="mord"><span class="mtable"><span class="col-align-r"><span class="vlist-t vlist-t2"><span class="vlist -r"><span class="vlist" 스타일="높이:5.500000000000001em;"><span style="top:-7.500000000000001em;"><span class="pstrut" 스타일="높이:2.84em;" ></span><span class="mord"></span></span><span style="top:-6em;"><span class="pstrut" style="height:2.84em;"> </span><span class="mord"></span></span><span style="top:-4.499999999999999em;"><span class="pstrut" style="height:2.84em;"> </span><span class="mord"></span></span><span style="top:-2.999999999999999em;"><span class="pstrut" style="height:2.84em;"> </span><span class="mord"></span></span><span style="top:-1.4999999999999991em;"><span class="pstrut" style="height:2.84em;"></span><span class="mord"></span></span><span style="top:1.7763568394002505e-15em;">< 스팬 클래스="pstrut" 스타일="높이:2.84em;"></span><span class="mord"></span></span><span style="top:1.5000000000000018em;"><span class="pstrut" style="height:2.84em;"></span><span class="mord"></span></span></span><span class="vlist-s">​ </span></span><span class="vlist-r"><span class="vlist" style="height:5.000000000000002em;"><span></span></span></span> </span></span><span class="col-align-l"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이:5.500000000000001em;"><span style="top:-7.660000000000001em;"><span class="pstrut" style="height:3em;"></span><span class="mord" ><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class= "msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.31166399999999994em;"><span style="top : -2.5500000000000003em;margin-left:-0.03588em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="크기 재설정- size6 size3 mtight"><span class="mord mathnormal mtight"></span></span></span></span><span class="vlist-s"><​</span></ 스팬 ><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></ 스팬 ></span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" 스타일 = "margin-right:0.2777777777777778em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이:0.30110799999999993em;"><스팬 스타일= " 상단:-2.5500000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class=" 크기 재설정-size6 size3 mtight"><span class="mord mtight">0</span></span></span></ 스팬><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span> </span></span></span></span></span></span><span class="mspace" style="margin-right:0.222222222222222em;"></span><span 클래스 ="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><span class="mord Mathnormal" 스타일 ="margin-right:0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><스팬 클래스 ="vlist" style="height:0.30110799999999993em;"><span style="top:-2.550000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut" 스타일 ="높이:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span>< / 스팬><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" 스타일="높이:0.15em;">< 스팬> </span></span></span></span></span></span><span class="mord"><span class="mord mathnormal">x</span><span class= "msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.31166399999999994em;"><span style="top :-2.550000000000003em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="크기 재설정-크기6" size3 mtight"><span class="mord mtight"><span class="mord mathnormal mtight">i</span><span class="mord mtight">1</span></span></span> </span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="높이:0.15 em ;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2222222222222222em;"> < /span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord"><스팬 클래스 ="mord mathnormal" style="margin-right:0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist - r"><span class="vlist" 스타일="높이:0.30110799999999993em;"><span 스타일="상단:-2.550000000000 0003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s"><​</span></span>< span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span>< / span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class= " vlist-r"><span class="vlist" style="height:0.31166399999999994em;"><span style="top:-2.550000000000003em;margin-left:0em;margin-right:0.05em;">< span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord 수학 일반 mtight " >i</span><span class="mord mtight">2</span></span></span></span></span><span class="vlist-s"><​< /span ></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span>< /스팬 ></span></span>< span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.22222222222222222 em;"></span><span class="mord">.</span><span class="mord">.</span><span class="mord">.</span><span 클래스 ="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.22222222222222222em; "></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.05278em;">β</span><span class="msupsub"><스팬 클래스 ="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.15139200000000003em;"><span style="top:-2.55000000000000003em;margin- 왼쪽:-0.05278em;여백-오른쪽:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight">< span class="mord mathnormal mtight">p</span></span></span></span><span class="vlist-s"><​</span></span><span class= " vlist-r"><span class="vlist" style="height:0.286108em;"><span></ 스팬></span></span></span></span></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub "><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.311664em;"><span style="top:- 2.5500000000000003em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight "><span class="mord mtight"><span class="mord mathnormal mtight">i</span><span class="mord mathnormal mtight">p</span></span></span>< /span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="height:0.286108em ; "><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2222222222222222em;"></ span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222222222222222em;"></span><span class="mord mathnormal">ϵ</ 스팬></span></span><span style="top:-6.16em;"><span class="pstrut" style="height:3em;"></span><span class="m ord"><span class="mord"></span><span class="mord text"><span class="mord textbf">여기서, </span></span><span class="mord mathnormal">나는</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace " style="margin-right:0.2777777777777778em;"></span><span class="mord mathnormal">n</span><span class="mord text"><span class="mord textbf"> 관찰 :</span></span></span></span><span style="top:-4.659999999999999em;"><span class="pstrut" style="height:3em;"></span> <span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y< /span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일="높이:0.31166399999999994em;" ><span style="top:-2.5500000000000003em;margin-left:-0.03588em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span> <span class="sizing reset-size6 size3 mtight"><span class="mord 수학 일반 mtight">i</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"> <span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace " style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;">< /span><span class="mord text"><span class="mord">종속 변수</span></span></span></span><span style="top:-3.1599999999999993em;" ><span class="pstrut" style="height:3em;"></span><span class="mord"><span class="mord"></span><span class="mord">< span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist " 스타일="높이:0.31166399999999994em;"><span style="top:-2.5500000000000003em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" 스타일="높이:2.7 em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">i</span></span ></span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" 스타일="높이: 0.15 em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em;" > </span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="모드 텍스트"> < span class="mord">설명 변수</span></span></span></span><span style="top:-1.6599999999999993em;"><span class="pstrut" style="height: 3em;"></span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord mathnormal" style="margin-right :0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" 스타일 ="높이:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut" style="높이: 2. em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></sp ></span></span><span class="vlist-s"></span></span><span class="vlist-r"><span class="vlist" style="높이: 0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2777777777777778em; " ></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="모드 텍스트" > <span class="mord">y 절편(상수)</span></span></span></span><span style="top:-0.15999999999999837em;"><span class=" pstrut " 스타일="높이:3em;"></span><span class="mord"><span class="mord"></span><span class="mord"><span class="mord 수학" style="margin-right:0.05278em;">β</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r">< 스팬 class="vlist" style="height:0.15139200000000003em;"><span style="top:-2.5500000000000003em;margin-left:-0.05278em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">p</span></span></span></span><span class="vlist-s"></span></span><span class="vlist-r">< 스팬 class="vlist" style="height:0.286108em;"><span></span></span></span></span></span></span><span class="mspace" 스타일 ="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2777777777777778em;"></ span ><span class="mord text"><span class="mord">각 설명 변수에 대한 기울기 계수</span></span></span></span><span style="top:1.3400000000000016em ; "><span class="pstrut" style="height:3em;"></span><span class="mord"><span class="mord"></span><span class="mord 수학정규 " >ϵ</span><span class="mspace" style="margin-right:0.2777777777777778em;"></span><span class="mrel">=</span><span class="mspace" 스타일 ="margin-right:0.2777777777777778em;"></span><span class="mord text"><span class="mord">모델의 오차항(잔차라고도 함)</span></span ></span></span></span><span class="vlist-s"></span></span><span class="v list-r"><span class="vlist" style="height:5.000000000000002em;"><span></span></span></span></span></span></span>< /span></span></span></span>



## 다중 선형 회귀가 알려줄 수 있는 것

단순 선형 회귀는 분석가나 통계학자가 다른 변수에 대해 알려진 정보를 기반으로 한 변수에 대해 예측할 수 있도록 하는 기능입니다. 선형 회귀는 독립 변수와 종속 변수라는 두 개의 연속 변수가 있는 경우에만 사용할 수 있습니다. 독립 변수는 종속 변수 또는 결과를 계산하는 데 사용되는 매개변수입니다. 다중 회귀 모델은 여러 설명 변수로 확장됩니다.

다중 회귀 모델은 다음 가정을 기반으로 합니다.

- 종속변수와 독립변수 사이에는 [선형 관계 가 있습니다.](/linearrelationship)

서로 [상관관계 가](/correlation) 너무 높지 않음

- y~i~ 관측치는 모집단에서 독립적으로 무작위로 선택됩니다.

평균이 0이고 [분산 이](/variance) **σ** 인 [정규 분포](/normaldistribution) 여야 합니다.

[결정 계수 (](/coefficient-of-determination) [R- 제곱)는 결과](/coefficient-of-determination) 의 변동이 독립 변수의 변동으로 설명될 수 있는 정도를 측정하는 데 사용되는 통계적 메트릭입니다. 예측 변수가 결과 변수와 관련이 없을 수도 있지만 MLR 모델에 더 많은 예측 변수가 추가될수록 R^2^는 항상 증가합니다.

따라서 R^2^ 자체는 모델에 포함되어야 하는 예측 변수와 제외해야 하는 예측 변수를 식별하는 데 사용할 수 없습니다. R^2^는 0과 1 사이에만 있을 수 있습니다. 여기서 0은 어떤 독립 변수로도 결과를 예측할 수 없음을 나타내고 1은 독립 변수에서 오류 없이 결과를 예측할 수 있음을 나타냅니다.

다중 회귀의 결과를 해석할 때 베타 계수는 다른 모든 변수를 일정하게 유지하면서 유효합니다("다른 모든 변수는 동일함"). 다중 회귀의 출력은 방정식으로 가로로 표시하거나 테이블 형식으로 세로로 표시할 수 있습니다.

## 다중 선형 회귀를 사용하는 방법의 예

예를 들어, 분석가는 시장의 움직임이 ExxonMobil(XOM)의 가격에 어떤 영향을 미치는지 알고 싶어할 수 있습니다. 이 경우 선형 방정식은 독립 변수 또는 예측 변수로 S&P 500 지수 값을, 종속 변수로 XOM 가격을 갖습니다.

실제로 여러 요인이 이벤트의 결과를 예측합니다. 예를 들어, ExxonMobil의 가격 움직임은 전체 시장의 성과 그 이상에 달려 있습니다. 유가, 이자율, 미래 유가 변동과 같은 기타 예측 변수 는 XOM의 가격과 다른 석유 회사의 주가에 영향을 미칠 수 있습니다 [.](/futures) 두 개 이상의 변수가 존재하는 관계를 이해하기 위해 다중 선형 회귀가 사용됩니다.

다중 선형 회귀(MLR)는 여러 확률 변수 간의 수학적 관계를 결정하는 데 사용됩니다. 즉, MLR은 여러 독립 변수가 하나의 종속 변수와 어떻게 관련되어 있는지 조사합니다. 각 독립 요인이 종속 변수를 예측하기 위해 결정되면 다중 변수에 대한 정보를 사용하여 결과 변수에 미치는 영향 수준에 대한 정확한 예측을 생성할 수 있습니다. 이 모델은 모든 개별 데이터 요소에 가장 근접한 직선(선형) 형태의 관계를 생성합니다.

위의 MLR 방정식을 참조하면 이 예에서:

- y~i~ = 종속변수 - XOM의 가격

- x~i1~ = 이자율

- x~i2~ = 유가

- x~i3~ = S&P 500 지수 값

- x~i4~= 석유 선물 가격

- B~0~ = 시간 0에서의 y절편

- B~1~ = x~i1~이 변할 때 종속변수의 단위 변화를 측정하는 [회귀 계수 - 금리가 변할 때 XOM 가격의 변화](/regression)

- B~2~ = x~i2~가 변할 때 종속변수의 단위 변화를 측정하는 계수 값 - 유가가 변할 때 XOM 가격의 변화

최소제곱 추정치(B~0~, B~1~, B~2~…B~p~)는 일반적으로 통계 소프트웨어에 의해 계산됩니다. 각 독립 변수가 숫자(1,2, 3, 4...p)로 미분되는 회귀 모델에 많은 변수가 포함될 수 있습니다. 다중 회귀 모델을 사용하면 분석가가 여러 설명 변수에 제공된 정보를 기반으로 결과를 예측할 수 있습니다.

그러나 각 데이터 포인트가 모델에서 예측한 결과와 약간 다를 수 있으므로 모델이 항상 완벽하게 정확하지는 않습니다. 실제 결과와 예측된 결과의 차이인 잔차 값 E는 이러한 약간의 변동을 설명하기 위해 모델에 포함됩니다.

통계 계산 소프트웨어를 통해 XOM 가격 회귀 모델을 실행한다고 가정하면 다음 출력이 반환됩니다.

<!--193B494081C84A1BDB50F6709905B87F-->

분석가는 이 결과를 다른 변수가 일정하게 유지되면 시장의 석유 가격이 1% 상승하면 XOM의 가격이 7.8% 상승한다는 의미로 해석합니다. 이 모델은 또한 이자율이 1% 상승한 후 XOM의 가격이 1.5% 하락할 것임을 보여줍니다. R^2^는 Exxon Mobil 주가 변동의 86.5%가 금리, 유가, 석유 선물 및 S&P 500 지수의 변동으로 설명될 수 있음을 나타냅니다.

## 선형 회귀와 다중 회귀의 차이점

[일반 선형 제곱](/least-squares-method) (OLS) 회귀는 일부 설명 변수의 변경이 주어진 종속 변수의 응답을 비교합니다. 그러나 종속변수는 하나의 변수로만 설명되는 경우는 거의 없습니다. 이 경우 분석가는 둘 이상의 독립 변수를 사용하여 종속 변수를 설명하려고 시도하는 다중 회귀를 사용합니다. 다중 회귀는 선형 및 비선형일 수 있습니다.

다중 회귀는 종속 변수와 독립 변수 사이에 선형 관계가 있다는 가정을 기반으로 합니다. 또한 독립 변수 사이에 큰 상관 관계가 없다고 가정합니다.

##하이라이트

- 다중 회귀는 하나의 설명 변수만 사용하는 선형(OLS) 회귀의 확장입니다.

- 단순히 다중 회귀라고도 하는 다중 선형 회귀(MLR)는 여러 설명 변수를 사용하여 응답 변수의 결과를 예측하는 통계 기법입니다.

- MLR은 계량 경제학 및 금융 추론에 광범위하게 사용됩니다.

##자주하는 질문

### 다중 회귀가 선형이라는 것은 무엇을 의미합니까?

다중 선형 회귀에서 모델 은 종속 변수와 관련하여 포함된 각 변수의 분산을 최소화하는 [최적선을 계산합니다.](/line-of-best-fit) 선에 맞기 때문에 선형 모델입니다. 로지스틱 회귀, 2차 회귀 및 프로빗 모델과 같은 다중 변수를 포함하는 비선형 회귀 모델도 있습니다.

### 다중 회귀 모델은 금융에서 어떻게 사용됩니까?

둘 이상의 변수를 보는 모든 계량 경제학 모델은 배수가 될 수 있습니다. [요인 모형](/multifactor-model) 은 두 개 이상의 요인을 비교하여 변수와 결과 성능 간의 관계를 분석합니다. [Fama and French Three-Factor Mod](/famaandfrenchthreefactormodel) 는 CAPM(회귀 모델)의 시장 위험 요소에 크기 위험 및 가치 위험 요소를 추가 하여 [자본 자산 가격 책정 모델 (CAPM)](/capm) 을 확장하는 모델입니다 . 이 두 가지 추가 요소를 포함함으로써 모델은 이러한 성과가 좋은 경향을 조정하므로 관리자 성과를 평가하는 데 더 나은 도구가 될 것으로 생각됩니다.

### 다중 회귀를 수동으로 수행할 수 있습니까?

다중 회귀 모델은 복잡하고 모델에 더 많은 변수가 포함되거나 분석할 데이터의 양이 증가하면 더 복잡해지기 때문에 그럴 가능성은 거의 없습니다. 다중 회귀를 실행하려면 Excel과 같은 프로그램 내에서 특수 통계 소프트웨어 또는 기능을 사용해야 할 수 있습니다.

### 다중 회귀를 다중으로 만드는 것은 무엇입니까?

다중 회귀는 일부 관심 결과에 대한 둘 이상의 설명 변수의 효과를 고려합니다. 모델 상수의 다른 모든 변수를 유지할 때 종속 변수에 대한 이러한 설명 또는 독립 변수의 상대적 효과를 평가합니다.

### 단순 OLS 회귀보다 다중 회귀를 사용하는 이유는 무엇입니까?

종속변수는 하나의 변수만으로 설명되는 경우가 거의 없습니다. 이러한 경우 분석가는 둘 이상의 독립 변수를 사용하여 종속 변수를 설명하려고 시도하는 다중 회귀를 사용합니다. 그러나 이 모델은 독립 변수 간에 주요 상관 관계가 없다고 가정합니다.

