---
keywords: Investing,Cryptocurrency,Blockchain
title: Hyperledger tyg
description: Hyperledger Fabric är en plattform för att bygga olika blockkedjebaserade produkter, lösningar och applikationer för affärsbruk.
---

# Hyperledger tyg
## Vad är Hyperledger-tyg?

Hyperledger Fabric är ett modulärt [blockkedjeramverk](/blockchain) som fungerar som en grund för utveckling av blockkedjebaserade produkter, lösningar och applikationer med plug-and-play-komponenter som är avsedda för användning inom privata företag.

Hyperledger Fabric initierades av Digital Asset och IBM och har nu vuxit fram som ett branschövergripande samarbete, som för närvarande drivs av Linux Foundation. Bland de flera Hyperledger-projekten var Fabric det första som lämnade "inkubationsstadiet" och uppnådde det "aktiva" steget i mars 2017.

## Hur Hyperledger Fabric fungerar

Traditionella blockchain-nätverk kan inte stödja privata transaktioner och konfidentiella kontrakt som är av yttersta vikt för företag. Hyperledger Fabric designades som svar på detta som en modulär, skalbar och säker grund för att erbjuda industriella blockkedjelösningar.

Hyperledger Fabric är open source-motorn för blockchain och tar hand om de viktigaste funktionerna för att utvärdera och använda blockchain för affärsanvändningsfall.

Inom privata industriella nätverk är den verifierbara identiteten för en deltagare ett primärt krav. Hyperledger Fabric stöder medlemskap baserat på tillstånd; alla nätverksdeltagare måste ha kända identiteter. Många näringslivssektorer, såsom hälso- och sjukvård och finans, är bundna av dataskyddsbestämmelser som kräver att uppgifter om de olika deltagarna och deras respektive tillgång till olika datapunkter ska upprätthållas. Fabric stöder sådant tillståndsbaserat medlemskap.

### Modulär arkitektur

Den modulära arkitekturen hos Hyperledger Fabric separerar transaktionsbearbetningsarbetsflödet i tre olika steg: [smarta kontrakt](/smart-contracts) som kallas kedjekod som omfattar den distribuerade logiska bearbetningen och avtalet för systemet, transaktionsbeställning och transaktionsvalidering och åtagande. Denna segregation erbjuder flera fördelar:

- Ett minskat antal förtroendenivåer och verifiering som håller nätverket och bearbetningen rena

- Förbättrad nätverksskalbarhet

- Bättre prestanda totalt sett

Dessutom möjliggör Hyperledger Fabrics stöd för plug-and-play av olika komponenter enkel återanvändning av befintliga funktioner och färdig integrering av olika moduler. Till exempel, om det redan finns en funktion som verifierar deltagarens identitet, behöver ett nätverk på företagsnivå helt enkelt koppla in och återanvända denna befintliga modul istället för att bygga samma funktion från början.

Deltagarna i nätverket har tre distinkta roller:

- Endossör

- Kommittén

- Consenter

I ett nötskal, transaktionsförslaget skickas till endosser-peern enligt den fördefinierade rekommendationspolicyn om antalet endorsers som krävs. Efter tillräckliga rekommendationer från givaren/endossörerna, levereras en batch eller block av transaktioner till committer(erna). Committers bekräftar att rekommendationspolicyn följts och att det inte finns några motstridiga transaktioner. När båda kontrollerna är gjorda överförs transaktionerna till huvudboken.

<!--6376536357DF4ADC77E5CAB266DCF459-->

Bildkälla: IBM

Eftersom endast bekräftande instruktioner – såsom signaturer och läs-/skrivuppsättningar – skickas över nätverket, förbättras nätverkets skalbarhet och prestanda. Endast endossers och committers har tillgång till transaktionen, och säkerheten förbättras med ett färre antal deltagare som har tillgång till viktiga datapunkter.

## Exempel på Hyperledger Fabric

Anta att det finns en tillverkare som vill skicka choklad till en specifik återförsäljare eller marknad för återförsäljare (dvs. alla amerikanska återförsäljare) till ett specifikt pris men som inte vill avslöja det priset på andra marknader (dvs kinesiska återförsäljare).

Eftersom förflyttningen av produkten kan involvera andra parter, som tullen, ett rederi och en finansieringsbank, kan det privata priset avslöjas för alla inblandade parter om en grundläggande version av blockchain-teknik används för att stödja denna transaktion.

