---
keywords: Crypto
title: Gruvedrift
description: Gruvedrift. Verifisering av transaksjoner på et blokkjedenettverk, der transaksjoner legges til som oppføringer i blokkjedeboken.
---

# Gruvedrift
Gruvedrift er prosessen der [kryptovalutatransaksjoner](/cryptocurrency) samles inn, verifiseres og registreres i en digital hovedbok kjent som [blockchain](/blockchain). Arbeidet som gjøres av gruvearbeidere er avgjørende for å opprettholde integriteten til nettverket og er også ansvarlig for å introdusere nye mynter i systemet.

Innenfor det tradisjonelle banksystemet blir fiat-valuta skrevet ut og distribuert av finansinstitusjoner og statlige myndigheter – men for de fleste kryptovalutaer er ikke utstedelsen av nye mynter i hendene på sentraliserte enheter. I stedet genereres nye kryptovalutaenheter gjennom prosessen med gruvedrift, som følger et forhåndsdefinert sett med regler etablert av den underliggende protokollen. Mens protokollen definerer hva de primære reglene er, skisserer de såkalte konsensusalgoritmene hvordan disse reglene vil bli fulgt (for eksempel under validering av transaksjoner).

For å ta Bitcoin som et eksempel, kalles deltakerne som er involvert i prosessen med gruvedrift gruvedriftsnoder (eller bare gruvearbeidere), og de spiller en nøkkelrolle i sikkerheten til blokkjedenettverket. Jobben til en gruvearbeider er å samle ubekreftede transaksjoner fra minnepoolen og organisere dem i en [kandidatblokk](/candidate-block) som de vil prøve å validere.

Når du oppretter en kandidatblokk, inkluderer en gruvearbeider en transaksjon der de sender [blokkbelønningen](/block-reward) til seg selv. Denne transaksjonen er kjent som en myntbasetransaksjon og er ofte den første som registreres i en blokk.

Etter at listen over ubekreftede transaksjoner er dannet, hashes hver transaksjon, og utdataene deres organiseres i par. Disse parene hashes deretter, og produserer nye utdata som også organiseres i par og hashes igjen. Prosessen gjentas til en enkelt hasj er produsert, som omtales som rothash eller [Merkle](/merkle-tree) trerot.

Rothashen blir deretter kombinert med hashen til den tidligere bekreftede blokken, sammen med et pseudo-tilfeldig tall kalt [nonce](/nonce) (pluss noen andre parametere). Disse elementene hashes deretter, og produserer blokkhashen for den kandidatblokken.

Imidlertid vil gruvearbeideren bare lykkes hvis den resulterende utgangen (blokkhash) for deres kandidatblokk er under en forhåndsbestemt verdi (mål). følgelig er prosessen basert på prøving og feiling, og de må utføre en rekke hashing-funksjoner med forskjellige nonces for å finne et gyldig resultat. Den første gruvearbeideren som finner en gyldig hash validerer sin kandidatblokk og får blokkbelønningen. Hele prosessen tar i gjennomsnitt ti minutter.

Når en blokk er validert, blir den lagt til blokkjeden og gruvearbeidere begynner å jobbe med neste blokk. Den gyldige hasjen produsert av gruvearbeidere fungerer som beviset for arbeidet deres, og dette er grunnen til at Bitcoin-konsensusalgoritmen kalles Proof of Work. Hver bekreftet blokk har en unik blokkhash som fungerer som en identifikator.

Blokkbelønningen er definert av Bitcoin-protokollen og avtar hver 210 000 blokker (rundt fire år) [.](/block-reward) Opprinnelig var blokkbelønningen 50 BTC og er nå 12,5 BTC.

