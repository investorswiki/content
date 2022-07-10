---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Svårighet i kryptovaluta
description: Svårighet i kryptovaluta är ett mått på hur svårt det är att bryta ett block i en blockkedja för en viss kryptovaluta.
---

# Svårighet i kryptovaluta
## Vad är svårt med kryptovaluta?

Svårighet i kryptovaluta är ett mått på hur svårt det är att bryta ett block i en [blockkedja](/blockchain) för en viss [kryptovaluta](/cryptocurrency). En hög cryptocurrency-svårighet innebär att det krävs ytterligare datorkraft för att verifiera transaktioner som görs i en blockchain – en process som kallas [gruvdrift](/bitcoin-mining).

Svårighet i kryptovaluta är en parameter som [bitcoin och andra](/bitcoin) [kryptovalutor](/bitcoin) använder för att hålla den genomsnittliga tiden mellan blocken stabil när nätverkets hashkraft ändras. Svårighet i kryptovaluta är viktig eftersom en hög svårighetsgrad kan hjälpa till att säkra blockchain-nätverket mot skadliga attacker.

## Förstå svårigheter med kryptovaluta

Bitcoin och andra kryptovalutor som använder [proof-of-work](/proof-work) blockchains upprätthålls genom gruvprocessen. Gruvarbetare verifierar transaktioner som görs på en blockchain och utför revisorernas uppgifter för att förhindra bedrägerier och säkerställa transaktionernas legitimitet. Gruvdrift skapades av bitcoins grundare, [Satoshi Nakamoto](/satoshi-nakamoto).

I det här systemet tävlar gruvarbetare – som kör kryptovalutans programvara på sina datorer – om att hitta ett nytt block, och lägger till den senaste batchen av transaktionsdata i kedjan. När tillräckligt många transaktioner har verifierats läggs ett nytt block till blockkedjan. Gruvarbetare kan få betalt för sina ansträngningar men det finns andra krav innan en gruvarbetare kan få ersättning om någon alls. Omfattningen av den datorkraft som behövs för att bryta ett block representeras av svårighetsgrad i kryptovaluta. Tiden det tar att hitta ett nytt block är beroende av svårighetsgraden för kryptovaluta och slumpmässig slump.

För att mäta krypteringssvårigheten för ett nytt block är det viktigt att förstå hashkraft, som representerar den kombinerade beräkningskraften som används för att bryta och bearbeta transaktionerna i blockkedjan.

### Slumpmässiga hash

En hash är en alfanumerisk kod som används för att representera ord eller data. Gruvarbetare tar en sats av transaktionsdata och kör den genom en [hash-algoritm](/hash),. en enkelriktad funktion som – givet en viss uppsättning data – alltid kommer att producera samma utdata, men vars utdata inte kan vändas för att visa originaldata. Hashingalgoritmer används för att skapa dessa slumpmässiga hashkoder. Innan ny data kan läggas till i en blockkedja måste gruvarbetare tävla om att producera en hash som är lägre eller lika med ett numeriskt värde som kallas [målhash](/target-hash).

Gruvarbetare åstadkommer hashprocessen genom att ändra ett enda värde, kallat [nonce](/nonce) – eller ett tal som används en gång – och varje gång nonce ändras skapas en ny hash med sin egen uppsättning siffror. Det finns inget sätt att förutsäga vad en hash kommer att vara och eftersom varje uppsättning data bara har en utdata för en given hashfunktion, måste gruvarbetare upprepa processen att lägga till en ny nonce till data tills de uppfyller hashkravet.

###Svårighet i kryptovaluta

Kravet en hash måste uppfylla motsvarar svårighetsgraden. En giltig hash måste vara under ett visst målvärde som automatiskt (och periodiskt justeras) av kryptovalutans protokoll. Ju lägre målvärde, desto fler upprepningar av hashfunktionen måste en gruvarbetare genomgå för att få ett acceptabelt resultat – med andra ord, desto högre svårighetsgrad. En gruvarbetare kan i teorin ha tur och få en giltig hash för ett givet block vid första försöket. Men med tiden innebär högre svårighetsgrad att gruvarbetare måste plugga igenom fler nonces per block i genomsnitt.