Hyperledger Fabric åtgärdar detta problem genom att hålla privata transaktioner privata på nätverket; endast deltagare som behöver veta är medvetna om de nödvändiga detaljerna. Datapartitionering på blockkedjan gör att specifika datapunkter är tillgängliga endast för de parter som behöver veta.

## Kritik av Hyperledger-tyg

Högvattenmärket för kryptoentusiasm bröts 2018 efter kollapsen av priset på bitcoin (som nådde sin topp den 17 december 2017). Överoptimistiska påståenden om värdet av den nya tekniken ersattes med skepsis, och relaterade teknologier, inklusive Hyperledger, led också av denna skepsis.

### Hyperledger Fabrics konkurrenter

Hyperledger Fabric konkurrerar med andra Hyperledger-projekt som Iroha, Indy och Sawtooth. Den konkurrerar också med R3:s Corda, som också är en privat, tillståndsbaserad DLT.

Blockchain-tjänsteföretaget Chainstack publicerade en artikel i januari 2020 som visar att utvecklingen i Corda har varit historiskt högre än utvecklingen inom Fabric, även om Fabric-utvecklingen passerade Cordas under Q3 2019 när Fabric bytte till GitHub.

Chainstack-rapporten visar att även om det finns tre gånger så många utvecklare som arbetar med Fabric, gjorde Corda-utvecklare mer än två gånger så många kodbidrag, och Fabric-utvecklare trycker på mycket mindre kod per utvecklare än Cordas utvecklare.

### Hyperledger-tyg är inte blockchain och är inte effektivt

Flera kritiker av Hyperledger Fabric påpekar att en tillståndsbaserad, privat blockkedja med Hyperledger Fabrics funktioner inte är en blockchain, och nuvarande icke-blockchain-teknologier är mycket billigare och ger samma mängd säkerhet. Cointelegraphs Stuart Popejoy uttryckte fallet så här:

>

> Fabrics arkitektur är mycket mer komplex än någon blockchain-plattform samtidigt som den är mindre säker mot manipulering och attacker. Man skulle kunna tro att en "privat" blockkedja åtminstone skulle erbjuda skalbarhet och prestanda, men Fabric misslyckas här också. Enkelt uttryckt kommer piloter byggda på Fabric att möta en komplex och osäker implementering som inte kommer att kunna skalas med deras företag .

>

Hyperledger Fabric har också kritiserats för bristande motståndskraft. Ett team av forskare från Sorbonne i Paris och CSIRO - Data61, Australiens nationella vetenskapsbyrå, fann att betydande nätverksförseningar minskade tillförlitligheten hos Fabric: "[B]genom att fördröja blockutbredningen visade vi att Hyperledger Fabric inte ger tillräckliga konsistensgarantier ska användas i kritiska miljöer. "

## Hyperledger Fabric 2.0 släpptes i januari 2020

I januari 2020 släpptes Hyperledger Fabric 2.0 för att ta itu med en del av den befintliga kritiken. Enligt Ron Miller på Techcrunch, "De största uppdateringarna innebär att man tvingar fram överenskommelse mellan parterna innan någon ny data kan läggas till i reskontran, känd som decentraliserad styrning av de smarta kontrakten."

Även om uppdateringen inte är en förändring i enkelheten eller tillämpbarheten av Fabric, visar den att framsteg fortsätter att göras i kryptovalutaindustrin bortom kryptomanin som inträffade 2018. Under de kommande fem till tio åren är det förväntas att företagsblockkedjan utan tvekan kommer att hitta rätt användning.

## Höjdpunkter

- Hyperledger är ett företagsklassat, distribuerat ledger-ramverk med öppen källkod som lanserades av Linux Foundation i december 2015.

– Eftersom Hyperledger Fabric är privat och kräver tillstånd för att få åtkomst, kan företag segregera information (som priser), plus transaktioner kan påskyndas eftersom antalet noder i nätverket minskar.

- Fabric 2.0 släpptes i januari 2020. Huvudfunktionerna i den här versionen är snabbare transaktioner, uppdaterad smart kontraktsteknik och strömlinjeformad datadelning.

- Fabric är en mycket modulär, decentraliserad ledger technology (DLT)-plattform som designades av IBM för industriellt företagsanvändning.

