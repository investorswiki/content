---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Binomial opsjonsprismodell
description: En binomial opsjonsprisingsmodell er en opsjonsvurderingsmetode som bruker en iterativ prosedyre og tillater nodespesifikasjonen i en bestemt periode.
---

# Binomial opsjonsprismodell
## Hva er den binomiale opsjonsprismodellen?

Den binomiale opsjonsprisingsmodellen er en [opsjonsvurderingsmetode](/valuation) utviklet i 1979. Den binomiale opsjonsprisingsmodellen bruker en iterativ prosedyre, som tillater spesifikasjon av noder, eller tidspunkter, i løpet av tidsrommet mellom verdsettelsesdatoen og opsjonens [utløpsdato](/expiration-date) [.](/expiration-date)

Modellen reduserer mulighetene for prisendringer og fjerner muligheten for [arbitrasje](/arbitrage). Et forenklet eksempel på et [binomialtre](/binomial_tree) kan se omtrent slik ut:

<!--87C9D3D79FF63D08201E6E848035602D-->

## Grunnleggende om prismodellen for binomial opsjon

Med binomiale opsjonsprismodeller er forutsetningene at det er to mulige utfall - derav den binomiale delen av modellen. Med en prismodell er de to utfallene en bevegelse opp eller en bevegelse ned. Den største fordelen med en binomial opsjonsprismodell er at de er matematisk enkle. Likevel kan disse modellene bli komplekse i en flerperiodemodell.

I motsetning til [Black-Scholes-modellen](/blackscholes),. som gir et numerisk resultat basert på input, gir den binomiale modellen mulighet for beregning av eiendelen og muligheten for flere perioder sammen med utvalget av mulige resultater for hver periode (se nedenfor).

Fordelen med denne flerperiodevisningen er at brukeren kan visualisere endringen i aktivaprisen fra periode til periode og vurdere alternativet basert på beslutninger tatt på forskjellige tidspunkter. For en USA-basert [opsjon](/americanoption),. som kan utøves når som helst før [utløpsdatoen](/expirationdate),. kan den binomiale modellen gi innsikt i når det kan være tilrådelig å utøve opsjonen og når den bør holdes i lengre perioder.

Ved å se på det [binomiale verditreet](/binomial_tree),. kan en trader på forhånd bestemme når en beslutning om en [øvelse](/exercise) kan skje. Hvis opsjonen har en positiv verdi, er det mulighet for utøvelse, mens hvis opsjonen har en verdi mindre enn null, bør den holdes i lengre perioder.

## Beregner pris med den binomiale modellen

Den grunnleggende metoden for å beregne den binomiale opsjonsmodellen er å bruke samme sannsynlighet hver periode for suksess og fiasko til opsjonen utløper. Imidlertid kan en næringsdrivende inkludere forskjellige sannsynligheter for hver periode basert på ny informasjon innhentet etter hvert som tiden går.

Et binomialt tre er et nyttig verktøy når du skal prise [amerikanske opsjoner](/americanoption) og [innebygde alternativer](/embeddedoption). Dens enkelhet er dens fordel og ulempe på samme tid. Treet er lett å modellere ut mekanisk, men problemet ligger i de mulige verdiene til den underliggende eiendelen kan ta i løpet av en tidsperiode. I en binomial tremodell kan den underliggende eiendelen bare være verdt nøyaktig én av to mulige verdier, noe som ikke er realistisk, da eiendeler kan være verdt et hvilket som helst antall verdier innenfor et gitt område.

For eksempel kan det være en 50/50 sjanse for at den underliggende aktivaprisen kan øke eller synke med 30 prosent i løpet av en periode. For den andre perioden kan imidlertid sannsynligheten for at den underliggende aktivaprisen øker vokse til 70/30.

For eksempel, hvis en investor evaluerer en [oljebrønn](/exploratory-well),. er den investoren ikke sikker på hva verdien av den oljebrønnen er, men det er en 50/50 sjanse for at prisen vil gå opp. Hvis oljeprisen går opp i periode 1, noe som gjør oljebrønnen mer verdifull og markedsfundamentalene [nå](/fundamentals) peker mot fortsatt økning i oljeprisen, kan sannsynligheten for ytterligere prisstigning nå være 70 prosent. Den binomiale modellen tillater denne fleksibiliteten; Black-Scholes-modellen gjør det ikke.

<!--94DBA31F9D3220C6052579D485B8A416-->

## Virkelig eksempel på binomial opsjonsprisingsmodell

Et forenklet eksempel på et [binomialt tre](/binomial_tree) har bare ett trinn. Anta at det er en aksje som er priset til $100 per aksje. Om en måned vil prisen på denne aksjen gå opp med $10 eller gå ned med $10, noe som skaper denne situasjonen:

- **Aksjekurs** = $100

- **Aksjekurs på én måned (opp-status)** = $110

- **Aksjekurs på én måned (nedstatus)** = $90

Anta deretter at det er en kjøpsopsjon tilgjengelig på denne aksjen som utløper om en måned og har en innløsningspris på $100. I opp-tilstanden er dette kjøpsalternativet verdt $10, og i ned-tilstand er det verdt $0. Binomialmodellen kan beregne hva prisen på kjøpsopsjonen skal være i dag.

For forenklingsformål, anta at en investor kjøper halvparten av aksjen og skriver eller selger én kjøpsopsjon. Den totale investeringen i dag er prisen på en halv aksje minus prisen på opsjonen, og de mulige utbetalingene ved slutten av måneden er:

- **Kostnad i dag** = $50 - opsjonspris

- **Porteføljeverdi** (opp-status) = $55 - maks ($110 - $100, 0) = $45

- **Porteføljeverdi** (nedstatus) = $45 - maks ($90 - $100, 0) = $45

Porteføljeutbetalingen er lik uansett hvordan aksjekursen beveger seg. Gitt dette resultatet, forutsatt at det ikke er noen arbitrasjemuligheter, bør en investor tjene den risikofrie renten i løpet av måneden. Kostnaden i dag må være lik utbetalingen diskontert med risikofri rente i én måned. Ligningen som skal løses er slik:

- **Opsjonspris** = $50 - $45 xe ^ (-risikofri rate x T), der e er den matematiske konstanten 2,7183.

Forutsatt at den risikofrie renten er 3 % per år, og T er lik 0,0833 (en delt på 12), så er prisen på kjøpsopsjonen i dag $5,11.

Den binomiale opsjonsprisingsmodellen gir to fordeler for opsjonsselgere fremfor Black-Scholes-modellen. Den første er dens enkelhet, som tillater færre feil i den kommersielle applikasjonen. Den andre er dens iterative operasjonen, som justerer prisene i tide for å redusere muligheten for kjøpere til å utføre arbitragestrategier.

For eksempel, siden det gir en strøm av verdivurderinger for et [derivat](/derivative) for hver node i løpet av en tidsperiode, er det nyttig for å verdsette derivater som amerikanske opsjoner - som kan utføres når som helst mellom kjøpsdato og utløpsdato. Det er også mye enklere enn andre prismodeller som Black-Scholes-modellen.

##Høydepunkter

– Modellen er intuitiv og brukes hyppigere i praksis enn den velkjente Black-Scholes-modellen.

- Med modellen er det to mulige utfall med hver iterasjon – en bevegelse opp eller en bevegelse ned som følger et binomialt tre.

- Den binomiale opsjonsprisingsmodellen verdsetter opsjoner ved å bruke en iterativ tilnærming som bruker flere perioder for å verdsette amerikanske opsjoner.