Individer och organisationer bidrar med sin beräkningskraft via sina gruvriggar för att bearbeta data och producera hash. Hashkraften i ett kryptovalutanätverk representerar de totala hashhastigheterna för alla gruvriggar. Hashhastigheten är antalet hash som kan beräknas per sekund.

Eftersom varje hash skapas slumpmässigt kan det ta miljontals gissningar eller hash innan målkravet för kryptovalutans hash uppfylls och nya mynt präglas till den framgångsrika gruvarbetaren. Först då läggs transaktionerna till ett nytt block inom blockkedjan. På ett sätt liknar hashprocessen ett lotterisystem. Som ett resultat utfärdas nya mynt genom denna gruvprocess.

> Ju högre hashhastighet, desto svårare är det för en bedragare att få kontroll över blockkedjan eftersom mer hashkraft behövs. Med andra ord, ju högre svårighetsgrad, desto säkrare nätverk.

>

## Fördelar med svårigheter med kryptovaluta

Man kan undra varför ett nätverks deltagare skulle etablera en högre kryptovaluta-svårighet om resultatet innebar att gruvarbetare upprepade samma funktion om och om igen. Det finns två viktiga fördelar med svårigheter med kryptovaluta.

### En jämn takt av nya block

Bitcoin whitepaper av Satoshi Nakamoto förklarar hur proof-of-work-svårigheten hjälper till att generera en stadig produktion av nya block som läggs till blockkedjan.

>

> "För att kompensera för ökande hårdvaruhastighet och varierande intresse för att köra noder över tiden, bestäms svårigheten att arbeta med bevis av ett glidande medelvärde som riktar sig till ett genomsnittligt antal block per timme. Om de genereras för snabbt ökar svårigheten ."

>

Bitcoin är designat för att lägga till ett nytt block till blockkedjan i genomsnitt var tionde minut. Andra kryptovalutor siktar på mer frekventa blockeringar; [litecoin siktar](/litecoin) till exempel på 2,5 minuter. Problemet är att mängden datorkraft som nätverkets gruvarbetare kollektivt kontrollerar kan variera enormt.

När Satoshi Nakamoto bröt det första blocket fanns det bara en maskin på nätverket – troligen en enkel bärbar dator eller stationär dator. Idag finns det ett antal vidsträckta ASIC-gårdar i lagerstorlek. ASIC:er är maskiner som är speciellt utformade för att plöja igenom hashfunktioner så snabbt som möjligt.

För att säkerställa att nätverket producerar ett nytt block med en jämn genomsnittlig takt, är programvaran inställd på att automatiskt justera målhashen uppåt eller nedåt, vilket resulterar i lägre respektive högre svårighetsgrad. När Nakamoto bröt genesisblocket var bitcoins svårighet en.

### Nätverkssäkerhet

Den övergripande hashhastigheten ger insikt i ett kryptovalutanätverks säkerhet eftersom bedragare eller dåliga aktörer skulle behöva övervinna nätverkets totala hashkraft för att ta kontroll i en skadlig attack. Specialdesignade datorer används för att utföra hashfunktioner, som kan göra biljoner gissningar varje sekund för att lösa hashproblemet.

Ju högre svårighetsgrad för kryptovaluta, desto fler gissningar eller hash krävs för att nå målet hashkrav. Som ett resultat gör denna process det mycket svårt och dyrt för angripare att få majoritetskontrollen – kallad [51 % majoritet – av](/51-attack) ett blockkedjenätverk.

## Exempel på svårighetsgrad i kryptovaluta

Den 2 april 2021 var svårighetsgraden för kryptovaluta för bitcoin 23,14 biljoner. Om vi jämför förändringen i svårighetsgrad kan vi se att den 1 april 2018 var bitcoins svårighetsgrad 3,51 biljoner.

Diagrammet nedan visar bitcoins förändring i svårighetsgrad under åren:

##Höjdpunkter

– Svårighet i kryptovaluta är ett mått på hur svårt det är att bryta ett block i en blockkedja för en viss kryptovaluta.

– En hög kryptovaluta-svårighet innebär att det krävs ytterligare datorkraft för att verifiera transaktioner som görs i en blockkedja.

- Ju högre svårighetsgrad som behövs för att skapa ett block förbättrar ett kryptovalutanätverks säkerhet eftersom angripare skulle behöva enorma resurser för att ta kontroll.

