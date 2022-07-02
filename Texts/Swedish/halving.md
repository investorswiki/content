---
keywords: Crypto
title: Halvering
description: Halvering. När blockbelöningen för en kryptotillgång sjunker till hälften av vad den var tidigare; detta används för att skapa en sjunkande emissionshastighet.
---

# Halvering
I kryptovalutautrymmet syftar termen halvering på en process som minskar utgivningstakten av nya mynt. Mer exakt, halvering är den periodiska minskningen av blocksubventionen som ges till gruvarbetare. Halveringen säkerställer att en kryptotillgång kommer att följa en jämn emissionshastighet tills dess [maximala utbud](/maximum-supply) så småningom nås.

När det kommer till Bitcoin genereras nyhetsmynt kontinuerligt som en del av [blockbelöningen](/block-reward) (som utgörs av blocksubventionen plus transaktionsavgifter). Så varje gång en gruvarbetare framgångsrikt "upptäcker" och validerar ett nytt [block](/block) tjänar de nyskapade mynt som kompensation för sitt arbete.

Så [gruvprocessen](/mining) är det som introducerar nya [Bitcoins](/bitcoin) i systemet, och detta görs i en förutsägbar och kontrollerad takt. Nya Bitcoin-block utvinns i genomsnitt var tionde minut, och blocksubventionen följer en kontrollerad sönderfallshastighet. Följaktligen är halveringen det som säkerställer att blockstödet minskar med 50 % vart 210 000:e block (ungefär vart fjärde år).

Från och med [genesis-blocket](/genesis-block) sattes Bitcoins blocksubvention initialt till 50 BTC. Sedan sänktes den till 25 BTC 2012 och till 12,5 BTC 2016. Följande halvering förväntas ske runt maj 2020, vilket minskar blocksubventionen till 6,25 BTC. När 32 halveringar har skett stoppas processen och inga fler Bitcoins kommer att skapas. Vid denna tidpunkt kommer det maximala utbudet på 21 miljoner BTC att nås.

[Följ med Bitcoin Halving](/halving)

Halveringen är en viktig del av Bitcoin-protokollet och eftersom koden är öppen källkod kan vem som helst se den. Till exempel är Bitcoin Core-implementeringen tillgänglig på [GitHub](/github),. och en av kodsektionerna som definierar blocksubventionen ser ut så här:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensusParams)

{

int halverings = nHeight / consensusParams.nSubsidyHalvingInterval;

// Tvinga blockbelöning till noll när högerväxling är odefinierad.

if (halvering >= 64)

returnera 0;

CAbelopp nSubvention = 50 * MYNT;

// Subventionen halveras var 210 000:e block, vilket kommer att ske ungefär vart fjärde år.

nSubvention >>= halveringar;

returnera nSubvention;

}

