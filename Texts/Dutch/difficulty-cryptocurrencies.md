---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Sværhedsgrad ved kryptovaluta
description: Cryptocurrency-sværhedsgrad er et mål for, hvor svært det er at mine en blok i en blockchain for en bestemt kryptovaluta.
---

# Sværhedsgrad ved kryptovaluta
## Hvad er svært ved kryptovaluta?

Cryptocurrency-sværhedsgrad er et mål for, hvor svært det er at mine en blok i en [blockchain](/blockchain) for en bestemt [kryptovaluta](/cryptocurrency). En høj cryptocurrency-sværhedsgrad betyder, at det kræver yderligere computerkraft at verificere transaktioner, der er indtastet på en blockchain - en proces kaldet [minedrift](/bitcoin-mining).

Cryptocurrency-sværhedsgrad er en parameter, som [bitcoin og andre](/bitcoin) [kryptovalutaer](/bitcoin) bruger til at holde den gennemsnitlige tid mellem blokke stabil, når netværkets hash-effekt ændres. Cryptocurrency-sværhedsgrad er vigtig, da en høj sværhedsgrad kan hjælpe med at sikre blockchain-netværket mod ondsindede angreb.

## Forståelse af kryptovaluta vanskeligheder

Bitcoin og andre kryptovalutaer, der bruger [proof-of-work](/proof-work) blockchains, vedligeholdes gennem minedriftsprocessen. Minearbejdere verificerer transaktioner, der udføres på en blockchain, og udfører revisorernes opgaver for at forhindre svig og sikre transaktionernes legitimitet. Minedrift blev udtænkt af bitcoins grundlægger, [Satoshi Nakamoto](/satoshi-nakamoto).

I dette system konkurrerer minearbejdere – som kører kryptovalutaens software på deres computere – om at finde en ny blok, der tilføjer den seneste batch af transaktionsdata til kæden. Når tilstrækkeligt mange transaktioner er blevet verificeret, tilføjes en ny blok til blockchain. Minearbejdere kan få betalt et gebyr for deres indsats, men der er andre krav, før en minearbejder kan modtage kompensation, hvis nogen overhovedet. Omfanget af den computerkraft, der er nødvendig for at udvinde en blok, er repræsenteret ved sværhedsgrad af kryptovaluta. Den tid, det tager at finde en ny blok, afhænger af sværhedsgraden af kryptovaluta og tilfældige tilfældigheder.

For at måle cryptocurrency-sværhedsgraden af en ny blok, er det vigtigt at forstå hash-kraft, som repræsenterer den kombinerede beregningskraft, der bruges til at mine og behandle transaktionerne på blockchain.

### Tilfældige hashes

En hash er en alfanumerisk kode, der bruges til at repræsentere ord eller data. Minearbejdere tager en batch af transaktionsdata og kører dem gennem en [hash-algoritme](/hash),. en envejsfunktion, der – givet et bestemt datasæt – altid vil producere det samme output, men hvis output ikke kan vendes for at vise de originale data. Hashing-algoritmer bruges til at oprette disse tilfældige hash-koder. Før nye data kan tilføjes til en blockchain, skal minearbejdere konkurrere om at producere en hash, der er lavere eller lig med en numerisk værdi kaldet en [target hash](/target-hash).

Minearbejdere udfører hashing-processen ved at ændre en enkelt værdi, kaldet en [nonce](/nonce) - eller et tal brugt én gang - og hver gang nonce ændres, oprettes en ny hash med sit eget sæt tal. Der er ingen måde at forudsige, hvad en hash vil være, og da hvert sæt data kun har ét output for en given hash-funktion, skal minearbejdere gentage processen med at tilføje en ny nonce til dataene, indtil de opfylder hash-kravet.

### Sværhedsgrad ved kryptovaluta

Kravet en hash skal opfylde svarer til sværhedsgraden. En gyldig hash skal være under en bestemt målværdi, der automatisk (og periodisk justeres) af kryptovalutaens protokol. Jo lavere målværdien er, jo flere gentagelser af hashfunktionen skal en minearbejder igennem for at få et acceptabelt resultat – med andre ord, jo højere sværhedsgrad. En minearbejder kan i teorien være heldig og få en gyldig hash for en given blok i første forsøg. Men over tid betyder højere sværhedsgrad, at minearbejdere i gennemsnit skal tilslutte flere nonces pr. blok.

