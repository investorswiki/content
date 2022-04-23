---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Hash
description: Hash. Úttakið framleitt af kjötkássafalli eftir að gagnastykki er kortlagt. Má einnig vísa til sem kjötkássagildi, kjötkássakóði eða samantekt.
---

# Hash
Í [dulmáli](/cryptography) vísar orðið kjötkássa til úttaksins sem framleitt er af kjötkássafalli eftir að gögn eru send (kortlögð) í gegnum það. Annað en einfaldlega kjötkássa, getur úttakið sem framleitt er af kjötkássaaðgerðum einnig verið vísað til sem kjötkássagildi, kjötkássakóði eða samantekt.

Til að skilja betur hvað kjötkássa er, er þess virði að ræða hvað eru kjötkássaaðgerðir og hvernig þær virka.

Kjötkássaföll eru stærðfræðileg [reiknirit](/algorithm) sem breyta inntaksgildi af hvaða stærð sem er í úttak (kássa) af fastri stærð. Í flestum tilfellum samanstendur úttakið af sextándu tölu. Þetta þýðir að kjötkássa er oft táknuð sem samsetning af tölum (0 til 9) og bókstöfum (a til f).

Til dæmis, ef við notum orðið „Binance“ sem inntaksgildi og kortleggjum það í gegnum SHA-256 kjötkássaaðgerð, þá verður úttaksgildið (eða kjötkássa) sem skilað er:

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Athugaðu að það skiptir ekki máli hversu oft við framkvæmum þessa aðgerð, úttakið verður alltaf það sama (svo lengi sem inntakið breytist ekki).

Á hinn bóginn mun allar minniháttar breytingar á inntakinu valda því að kjötkássaaðgerðin skilar allt öðru kjötkássa en úttakið. Til dæmis, ef við sendum inn orðið „binance“ í stað „Binance“ myndum við hafa eftirfarandi kjötkássa sem afleiðing:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Kjötkápa er gagnleg til að sannreyna réttmæti ákveðinna upplýsinga, án þess að upplýsa um hverjar upplýsingarnar eru. Í reynd er hægt að nota kjötkássaaðgerðir á ýmsar aðstæður. Nokkur notkunartilvik eru gagnagrunnsuppflettingar, greiningar á stórum skrám og gagnastjórnun.

Þegar það er blandað saman við dulmálstækni höfum við svokallaðar dulritunar kjötkássaaðgerðir. Þetta er mikið notað í upplýsingaöryggi og er ómissandi hluti af flestum blockchain netum.

Til dæmis hefur Bitcoin blockchain margar aðgerðir sem fela í sér hashing og þær skipta sköpum í námuvinnsluferlinu.

## Hápunktar

- Hash er aðgerð sem uppfyllir dulkóðuðu kröfurnar sem þarf til að leysa fyrir blockchain útreikning.

- Hash, eins og nonce eða lausn, er burðarás blockchain netsins.

- Hash er þróað út frá upplýsingum sem eru til staðar í blokkarhausnum.

- Kjötkássa eru af föstri lengd þar sem það gerir það næstum ómögulegt að giska á lengd kjötkássa ef einhver var að reyna að brjóta blokkkeðjuna.

- Sömu gögn munu alltaf framleiða sama hashed gildi.

## Algengar spurningar

### Hvernig er kjötkássagildi reiknað?

Kjötkássaaðgerð notar flókin stærðfræðileg reiknirit sem breyta gögnum af handahófskenndri lengd í gögn með fastri lengd (til dæmis 256 stafi). Ef þú breytir einum bita hvar sem er í upprunalegu gögnunum breytist allt kjötkássagildið, sem gerir það gagnlegt til að sannreyna áreiðanleika stafrænna skráa og annarra gagna.

### Til hvers eru hass notaðir í blokkakeðjur?

Hashes eru notuð í nokkrum hlutum blockchain kerfis. Í fyrsta lagi inniheldur hver kubbur kjötkássa [blokkarhauss](/block-header-cryptocurrency) fyrri blokkar, sem tryggir að ekkert hafi verið átt við þegar nýjum kubbum er bætt við. Námuvinnsla dulritunargjaldmiðla með því að nota [vinnusönnun](/proof-work) (PoW) notar ennfremur hashing af handahófsbundnum tölum til að komast að tilteknu hashed gildi sem inniheldur röð af fremstu núllum. Þessi handahófskennda aðgerð er auðlindafrek, sem gerir það erfitt fyrir slæman leikara að ná netkerfinu.

### Hvað er kjötkássaaðgerð?

Kjötkássaföll eru stærðfræðileg föll sem umbreyta eða „kortleggja“ tiltekið safn gagna í bitastreng af fastri stærð, einnig þekkt sem „kássagildi“.

