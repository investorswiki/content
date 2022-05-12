---
keywords: Investing,Cryptocurrency,Altcoins
title: Mål Hash
description: En målhash angir vanskeligheten for gruvedrift av kryptovaluta ved å bruke et proof-of-work (PoW) blockchain-system.
---

# Mål Hash
## Hva er en målhash?

I gruvedrift av kryptovaluta er en målhash en numerisk verdi som en hashed blokkoverskrift [må](/block-header-cryptocurrency) være mindre enn eller lik for at en ny blokk skal tildeles en gruvearbeider. Blokkhoder identifiserer individuelle blokker i en blokkjede.

Utvinning av kryptovaluta refererer til prosessen med å samle kryptovaluta som en belønning for arbeidet du fullfører. Arten av dette arbeidet er å verifisere legitimiteten til en gitt kryptovalutas transaksjoner. På denne måten er kryptovalutagruvearbeidere i hovedsak revisorer. Når du miner, kan du tjene kryptovaluta uten å måtte legge ned penger for det.

Målhashen brukes til å bestemme inndataens vanskelighetsgrad og kan justeres for å sikre at blokker behandles effektivt. For eksempel brukes mål-hasher i kryptovalutaer som bruker et proof-of-work-system ( [PoW](/difficulty-cryptocurrencies) ) for å angi gjeldende [gruvedrift](/difficulty-cryptocurrencies) (inkludert Bitcoin). Hvis en kryptovaluta bruker et annet system for gruvedrift, kan det hende at den ikke krever en målhash.

## Hvordan en målhash fungerer

[Kryptovalutaer](/cryptocurrency) er avhengige av bruk av [blokkjeder](/blockchain) som inneholder historien til alle kryptovalutatransaksjonene. Disse transaksjonene [hashes](/hash) eller kodes kryptografisk til en serie alfanumeriske tegn. Hashing innebærer å ta en datastreng av hvilken som helst lengde og kjøre den gjennom en algoritme for å produsere en utgang med en fast lengde. Utgangen vil alltid ha samme lengde, uavhengig av hvor stor eller liten inngangen er (selv om antallet permutasjoner av en hash er astronomisk stort). Hver blokk vil inneholde hashen til forrige blokkoverskrift.

Validering og koding av blokkjeden kalles [gruvedrift](/bitcoin-mining). Mining innebærer bruk av datamaskiner for å kjøre hashing-algoritmer for å behandle den siste blokken; informasjonen som en bruker trenger å gruve finnes i blokkens overskrift. Kryptovalutanettverket setter en målverdi for denne hashen – kalt målhash – og gruvearbeidere prøver å finne ut hva denne verdien er ved å teste ut alle mulige verdier.

Blokkoverskriften inneholder blokkversjonsnummeret, et tidsstempel, hashen brukt i forrige blokk, hashen til [Merkle Root](/merkle-root-cryptocurrency) [t](/merkle-root-cryptocurrency),. [nonce](/nonce) og målhashen. Blokken genereres ved å ta hashen av blokkinnholdet, legge til en tilfeldig streng med tall (nonce), og hashe blokken på nytt.

Hvis hashen oppfyller kravet til målet, blir blokken lagt til blokkjeden. Å sykle gjennom løsninger for å gjette nonce blir referert til som [proof of work](/proof-work) (PoW), og gruvearbeideren som er i stand til å finne verdien tildeles blokken og betales i kryptovaluta.

## Spesielle hensyn

### Målhash for Bitcoin

Bitcoin bruker SHA-256 hash-algoritmen. Denne algoritmen genererer verifiserbart tilfeldige tall på en måte som krever en forutsigbar mengde databehandlingskraft.

Mining av en blokk krever at gruvearbeideren produserer en verdi (en nonce) som, etter å ha blitt hashed (kryptografisk kodet), er mindre enn eller lik den som ble brukt i den siste blokken som ble akseptert av bitcoin-nettverket. Dette tallet er mellom 0- (det minste alternativet) og 256-bits (det største alternativet), men det er usannsynlig at det noen gang vil være det maksimale antallet.

Fordi målhashen kan være et stort antall, kan det hende at gruvearbeideren må teste et stort antall verdier før de lykkes. En mislykket gruvearbeider må vente på neste blokk (det er grunnen til at gruvearbeidere som finner en hash-løsning sammenlignes med vinnere av et løp eller lotteri).

Målhashen justeres med jevne mellomrom. Hash-funksjonene som brukes til å generere det nye målet har spesifikke egenskaper designet for å gjøre blokkjeden (og dens kryptovaluta) sikker. Denne prosessen er deterministisk, noe som betyr at den vil gi det samme resultatet hver gang den samme inngangen brukes. Det er raskt nok til at det ikke tar for lang tid å returnere en hash for input. Det gjør også å bestemme input svært vanskelig, spesielt for store tall, og gjør små endringer i input resulterer i en helt annen hash-utgang.

## Høydepunkter

- Mål-hasher brukes i kryptovalutaer som bruker et proof-of-work (PoW)-system for å angi gjeldende gruvevanskelighet (inkludert Bitcoin); hvis en kryptovaluta bruker et annet system for gruvedrift, krever det kanskje ikke en målhash.

- I gruvedrift av kryptovaluta er en målhash en numerisk verdi som en hashed blokkhode (som brukes til å identifisere individuelle blokker i en blokkjede) må være mindre enn eller lik for at en ny blokk skal tildeles en gruvearbeider.

- Bitcoin-nettverket justerer vanskelighetsgraden med gruvedrift ved å heve eller senke målhashen for å bevare et gjennomsnittlig 10-minutters intervall mellom nye blokker.

