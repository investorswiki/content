---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (kryptovaluta)
description: En Merkle-rot inneholder informasjon om hver enkelt transaksjons-hash som noen gang har vært på en bestemt blokk i en blokkjede.
---

# Merkle Root (kryptovaluta)
## Hva er en Merkle-rot?

En Merkle-rot er [hashen](/hash) av alle hashene til alle transaksjonene som er en del av en blokk i et [blokkjedenettverk](/blockchain).

## Forstå en Merkle-rot

En blokkjede består av forskjellige blokker som er knyttet til hverandre (derav navnet blokkjede). Et hash-tre, eller [Merkle-treet](/merkle-tree),. koder blokkjededataene på en effektiv og sikker måte. Det muliggjør rask verifisering av blokkjededata, samt rask flytting av store mengder data fra en datamaskinnode til den andre på peer-to-peer blockchain-nettverket.

Hver transaksjon som skjer på blokkjedenettverket har en hash knyttet til seg. Imidlertid er disse hashene ikke lagret i en sekvensiell rekkefølge på blokken, snarere i form av en trelignende struktur slik at hver hash er knyttet til sin overordnede etter en foreldre-barn tre-lignende relasjon.

Siden det er mange transaksjoner lagret på en bestemt blokk, hashes også alle transaksjons-hashene i blokken, noe som resulterer i en Merkle-rot.

Tenk for eksempel på en blokk med syv transaksjoner. På det laveste nivået (kalt bladnivået), vil det være fire transaksjons-hasher. På nivå én over bladnivået vil det være to transaksjons-hasher, som hver vil kobles til to hasher som er under dem på bladnivå. På toppen (nivå to) vil det være den siste transaksjons-hashen kalt roten, og den vil koble til de to hashene under den (på nivå én).

Effektivt får du et opp-ned binært tre, der hver node i treet kobles til kun to noder under det (derav navnet "binært tre"). Den har en rot-hash på toppen, som kobles til to hashes på nivå én, som hver igjen kobles til de to hashene på nivå tre (bladnivå), og strukturen fortsetter avhengig av antall transaksjons-hasher.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Hashen starter på det laveste nivået (bladnivå) nodene, og alle fire hashen er inkludert i hashen av noder som er knyttet til den på nivå én. På samme måte fortsetter hashing på nivå én, noe som fører til at hash-hash når til høyere nivåer, helt til den når den enkle topprot-hashen.

Denne rot-hashen kalles Merkle-roten, og på grunn av den trelignende koblingen av hash, inneholder den all informasjon om hver enkelt transaksjons-hash som finnes på blokken. Den tilbyr en enkeltpunkts hash-verdi som gjør det mulig å validere alt som finnes på den blokken.

For eksempel, hvis man må bekrefte en transaksjon som hevder å ha kommet fra blokk #137, trenger de bare å sjekke blokkens Merkle-tre, uten å bekymre seg for å verifisere noe på andre blokker på blokkjeden, som blokk #136 eller blokk # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Skriv inn Merkle-roten, noe som øker verifiseringen ytterligere. Siden den bærer all informasjon om hele treet, trenger man bare å verifisere den transaksjons-hashen, dens søskennode (hvis den finnes), og deretter fortsette oppover til den når toppen.

I hovedsak reduserer Merkle-treet og Merkle-rotmekanismen betydelig nivåene av hashing som skal utføres, noe som muliggjør raskere verifisering og transaksjoner.

##Høydepunkter

- Merkles røtter er sentrale i beregningen som kreves for å opprettholde kryptovalutaer som bitcoin og eter.

- Merkle-røtter brukes i kryptovaluta for å sikre at datablokker som sendes mellom peers på et peer-to-peer-nettverk er hele, uskadet og uendret.

– En Merkle-rot er en enkel matematisk måte å verifisere dataene på et Merkle-tre på.

