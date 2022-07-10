---
keywords: Investing,Cryptocurrency,Bitcoin
title: Bevis på arbete (PoW)
description: Bevis på arbete beskriver processen som gör det möjligt för bitcoin-nätverket att förbli robust genom att göra processen att bryta eller registrera transaktioner svår.
---

# Bevis på arbete (PoW)
## Vad är bevis på arbete (PoW)?

Proof of work (PoW) beskriver ett system som kräver en inte obetydlig men genomförbar mängd ansträngning för att avskräcka oseriöst eller skadlig användning av datorkraft, som att skicka spam-e-post eller att starta överbelastningsattacker. Konceptet anpassades därefter för att säkra digitala pengar av Hal Finney 2004 genom idén om "återanvändbart bevis på arbete" med hjälp av SHA-256 hashalgoritmen.

Efter introduktionen 2009 blev Bitcoin den första allmänt använda tillämpningen av Finneys PoW-idé (Finney var också mottagaren av den första bitcointransaktionen). Bevis på arbete utgör grunden för många andra [kryptovalutor](/cryptocurrency) [också](/cryptocurrency),. vilket möjliggör en säker, decentraliserad konsensus.

## Förstå bevis på arbete

Denna förklaring kommer att fokusera på bevis på arbete eftersom det fungerar i [bitcoin](/bitcoin) -nätverket. Bitcoin är en digital valuta som stöds av en sorts [distribuerad reskontra](/distributed-ledger-technology-dlt) känd som en " [blockchain](/blockchain) ". Denna reskontra innehåller ett register över alla bitcoin-transaktioner, arrangerade i sekventiella "block", så att ingen användare får spendera något av sina innehav två gånger. för att förhindra manipulering är huvudboken offentlig eller "distribuerad"; en ändrad version skulle snabbt avvisas av andra användare.

Det sätt som användare upptäcker manipulering i praktiken är genom [hash](/hash),. långa siffror som fungerar som bevis på arbetet. Lägg en given uppsättning data genom en hash-funktion (bitcoin använder SHA-256), och det kommer bara någonsin att generera en hash. På grund av "lavineffekten" kommer dock även en liten ändring av någon del av originaldatan att resultera i en helt oigenkännlig hash. Oavsett storleken på den ursprungliga datamängden kommer hashen som genereras av en given funktion att ha samma längd. Hashen är en enkelriktad funktion: den kan inte användas för att erhålla originaldata, bara för att kontrollera att data som genererade hash matchar originaldata.

Att generera vilken hash som helst för en uppsättning bitcoin-transaktioner skulle vara trivialt för en modern dator, så för att förvandla processen till "arbete" sätter bitcoin-nätverket en viss nivå av "svårighet". Den här inställningen justeras så att ett nytt block " mineras" [– läggs](/bitcoin-mining) till blockkedjan genom att generera en giltig hash – ungefär var tionde minut. Inställningssvårigheter uppnås genom att fastställa ett ["mål" för hashen](/target-hash) : ju lägre mål, desto mindre uppsättning giltiga hash, och desto svårare är det att generera en. I praktiken innebär detta en hash som börjar med en mycket lång rad nollor.

> Bevis på arbete skapades ursprungligen som en föreslagen lösning på det växande problemet med skräppost.

>

## Särskilda överväganden

Eftersom en given uppsättning data bara kan generera en hash, hur ser gruvarbetare till att de genererar en hash under målet? De ändrar inmatningen genom att lägga till ett heltal, som kallas en [nonce](/nonce) ("nummer används en gång"). När en giltig hash har hittats sänds den till nätverket och blocket läggs till blockkedjan.

Gruvdrift är en konkurrenskraftig process, men det är mer ett lotteri än ett lopp. I genomsnitt kommer någon att generera acceptabla bevis på arbete var tionde minut, men vem det kommer att vara är någons gissning. Gruvarbetare slår samman för att öka sina chanser till gruvblock, vilket genererar transaktionsavgifter och, under en begränsad tid, en belöning av nyskapade bitcoins.

