---
keywords: Crypto
title: Bloom Filter
description: Bloom Filter. En datastruktur som kan brukes til å informere brukeren om hvorvidt et bestemt element er en del av et sett med elementer
---

# Bloom Filter
Et Bloom-filter er en datastruktur som kan brukes til å informere brukeren om et bestemt element er en del av et sett. Selv om det ikke kan si med sikkerhet om et element er i settet, kan det si med sikkerhet om elementet ikke er det.

Bloom-filtre ble opprettet av Burton Howard Bloom i 1970, og er et attraktivt tilbud for en rekke bruksområder på grunn av deres effektivitet i plassbruk. I noen kryptovalutaer (spesielt Bitcoin), spiller de en integrert rolle i forenklet betalingsverifisering, eller SPV.

Ved å bruke en SPV-klient kan brukere samhandle med Bitcoin-nettverket uten å kjøre en full node. Fulle noder kommer med visse lagrings- og beregningskrav som gjør dem uhåndterlige å kjøre på enheter med lite strøm som smarttelefoner. SPV-klienter, på den annen side, spør ganske enkelt hele noder for informasjon som er relevant for brukerens lommebok(e).

Den enkleste løsningen for å videresende disse dataene til brukeren vil være å gjøre fulle noder oppmerksomme på klientens nøkler, slik at kun relevante transaksjoner sendes til dem. Tydeligvis er dette en underordnet løsning da klientens personvern ville bli ofret. På den annen side, å laste ned alle transaksjoner bare for å forkaste de fleste av dem ville være bortkastet båndbredde. Gå inn i Bloom-filtre.

La oss illustrere. Anta at en klient, Alice, har en transaksjon med høy verdi hun ikke vil at Bob, som kjører en full node, skal være klar over. Hun konstruerer et Bloom-filter, som vi vil illustrere som et 10x1 rutenett:

Hun sender transaksjonsdataene hun er interessert i gjennom to forskjellige hash-funksjoner, som gir ut to tall mellom 0 og 9. La oss kalle dem 4 og 7. Hun sender filteret til Bob.

Når du ser på dette rutenettet, aner du ikke hvilke data Alice har sendt til filteret. Hvis du hadde et sett der dataene var inneholdt, ville du kunne hash det og sammenlignet det med filteret – hvis det er et samsvar, er det en mulighet for at det var informasjonen Alice ba om.

Samtidig vil det sannsynligvis være mange innganger som vil kartlegges til 4 og 7, så Bob kan ikke bestemme hvilken del av dataene Alice er interessert i. Han returnerer ganske enkelt alle kampene, og Alice filtrerer dem på sin side.

Dette er selvfølgelig en grov overforenkling, men det demonstrerer konseptet: Bloom-filtre tilslører de sanne interessene til klienten. Det er ikke en perfekt metode (det er fortsatt bekymringer for personvernet), men det er en forbedring i forhold til en uskjermet forespørsel til en node.

