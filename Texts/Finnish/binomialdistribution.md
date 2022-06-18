---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Binomiaalinen jakauma
description: Binomijakauma on todennäköisyysjakauma, joka esittää yhteenvedon todennäköisyydestä, että arvo saa toisen kahdesta riippumattomasta arvosta.
---

# Binomiaalinen jakauma
## Mikä on binomiaalinen jakauma?

Binomijakauma on [todennäköisyysjakauma](/probabilitydistribution),. joka tiivistää todennäköisyyden, että arvo saa toisen kahdesta riippumattomasta arvosta tietyn parametrijoukon tai olettamusten alla.

Binomijakauman taustalla olevat oletukset ovat, että jokaisessa tutkimuksessa on vain yksi tulos, että jokaisella kokeella on sama onnistumisen todennäköisyys ja että jokainen kokeilu on [toisensa poissulkeva](/mutuallyexclusive) tai toisistaan riippumaton.

## Binomiaalijakauman ymmärtäminen

Binomijakauma on yleinen tilastoissa käytetty [diskreettijakauma](/discrete-distribution),. toisin kuin jatkuva jakauma, kuten [normaalijakauma](/normaldistribution). Tämä johtuu siitä, että binomijakauma laskee vain kaksi tilaa, jotka esitetään tyypillisesti 1:nä (onnistuminen) tai 0:na (epäonnistuminen), kun tiedoissa on useita kokeita. Binomijakauma edustaa siten x onnistumisen todennäköisyyttä n tutkimuksessa, kun kullekin kokeilulle on annettu onnistumistodennäköisyys p.

Binomijakauma esittää yhteenvedon kokeiden tai havaintojen lukumäärästä, kun jokaisella kokeella on sama todennäköisyys saavuttaa yksi tietty arvo. Binomijakauma määrittää todennäköisyyden havaita tietty määrä onnistuneita tuloksia tietyssä määrässä kokeita.

Binomijakaumaa käytetään usein yhteiskuntatieteiden tilastoissa rakennuspalikkana kaksijakoisten tulosmuuttujien malleille, kuten voittaako republikaani tai demokraatti tulevat vaalit vai kuoleeko henkilö tietyn ajan kuluessa jne.

## Binomiaalijakauman analysointi

Binomijakauman odotusarvo eli keskiarvo lasketaan kertomalla kokeiden määrä (n) onnistumistodennäköisyydellä (p) tai nx p.

Esimerkiksi päiden lukumäärän odotusarvo 100 Head and Tales -kokeessa on 50 eli (100 * 0,5). Toinen yleinen esimerkki binomijakaumasta on vapaaheiton onnistumismahdollisuuksien arviointi koripallossa, jossa 1 = kori on tehty ja 0 = ohitus.

Binomijakauman kaava lasketaan seuraavasti:

>

> P~(x:n,p)~ = ~n~C~x~ xp^x^(1-p)^nx^

>

missä:

- n on kokeiden (esiintymien) määrä

- X on onnistuneiden kokeiden lukumäärä

- p on onnistumisen todennäköisyys yhdessä kokeessa

- nCx on n:n ja x:n yhdistelmä. Yhdistelmä on joukko tapoja valita x elementin näyte n erillisen objektin joukosta, kun järjestyksellä ei ole väliä ja korvaukset eivät ole sallittuja. Huomaa, että nCx=n!/(r!(n−r)!), missä ! on faktoraalinen (eli 4! = 4 x 3 x 2 x 1)

Binomijakauman keskiarvo on np ja binomijakauman varianssi on np (1 − p). Kun p = 0,5, jakauma on symmetrinen keskiarvon ympärillä. Kun p > 0,5, jakauma on vinossa vasemmalle. Kun p < 0,5, jakauma on vinossa oikealle.

Binomijakauma on useiden riippumattomien ja identtisesti jakautuneiden Bernoulli-kokeiden sarjan summa. Bernoullin kokeessa kokeen sanotaan olevan satunnainen ja sillä voi olla vain kaksi mahdollista lopputulosta: menestys tai epäonnistuminen.

Esimerkiksi kolikon heittämistä pidetään Bernoullin oikeudenkäynninä; jokainen koe voi ottaa vain yhden kahdesta arvosta (pää tai häntä), jokaisella onnistumisella on sama todennäköisyys (pään kääntämisen todennäköisyys on 0,5), eivätkä yhden kokeen tulokset vaikuta toisen tuloksiin. Bernoullin jakauma on binomijakauman erikoistapaus, jossa kokeiden lukumäärä n = 1.

## Esimerkki binomijakaumasta

Binomijakauma lasketaan kertomalla onnistumisen todennäköisyys onnistumisten lukumäärän potenssilla ja epäonnistumistodennäköisyys korotettuna onnistumisten lukumäärän ja kokeiden lukumäärän erotuksen potenssilla. Kerro sitten tuote kokeiden määrän ja onnistumisten yhdistelmällä.

Oletetaan esimerkiksi, että kasino loi uuden pelin, jossa osallistujat voivat lyödä vetoa päiden tai tailojen määrästä tietyssä määrässä kolikonheittoja. Oletetaan, että osallistuja haluaa lyödä 10 dollarin vetoa, että 20 kolikonheitossa on täsmälleen kuusi päätä. Osallistuja haluaa laskea tämän tapahtumisen todennäköisyyden, ja siksi hän käyttää binomijakauman laskentaa.

Todennäköisyys laskettiin seuraavasti: (20! / (6! * (20 - 6)!)) * (0,50)^(6) * (1 - 0,50) ^ (20 - 6). näin ollen todennäköisyys, että täsmälleen kuusi päätä esiintyy 20 kolikonheitossa, on 0,037 eli 3,7 %. Odotettu arvo oli tässä tapauksessa 10 päätä, joten osallistuja teki huonon vedon.

##Kohokohdat

- Binomijakauma on todennäköisyysjakauma, joka tekee yhteenvedon todennäköisyydestä, että arvo saa toisen kahdesta riippumattomasta arvosta tietyn parametri- tai olettamusjoukon alla.

- Binomijakauman taustalla olevat oletukset ovat, että jokaisessa tutkimuksessa on vain yksi tulos, jokaisella kokeella on sama onnistumisen todennäköisyys ja että jokainen kokeilu on toisensa poissulkeva tai toisistaan riippumaton.

- Binomijakauma on yleinen tilastoissa käytetty diskreettijakauma, toisin kuin jatkuva jakauma, kuten normaalijakauma.

