---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: CoinJoin
description: CoinJoin är en anonymiseringsstrategi som skyddar Bitcoin-användares integritet när de genomför transaktioner med varandra.
---

# CoinJoin
## Vad är CoinJoin?

CoinJoin är en anonymiseringsstrategi som skyddar Bitcoin-användares integritet när de genomför transaktioner med varandra, vilket döljer källorna och destinationerna för BTC som används i transaktioner.

CoinJoin kräver att flera parter tillsammans undertecknar ett digitalt [smart kontrakt](/smart-contracts) för att blanda sina mynt i en ny Bitcoin-transaktion, där utdata från transaktionen lämnar deltagarna med samma antal mynt, men adresserna har blandats för att göra extern spårning svår.

Processen är också känd som myntblandning.

## Hur fungerar CoinJoin?

CoinJoin utvecklades för att introducera ett lager av integritet till annars offentliga Bitcoin-transaktioner. Frasen myntades av Bitcoin-utvecklaren Gregory Maxwell i en tillkännagivandetråd på Bitcoin Forum.

### Varför Bitcoin inte är helt privat

Även om Bitcoin i sina tidiga dagar hade ett rykte om sig att vara anonym och så användes för transaktioner på darknet-sajter som Silk Road, ger [kryptovalutan](/cryptocurrency) faktiskt väldigt lite sekretess. Bitcoin-adresser visar inte användarnas namn och adresser, men de är lätta att spåra och någon kanske kan koppla din IP-adress till din Bitcoin-transaktion.

När en användare har identifierats kan forskare använda vanliga digitala kriminaltekniska metoder för att spåra alla kontakter i nätverket. Detta är inte en bugg av Bitcoin, det är grunden för dess "trustless" system: alla transaktioner är offentliga för att förhindra användarbedrägerier.

Andra mynt har utvecklats för att införliva användarnas integritet i myntkoden. Monero, [ZCash](/zcash) och Dash är framträdande exempel. Moneros sekretessteknologi liknar CoinJoin, genom att den använder ringsignaturer för att blanda spenderarens signatur med andra användares signaturer för att göra spårning av adresser nästan omöjlig.

### CoinJoin är den första generationens sekretessåtgärd för Bitcoin

En användare som vill implementera CoinJoin i sin Bitcoin-transaktion måste hitta en annan användare som också vill blanda mynt, och tillsammans initierar de en gemensam transaktion. Adressen en bitcoin skickas från kallas en ingång.

Tänk på följande transaktioner som görs samtidigt: A köper en vara från B, C köper en vara från D och E köper en vara från F. Utan CoinJoin skulle den offentliga [blockchain](/blockchain) -reskontran registrera tre separata transaktioner för varje input-output-matchning . Med CoinJoin registreras endast en enda transaktion. Huvudboken skulle visa att bitcoins betalades från A-, C- och E-adresser till B, D och F. Genom att maskera affärerna som gjorts av alla parter kan en observatör inte med full säkerhet avgöra vem som skickade bitcoins till vem.

## CoinJoin-verktyg

Även om processen verkar klar i teorin, är det i praktiken svårt att gå med i transaktioner av flera skäl. För att deltagarna i anslutningen ska förbli anonyma måste de ansluta över ett Tor-nätverk, de måste kunna ganska mycket om kodning och de måste lita på varandra.

För att övervinna dessa hinder började CoinJoin-utvecklare tidigt att skapa verktyg som skulle göra processen automatisk för de flesta användare. De första försöken med ett CoinJoin-verktyg införlivades i plånböcker. De tidigaste exemplen var Dark Wallet, JoinMarket och SharedCoins. Dessa plattformar syftade till att ge en extra nivå av datamaskering för användare som gör transaktioner i Bitcoin.

Senare insatser inkluderar Wasabi Wallet och Whirlpool från Samourai Wallet. Det finns dock en viss kontrovers om hur pålitliga och säkra dessa plånböcker är och hur väl de [anonymiserar](/data-anonymization) Bitcoin-innehav.

## Höjdpunkter

– CoinJoin innebär en Bitcoin-transaktion med flera parter där alla parter i transaktionen lägger in och får ut samma mängd Bitcoin, men adresserna är blandade i transaktionen vilket gör myntens ursprung svår att spåra.

- CoinJoin utförs vanligtvis automatiskt av dedikerade tjänster som utför det. Att utföra en CoinJoin utan ett sådant verktyg är svårt och kräver avancerade kodningskunskaper.

- CoinJoin är en process som används för att anonymisera Bitcoin-transaktioner online.

