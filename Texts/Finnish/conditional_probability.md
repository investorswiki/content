---
keywords: Investing,Fundamental Analysis,Tools for Fundamental Analysis,Tools
title: Ehdollinen todennäköisyys
description: Ehdollinen todennäköisyys on tapahtuman tai lopputuloksen todennäköisyys, joka perustuu jonkin muun aikaisemman tapahtuman tai tuloksen toteutumiseen.
---

# Ehdollinen todennäköisyys
## Mikä on ehdollinen todennäköisyys?

Ehdollinen todennäköisyys määritellään tapahtuman tai lopputuloksen toteutumisen todennäköisyydeksi, joka perustuu aikaisemman tapahtuman tai lopputuloksen esiintymiseen. Ehdollinen todennäköisyys lasketaan kertomalla edellisen tapahtuman [todennäköisyys](/compound-probability) seuraavan tai ehdollisen tapahtuman päivitetyllä todennäköisyydellä.

Esimerkiksi:

- Tapahtuma A on, että korkeakouluun hakeva henkilö hyväksytään. On 80 %:n todennäköisyys, että tämä henkilö hyväksytään yliopistoon.

- Tapahtuma B on, että tälle henkilölle annetaan asuntola. Asuntola-asuntoja tarjotaan vain 60 %:lle kaikista hyväksytyistä opiskelijoista.

- P (Hyväksytty asunto ja asuntola) = P (Asuntola-asunto | Hyväksytty) P (Hyväksytty) = (0,60)*(0,80) = 0,48.

Ehdollinen todennäköisyys tarkastelee näitä kahta tapahtumaa suhteessa toisiinsa, kuten todennäköisyys, että teidät molemmat hyväksytään korkeakouluun, **ja** sinulle tarjotaan asuntola.

Ehdollinen todennäköisyys voidaan verrata [ehdottomaan todennäköisyyteen](/unconditional_probability). Ehdoton todennäköisyys viittaa todennäköisyyteen, että tapahtuma tapahtuu riippumatta siitä, onko muita tapahtumia tai muita ehtoja olemassa.

## Ehdollisen todennäköisyyden ymmärtäminen

Kuten aiemmin todettiin, ehdolliset todennäköisyydet riippuvat [aikaisemmasta tuloksesta](/prior_probability). Se tekee myös useita oletuksia. Oletetaan esimerkiksi, että piirrät kolme marmoria – punaista, sinistä ja vihreää – pussista. Jokaisella marmorilla on yhtä suuri mahdollisuus tulla piirretyksi. Mikä on ehdollinen todennäköisyys piirtää punainen marmori sen jälkeen, kun sininen on jo piirretty?

Ensinnäkin sinisen marmorin piirtämisen todennäköisyys on noin 33%, koska se on yksi mahdollinen tulos kolmesta. Olettaen, että tämä ensimmäinen tapahtuma tapahtuu, jäljelle jää kaksi marmoria, joista kummallakin on 50 %:n mahdollisuus tulla arvoon. Joten mahdollisuus piirtää sininen marmori punaisen marmorin jo piirtämisen jälkeen olisi noin 16,5 % (33 % x 50 %).

> Ehdollista todennäköisyyttä käytetään useilla aloilla, kuten [vakuutusalalla](/probable-maximum-loss-pml),. politiikassa ja monilla eri matematiikan aloilla.

>

Toisena esimerkkinä, joka antaa lisätietoa tästä käsitteestä, harkitse, että reilu noppaa on heitetty ja sinua pyydetään antamaan todennäköisyys, että se oli viisi. On kuusi yhtä todennäköistä lopputulosta, joten vastauksesi on 1/6.

Mutta kuvittele, jos ennen vastaamista saat lisätietoa siitä, että heitetty numero oli pariton. Koska mahdollisia on vain kolme paritonta lukua, joista yksi on viisi, tarkistat varmasti arviosi todennäköisyydestä, että viisi heitettiin 1/6:sta 1/3:ksi.

Tätä **tarkistettua** todennäköisyyttä, että tapahtuma **A** on tapahtunut, kun otetaan huomioon lisätiedot, että toinen tapahtuma **B** on ehdottomasti tapahtunut tässä kokeen kokeessa, kutsutaan **ehdolliseksi todennäköisyydeksi** **A** **annettu** **B** ja sitä merkitään P(A|B).

## Ehdollinen todennäköisyyskaava

>

> **P(B|A) = P(A ja B) / P(A)**

>

**Tai:**

>

> **P(B|A) = P(A∩B) / P(A)**

>

>

> **Missä**

>

>

> **P = todennäköisyys**

>

>

> **A = Tapahtuma A**

>

>

> **B = Tapahtuma B**

>

## Toinen esimerkki ehdollisesta todennäköisyydestä

Toisena esimerkkinä oletetaan, että opiskelija hakee pääsyä yliopistoon ja toivoo saavansa akateemisen stipendin. Koulu, johon he hakevat, hyväksyy 100 jokaisesta 1000 hakijasta (10 %) ja myöntää akateemisia stipendejä 10:lle jokaisesta 500 hyväksytystä opiskelijasta (2 %).

Apurahansaajista 50 % saa myös yliopisto-apurahaa kirjoihin, aterioihin ja asumiseen. Opiskelijoiden mahdollisuus tulla hyväksytyksi ja sitten saada stipendi on 0,2 % (.1 x .02). Mahdollisuus tulla hyväksytyksi, saada stipendi, sitten myös stipendi kirjoista jne. on ,1 % (.1 x .02 x .5).

## Ehdollinen todennäköisyys vs. yhteinen todennäköisyys ja marginaalitodennäköisyys

