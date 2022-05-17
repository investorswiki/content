---
keywords: Crypto
title: Halvering
description: Halvering. Når blokbelønningen for et kryptoaktiv falder til halvdelen af, hvad det var før; dette bruges til at skabe en faldende udstedelseshastighed.
---

# Halvering
I kryptovalutaområdet refererer udtrykket halvering til en proces, der reducerer udstedelsesraten af nye mønter. Mere præcist er halvering den periodiske reduktion af bloktilskuddet til minearbejdere. Halveringen sikrer, at et kryptoaktiv vil følge en stabil udstedelsesrate, indtil dets [maksimale forsyning](/maximum-supply) til sidst nås.

Når det kommer til Bitcoin, genereres nyhedsmønter løbende som en del af [blokbelønningen](/block-reward) (som består af bloktilskuddet plus transaktionsgebyrer). Så hver gang en minearbejder med succes "opdager" og validerer en ny [blok](/block),. tjener de nyoprettede mønter som kompensation for deres arbejde.

Så [mineprocessen](/mining) er det, der introducerer nye [Bitcoins](/bitcoin) i systemet, og dette sker i et forudsigeligt og kontrolleret tempo. Nye Bitcoin-blokke udvindes i gennemsnit hvert 10. minut, og bloktilskuddet følger en kontrolleret henfaldshastighed. Det er således halveringen, der sikrer, at bloktilskuddet falder med 50 % for hver 210.000 blokke (cirka hvert fjerde år).

Startende ved [genesis-blokken](/genesis-block) blev Bitcoins bloktilskud oprindeligt sat til 50 BTC. Derefter blev det reduceret til 25 BTC i 2012 og til 12,5 BTC i 2016. Den følgende halvering forventes at ske omkring maj 2020, hvilket reducerer bloktilskuddet til 6,25 BTC. Når der er sket 32 halveringer, stopper processen, og der vil ikke blive oprettet flere Bitcoins. På dette tidspunkt vil den maksimale forsyning på 21 millioner BTC blive nået.

[Følg med på Bitcoin Halving](/halving)

Halveringen er en vigtig del af Bitcoin-protokollen, og da koden er open source, kan enhver se den. For eksempel er Bitcoin Core-implementeringen tilgængelig på [GitHub](/github),. og en af kodesektionerne, der definerer bloktilskuddet, ser sådan ud:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensusParams)

{

int halveringer = nHøjde / konsensusParams.nSubsidyHalvingInterval;

// Tving blokbelønning til nul, når højreskift er udefineret.

hvis (halveringer >= 64)

returnere 0;

CA-beløb nSubsidy = 50 * MØNT;

// Tilskuddet halveres for hver 210.000 blokke, hvilket vil ske cirka hvert 4. år.

nTilskud >>= halveringer;

retur nTilskud;

}

