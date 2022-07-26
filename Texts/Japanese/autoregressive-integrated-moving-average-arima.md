---
keywords: Trading,Technical Analysis,Advanced Technical Analysis Concepts
title: 自己回帰和分移動平均（ARIMA）
description: 自己回帰和分移動平均（ARIMA）は、時系列データを活用して将来の傾向を予測する統計分析モデルです。
---

# 自己回帰和分移動平均（ARIMA）
##自己回帰和分移動平均（ARIMA）とは何ですか？

自己回帰和分移動平均（ARIMA）は、[時系列データ](/timeseries)を使用してデータセットをよりよく理解するか、将来の傾向を予測する統計分析モデルです。

統計モデルは、過去の値に基づいて将来の値を予測する場合、自己回帰です。たとえば、ARIMAモデルは、過去のパフォーマンスに基づいて株式の将来の価格を予測したり、過去の期間に基づいて会社の収益を予測したりする場合があります。

##自己回帰和分移動平均（ARIMA）を理解する

自己回帰和分移動平均モデルは、他の変化する変数と比較した1つの従属変数の強度を測定する[回帰分析の形式です。](/regression)モデルの目標は、実際の値ではなく、シリーズの値の違いを調べることによって、将来の証券または金融市場の動きを予測することです。

ARIMAモデルは、その各コンポーネントの概要を次のように説明することで理解できます。

-[自動回帰（AR）](/autoregressive) ：それ自体の遅れた値または以前の値で回帰する変化する変数を示すモデルを指します。

-**統合（I）：**は、時系列が静止することを可能にするための生の観測値の差異を表します（つまり、データ値は、データ値と以前の値の差に置き換えられます）。

-[移動平均（MA）](/movingaverage) ：観測と、遅延観測に適用された移動平均モデルからの残差誤差との間の依存関係を組み込みます。

##ARIMAパラメーター

ARIMAの各コンポーネントは、標準表記のパラメーターとして機能します。 ARIMAモデルの場合、標準表記はp、d、およびqのARIMAになります。ここで、整数値は、使用されるARIMAモデルのタイプを示すパラメーターの代わりになります。パラメータは次のように定義できます。

-** p **：モデル内のラグ観測の数。ラグオーダーとも呼ばれます。

-** d **：生の観測値が異なる回数。差異の程度としても知られています。

--q：移動平均ウィンドウのサイズ。移動平均の次数とも呼ばれます。

たとえば、線形回帰モデルでは、用語の数とタイプが含まれます[。](/nonlinear-regression)パラメータとして使用できる0の値は、特定のコンポーネントをモデルで使用してはならないことを意味します。このようにして、ARIMAモデルを構築して、ARMAモデル、または単純なAR、I、またはMAモデルの機能を実行することができます。

> ARIMAモデルは複雑で、非常に大きなデータセットで最適に機能するため、コンピューターアルゴリズムと機械学習技術を使用してそれらを計算します。

>>

##自己回帰和分移動平均（ARIMA）と定常性

自己回帰和分移動平均モデルでは、データを静止させるためにデータが差分されます。定常性を示すモデルは、時間の経過とともにデータに一定性があることを示すモデルです。ほとんどの経済および市場データは傾向を示しているため、差異化の目的は、傾向または季節構造を削除することです。

[季節](/seasonality)性、またはデータが暦年にわたって繰り返される規則的で予測可能なパターンを示す場合、回帰モデルに悪影響を与える可能性があります。傾向が現れ、定常性が明らかでない場合、プロセス全体の計算の多くを非常に効率的に行うことはできません。

> 1回限りのショックは、ARIMAモデルのその後の値に無限に影響を及ぼします。したがって、金融危機の遺産は、今日の自動回帰モデルに残っています。

>>

##特別な考慮事項

ARIMAモデルは、過去の値が現在または将来の値にいくらかの残余の影響を与えるという仮定に基づいています。たとえば、ARIMAモデルを使用して株価を予測する投資家は、証券を提供または受け入れる金額を決定する際に、その株式の新規の買い手と売り手が最近の市場取引の影響を受けると想定します。

この仮定は多くの状況で当てはまりますが、常にそうであるとは限りません。たとえば、2008年の金融危機以前の数年間、ほとんどの投資家は、多くの金融会社が保有する[住宅ローン担保証券（MBS）の大規模なポートフォリオによってもたらされるリスクを認識していませんでした。](/mbs)

その間、自動回帰モデルを使用して米国の金融株のパフォーマンスを予測する投資家は、そのセクターの安定したまたは上昇する株価の継続的な傾向を予測する十分な理由がありました。しかし、多くの金融機関が差し迫った崩壊のリスクにさらされていることが一般に知られるようになると、投資家は突然これらの株式の最近の価格に関心を失い、潜在的なリスクエクスポージャーにはるかに関心を持つようになりました。したがって、市場は急速に金融株をはるかに低いレベルに再評価します。これは、自己回帰モデルを完全に混乱させる動きです。

＃＃ よくある質問

### ARIMAは何に使用されますか？

ARIMAは、過去の時系列に基づいて将来の結果を予測または予測するための方法です。これは、過去のデータポイントが将来のデータポイントに影響を与えるシリアル相関の統計的概念に基づいています。

###自己回帰モデルと移動平均モデルの違いは何ですか？

ARIMAは、自己回帰機能と移動平均の機能を組み合わせたものです。たとえば、AR（1）自己回帰プロセスは、現在の値が直前の値に基づくプロセスであり、AR（2）プロセスは、現在の値が前の2つの値に基づくプロセスです。移動平均は、外れ値の影響を平滑化するために、完全なデータセットのさまざまなサブセットの一連の平均を作成することによってデータポイントを分析するために使用される計算です。この手法の組み合わせの結果として、ARIMAモデルは、予測を行うときに、傾向、サイクル、季節性、およびその他の非静的タイプのデータを考慮に入れることができます。

### ARIMA予測はどのように機能しますか？

ARIMA予測は、対象の変数の時系列データをプラグインすることによって実現されます。統計ソフトウェアは、データに適用されるラグの適切な数または差異の量を識別し、定常性をチェックします。次に、結果を出力します。結果は、多重線形回帰モデルの結果と同様に解釈されることがよくあります。

##ハイライト

-自己回帰和分移動平均（ARIMA）モデルは、過去の値に基づいて将来の値を予測します。

-ARIMAは、時系列データを平滑化するために遅延移動平均を利用します。

-将来の証券価格を予測するためのテクニカル分析で広く使用されています。

-自己回帰モデルは、未来が過去に似ていることを暗黙的に想定しています。

-したがって、金融危機や急速な技術変化の時期など、特定の市場条件の下では不正確であることが判明する可能性があります。

