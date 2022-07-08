---
keywords: Crypto
title: Helmingur
description: Helmingur. Þegar blokkarverðlaun dulritunareignar falla niður í helming af því sem áður var; þetta er notað til að skapa rýrnandi útgáfuhraða.
---

# Helmingur
Í dulritunargjaldmiðilsrýminu vísar hugtakið helmingun til ferlis sem dregur úr útgáfuhlutfalli nýrra mynta. Nánar tiltekið, helmingun er reglubundin lækkun á blokkastyrknum sem námuverkamönnum er veittur. Helmingahækkunin tryggir að dulmálseign fylgi stöðugu útgáfuhlutfalli þar til [hámarksframboði hennar](/maximum-supply) er að lokum náð.

Þegar kemur að Bitcoin er stöðugt verið að búa til fréttamynt sem hluti af [blokkarverðlaununum](/block-reward) (sem samanstendur af blokkarstyrknum auk viðskiptagjalda). Þannig að í hvert sinn sem námuverkamaður „uppgötvar“ og staðfestir nýja [blokk](/block),. vinna sér inn nýstofnaða mynt sem bætur fyrir vinnu sína.

Svo [námuvinnsluferlið](/mining) er það sem kynnir nýja [Bitcoins](/bitcoin) inn í kerfið og þetta er gert á fyrirsjáanlegum og stjórnuðum hraða. Nýjar Bitcoin blokkir eru unnar að meðaltali á 10 mínútna fresti og blokkarstyrkurinn fylgir stýrðu hrörnunarhraða. Samkvæmt því er helmingslækkunin það sem tryggir að blokkastyrkurinn lækkar um 50% á 210.000 blokkum (u.þ.b. á fjögurra ára fresti).

Frá og með [upphafsblokkinni var blokkastyrkur](/genesis-block) Bitcoin upphaflega stilltur sem 50 BTC. Síðan var það lækkað í 25 BTC árið 2012 og í 12,5 BTC árið 2016. Gert er ráð fyrir að eftirfarandi helmingaskipti verði í kringum maí 2020, sem dregur úr blokkarstyrknum í 6,25 BTC. Þegar 32 helmingaskipti hafa átt sér stað hættir ferlið og ekki verða fleiri Bitcoins búnir til. Á þessum tímapunkti verður hámarksframboði 21 milljón BTC náð.

[Fylgstu með Bitcoin helminguninni](/halving)

Helmingin er mikilvægur hluti af Bitcoin samskiptareglunum og þar sem kóðinn er opinn getur hver sem er séð hann. Til dæmis er Bitcoin Core útfærslan fáanleg á [GitHub](/github) og einn af kóðahlutunum sem skilgreinir blokkarstyrkinn lítur svona út:

CAmount GetBlockSubsidy(int nHeight, const Consensus::Params& consensusParams)

{

int helmingunar = nHeight / consensusParams.nSubsidyHalvingInterval;

// Þvingaðu blokkarverðlaun á núll þegar hægri vakt er óskilgreind.

ef (helmingur >= 64)

skila 0;

CAmount nSubsidy = 50 * COIN;

// Niðurgreiðsla er skorin niður í tvennt á 210.000 blokkum sem verða á um það bil 4 ára fresti.

nNiðurgreiðsla >>= helmingaskipti;

skila nNiðurgreiðsla;

}

