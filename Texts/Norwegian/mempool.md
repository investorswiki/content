---
keywords: Crypto
title: Mempool
description: Mempool. En nodes mekanisme for å holde styr på ubekreftede transaksjoner som noden har sett (men ennå ikke er lagt til i en blokk).
---

# Mempool
En mempool (en sammentrekning av minne og pool) er en kryptovaluta-nodes mekanisme for å lagre informasjon om ubekreftede transaksjoner. Det fungerer som et slags venterom for transaksjoner som ennå ikke er inkludert i en [blokk](/block).

Når en transaksjon kringkastes, sendes den fra en node til sine jevnaldrende, som deretter sender den videre til sine jevnaldrende. Dette fortsetter til transaksjonen har blitt bredt spredt, klar for gruvearbeidere å legge den til i en blokk. Det er viktig at denne buffersonen eksisterer, siden transaksjoner ikke legges til blokkjeden umiddelbart.

Noder vil kjøre en rekke kontroller for å sikre at transaksjonen er gyldig – dvs. å verifisere at signaturer er korrekte, utdata ikke overstiger inndata og at midler ikke allerede er brukt. Hvis den ikke oppfyller disse betingelsene, blir den avvist.

Vi snakker ofte om mempoolen, men det bør bemerkes at det ikke er noen universell pool som deles av alle noder. Hver enkelt er konfigurert forskjellig og mottar transaksjoner til forskjellige tider. Lavere enheter med begrensede ressurser kan bare dedikere små mengder minne til logging av transaksjoner, mens høyere enheter kan bruke betydelig mer.

Siden gruvearbeidere hovedsakelig er motivert av fortjeneste, er transaksjoner med høyere avgifter de som mest sannsynlig blir kastet fra mempoolen først når de er bekreftet. Det er vanskelig å estimere avgifter nøyaktig, spesielt når blokkplassen er begrenset og etterspørselen er høy, men mempoolen gir et utgangspunkt.

For å estimere gebyrer kan man se på gjeldende ubekreftede transaksjoner. Det er naturlig at brukere ikke bør betale for mye i tider med lav gjennomstrømning. De bør heller ikke underbetale for tidssensitive transaksjoner i rushtiden, da det kan ta en stund før det blir bekreftet. Ved å ta hensyn til spredningen av gebyrer på et gitt tidspunkt, kan de gjøre en utdannet gjetning på hvor raskt transaksjonen deres vil bli inkludert.

