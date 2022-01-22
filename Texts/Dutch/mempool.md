---
keywords: Crypto
title: Mempool
description: Mempool. En nodes mekanisme til at holde styr på ubekræftede transaktioner, som noden har set (men endnu ikke er blevet tilføjet til en blok).
---

# Mempool
En mempool (en sammentrækning af hukommelse og pool) er en cryptocurrency nodes mekanisme til lagring af information om ubekræftede transaktioner. Det fungerer som en slags venteværelse for transaktioner, der endnu ikke er inkluderet i en [blok](/block).

Når en transaktion udsendes, sendes den fra en node til dens peers, som så sender den videre til deres peers. Dette fortsætter, indtil transaktionen er blevet bredt udbredt, klar til at minearbejdere kan tilføje den til en blok. Det er afgørende, at denne bufferzone eksisterer, da transaktioner ikke føjes til blockchain med det samme.

Noder vil køre en række kontroller for at sikre, at transaktionen er gyldig – dvs. at verificere, at signaturer er korrekte, output ikke overstiger input, og midler er ikke allerede blevet brugt. Hvis det ikke opfylder disse betingelser, afvises det.

Vi taler ofte om mempoolen, men det skal bemærkes, at der ikke er nogen universel pool, der deles af alle noder. Hver enkelt er konfigureret forskelligt og modtager transaktioner på forskellige tidspunkter. Lavere enheder med begrænsede ressourcer kan kun dedikere små mængder hukommelse til at logge transaktioner, hvorimod enheder i højere ende kan afsætte betydeligt mere.

Da minearbejdere primært er motiveret af overskud, er transaktioner med højere gebyrer dem, der med størst sandsynlighed bliver kasseret fra mempoolen først, når de er bekræftet. Det er vanskeligt at estimere gebyrer nøjagtigt, især når blokpladsen er begrænset, og efterspørgslen er høj, men mempoolen giver et udgangspunkt.

For at estimere gebyrer kan man se på de aktuelle ubekræftede transaktioner. Det er naturligt, at brugere ikke bør betale for meget i tider med lav gennemstrømning. De bør heller ikke underbetale for tidsfølsomme transaktioner i spidsbelastningsperioder, da der kan gå et stykke tid, før det bliver bekræftet. Ved at tage højde for spredningen af gebyrer på et givet tidspunkt, kan de lave et kvalificeret gæt på, hvor hurtigt deres transaktion vil blive inkluderet.

