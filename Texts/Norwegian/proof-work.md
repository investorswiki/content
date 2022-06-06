---
keywords: Investing,Cryptocurrency,Bitcoin
title: Arbeidsbevis (PoW)
description: Bevis på arbeid beskriver prosessen som gjør at bitcoin-nettverket forblir robust ved å gjøre prosessen med gruvedrift, eller registrering av transaksjoner, vanskelig.
---

# Arbeidsbevis (PoW)
## Hva er bevis på arbeid (PoW)?

Proof of work (PoW) beskriver et system som krever en ikke ubetydelig, men gjennomførbar mengde innsats for å avskrekke useriøs eller ondsinnet bruk av datakraft, for eksempel å sende spam-e-post eller starte tjenestenektangrep. Konseptet ble deretter tilpasset for å sikre digitale penger av Hal Finney i 2004 gjennom ideen om "gjenbrukbart bevis på arbeid" ved bruk av SHA-256 hashing-algoritmen.

Etter introduksjonen i 2009 ble Bitcoin den første allment vedtatte anvendelsen av Finneys PoW-idé (Finney var også mottakeren av den første bitcoin-transaksjonen). Bevis på arbeid danner også grunnlaget for mange andre [kryptovalutaer ,](/cryptocurrency) [noe](/cryptocurrency) som muliggjør sikker, desentralisert konsensus.

## Forstå bevis på arbeid

Denne forklaringen vil fokusere på bevis på arbeid ettersom den fungerer i [bitcoin](/bitcoin) -nettverket. Bitcoin er en digital valuta som er underbygget av en slags [distribuert hovedbok](/distributed-ledger-technology-dlt) kjent som en " [blokkjede](/blockchain) ". Denne hovedboken inneholder en oversikt over alle bitcoin-transaksjoner, ordnet i sekvensielle «blokker», slik at ingen bruker har lov til å bruke noen av beholdningene sine to ganger. For å forhindre tukling er hovedboken offentlig, eller "distribuert"; en endret versjon vil raskt bli avvist av andre brukere.

Måten brukere oppdager tukling på i praksis, er gjennom [hasher](/hash),. lange rekker med tall som fungerer som bevis på arbeidet. Sett et gitt sett med data gjennom en hash-funksjon (bitcoin bruker SHA-256), og den vil bare generere én hash. På grunn av "skredeffekten" vil imidlertid selv en liten endring av noen del av de originale dataene resultere i en totalt ugjenkjennelig hash. Uansett størrelsen på det originale datasettet, vil hashen som genereres av en gitt funksjon ha samme lengde. Hashen er en enveisfunksjon: den kan ikke brukes til å hente de originale dataene, bare for å kontrollere at dataene som genererte hashen stemmer overens med de originale dataene.

Å generere bare hvilken som helst hash for et sett med bitcoin-transaksjoner ville være trivielt for en moderne datamaskin, så for å gjøre prosessen om til "arbeid", setter bitcoin-nettverket et visst "vanskelighetsnivå". Denne innstillingen justeres slik at en ny blokk " [mineres](/bitcoin-mining) " – lagt til blokkjeden ved å generere en gyldig hash – omtrent hvert 10. minutt. Innstillingsvansker oppnås ved å etablere et ["mål" for hashen](/target-hash) : jo lavere målet er, desto mindre sett med gyldige hashes, og jo vanskeligere er det å generere en. I praksis betyr dette en hash som starter med en veldig lang streng med nuller.

> Arbeidsbevis ble opprinnelig laget som en foreslått løsning på det økende problemet med spam-e-post.

>

## Spesielle hensyn

Siden et gitt sett med data bare kan generere én hash, hvordan sørger gruvearbeidere for at de genererer en hash under målet? De endrer inndata ved å legge til et heltall, kalt en [nonce](/nonce) ("nummer brukt én gang"). Når en gyldig hash er funnet, kringkastes den til nettverket, og blokken legges til blokkjeden.

Gruvedrift er en konkurranseprosess, men det er mer et lotteri enn et løp. I gjennomsnitt vil noen generere akseptable bevis på arbeid hvert tiende minutt, men hvem det vil være er noens gjetning. Gruvearbeidere slår seg sammen for å øke sjansene for gruveblokker, noe som genererer transaksjonsgebyrer og, i en begrenset periode, en belønning av nyopprettede bitcoins.

