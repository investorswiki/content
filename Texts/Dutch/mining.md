---
keywords: Crypto
title: Minedrift
description: Minedrift. Verifikation af transaktioner på et blockchain-netværk, hvor transaktioner tilføjes som poster i blockchain-hovedbogen.
---

# Minedrift
Mining er den proces, hvorigennem [kryptovalutatransaktioner](/cryptocurrency) samles, verificeres og registreres i en digital hovedbog kendt som [blockchain](/blockchain). Det arbejde, der udføres af minearbejdere, er afgørende for at opretholde netværkets integritet og er også ansvarlig for at indføre nye mønter i systemet.

Inden for det traditionelle banksystem udskrives og distribueres fiat-valutaer af finansielle institutioner og statslige myndigheder - men for de fleste kryptovalutaer er udstedelsen af nye mønter ikke i hænderne på centraliserede enheder. I stedet genereres nye cryptocurrency-enheder gennem minedriftsprocessen, som følger et foruddefineret sæt regler, der er etableret af den underliggende protokol. Mens protokollen definerer, hvad de primære regler er, skitserer de såkaldte konsensusalgoritmer, hvordan disse regler vil blive fulgt (for eksempel under validering af transaktioner).

Tager vi Bitcoin som eksempel, kaldes deltagerne, der er involveret i processen med minedrift, minedriftsknuder (eller bare minearbejdere), og de spiller en nøglerolle i sikkerheden af blockchain-netværket. En minearbejders opgave er at samle ubekræftede transaktioner fra hukommelsespuljen og organisere dem i en [kandidatblok,](/candidate-block) som de vil forsøge at validere.

Når man opretter en kandidatblok, inkluderer en minearbejder en transaktion, hvor de sender [blokbelønningen](/block-reward) til sig selv. Denne transaktion er kendt som en møntbase-transaktion og er ofte den første, der registreres i en blok.

Efter at listen over ubekræftede transaktioner er dannet, hashes hver transaktion, og deres output organiseres i par. Disse par hashes derefter, hvilket producerer nye output, der også organiseres i par og hash igen. Processen gentages, indtil der produceres en enkelt hash, som omtales som rodhash eller [Merkle](/merkle-tree) trærod.

Rodhashen kombineres derefter med hashen for den tidligere bekræftede blok sammen med et pseudo-tilfældigt tal kaldet [nonce](/nonce) (plus nogle andre parametre). Disse elementer hashes derefter, hvilket producerer blokhashen for den pågældende kandidatblok.

Miner vil dog kun få succes, hvis det resulterende output (blokhash) for deres kandidatblok er under en forudbestemt værdi (mål). Derfor er processen baseret på forsøg og fejl, og de skal udføre adskillige hashing-funktioner med forskellige nonces for at finde et gyldigt resultat. Den første minearbejder, der finder en gyldig hash, validerer deres kandidatblok og får blokbelønningen. Hele processen tager i gennemsnit ti minutter.

Når en blok er blevet valideret, føjes den til blockchain, og minearbejdere begynder at arbejde på den næste blok. Den gyldige hash produceret af minearbejdere fungerer som beviset for deres arbejde, og det er derfor, Bitcoin-konsensusalgoritmen kaldes Proof of Work. Hver bekræftet blok har en unik blokhash, der fungerer som en identifikator.

Blokbelønningen er defineret af Bitcoin-protokollen og falder for hver 210.000 blokke (omkring fire år) [.](/block-reward) Oprindeligt var blokbelønningen 50 BTC og er nu 12,5 BTC.

