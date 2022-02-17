---
keywords: Crypto
title: Blomfilter
description: Blomfilter. En datastruktur som kan användas för att informera användaren om ett visst objekt är en del av en uppsättning artiklar
---

# Blomfilter
Ett Bloom-filter är en datastruktur som kan användas för att informera användaren om ett visst objekt är en del av en uppsättning. Även om det inte kan säga med säkerhet om ett element är i mängden, kan det med säkerhet säga om elementet inte är det.

Bloom-filter skapades av Burton Howard Bloom 1970 och är ett attraktivt erbjudande för en rad applikationer på grund av deras effektivitet i utrymmesanvändning. I vissa kryptovalutor (främst Bitcoin) spelar de en integrerad roll i Simplified Payment Verification, eller SPV.

Genom att använda en SPV-klient kan användare interagera med Bitcoin-nätverket utan att köra en full nod. Fullständiga noder kommer med vissa lagrings- och beräkningskrav som gör dem svårhanterliga att köra på lågeffektsenheter som smartphones. SPV-klienter, å andra sidan, frågar helt enkelt hela noder för information som är relevant för användarens plånbok(ar).

Den enklaste lösningen för att vidarebefordra denna data till användaren skulle vara att göra fullständiga noder medvetna om klientens nycklar, så att endast relevanta transaktioner skickas till dem. Uppenbarligen är detta en undermålig lösning eftersom kundens integritet skulle offras. Å andra sidan skulle det vara ett slöseri med bandbredd att ladda ner alla transaktioner bara för att kassera majoriteten av dem. Ange Bloom-filter.

Låt oss illustrera. Anta att en klient, Alice, har en transaktion av högt värde som hon inte vill att Bob, som kör en hel nod, ska vara medveten om. Hon konstruerar ett Bloom-filter, som vi illustrerar som ett 10x1 rutnät:

Hon skickar transaktionsdata hon är intresserad av genom två olika hashfunktioner, som matar ut två nummer mellan 0 och 9. Låt oss kalla dem 4 och 7. Hon skickar filtret till Bob.

När du tittar på det här rutnätet har du ingen aning om vilken data Alice har skickat till filtret. Om du hade en uppsättning där data fanns i, skulle du kunna hasha den och jämföra den med filtret – om det finns en matchning finns det en möjlighet att det var informationen som Alice begärde.

Samtidigt kommer det sannolikt att finnas många ingångar som kommer att mappas till 4 och 7, så Bob kan inte avgöra vilken del av data Alice är intresserad av. Han returnerar helt enkelt alla matcherna och Alice filtrerar dem på hennes sida.

Detta är naturligtvis en grov överförenkling, men det visar konceptet: Bloom-filter fördunklar kundens verkliga intressen. Det är inte en perfekt metod (det finns fortfarande oro över dess integritet), men det är en förbättring jämfört med en oskärmad begäran till en nod.

