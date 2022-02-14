---
keywords: Business,Corporate Finance and Accounting,Financial Ratios
title: Keskihajonnan laskenta
description: Mikä on keskihajonta? Keskihajonta on mittari, joka mittaa arvopaperin tuoton vaihtelua ajan kuluessa. Sitä voidaan käyttää volatiliteetin mittaamiseen
---

# Keskihajonnan laskenta
## Mikä on keskihajonta?

Keskihajonta on mittari, joka mittaa [arvopaperin](/security) tuoton vaihtelua ajan kuluessa. Sitä voidaan käyttää [volatiliteetin mittaamiseen](/volatility) aiempaan tuottoon perustuen ja tulevan tuoton vertaamiseen aikaisempaan tuottoon. Keskihajonta voi myös kvantifioida yksittäisten salkkujen tuottojen jakautumisen, ja sitä voidaan käyttää erityyppisiin omaisuuseriin, mukaan lukien [joukkovelkakirjat](/bond),. hyödykkeet ja kryptovaluutat. Tämä artikkeli keskittyy kuitenkin osakkeisiin.

Keskihajonta näyttää kuinka kaukana osakkeen tuotto on sen jakson keskimääräisestä tuotosta, ja se voi myös määrittää, onko tietyn ajanjakson tuotto poikkeava. On hyödyllistä soveltaa julkisesti noteeratun yhtiön osakekurssin epävakauden aikoina, koska lyhyen ajanjakson suuret nousu- ja laskuheilahtelut voivat auttaa määrittämään sijoitusriskin suhteessa tuottoon.

## Keskihajonnan laskeminen laskentataulukon avulla (esimerkki: Apple)

Keskihajonnan ymmärtäminen tarkoittaa ensinnäkin varianssin ymmärtämistä, koska keskihajonta on matemaattisesti ottaen varianssin neliöjuuri. Varianssi osoittaa, kuinka kaukana kukin tuotto on tuottotietojen joukon keskiarvosta tai keskiarvosta.

Luku, joka on suurempi kuin 0, osoittaa, että joukon tuotot ovat kaukana keskiarvosta ja kaukana toisistaan, kun taas numero, joka on huomattavasti suurempi kuin 0, viittaa paljon kauempana keskiarvosta. Koska tietojen varianssi on neliöity, keskihajonta palauttaa tiedot takaisin samaan mittayksikköön (osakkeiden tapauksessa prosenttiin) ottamalla neliöjuuren.

**Huomautus**: Keskihajonnat esitetään kaavoissa σ:llä, kreikan pienellä sigman kirjaimella.

Tehokkain tapa laskea keskihajonta, erityisesti suuren tietojoukon, kuten päivittäisten osakekurssien, kanssa on laskentataulukko. Alla on esimerkki Applen osaketuoton keskihajonnan laskemisesta kolmen kuukauden ajalta.

**Vaihe 1**: Kerää päivittäisiä tietoja kolmen kuukauden ajalta. Tämä vastaa karkeasti noin 20 päivää kuukaudessa, ja ensimmäinen päivä toimii perushintana laskettaessa ensimmäistä prosentuaalista muutosta. Laske Applen osakkeen päivittäinen prosenttimuutos ja ilmaise tiedot prosentteina. **Huomautus**: Kaava näkyy solussa sekä laskentataulukon vasemman yläkulman kenttäalueella. Applen osakkeen päätöskurssi (ilmaistuna Yhdysvaltain dollareina) sisältää oikaisut, mukaan lukien splitsit, osingot ja/tai myyntivoiton jakaminen.

**Vaihe 2**: Laske tuottojen keskiarvo käyttämällä AVERAGE-funktiota.

**Vaihe 3**: Laske palautusten varianssi käyttämällä VAR-funktiota.

**Vaihe 4**: Laske palautusten keskihajonta käyttämällä STDEV-funktiota. **Huomautus**: Keskimääräinen ja keskihajonna ilmaistaan prosentteina, kun taas varianssi on desimaaliluku.

## Keskihajonnan tulkitseminen

Yllä olevassa Applen esimerkissä tiedot osoittavat, että kolmen kuukauden keskimääräinen tuotto oli 0,08 prosenttia. Varianssi näyttää lukualueen etäisyyden keskiarvosta. Mutta keskihajonta näyttää tarkalleen kuinka kaukana tuotot ovat keskiarvosta. Keskihajonnan ollessa 1,91 prosenttia, se viittaa siihen, että vaihteluväli on plus tai miinus 1,91 prosenttiyksikköä keskiarvosta, mikä tarkoittaa, että Applen tuotto vaihtelee -1,83 prosentista 1,99 prosenttiin.

### Keskihajonnan todennäköisyys normaalijakaumassa

Keskihajonta voidaan parhaiten havainnollistaa todennäköisyyden normaalijakaumakuviolla, joka antaa tilastollisen kuvan siitä, missä keskihajonna voi olla. Normaalijakaumassa suurin osa skenaarioista tapahtuu todennäköisyydellä lähempänä keskiarvoa. Harvemmilla tapauksilla on taipumus esiintyä ulospäin, kohti litistyviä alueita, jotka tunnetaan nimellä häntä.

Alla olevassa kaaviossa normaalijakauma on kellon muotoinen, mistä johtuu sen lempinimi kellokäyrä, jossa käyrän keskikohta edustaa keskiarvoa. Kuvaajan alla vaakasuunnassa luetellut luvut tunnetaan z-pisteinä, jotka vaihtelevat -3:sta 3:een. Ne ovat keskihajonnan pisteitä ja ne on artikuloitu eri tavalla kuin keskihajontakaava, joka ilmaistaan prosentteina.

