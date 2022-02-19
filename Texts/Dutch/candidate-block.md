---
keywords: Crypto
title: Kandidatblok
description: Kandidatblok. En midlertidig blok oprettet af en minedriftsknude (miner) for at tilføje til blockchain for at modtage blokbelønninger.
---

# Kandidatblok
Med få ord er en kandidatblok en blok, som en mineknude (miner) forsøger at mine for at modtage blokbelønningen. Så en kandidatblokering kan beskrives som en midlertidig blokering, der enten vil blive valideret eller kasseret af netværket. Minearbejdere konkurrerer med hinanden om at validere den næste blok og tilføje den til blockchainen, men først skal de oprette en kandidatblok for at deltage i minekonkurrencen.

Kandidatblokke oprettes af minearbejdere ved at indsamle og organisere flere ubekræftede transaktioner fra hukommelsespuljen. Transaktionerne hashes derefter for at danne en [Merkle-træstruktur](/merkle-tree),. som til sidst vil producere en Merkle-rod (eller rodhash). Merkle-roden er en enkelt hash, der repræsenterer alle tidligere hashes i det pågældende træ, og derfor alle transaktioner, der var inkluderet i den pågældende blok.

Rodhashen - sammen med den forrige bloks hash og et tilfældigt tal kaldet [nonce](/nonce) - sættes derefter i blokkens overskrift. Blokhovedet hashes derefter af miner, og genererer et output baseret på disse komponenter (rodhash, forrige bloks hash og nonce) plus et par andre elementer. Det resulterende output er blokhashen og vil tjene som en unik identifikator for den nyligt genererede blok (kandidatblok).

For at blive betragtet som gyldig, skal output (blokhash) starte med et vist antal nuller (mindre end en målværdi, der er defineret af protokollen). Det betyder, at miningprocessen er baseret på flere forsøg (trial and error), da minedriftsknuderne skal udføre et utal af hashing-funktioner med forskellige nonce-værdier, indtil der til sidst produceres en gyldig blokhash. Den producerede blokhash er det, der beviser, at minearbejderen udførte sit arbejde (derfor bevis på arbejde).

Når en minearbejder har fundet en gyldig blokhash, vil deres kandidatblok blive udsendt til resten af netværkets noder, som vil bekræfte hashens ægthed. Hvis alt er godt, vil kandidatblokken derefter blive registreret i blockchainen. På dette tidspunkt opdaterer hver validerende node sin kopi af blockchain-dataene for at afspejle den seneste minerede blok, og minearbejderen vil modtage blokbelønningen.

