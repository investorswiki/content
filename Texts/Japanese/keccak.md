---
keywords: Crypto
title: Keccak
description: Keccak。 Guido Bertoni、Joan Daemen、MichaëlPeeters、GillesVanAsscheによって設計された多用途の暗号化機能。
---

# Keccak
Keccak（「ketchak」と発音）は、Guido Bertoni、Joan Daemen、MichaëlPeeters、およびGillesVanAsscheによって設計された多用途の暗号化機能です。 Keccakは他の目的にも使用できますが、SHA-1やSHA-2などの古いハッシュアルゴリズムと比較してセキュリティレベルを向上させるハッシュ関数として最もよく知られています。

SHAはSecureHashAlgorithmの略で、米国国立標準技術研究所（NIST）によって公開されている一連の暗号化ハッシュ関数を指します。 SHA-1とSHA-2はどちらも、米国国家安全保障局（NSA）によって設計されたものであり、同様の構造を示しています。 KeccakはSHA-2と同じ出力サイズ（ハッシュ長）をサポートしていますが、その動作メカニズムはまったく異なります。それでも、KeccakはSHAファミリーの一部であり、SHA-3と呼ばれることがよくあります。

SHA-1に対する理論上の攻撃は、2004年に実行され、2005年に公開されました。数年後の2011年に、SHA-2は使用される新しい標準ハッシュ関数としてNISTによって宣言されました。ただし、SHA-1からSHA-2への移行は非常に遅く、開発者とコンピューター科学者の大部分が最終的にSHA-2に移行したのは2017年の初めまででした。その後まもなく、Googleは2017年2月にSHA-1衝突攻撃の成功を発表しました。それ以降、SHA-1は安全であるとは見なされなくなり、その使用は推奨されていません。

Keccak関数（SHA-3）は、NISTが公開競争と審査プロセスを発表した後、2007年頃に開発が開始され、先行するSHA-1とSHA-2の潜在的な欠陥を克服できる新しい暗号化ハッシュ関数を探しました。

SHA-2に対する重大な攻撃はまだ実証されていませんが、ハッシュ関数は時間の経過とともにクラックされると予想され、新しい標準関数が開発されるまでには何年もかかります。これを考慮に入れて、2004年と2005年にSHA-1に対して実行された攻撃の成功とともに、NISTは新しい暗号化ハッシュアルゴリズムを作成する必要性を認識しました。 2012年、NISTはKeccakを競争の勝利アルゴリズムとして宣言し、SHAファミリーの最新メンバー（したがって、SHA-3）として標準化されました。

KeccakがNISTによって選ばれた理由の1つは、他のアルゴリズムよりも安全で効率的であることが証明された革新的な構造によるものです。技術的に言えば、SHA-3アルゴリズムは、SHA-1およびSHA-2で使用されるMerkleDamgård構造とは対照的に、いわゆるスポンジ関数（またはスポンジ構造）に依存しています。

今のところ、SHA-2は依然として安全であると見なされており、広く使用されています。たとえば、SHA-256はビットコインやその他の暗号通貨で使用されており、マイニングのプロセスで重要な役割を果たします。攻撃に成功するにはほど遠いように思われるため、今後、SHA-3の採用が増える可能性があります。それでも、暗号化の分野が進歩し、新しい欠陥が発見されるにつれて、今後数年間でさらに多くの暗号化ハッシュアルゴリズムが開発されるでしょう。