Enkeltpersoner og organisationer bidrager med deres beregningskraft via deres minerigge til at behandle dataene og producere hashen. Hash-kraften i et kryptovaluta-netværk repræsenterer de samlede hash-rater for alle mineriggene. Hashhastigheden er antallet af hashes, der kan beregnes pr. sekund.

Da hver hash oprettes tilfældigt, kan det tage millioner af gæt eller hashes, før målet hash-kravet er opfyldt, og nye kryptovaluta-mønter præges til den succesfulde minearbejder. Først derefter føjes transaktionerne til en ny blok i blockchainen. På en måde ligner hashing-processen et lotterisystem. Som følge heraf udstedes nye mønter gennem denne minedrift.

> Jo højere hash-raten er, jo sværere er det for en svindler at få kontrol over blockchainen, da der er behov for mere hash-kraft. Med andre ord, jo højere sværhedsgrad, jo mere sikkert netværket.

>

## Fordele ved sværhedsgrad ved kryptovaluta

Man kan undre sig over, hvorfor et netværks deltagere ville etablere en højere cryptocurrency-sværhedsgrad, hvis resultatet betød, at minearbejdere gentog den samme funktion igen og igen. Der er to vigtige fordele ved cryptocurrency-vanskeligheder.

### En stabil rate af nye blokke

Bitcoin-hvidbogen af Satoshi Nakamoto forklarer, hvordan proof-of-work-besværet hjælper med at generere en stabil produktion af nye blokke tilføjet til blockchain.

>

> "For at kompensere for stigende hardwarehastighed og varierende interesse for at køre noder over tid, bestemmes bevis-of-work-sværhedsgraden af et glidende gennemsnit, der er målrettet mod et gennemsnitligt antal blokke i timen. Hvis de genereres for hurtigt, øges sværhedsgraden ."

>

Bitcoin er designet til at tilføje en ny blok til blockchain hvert 10. minut i gennemsnit. Andre kryptovalutaer sigter mod hyppigere blokeringer; [litecoin](/litecoin) sigter for eksempel efter 2,5 minutter. Problemet er, at mængden af computerkraft, netværkets minearbejdere tilsammen kontrollerer, kan variere enormt.

Da Satoshi Nakamoto minede den første blok, var der kun én maskine på netværket - sandsynligvis en simpel bærbar eller stationær. I dag er der en række vidtstrakte ASIC-farme i lagerstørrelse. ASIC'er er maskiner designet specifikt til at pløje hash-funktioner så hurtigt som muligt.

For at sikre, at netværket producerer en ny blok med en konstant gennemsnitshastighed, er softwaren indstillet til automatisk at justere target-hashen op eller ned, hvilket resulterer i henholdsvis lavere eller højere sværhedsgrad. Da Nakamoto minede genesis-blokken, var bitcoins vanskelighed én.

### Netværkssikkerhed

Den overordnede hash-rate giver indsigt i et kryptovaluta-netværks sikkerhed, da svindlere eller dårlige aktører ville være nødt til at overvinde netværkets totale hash-kraft for at tage kontrol i et ondsindet angreb. Specielt designede computere bruges til at udføre hashing-funktioner, som er i stand til at foretage billioner af gæt hvert sekund for at løse hashing-problemet.

Jo højere cryptocurrency-sværhedsgraden er, jo flere gæt eller hashes er nødvendige for at nå målet hash-kravet. Som et resultat heraf gør denne proces det meget vanskeligt og dyrt for angribere at få flertalskontrol - kaldet [51 % majoritet](/51-attack) - af et blockchain-netværk.

## Eksempel på sværhedsgrad ved kryptovaluta

Pr. 2. april 2021 var cryptocurrency-sværhedsgraden for bitcoin 23,14 billioner. Hvis vi sammenligner ændringen i sværhedsgrad, kan vi se, at den 1. april 2018 var bitcoins sværhedsgrad 3,51 billioner.

Diagrammet nedenfor viser bitcoins ændring i sværhedsgrad gennem årene:

## Højdepunkter

- Cryptocurrency-sværhedsgrad er et mål for, hvor svært det er at mine en blok i en blockchain for en bestemt kryptovaluta.

- En høj cryptocurrency-sværhedsgrad betyder, at det kræver yderligere computerkraft at verificere transaktioner, der er indtastet på en blockchain.

- Jo højere sværhedsgrad, der er nødvendig for at oprette en blok, forbedrer et kryptovaluta-netværks sikkerhed, da angribere ville have brug for enorme ressourcer for at tage kontrol.

