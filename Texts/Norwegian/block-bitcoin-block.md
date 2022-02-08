---
keywords: Investing,Cryptocurrency,Blockchain
title: Blokk (Bitcoin Block)
description: Blokker er datastrukturer i en database hvor kryptovalutatransaksjonsdata registreres permanent; når den er skrevet, kan den ikke endres eller fjernes.
---

# Blokk (Bitcoin Block)
## Hva er en blokk (Blockchain Block)?

Blokker er datastrukturer i blokkjededatabasen, der transaksjonsdata i en kryptovalutablokkjede registreres permanent. En blokk registrerer noen eller alle de siste transaksjonene som ennå ikke er validert av nettverket. Når dataene er validert, lukkes blokken. Deretter opprettes en ny blokk for nye transaksjoner som skal inngås og valideres.

En blokk er dermed et permanent lager av poster som, når de først er skrevet, ikke kan endres eller fjernes.

## Hvordan en blokk (Blockchain Block) fungerer

Et [blokkjedenettverk](/blockchain) er vitne til mye transaksjonsaktivitet. Når det brukes i kryptovaluta, hjelper det å holde oversikt over disse transaksjonene systemet med å spore hvor mye som ble eller ikke ble brukt og hvilke parter som var involvert. Transaksjonene som gjøres i løpet av en gitt periode, registreres i en fil kalt en blokk, som er grunnlaget for blokkjedenettverket.

En blokk lagrer informasjon. Det er mange deler av informasjon inkludert i en blokk, men den opptar ikke en stor mengde lagringsplass. Blokker inkluderer vanligvis disse elementene, men det kan variere mellom ulike typer:

- **Magisk tall**: Et tall som inneholder spesifikke verdier som identifiserer den blokken som en del av en bestemt kryptovalutas nettverk.

- **Blokkstørrelse**: Angir størrelsesgrensen på blokken slik at bare en bestemt mengde informasjon kan skrives i den.

- **Blokkoverskrift**: Inneholder informasjon om blokken.

- **Transaksjonsteller**: Et tall som representerer hvor mange transaksjoner som er lagret i blokken.

- **Transaksjoner**: En liste over alle transaksjonene i en blokk.

Transaksjonselementet er størst fordi det inneholder mest informasjon. Den følges i lagringsstørrelse av blokkoverskriften, som inkluderer disse underelementene:

- **Versjon**: Kryptovalutaversjonen som brukes.

- **Forrige blokkhash**: Inneholder en hash (kryptert nummer) av forrige blokks overskrift.

- **Hash Merkle-rot**: Hash av transaksjoner i [Merkle-treet](/merkle-tree) i gjeldende blokk.

- **Tid**: Et tidsstempel for å plassere blokken i blokkjeden.

- **Bits**: Vanskelighetsgraden til målhashen, som angir vanskeligheten med å løse nonce.

- **Nonce**: Det krypterte nummeret som en gruvearbeider må løse for å bekrefte blokkeringen og lukke den.

Ett 32-bits tall i overskriften kalles en nonce - gruveprogrammet bruker tilfeldige tall for å "gjette" nonce i [hashen](/hash). Når en nonce er bekreftet, løses hashen når nonce, eller et tall mindre enn det, gjettes. Deretter lukker nettverket den blokken, genererer en ny med en overskrift, og prosessen gjentas.

forskjellige mekanismer brukes for å nå en konsensus; den mest populære for kryptovaluta er [proof-of-work](/proof-work) (PoW), med proof-of-stake (PoS) som blir mer det på grunn av redusert energiforbruk sammenlignet med PoW.

## Gruvedriftens forhold til blokker

Mining er begrepet som brukes for å løse tallet som er nonce, det eneste tallet som kan endres i en blokkoverskrift. Det er også prosessen kryptovalutaens nettverk bruker dersom proof-of-work brukes i protokollen.

Utvinning av kryptovaluta er vanligvis antatt å være et komplekst matematisk problem; det er faktisk et tilfeldig tall generert gjennom hashing. Hashing er prosessen med å kryptere informasjon ved hjelp av krypteringsmetoden en kryptovaluta bruker. For eksempel bruker Bitcoin SHA256 for sin krypteringsalgoritme. For at en gruvearbeider skal generere det "vinnende" nummeret, må gruveprogrammet bruke SHA 256 for å hash tilfeldige tall og plassere dem i nonce for å se om det stemmer.

> Å løse tilfeldig tall-hash under proof-of-work-protokollen er det som krever så mye energi og beregningskraft. Et omfattende nettverk av gruvearbeidere og nok energi til å drive et lite land er nødvendig for å holde det gående.

>

Vanskeligheten ligger i at alle tidligere blokkhoder er kryptert tilfeldig. Derfor er den nåværende blokkoverskriften et tilfeldig generert kryptert tall basert på de tilfeldig genererte krypterte tallene til tidligere blokker og informasjon fra gjeldende blokk.

## Andre blokk- og blokkjedebruk

Fordi de fleste blokkjededefinisjoner refererer til Bitcoin fordi det var den første kryptovalutaen som brukte en, er det mange som forbinder blokker og blokkjeder med Bitcoin. Andre kryptovalutaer bruker imidlertid også blokker og blokkjeder. Det er viktig å merke seg at Ethereums nettverk har en kryptovaluta kalt ether som også bruker blokker og blokkjede.

Imidlertid ble Ethereum og blokkjeden designet for flere bruksområder som strekker seg til mye mer enn kryptovaluta. For eksempel er ikke-fungible tokens, smarte kontrakter, desentraliserte finansapplikasjoner og mer utviklet ved hjelp av Ethereum.

##Høydepunkter

– Blokker og blokkjeder brukes ikke kun av kryptovalutaer. De har også mange andre bruksområder.

- Blokker identifiseres med lange tall som inkluderer kryptert transaksjonsinformasjon fra tidligere blokker og ny transaksjonsinformasjon.

– Blokker og informasjonen i dem må verifiseres av et nettverk før nye blokker kan opprettes.

– En blokk er et sted i en blokkjede hvor informasjon lagres og krypteres.

##FAQ

### Hva er Blockchain med enkle ord?

En blokkjede er en database som lagrer og krypterer informasjon på en koblet måte, slik at tidligere informasjon ikke kan endres, og en gruppe verifiserer eventuelle oppføringer før de er ferdigstilt gjennom en konsensus - en avtale om at dataene er korrekte.

### Hva brukes blokkjeder til?

Blokkjeder brukes i kryptovaluta, desentraliserte finansapplikasjoner, ikke-fungible tokens, med flere bruksområder konstant under utvikling.

### Hvordan lages en blokkjedeblokk?

Blokker opprettes når gruvearbeidere eller blokkvalidatorer validerer den krypterte informasjonen i blokkhodet, noe som ber om opprettelse av en ny blokk.

