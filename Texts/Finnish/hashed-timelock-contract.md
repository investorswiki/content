---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Crypto,Strategy and Education
title: Hashed Timelock Contract (HTLC)
description: Hashed TimeLock -sopimus (HTLC). Viittaa erikoisominaisuuteen, jota käytetään luomaan älykkäitä sopimuksia, jotka pystyvät muokkaamaan maksukanavia.
---

# Hashed Timelock Contract (HTLC)
Termi Hashed TimeLock Contract (HTLC) viittaa erikoisominaisuuteen, jolla luodaan [älykkäitä sopimuksia](/smart-contract),. jotka pystyvät muokkaamaan maksukanavia. Teknisesti HTLC-ominaisuus mahdollistaa aikasidonnaisten tapahtumien toteuttamisen kahden käyttäjän välillä. Käytännössä HTLC-tapahtuman vastaanottajan on kuitattava maksu lähettämällä salaustodiste tietyn ajan kuluessa (lohkojen lukumäärä). Jos vastaanottaja menettää maksun tai ei vaadi maksua, varat palautetaan alkuperäiselle lähettäjälle.

HTLC-ominaisuutta käytetään sekä kaksisuuntaisissa että reititetyissä maksukanavissa, jotta varoja voidaan siirtää turvallisesti eri kanavien kautta ilman, että välittäjät tarvitsevat luottamusta.

On olemassa kaksi avaintekijää, jotka erottavat HTLC:n tavallisista kryptovaluuttatransaktioista, jotka ovat:

- Hashlock: toiminto, joka rajoittaa varojen käyttöä, kunnes tietty tieto on julkistettu (salauksen todisteena). Tällaista todistetta voidaan kutsua myös hashlockin esikuvaksi. Esikuva on yksinkertaisesti tieto, jota käytetään hajautuslukon luomiseen ja myöhemmin sen varojen avaamiseen.

- Aikalukko: on toiminto, joka rajoittaa varojen käyttöä tiettyyn aikaan (tai lohkokorkeuteen) tulevaisuudessa. Se voidaan saavuttaa esimerkiksi Bitcoinissa käyttämällä toimintoja, kuten CheckLockTimeVerify tai CheckSequenceVerify.

Bitcoin Lightning Network on yksi Hashed Timelocked -sopimusten suosituimmista käyttötapauksista. Ottamalla HTLC käyttöön maksukanavissa, varoja voidaan siirtää käyttäjältä käyttäjälle toisiinsa yhdistettyjen maksukanavien kautta ilman, että vaaditaan minkäänlaista luottamusta. Tämä prosessi tunnetaan verkkoreitityksenä. Sen avulla Alice voi vaihtaa varoja Carolin kanssa, vaikka ne eivät olisi suoraan yhteydessä maksukanavan kautta. HTLC:t antavat Alicelle mahdollisuuden lähettää varansa Carolille verkoston muiden osallistujien (esim. Bobin) kautta – ja hashlock- ja timelock-ominaisuudet varmistavat, että Bob ei voi siepata varoja.

Sen lisäksi, että niitä käytetään Lightning Networkissa, HTLC:t voivat olla hyödyllisiä myös muissa yhteyksissä, kuten ketjujen välisissä atominvaihtosopimuksissa [,](/atomic-swaps) taloudellisissa älykkäissä sopimuksissa ja sulkutiloissa ja paljon muuta.

## Kohokohdat

- HTLC:tä käyttävät maksut ovat ehdollisia, joten niillä on tehokkuusetuja blockchain-tapahtumissa. Tämä ominaisuus tekee HTLC:istä salamaverkon käyttämän perustyökalun.

- Tämäntyyppinen älykäs sopimus edellyttää, että maksun vastaanottaja kuittaa maksun tietyn ajan kuluessa tai menettää sen.

- Hajautettu aikalukkosopimus (HTLC) vähentää vastapuoliriskiä hajautetuissa älykkäissä sopimuksissa luomalla tehokkaasti aikapohjaisen sulkutilin, joka hyödyntää kryptografista tunnuslausetta.

## UKK

### Kuinka paljon älykäs sopimus maksaa?

Ethereum-lohkoketjussa älykäs sopimuskäyttöönotto vie kaasua, mikä maksaa Gweille (pienempi eetterin nimitys). Sopimuksen monimutkaisuudesta riippuen älykkään sopimuksen käyttöönotto voi maksaa miljardeja Gweille. Vähemmän monimutkaiset sopimukset, kuten yksinkertainen vaihto, ovat paljon halvempia.

### Mikä on älykäs sopimus?

Älykäs sopimus on lohkoketjuun tallennettu ohjelma, joka suoritetaan, kun tietyt ehdot täyttyvät.

### Mikä on aikalukkosopimus?

Aikalukkosopimus on lohkoketjuun upotettu älykäs sopimus, joka suorittaa tapahtuman tiettynä ajankohtana. Niitä käytetään tiivistetyissä aikalukkosopimuksissa ja maksukanavissa, joissa tarvitaan tiettyjä maksuaikoja.

### Onko Bitcoinilla älykkäitä sopimuksia?

Aluksi Bitcoinin lohkoketju ei kyennyt toteuttamaan älykkäitä sopimuksia. Vuonna 2021 tehty Taproot-päivitys kuitenkin antoi lohkoketjulle mahdollisuuden käyttää älykkäitä sopimuksia tapahtumissa.