Bevis på arbete gör det extremt svårt att ändra någon aspekt av blockkedjan, eftersom en sådan förändring skulle kräva att alla efterföljande block återupptas. Det gör det också svårt för en användare eller pool av användare att monopolisera nätverkets datorkraft, eftersom maskineriet och kraften som krävs för att slutföra hashfunktionerna är dyra.

> Om en del av ett gruvnätverk börjar acceptera ett alternativt bevis på arbete, kallas det en [hård gaffel](/hard-fork).

>

## Exempel på bevis på arbete

Bevis på arbete kräver att en dator slumpmässigt ägnar sig åt hashfunktioner tills den når en utgång med rätt minsta antal inledande nollor. Till exempel, hashen för block #660000, bryts den dec. 4, 2020 är 000000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. Blockbelöningen för den framgångsrika hashen var 6,25 BTC.

Det blocket kommer alltid att innehålla 745 transaktioner som involverar drygt 1 666 bitcoins, samt rubriken för det föregående blocket. Om någon försökte ändra ett transaktionsbelopp med till och med 0,000001 bitcoin, skulle den resulterande hashen vara oigenkännlig, och nätverket skulle avvisa bedrägeriförsöket.

## Vanliga frågor om bevis på arbete

### Vad betyder bevis på arbete?

PoW kräver att noder på ett nätverk ger bevis på att de har förbrukat beräkningskraft (dvs. arbete) för att uppnå konsensus på ett decentraliserat sätt och för att förhindra dåliga aktörer från att gå om nätverket.

### Hur validerar arbetsbevis en kryptotransaktion?

Arbetet i sig är godtyckligt. För Bitcoin innebär det iterationer av SHA-256-hashalgoritmer. "Vinnaren" av en hashingrunda aggregerar dock och registrerar transaktioner från mempoolen till nästa block. Eftersom "vinnaren" är slumpmässigt vald i proportion till det utförda arbetet, uppmuntrar det alla i nätverket att agera ärligt och endast registrera verkliga transaktioner.

### Varför behöver kryptovalutor bevis på arbete?

Eftersom de är decentraliserade och peer-to-peer genom design, kräver blockkedjor som kryptovalutanätverk på något sätt för att uppnå både konsensus och säkerhet. Bevis på arbete är en sådan metod som gör det för resurskrävande att försöka köra om nätet. Det finns också andra bevismekanismer som är mindre resurskrävande, men som har andra nackdelar eller brister, såsom [proof](/proof-stake-pos) [of stake (PoS)](/proof-stake-pos) och [proof of burn](/proof-burn-cryptocurrency). Utan en bevismekanism skulle nätverket och den data som lagras i det vara sårbart för attacker eller stöld.

### Använder Bitcoin bevis på arbete?

Ja. Den använder en PoW-algoritm baserad på SHA-256-hashningsfunktionen för att validera och bekräfta transaktioner samt för att utfärda nya bitcoins i omlopp.

### Hur skiljer sig Proof of Stake (PoS) från PoW?

PoS är en konsensusmekanism som slumpmässigt tilldelar noden som ska bryta eller validera blocktransaktioner beroende på hur många mynt den noden innehåller. Ju fler tokens som finns i en plånbok, desto mer kraft tilldelas den effektivt. Även om PoS är mycket mindre resurskrävande, har det flera andra brister, inklusive en större chans för en [attack på 51 %](/51-attack) i mindre altcoins och incitament att hamstra tokens och inte använda dem.

##Höjdpunkter

– Proof of Stake (POS) var en av flera nya konsensusmekanismer som skapats som ett alternativ till bevis på arbete.

- Proof of work (PoW) är en decentraliserad konsensusmekanism som kräver att medlemmar i ett nätverk lägger ner kraft på att lösa ett godtyckligt matematiskt pussel för att hindra någon från att spela systemet.

– Bevis på arbete i stor skala kräver enorma mängder energi, vilket bara ökar när fler gruvarbetare ansluter sig till nätverket.

– På grund av bevis på arbete kan Bitcoin och andra kryptovalutatransaktioner behandlas peer-to-peer på ett säkert sätt utan behov av en pålitlig tredje part.

– Bevis på arbete används i stor utsträckning vid brytning av kryptovalutor, för att validera transaktioner och utvinna nya tokens.

