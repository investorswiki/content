---
keywords: Investing,Cryptocurrency,Bitcoin
title: Bevis for arbejde (PoW)
description: Bevis for arbejde beskriver den proces, der gør det muligt for bitcoin-netværket at forblive robust ved at gøre processen med minedrift eller registrering af transaktioner vanskelig.
---

# Bevis for arbejde (PoW)
## Hvad er bevis for arbejde (PoW)?

Proof of work (PoW) beskriver et system, der kræver en ikke-ubetydelig, men gennemførlig mængde indsats for at afskrække useriøs eller ondsindet brug af computerkraft, såsom at sende spam-e-mails eller iværksætte lammelsesangreb. Konceptet blev efterfølgende tilpasset til at sikre digitale penge af Hal Finney i 2004 gennem ideen om "genanvendeligt bevis på arbejde" ved hjælp af SHA-256 hashing-algoritmen.

Efter introduktionen i 2009 blev Bitcoin den første bredt anvendte anvendelse af Finneys PoW-idé (Finney var også modtageren af den første bitcoin-transaktion). Bevis for arbejde danner også grundlaget for mange andre [kryptovalutaer ,](/cryptocurrency) [hvilket](/cryptocurrency) giver mulighed for en sikker, decentraliseret konsensus.

## Forståelse af bevis for arbejde

Denne forklaring vil fokusere på bevis for arbejde, da det fungerer i [bitcoin](/bitcoin) -netværket. Bitcoin er en digital valuta, der er understøttet af en slags [distribueret hovedbog](/distributed-ledger-technology-dlt) kendt som en " [blockchain](/blockchain) ". Denne hovedbog indeholder en registrering af alle bitcoin-transaktioner, arrangeret i sekventielle "blokke", så ingen bruger har tilladelse til at bruge nogen af deres beholdninger to gange. For at forhindre manipulation er hovedbogen offentlig eller "distribueret"; en ændret version ville hurtigt blive afvist af andre brugere.

Den måde, hvorpå brugere opdager manipulation i praksis, er gennem [hashes](/hash),. lange rækker af tal, der tjener som bevis på arbejdet. Sæt et givet sæt data gennem en hash-funktion (bitcoin bruger SHA-256), og det vil kun generere én hash. På grund af "lavineeffekten" vil selv en lille ændring af enhver del af de originale data imidlertid resultere i en fuldstændig uigenkendelig hash. Uanset størrelsen af det originale datasæt, vil hashen, der genereres af en given funktion, have samme længde. Hashen er en envejsfunktion: den kan ikke bruges til at få de originale data, kun til at kontrollere, at de data, der genererede hashen, matcher de originale data.

At generere bare en hvilken som helst hash for et sæt bitcoin-transaktioner ville være trivielt for en moderne computer, så for at gøre processen til "arbejde", sætter bitcoin-netværket et vist niveau af "sværhedsgrad". Denne indstilling er justeret, så en ny blok " mineres" – [tilføjet](/bitcoin-mining) til blockchainen ved at generere en gyldig hash – cirka hvert 10. minut. Indstillingsvanskeligheder opnås ved at etablere et ["mål" for hashen](/target-hash) : Jo lavere målet er, desto mindre sæt af gyldige hashes, og jo sværere er det at generere en. I praksis betyder det en hash, der starter med en meget lang række af nuller.

> Bevis for arbejde blev oprindeligt skabt som en foreslået løsning på det voksende problem med spam-e-mail.

>

## Særlige overvejelser

Da et givet sæt data kun kan generere én hash, hvordan sikrer minearbejdere, at de genererer en hash under målet? De ændrer input ved at tilføje et heltal, kaldet en [nonce](/nonce) ("tal brugt én gang"). Når en gyldig hash er fundet, udsendes den til netværket, og blokken føjes til blockchain.

Minedrift er en konkurrencepræget proces, men det er mere et lotteri end et kapløb. I gennemsnit vil nogen generere acceptabelt bevis for arbejde hvert tiende minut, men hvem det vil være, er nogens gæt. Minearbejdere slår sig sammen for at øge deres chancer for mineblokke, hvilket genererer transaktionsgebyrer og i en begrænset periode en belønning af nyoprettede bitcoins.

