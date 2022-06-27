---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (kryptovaluta)
description: En Merkle-rot innehåller information om varje enskild transaktionshash som någonsin fanns på ett visst block i en blockkedja.
---

# Merkle Root (kryptovaluta)
## Vad är en Merkle-rot?

En Merkle-rot är [hashen](/hash) av alla hash-värden för alla transaktioner som ingår i ett block i ett [blockkedjenätverk](/blockchain).

## Förstå en Merkle-rot

En blockkedja består av olika block som är länkade med varandra (därav namnet blockchain). Ett hashträd, eller [Merkle-trädet](/merkle-tree),. kodar blockkedjedata på ett effektivt och säkert sätt. Det möjliggör snabb verifiering av blockkedjedata, såväl som snabb förflyttning av stora mängder data från en datornod till den andra på peer-to-peer blockchain-nätverket.

Varje transaktion som sker på blockchain-nätverket har en hash associerad med sig. Dessa hash lagras dock inte i en sekventiell ordning på blocket, snarare i form av en trädliknande struktur så att varje hash är länkad till sin förälder efter en förälder-barn-trädliknande relation.

Eftersom det finns många transaktioner lagrade på ett visst block, hashas även alla transaktionshashar i blocket, vilket resulterar i en Merkle-rot.

Tänk till exempel på ett block med sju transaktioner. På den lägsta nivån (kallad bladnivå) kommer det att finnas fyra transaktionshashar. På nivå ett ovanför lövnivån kommer det att finnas två transaktionshashar, som var och en ansluter till två hashar som ligger under dem på bladnivån. Överst (nivå två) kommer det att finnas den sista transaktions-hashen som kallas roten, och den kommer att ansluta till de två hasharna under den (på nivå ett).

I praktiken får du ett upp och nedvänt binärt träd, där varje nod i trädet ansluter till endast två noder under det (därav namnet "binärt träd"). Den har en rot-hash överst, som ansluter till två hash-hashar på nivå ett, som var och en åter ansluter till de två hasharna på nivå tre (bladnivå), och strukturen fortsätter beroende på antalet transaktionshashar.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Hashen startar på den lägsta nivån (lövnivå) noderna, och alla fyra hasharna ingår i hashen av noder som är länkade till den på nivå ett. På samma sätt fortsätter hashningen på nivå ett, vilket leder till att hashhaschar når högre nivåer, tills den når den enda övre rothashen.

Denna rothash kallas Merkle-roten, och på grund av den trädliknande kopplingen av hash innehåller den all information om varje enskild transaktionshash som finns på blocket. Den erbjuder ett enpunkts hashvärde som gör det möjligt att validera allt som finns på det blocket.

Till exempel, om man måste verifiera en transaktion som påstår sig ha kommit från block #137, behöver de bara kontrollera blockets Merkle-träd, utan att oroa sig för att verifiera något på andra block i blockkedjan, som block #136 eller block # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Ange Merkle-roten, vilket ytterligare påskyndar verifieringen. Eftersom den innehåller all information om hela trädet behöver man bara verifiera transaktionshashen, dess syskonnod (om den finns) och sedan fortsätta uppåt tills den når toppen.

I huvudsak minskar Merkle-trädet och Merkle-rotmekanismen avsevärt nivåerna av hash som ska utföras, vilket möjliggör snabbare verifiering och transaktioner.

## Höjdpunkter

– Merkles rötter är centrala för den beräkning som krävs för att upprätthålla kryptovalutor som bitcoin och eter.

- Merkle-rötter används i kryptovaluta för att se till att datablock som skickas mellan peers i ett peer-to-peer-nätverk är hela, oskadade och oförändrade.

– En Merkle-rot är ett enkelt matematiskt sätt att verifiera data på ett Merkle-träd.

