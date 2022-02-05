---
keywords: Crypto
title: Kandidatblokk
description: Kandidatblokk. En midlertidig blokk opprettet av en mining node (miner) for å legge til blokkjeden for å motta blokkbelønningene.
---

# Kandidatblokk
Med noen få ord er en kandidatblokk en blokk som en miningnode (gruvearbeider) prøver å gruve for å motta blokkbelønningen. Så en kandidatblokk kan beskrives som en midlertidig blokkering som enten vil bli validert eller forkastet av nettverket. Gruvearbeidere konkurrerer med hverandre for å validere neste blokk og legge den til blokkjeden, men først må de opprette en kandidatblokk for å delta i gruvekonkurransen.

Kandidatblokker opprettes av gruvearbeidere ved å samle og organisere flere ubekreftede transaksjoner fra minnepoolen. Transaksjonene hashes deretter for å danne en [Merkle-trestruktur](/merkle-tree),. som til slutt vil produsere en Merkle-rot (eller root-hash). Merkle-roten er en enkelt hash som representerer alle tidligere hashes av det treet, og derfor alle transaksjoner som ble inkludert i den aktuelle blokken.

Rothashen - sammen med hashen til forrige blokk og et tilfeldig tall kalt [nonce](/nonce) - settes deretter inn i blokkens overskrift. Blokkoverskriften hashes deretter av gruvearbeideren, og genererer en utgang basert på disse komponentene (root-hash, forrige blokks hash og nonce) pluss noen få andre elementer. Den resulterende utgangen er blokkhashen og vil tjene som en unik identifikator for den nylig genererte blokken (kandidatblokk).

For å bli ansett som gyldig, må utgangen (blokkhash) starte med et visst antall nuller (mindre enn en målverdi som er definert av protokollen). Dette betyr at gruveprosessen er basert på flere forsøk (prøving og feiling) ettersom gruvenodene må utføre et utall av hashing-funksjoner med forskjellige nonce-verdier inntil en gyldig blokkhash til slutt produseres. Blokkhashen som ble produsert er det som beviser at gruvearbeideren gjorde arbeidet sitt (derav Proof of Work).

Etter at en gruvearbeider har funnet en gyldig blokkhash, vil kandidatblokken deres kringkastes til resten av nodene i nettverket, som vil bekrefte ektheten til hashen. Hvis alt er bra, vil kandidatblokken bli registrert i blokkjeden. På dette tidspunktet oppdaterer hver validerende node sin kopi av blokkjededataene for å gjenspeile den nylig utvunnede blokken, og gruvearbeideren vil få blokkbelønningen.