Normaalijakauman laskelma voi antaa todennäköisyyksiä, millä parametreilla potentiaaliset tuotot voivat olla. Oletetaan, että päiväkauppias ennustaa Applen osakkeen nousevan 5 prosenttia seuraavana päivänä sen jälkeen, kun se on raportoinut viimeisimmän raportoidun vuosineljänneksen ennätystulot ja tulot. Millä todennäköisyydellä osake tuottaa 5 prosentin tuoton seuraavana päivänä?

Z-koodin kaava voi näyttää, missä tuotto olisi normaalijakauman kaaviossa.

Kytkemällä Applen ennustettu tuotto, keskiarvo ja keskihajonta yllä olevasta laskentataulukosta:

> (5 % - 0,08 %) / 1,91 % = 2,57 keskihajontaa keskiarvon yläpuolella.

Mahdollinen 5 prosentin tuotto Applen osakkeelle olisi 2,57 standardipoikkeamaa keskiarvon yläpuolella, mikä jää 2–3 standardipoikkeaman välille keskiarvosta. Tilastollisesti se tarkoittaa 2,28 prosentin todennäköisyyttä saavuttaa ennustettu 5 prosentin tuotto. Tämä 2,28 prosentin todennäköisyys saadaan vähentämällä 95,44 prosenttia 100 prosentista, ja erotus (4,56 prosenttia) jaetaan sitten kahdella, koska normaalijakaumakaavion symmetrisen viivan kummallakin puolella on yhtä suuri todennäköisyys (negatiivinen ja positiivinen). . Joka tapauksessa 5 prosentin päivittäinen voitto Applen osakkeista ei olisi yleistä.

Toinen tapa tulkita normaalijakaumaa on sanoa, että todennäköisyys, että Applen tuotto (välillä -1,83 prosenttia ja 1,99 prosenttia) osuu -1 ja 1 keskihajonnan sisälle keskiarvosta on 68,26 prosenttia. Keskihajonnan todennäköisyys välillä -2 ja 2 on 95,44 prosenttia ja välillä -3 ja 3 se on 99,74 prosenttia.

## Miten keskihajonta liittyy volatiliteettiin?

Keskihajonta voi osoittaa, kuinka tuotto liittyy keskiarvoon. Suuri keskihajonta osoittaisi suurta volatiliteettia, ja standardipoikkeama-aluetta suurempi tuotto viittaa siihen, että se on poikkeava. Sarja ylös ja alas heilahteluja tämän alueen ulkopuolella tietyn ajanjakson ajan osoittaisivat myös suurta volatiliteettia.

## Kohokohdat

- Se lasketaan varianssin neliöjuurena.

- Rahoitusalalla standardipoikkeamaa käytetään usein omaisuuserän suhteellisen riskin mittarina.

- Keskihajonta mittaa aineiston hajontaa suhteessa sen keskiarvoon.

- Haihtuvalla osakkeella on korkea keskihajonta, kun taas vakaan blue-chip -osakkeen poikkeama on yleensä melko pieni.

- Haittapuolena keskihajonta laskee kaiken epävarmuuden riskiksi, vaikka se olisikin sijoittajan edun mukaista – esimerkiksi keskimääräistä paremmat tuotot.

## UKK

### Mitä suuri standardipoikkeama tarkoittaa?

Suuri keskihajonta osoittaa, että havaituissa tiedoissa on paljon varianssia keskiarvon ympärillä. Tämä osoittaa, että havaitut tiedot ovat melko hajallaan. Pieni tai alhainen keskihajonta osoittaisi sen sijaan, että suuri osa havaituista tiedoista on ryhmitelty tiukasti keskiarvon ympärille.

### Miksi keskihajonta on tärkeää?

Keskihajonta on tärkeä, koska se voi auttaa käyttäjiä arvioimaan riskejä. Harkitse sijoitusvaihtoehtoa, jonka keskimääräinen vuosituotto on 10 % vuodessa. Tämä keskiarvo on kuitenkin johdettu viimeisten kolmen vuoden tuotoista 50%, -15% ja -5%. Laskemalla keskihajonnan ja ymmärtämällä alhaisen todennäköisyytesi, että keskiarvo on 10 % jonakin yksittäisenä vuonna, olet paremmin varustautunut tekemään tietoisia päätöksiä ja tunnistamaan taustalla olevat riskit.

### Mitä keskihajonta kertoo?

Keskihajonta kuvaa, kuinka hajanainen tietojoukko on. Se vertaa kutakin datapistettä kaikkien datapisteiden keskiarvoon, ja keskihajonta palauttaa lasketun arvon, joka kuvaa, ovatko datapisteet lähellä vai ovatko ne hajallaan. Normaalijakaumassa keskihajonta kertoo, kuinka kaukana arvot ovat keskiarvosta.

### Miten keskihajonta lasketaan?

Keskihajonta lasketaan varianssin neliöjuurena. Vaihtoehtoisesti se lasketaan etsimällä tietojoukon keskiarvo, etsimällä kunkin datapisteen ero keskiarvoon, neliöimällä erot, laskemalla ne yhteen, jakamalla tietojoukon pisteiden määrällä 1 vähennettynä ja etsimällä neliö juuri.

### Kuinka löydät keskihajonnan nopeasti?

Jos katsot joidenkin havaittujen tietojen jakautumista visuaalisesti, voit nähdä, onko muoto suhteellisen laiha vs. lihava. Lihavammilla jakaumilla on suurempi keskihajonta. Vaihtoehtoisesti Excelissä on sisäänrakennetut standardipoikkeamafunktiot tietojoukosta riippuen.

