---
keywords: Crypto
title: Bloom Filter
description: Bloom Filter. En datastruktur, som kan bruges til at informere brugeren om, hvorvidt et bestemt element er en del af et sæt elementer
---

# Bloom Filter
Et Bloom-filter er en datastruktur, der kan bruges til at informere brugeren om, hvorvidt et bestemt element er en del af et sæt. Selvom det ikke kan sige med sikkerhed, om et element er i sættet, kan det med sikkerhed sige, om elementet ikke er det.

Bloom-filtre blev skabt af Burton Howard Bloom i 1970 og er et attraktivt tilbud til en række applikationer på grund af deres effektivitet i pladsforbrug. I nogle kryptovalutaer (især Bitcoin) spiller de en integreret rolle i Simplified Payment Verification, eller SPV.

Ved at bruge en SPV-klient kan brugere interagere med Bitcoin-netværket uden at køre en fuld node. Fuld noder kommer med visse lagrings- og beregningskrav, der gør dem uhåndterlige at køre på enheder med lav effekt som smartphones. SPV-klienter, på den anden side, forespørger simpelthen hele noder for information, der er relevant for brugerens tegnebog(er).

Den mest ligetil løsning til at videresende disse data til brugeren ville være ved at gøre fulde noder opmærksomme på klientens nøgler, så kun relevante transaktioner sendes til dem. Dette er åbenbart en underordnet løsning, da klientens privatliv ville blive ofret. På den anden side ville det være spild af båndbredde at downloade alle transaktioner kun for at kassere størstedelen af dem. Indtast Bloom-filtre.

Lad os illustrere. Antag, at en klient, Alice, har en transaktion af høj værdi, som hun ikke ønsker, at Bob, der kører en fuld node, skal være opmærksom på. Hun konstruerer et Bloom-filter, som vi vil illustrere som et 10x1 gitter:

Hun sender de transaktionsdata, hun er interesseret i, gennem to forskellige hash-funktioner, som udsender to tal mellem 0 og 9. Lad os kalde dem 4 og 7. Hun sender filteret til Bob.

Når du ser på dette gitter, har du ingen idé om, hvilke data Alice har videregivet til filteret. Hvis du havde et sæt, hvori dataene var indeholdt, ville du være i stand til at hash det og sammenligne det med filteret – hvis der er et match, er der mulighed for, at det var den information, som Alice bad om.

Samtidig vil der sandsynligvis være mange input, der vil blive knyttet til 4 og 7, så Bob kan ikke bestemme, hvilken del af dataene Alice er interesseret i. Han returnerer simpelthen alle kampene, og Alice filtrerer dem i sin ende.

Dette er selvfølgelig en grov overforenkling, men det demonstrerer konceptet: Bloom-filtre slører kundens sande interesser. Det er ikke en perfekt metode (der er stadig bekymringer over dens privatliv), men det er en forbedring i forhold til en uafskærmet anmodning til en node.