**Ehdollinen todennäköisyys**: p(A|B) on tapahtuman A todennäköisyys, jos tapahtuma B tapahtuu. Jos esimerkiksi vedit punaisen kortin, mikä on todennäköisyys, että se on neljä (p(neljä|punainen))=2/26=1/13. Joten 26 punaisesta kortista (joille annetaan punainen kortti) on kaksi neloa, joten 2/26=1/13.

**Marginaalitodennäköisyys**: tapahtuman todennäköisyys (p(A)), sitä voidaan pitää ehdottomana todennäköisyytenä. Se ei ole sidottu toiseen tapahtumaan. Esimerkki: todennäköisyys, että vedetty kortti on punainen (p(punainen) = 0,5). Toinen esimerkki: todennäköisyys, että vedetty kortti on 4 (p(neljä)=1/13).

[Yhteinen todennäköisyys](/jointprobability) : p(A ja B). Tapahtuman A **ja** tapahtuman B todennäköisyys. Se on kahden tai useamman tapahtuman risteyksen todennäköisyys. A:n ja B:n leikkauspisteen todennäköisyys voidaan kirjoittaa p(A ∩ B). Esimerkki: todennäköisyys, että kortti on neljä ja punainen =p(neljä ja punainen) = 2/52=1/26. (52:n pakassa on kaksi punaista neloa, sydämen 4 ja timanttien 4).

## Bayesin lause

[Bayesin lause](/bayes-theorem),. joka on nimetty 1700-luvun brittiläisen matemaatikon Thomas Bayesin mukaan, on matemaattinen kaava ehdollisen todennäköisyyden määrittämiseksi. Lause tarjoaa tavan tarkistaa olemassa olevia ennusteita tai teorioita (päivitystodennäköisyyksiä) saatujen uusien tai lisätodistusten perusteella. Rahoituksessa Bayesin lausetta voidaan käyttää arvioimaan [riskiä](/risk) lainata rahaa mahdollisille lainanottajille.

> Bayesin lause sopii hyvin ja sitä käytetään laajasti koneoppimisessa.

>

Bayesin lausetta kutsutaan myös Bayesin säännöksi tai Bayesin laiksi, ja se on Bayesin tilastokentän perusta. Tämä todennäköisyyssääntöjoukko mahdollistaa tapahtumien ennusteiden päivittämisen vastaanotetun uuden tiedon perusteella, jolloin saadaan parempia ja dynaamisempia arvioita.

## Bottom Line

Ehdollinen todennäköisyys tutkii tapahtuman todennäköisyyttä edeltävän tapahtuman todennäköisyyden perusteella. Toinen tapahtuma riippuu ensimmäisestä tapahtumasta. Se lasketaan kertomalla ensimmäisen tapahtuman todennäköisyys toisen tapahtuman todennäköisyydellä.

## Kohokohdat

- Bayesin lause on matemaattinen kaava, jota käytetään ehdollisen todennäköisyyden laskemiseen.

- Se ilmoitetaan usein B:n todennäköisyydeksi annettuna A ja kirjoitetaan muodossa P(B|A), jossa B:n todennäköisyys riippuu A:n todennäköisyydestä.

- Todennäköisyydet luokitellaan joko ehdollisiin, marginaalisiin tai yhteisiin.

- Ehdollinen todennäköisyys viittaa mahdollisuuteen, että jokin lopputulos tapahtuu, jos myös toinen tapahtuma on tapahtunut.

- Ehdollinen todennäköisyys voidaan verrata ehdottomaan todennäköisyyteen.

## UKK

### Mikä on yhdistetty todennäköisyys?

Yhdistetyn todennäköisyyden tarkoituksena on määrittää kahden riippumattoman tapahtuman todennäköisyys. Yhdistetty todennäköisyys kertoo ensimmäisen tapahtuman todennäköisyyden toisen tapahtuman todennäköisyydellä. Yleisin esimerkki on kahdesti käännetty kolikko ja sen määrittäminen, onko toinen tulos sama vai erilainen kuin ensimmäinen.

### Kuinka lasket ehdollisen todennäköisyyden?

Ehdollinen todennäköisyys lasketaan kertomalla edellisen tapahtuman todennäköisyys seuraavan tai ehdollisen tapahtuman todennäköisyydellä. Ehdollinen todennäköisyys tarkastelee yhden tapahtuman todennäköisyyttä edellisen tapahtuman todennäköisyyden perusteella.

### Mikä on ehdollinen todennäköisyyslaskin?

Ehdollinen todennäköisyyslaskin on online-työkalu, joka laskee ehdollisen todennäköisyyden. Se antaa ensimmäisen ja toisen tapahtuman todennäköisyyden. Ehdollinen todennäköisyyslaskin säästää käyttäjän tekemästä matematiikkaa manuaalisesti.

### Mikä on ennakkotodennäköisyys?

Aikaisempi todennäköisyys on tapahtuman todennäköisyys ennen kuin mitään dataa on kerätty todennäköisyyden määrittämiseksi. Se on aikaisemman uskomuksella määritetty todennäköisyys. Aikaisempi todennäköisyys on osa Bayesin tilastollista päättelyä.

### Mitä eroa on todennäköisyydellä ja ehdollisella todennäköisyydellä?

Todennäköisyys laskee yhden tapahtuman todennäköisyyttä. Ehdollinen todennäköisyys tarkastelee kahta tapahtumaa, jotka tapahtuvat suhteessa toisiinsa. Se tarkastelee toisen tapahtuman todennäköisyyttä ensimmäisen tapahtuman todennäköisyyden perusteella.

