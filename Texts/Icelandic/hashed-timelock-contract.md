---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Hashed Timelock Contract (HTLC)
description: Hashed TimeLock samningur (HTLC). Vísar til sérstaks eiginleika sem er notaður til að búa til snjalla samninga sem geta breytt greiðslurásum.
---

# Hashed Timelock Contract (HTLC)
Hugtakið Hashed TimeLock Contract (HTLC) vísar til sérstaks eiginleika sem er notaður til að búa til [snjalla samninga](/smart-contract) sem geta breytt greiðslurásum. Tæknilega séð gerir HTLC eiginleikinn kleift að innleiða tímabundin viðskipti milli tveggja notenda. Í reynd þarf viðtakandi HTLC-viðskipta að viðurkenna greiðsluna með því að leggja fram dulmálssönnun innan tiltekins tímaramma (fjöldi blokka). Ef viðtakandinn tapar eða krefst ekki greiðslunnar verður fénu skilað til upphaflega sendanda.

HTLC eiginleikinn er notaður í bæði tvíátta og beina greiðslurásum til að leyfa öruggar millifærslur fjármuna yfir ýmsar rásir, án þess að þurfa að treysta á einhvern milliliðanna.

Það eru tveir lykilþættir sem aðgreina HTLC frá venjulegum cryptocurrency viðskiptum, sem eru:

- Hashlock: aðgerð sem takmarkar eyðslu fjármuna þar til ákveðin gögn eru birt opinberlega (sem dulmálssönnun). Einnig má vísa til slíkrar sönnunar sem formyndar hashlocksins. Formyndin er einfaldlega upplýsingarnar sem eru notaðar til að búa til hashlockið og til að opna síðar fjármuni þess.

- Timelock: er aðgerð sem takmarkar eyðslu fjármuna þar til ákveðnum tíma (eða blokkarhæð) í framtíðinni. Það er hægt að ná í Bitcoin, til dæmis með því að nota aðgerðir eins og CheckLockTimeVerify eða CheckSequenceVerify.

Bitcoin Lightning Network er meðal vinsælustu notkunartilvika Hashed Timelocked Contracts. Með því að innleiða HTLC í greiðslurásir er hægt að flytja fjármuni frá notanda til notanda í gegnum samtengdar greiðsluleiðir, án þess að krefjast nokkurs trausts. Þetta ferli er þekkt sem netleiðsögn. Það gerir Alice kleift að skiptast á fjármunum við Carol jafnvel þótt þeir séu ekki beintengdir í gegnum greiðslurás. HTLC gerir Alice kleift að senda fjármuni sína til Carol í gegnum aðra þátttakendur netsins (td Bob) - og hashlock og timelock eiginleikar tryggja að Bob geti ekki stöðvað fjármunina.

Auk þess að vera notaður á Lightning Network, geta HTLCs einnig verið gagnlegar í öðru samhengi, svo sem krosskeðjuatómskiptasamningum [,](/atomic-swaps) fjárhagslegum snjöllum samningum og escrow, og margt fleira.

## Hápunktar

- Greiðslur með HTLC eru skilyrtar og hafa því hagkvæmni fyrir blockchain viðskipti. Þessi eiginleiki gerir HTLC að grundvallarverkfæri sem eldingarnetið notar.

- Þessi tegund snjallsamninga krefst þess að viðtakandi greiðslu viðurkenni hana innan ákveðins tíma eða missi hana.

- A hashed timelock contract (HTLC) dregur úr mótaðilaáhættu í dreifðum snjöllum samningum með því að búa til tímabundna vörslu sem notar dulmálsaðgangsorð.

## Algengar spurningar

### Hvað kostar snjall samningur?

Á Ethereum blockchain tekur snjall samningsdreifing gas, sem kostar Gwei (lægra nafn á eter). Það fer eftir því hversu flókinn samningurinn er, það getur kostað milljarða Gwei að setja upp snjallsamning. Minni flóknir samningar eins og einföld skipti eru miklu ódýrari.

### Hvað er snjall samningur?

Snjallsamningur er forrit sem er geymt á blockchain sem keyrir þegar sérstök skilyrði eru uppfyllt.

### Hvað er Timelock samningur?

Timelock samningur er snjall samningur innbyggður í blockchain sem framkvæmir viðskipti á ákveðnum tíma. Þau eru notuð í hashed timelock samningum og greiðsluleiðum þar sem þörf er á sérstökum greiðslutíma.

### Er Bitcoin með snjalla samninga?

Upphaflega gat blockchain Bitcoin ekki framkvæmt snjalla samninga. Hins vegar, Taproot uppfærslan árið 2021 gerði blockchain kleift að nota snjalla samninga í viðskiptum.

