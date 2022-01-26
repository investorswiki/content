---
keywords: Crypto
title: BEP-95
description: BEP-95. BEP-95 er et Binance Evolution-forslag, der introducerer en realtidsbrændingsmekanisme til Binance Smart Chain. Det gør BNB tokenomics mere dynamisk og decentraliseret.
---

# BEP-95
BEP-95 er et Binance Evolution-forslag, der introducerer en realtidsbrændingsmekanisme til Binance Smart Chain. Det er blevet introduceret for at gøre BNB's tokenomics endnu mere dynamisk og yderligere decentralisere netværket.

Med BEP-95 vil netværket brænde et fast forhold mellem hver bloks gasgebyrer, som validatorer indsamler. Det nøjagtige forhold vil blive bestemt via BSC's styringsmekanismer. Afbrændingerne vil finde sted, selv efter at BSC har nået sit mål på 100 millioner BNB. Ved at reducere udbuddet af BNB lægges der et opadgående pres på møntens pris. BEP'en kan også reducere antallet af BNB-delegatorer og validatorer, der modtages. Men med opadgående prispres kan fiat-værdien også stige, hvilket opvejer enhver reduktion i mønter.

For at implementere dette teknisk, indsamler netværket hver bloks gasgebyrer og opdeler mellem to smarte kontrakter:

**en. Systembelønningskontrakt.** 1/16 af gasgebyrerne vil indgå i Systembelønningskontrakten, indtil den når et maksimum på 100 BNB. Disse mønter vil blive brugt som pakketilskud på tværs af kæder.

**2. ValidatorSet-kontrakt.** Alle andre gasgebyrer vil indgå i ValidatorSet-kontrakten og deles dagligt med delegatorer og validatorer via Binance Chain.

For at udføre en brænding har ValidatorSet-kontrakten en burnRatio-variabel. Efter at have afsluttet hver blok, vil en validator underskrive en transaktion, der overfører sine gasgebyrer til de smarte kontrakter. Deponeringsfunktionen indeholder brændende logik, der udløser den simple formel: burnRatio * gasFee. Dette beløb vil så blive overført til brændingsadressen. Forbrændingsforholdet vil i første omgang blive indstillet til 10%.

BSC Validatorer vil være i stand til at stemme via forslag om at ændre burnRatio-beløbet. Denne styringsmekanisme forekommer på Binance Chain, og ethvert fællesskabsmedlem kan indsende et forslag til gennemgang med et minimumsindskud på 2.000 BNB. Alle BNB står bag et forslag og i en afstemning returneres efter en beslutning er truffet. Quorum nås ved 50%, og ændringen implementeres via tværkædekommunikation med det samme.