Bevis på arbeid gjør det ekstremt vanskelig å endre noen aspekter av blokkjeden, siden en slik endring vil kreve re-mining av alle påfølgende blokker. Det gjør det også vanskelig for en bruker eller gruppe av brukere å monopolisere nettverkets datakraft, siden maskineriet og kraften som kreves for å fullføre hash-funksjonene er dyre.

> Hvis en del av et gruvenettverk begynner å akseptere et alternativt bevis på arbeid, er det kjent som en [hard gaffel](/hard-fork).

>

## Eksempel på bevis på arbeid

Bevis på arbeid krever at en datamaskin tilfeldig engasjerer seg i hashing-funksjoner til den kommer til en utgang med riktig minimumsmengde innledende nuller. For eksempel er hashen for blokk #660000, utvunnet 4. desember 2020 00000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. Blokkbelønningen for den vellykkede hasjen var 6,25 BTC.

Den blokken vil alltid inneholde 745 transaksjoner som involverer litt over 1666 bitcoins, samt overskriften til forrige blokk. Hvis noen prøvde å endre et transaksjonsbeløp med til og med 0,000001 bitcoin, ville den resulterende hashen være ugjenkjennelig, og nettverket ville avvise svindelforsøket.

## Vanlige spørsmål om bevis på arbeid

### Hva betyr bevis på arbeid?

PoW krever at noder på et nettverk gir bevis på at de har brukt regnekraft (dvs. arbeid) for å oppnå konsensus på en desentralisert måte og for å hindre dårlige aktører fra å overta nettverket.

### Hvordan validerer bevis på arbeid en kryptotransaksjon?

Selve arbeidet er vilkårlig. For Bitcoin involverer det iterasjoner av SHA-256 hashing-algoritmer. "Vinneren" av en hashing-runde, aggregerer og registrerer transaksjoner fra mempoolen til neste blokk. Fordi "vinneren" er tilfeldig valgt proporsjonal med arbeidet som er utført, oppmuntrer det alle på nettverket til å opptre ærlig og registrere bare sanne transaksjoner.

### Hvorfor trenger kryptovaluta bevis på arbeid?

Fordi de er desentralisert og peer-to-peer av design, krever blokkjeder som kryptovalutanettverk en måte å oppnå både konsensus og sikkerhet på. Arbeidsbevis er en slik metode som gjør det for ressurskrevende å forsøke å overkjøre nettverket. Det finnes også andre bevismekanismer som er mindre ressurskrevende, men som har andre ulemper eller mangler, som [bevis](/proof-stake-pos) [på innsats (PoS)](/proof-stake-pos) og [bevis på forbrenning](/proof-burn-cryptocurrency). Uten en bevismekanisme ville nettverket og dataene som er lagret i det være sårbare for angrep eller tyveri.

### Bruker Bitcoin bevis på arbeid?

Ja. Den bruker en PoW-algoritme basert på SHA-256-hash-funksjonen for å validere og bekrefte transaksjoner samt utstede nye bitcoins i omløp.

### Hvordan skiller Proof of Stake (PoS) seg fra PoW?

PoS er en konsensusmekanisme som tilfeldig tildeler noden som skal utvinne eller validere blokktransaksjoner i henhold til hvor mange mynter den noden har. Jo flere tokens som holdes i en lommebok, jo mer gruvekraft får den effektivt. Selv om PoS er langt mindre ressurskrevende, har det flere andre feil, inkludert en større sjanse for et [angrep på 51 %](/51-attack) i mindre altcoins og insentiver til å hamstre tokens og ikke bruke dem.

## Høydepunkter

– Proof of Stake (POS) var en av flere nye konsensusmekanismer laget som et alternativ til bevis på arbeid.

- Proof of work (PoW) er en desentralisert konsensusmekanisme som krever at medlemmer av et nettverk bruker krefter på å løse et vilkårlig matematisk puslespill for å hindre noen fra å spille systemet.

– Bevis på arbeid i stor skala krever enorme mengder energi, som bare øker etter hvert som flere gruvearbeidere blir med i nettverket.

– På grunn av bevis på arbeid kan Bitcoin og andre kryptovalutatransaksjoner behandles peer-to-peer på en sikker måte uten behov for en pålitelig tredjepart.

– Arbeidsbevis brukes mye i gruvedrift av kryptovaluta, for å validere transaksjoner og utvinne nye tokens.