Bevis for arbejde gør det ekstremt vanskeligt at ændre noget som helst aspekt af blockchain, da en sådan ændring ville kræve genudvinding af alle efterfølgende blokke. Det gør det også vanskeligt for en bruger eller pulje af brugere at monopolisere netværkets computerkraft, da det maskineri og kraft, der kræves for at fuldføre hash-funktionerne, er dyre.

> Hvis en del af et minenetværk begynder at acceptere et alternativt bevis på arbejde, er det kendt som en [hård gaffel](/hard-fork).

>

## Eksempel på bevis for arbejde

Bevis for arbejde kræver, at en computer tilfældigt engagerer sig i hash-funktioner, indtil den når et output med den korrekte minimumsmængde af indledende nuller. For eksempel, hashen for blok #660000, udvundet den dec. 4, 2020 er 000000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. Blokbelønningen for den vellykkede hash var 6,25 BTC.

Den blok vil altid indeholde 745 transaktioner, der involverer lidt over 1.666 bitcoins, samt overskriften på den forrige blok. Hvis nogen forsøgte at ændre et transaktionsbeløb med endda 0,000001 bitcoin, ville den resulterende hash være uigenkendelig, og netværket ville afvise svindelforsøget.

## Ofte stillede spørgsmål om bevis på arbejde

### Hvad betyder bevis for arbejde?

PoW kræver, at noder på et netværk giver bevis for, at de har brugt regnekraft (dvs. arbejde) for at opnå konsensus på en decentral måde og for at forhindre dårlige aktører i at overhale netværket.

### Hvordan validerer bevis for arbejde en kryptotransaktion?

Selve arbejdet er vilkårligt. For Bitcoin involverer det gentagelser af SHA-256 hashing-algoritmer. "Vinderen" af en hashing-runde samler og registrerer transaktioner fra mempoolen til den næste blok. Fordi "vinderen" er tilfældigt udvalgt i forhold til det udførte arbejde, tilskynder det alle på netværket til at handle ærligt og kun registrere sande transaktioner.

### Hvorfor har kryptovalutaer brug for bevis for arbejde?

Fordi de er decentraliserede og peer-to-peer af design, kræver blockchains såsom kryptovaluta-netværk en måde at opnå både konsensus og sikkerhed på. Bevis for arbejde er en sådan metode, der gør det for ressourcekrævende at forsøge at overhale netværket. Der findes også andre bevismekanismer, som er mindre ressourcekrævende, men som har andre ulemper eller mangler, såsom [bevis](/proof-stake-pos) [for indsats (PoS)](/proof-stake-pos) og [bevis for forbrænding](/proof-burn-cryptocurrency). Uden en bevismekanisme ville netværket og de data, der er gemt i det, være sårbare over for angreb eller tyveri.

### Bruger Bitcoin bevis for arbejde?

Ja. Den bruger en PoW-algoritme baseret på SHA-256 hashing-funktionen for at validere og bekræfte transaktioner samt udstede nye bitcoins i omløb.

### Hvordan adskiller Proof of Stake (PoS) sig fra PoW?

PoS er en konsensusmekanisme, der tilfældigt tildeler den node, der vil mine eller validere bloktransaktioner i henhold til, hvor mange mønter den node indeholder. Jo flere tokens der er i en pung, jo mere minedrift får den effektivt. Selvom PoS er langt mindre ressourcekrævende, har det flere andre fejl, herunder en større chance for et [angreb på 51 %](/51-attack) i mindre altcoins og incitamenter til at hamstre tokens og ikke bruge dem.

##Højdepunkter

- Proof of Stake (POS) var en af flere nye konsensusmekanismer skabt som et alternativ til bevis for arbejde.

- Proof of work (PoW) er en decentraliseret konsensusmekanisme, der kræver, at medlemmer af et netværk bruger kræfter på at løse et vilkårligt matematisk puslespil for at forhindre nogen i at spille systemet.

- Bevis for arbejde i stor skala kræver enorme mængder energi, som kun stiger, efterhånden som flere minearbejdere tilslutter sig netværket.

- På grund af bevis for arbejde kan Bitcoin og andre kryptovalutatransaktioner behandles peer-to-peer på en sikker måde uden behov for en betroet tredjepart.

- Bevis for arbejde bruges i vid udstrækning i cryptocurrency-mining, til validering af transaktioner og udvinding af nye tokens.

