---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Binomial Option prissättningsmodell
description: En binomial optionsprissättningsmodell är en optionsvärderingsmetod som använder en iterativ procedur och tillåter nodspecifikationen under en bestämd period.
---

# Binomial Option prissättningsmodell
## Vad är prissättningsmodellen för binomialoptioner?

Den binomiala optionsprissättningsmodellen är en [optionsvärderingsmetod](/valuation) som utvecklades 1979. Den binomiala optionsprissättningsmodellen använder en iterativ procedur som tillåter specificering av noder, eller tidpunkter, under tidsspannet mellan värderingsdatumet och [optionens](/expiration-date) [utgångsdatum](/expiration-date).

Modellen minskar möjligheterna till prisförändringar och tar bort möjligheten till [arbitrage](/arbitrage). Ett förenklat exempel på ett [binomialträd](/binomial_tree) kan se ut ungefär så här:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Grunderna i prissättningsmodellen för binomialoptioner

Med binomialoptionsprismodeller är antagandena att det finns två möjliga utfall – alltså den binomala delen av modellen. Med en prissättningsmodell är de två resultaten en uppgång eller en nedgång. Den stora fördelen med en binomial optionsprismodell är att de är matematiskt enkla. Ändå kan dessa modeller bli komplexa i en flerperiodsmodell.

I motsats till [Black-Scholes-modellen](/blackscholes),. som ger ett numeriskt resultat baserat på indata, tillåter den binomiala modellen beräkning av tillgången och möjligheten för flera perioder tillsammans med intervallet av möjliga resultat för varje period (se nedan).

Fördelen med denna flerperiodvy är att användaren kan visualisera förändringen i tillgångspriset från period till period och utvärdera alternativet baserat på beslut som fattats vid olika tidpunkter. För en USA-baserad [option](/americanoption),. som kan utnyttjas när som helst före [utgångsdatumet](/expirationdate),. kan den binomala modellen ge insikt om när det kan vara tillrådligt att utnyttja optionen och när den bör hållas under längre perioder.

Genom att titta på det [binomala](/binomial_tree) värdeträdet kan en handlare i förväg bestämma när ett beslut om en [övning](/exercise) kan inträffa. Om optionen har ett positivt värde finns möjlighet till utnyttjande medan, om optionen har ett värde mindre än noll, bör den innehas under längre perioder.

## Beräknar pris med binomialmodellen

Den grundläggande metoden för att beräkna binomialoptionsmodellen är att använda samma sannolikhet varje period för framgång och misslyckande tills optionen löper ut. En näringsidkare kan dock införliva olika sannolikheter för varje period baserat på ny information som erhålls allt eftersom.

Ett binomialträd är ett användbart verktyg vid prissättning av [amerikanska optioner](/americanoption) och [inbäddade optioner](/embeddedoption). Dess enkelhet är dess fördel och nackdel på samma gång. Trädet är lätt att modellera ut mekaniskt, men problemet ligger i de möjliga värdena på den underliggande tillgången kan ta på en tidsperiod. I en binomial trädmodell kan den underliggande tillgången bara vara värd exakt ett av två möjliga värden, vilket inte är realistiskt, eftersom tillgångar kan vara värda valfritt antal värden inom ett givet intervall.

Till exempel kan det finnas en 50/50 chans att det underliggande tillgångspriset kan öka eller minska med 30 procent under en period. För den andra perioden kan dock sannolikheten att det underliggande tillgångspriset ökar till 70/30.

Till exempel, om en investerare utvärderar en [oljekälla](/exploratory-well),. är den investeraren inte säker på vad värdet på den oljekällan är, men det finns en 50/50 chans att priset kommer att gå upp. Om oljepriserna går upp under period 1, vilket gör oljekällan mer värdefull och marknadsfundamenten [nu](/fundamentals) pekar på fortsatta ökningar av oljepriserna, kan sannolikheten för ytterligare prisuppgång nu vara 70 procent. Den binomiala modellen möjliggör denna flexibilitet; Black-Scholes-modellen gör det inte.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Real-World Exempel på binomial Option prissättningsmodell

Ett förenklat exempel på ett [binomialträd](/binomial_tree) har bara ett steg. Anta att det finns en aktie som är prissatt till $100 per aktie. Om en månad kommer priset på denna aktie att gå upp med $10 eller gå ned med $10, vilket skapar denna situation:

- **Lagerpris** = 100 USD

- **Aktiekurs på en månad (upp tillstånd)** = 110 USD

- **Aktiekurs på en månad (nedåt)** = 90 USD

Antag sedan att det finns en köpoption tillgänglig på denna aktie som löper ut om en månad och har ett lösenpris på 100 $. I upp-tillståndet är det här köpoptionen värt $10, och i ned-tillståndet är det värt $0. Binomialmodellen kan beräkna vad priset på köpoptionen ska vara idag.

För förenklingsändamål, anta att en investerare köper en halv andel av aktierna och skriver eller säljer en köpoption. Den totala investeringen idag är priset på en halv aktie minus priset på optionen, och de möjliga utbetalningarna i slutet av månaden är:

- **Kostnad idag** = 50 $ - optionpris

- **Portföljvärde** (upptillstånd) = 55 USD - max (110 USD - 100 USD, 0) = 45 USD

- **Portföljvärde** (nedåt) = 45 USD - max (90 USD - 100 USD, 0) = 45 USD

Portföljens utdelning är lika oavsett hur aktiekursen rör sig. Med tanke på detta resultat, förutsatt att det inte finns några arbitragemöjligheter, bör en investerare tjäna den riskfria räntan under månadens lopp. Kostnaden i dag ska vara lika med utdelningen diskonterad med riskfri ränta under en månad. Ekvationen att lösa är alltså:

- **Optionspris** = $50 - $45 xe ^ (-riskfri kurs x T), där e är den matematiska konstanten 2,7183.

Om vi antar att den riskfria räntan är 3 % per år och T är lika med 0,0833 (en dividerad med 12), så är priset på köpoptionen idag 5,11 USD.

Den binomiala prissättningsmodellen för optioner ger två fördelar för optionssäljare jämfört med Black-Scholes-modellen. Den första är dess enkelhet, vilket möjliggör färre fel i den kommersiella applikationen. Den andra är dess iterativa drift, som justerar priserna i tid för att minska möjligheten för köpare att utföra arbitragestrategier.

Till exempel, eftersom det tillhandahåller en ström av värderingar för ett [derivat](/derivative) för varje nod under en tidsperiod, är det användbart för att värdera derivat som amerikanska optioner – som kan utföras när som helst mellan köpdatum och utgångsdatum. Det är också mycket enklare än andra prismodeller som Black-Scholes-modellen.

##Höjdpunkter

– Modellen är intuitiv och används oftare i praktiken än den välkända Black-Scholes-modellen.

- Med modellen finns det två möjliga utfall med varje iteration—en flyttning uppåt eller en flyttning nedåt som följer ett binomialträd.

- Den binomala optionsprismodellen värderar optioner med hjälp av en iterativ metod som använder flera perioder för att värdera amerikanska optioner.

