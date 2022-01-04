---
keywords: Crypto
title: Halvering
description: Halvering. Når blokkbelønningen for en kryptoaktiva faller til halvparten av hva den var før; dette brukes til å skape en avtagende utstedelsesrate.
---

# Halvering
I kryptovalutaområdet refererer begrepet halvering til en prosess som reduserer utstedelsesraten av nye mynter. Mer presist er halvering den periodiske reduksjonen av blokktilskuddet som gis til gruvearbeidere. Halveringen sikrer at en kryptoaktiva vil følge en jevn utstedelsesrate til dens [maksimale forsyning](/maximum-supply) til slutt er nådd.

Når det gjelder Bitcoin, genereres nyhetsmynter kontinuerlig som en del av [blokkbelønningen](/block-reward) (som består av blokktilskuddet pluss transaksjonsgebyrer). Så hver gang en gruvearbeider "oppdager" og validerer en ny [blokk](/block),. tjener de nyopprettede mynter som kompensasjon for arbeidet sitt.

Så [gruveprosessen](/mining) er det som introduserer nye [Bitcoins](/bitcoin) i systemet, og dette gjøres i et forutsigbart og kontrollert tempo. Nye Bitcoin-blokker utvinnes i gjennomsnitt hvert 10. minutt, og blokkstøtten følger en kontrollert forfallshastighet. Følgelig er halveringen det som sikrer at blokktilskuddet reduseres med 50 % for hver 210 000 blokker (omtrent hvert fjerde år).

Fra og med [genesis-blokken](/genesis-block) ble Bitcoins blokkstøtte opprinnelig satt til 50 BTC. Deretter ble den redusert til 25 BTC i 2012, og til 12,5 BTC i 2016. Følgende halvering forventes å skje rundt mai 2020, og reduserer blokktilskuddet til 6,25 BTC. Når 32 halveringer har skjedd, stopper prosessen og det vil ikke bli opprettet flere Bitcoins. På dette tidspunktet vil den maksimale forsyningen på 21 millioner BTC nås.

[Følg med på Bitcoin Halving](/halving)

Halveringen er en viktig del av Bitcoin-protokollen, og siden koden er åpen kildekode, kan alle se den. For eksempel er Bitcoin Core-implementeringen tilgjengelig på [GitHub](/github),. og en av kodedelene som definerer blokktilskuddet ser slik ut:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensusParams)

{

int halveringer = nHøyde / konsensusParams.nSubsidyHalvingInterval;

// Tving blokkbelønning til null når høyreskift er udefinert.

if (halveringer >= 64)

returner 0;

CA-beløp nSubsidy = 50 * MYNT;

// Tilskuddet halveres hver 210.000 blokker som vil skje omtrent hvert 4. år.

nTilskudd >>= halveringer;

retur nTilskudd;

}

