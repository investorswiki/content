---
keywords: Crypto
title: Keccak
description: Keccak. Guido Bertonin, Joan Daemenin, Michaël Peetersin ja Gilles Van Asschen suunnittelema monipuolinen salaustoiminto.
---

# Keccak
Keccak (lausutaan "ketchak") on Guido Bertonin, Joan Daemenin, Michaël Peetersin ja Gilles Van Asschen suunnittelema monipuolinen salaustoiminto. Vaikka Keccakia voidaan käyttää muihin tarkoituksiin, se tunnetaan parhaiten hash-funktiona, joka tarjoaa paremman suojan verrattuna vanhempiin hajautusalgoritmeihin, kuten SHA-1 ja SHA-2.

SHA on lyhenne sanoista Secure Hash Algorithm ja viittaa joukkoon kryptografisia hajautusfunktioita, jotka US National Institute of Standards and Technology (NIST) on julkaissut. Sekä SHA-1:n että SHA-2:n on suunnitellut Yhdysvaltain kansallinen turvallisuusvirasto (NSA), ja sellaisenaan niillä on samanlainen rakenne. Vaikka Keccak tukee samaa tulostuskokoa (hash-pituudet) kuin SHA-2, sen toimintamekanismi on melko erilainen. Silti Keccak on osa SHA-perhettä ja sitä kutsutaan usein SHA-3:ksi.

Teoreettiset hyökkäykset SHA-1:tä vastaan tehtiin vuonna 2004 ja julkistettiin vuonna 2005. Pari vuotta myöhemmin, vuonna 2011, NIST julisti SHA-2:n uudeksi standardihajautusfunktioksi käytettäväksi. Siirtyminen SHA-1:stä SHA-2:een oli kuitenkin melko hidasta, ja vasta vuoden 2017 alussa suuri osa kehittäjistä ja tietojenkäsittelytieteilijöistä siirtyi lopulta SHA-2:een. Pian sen jälkeen Google ilmoitti onnistuneesta SHA-1-törmäyshyökkäyksestä helmikuussa 2017, ja sen jälkeen SHA-1:tä ei pidetä enää turvallisena, eikä sen käyttöä suositella.

Keccak-funktiota (SHA-3) alettiin kehittää noin vuonna 2007 sen jälkeen, kun NIST julkaisi julkisen kilpailun ja tarkastusprosessin, jossa etsittiin uutta kryptografista hajautustoimintoa, joka voisi voittaa aiempien SHA-1:n ja SHA-2:n mahdolliset puutteet.

Vaikka merkittävää hyökkäystä SHA-2:ta vastaan ei ole vielä osoitettu, on odotettavissa, että hash-funktiot murtuvat ajan myötä ja uuden vakiotoiminnon kehittäminen kestää vuosia. Ottaen huomioon tämän sekä SHA-1:tä vastaan vuosina 2004 ja 2005 suoritetut onnistuneet hyökkäykset, NIST havaitsi tarpeen luoda uusi kryptografinen hajautusalgoritmi. Vuonna 2012 NIST julisti Keccakin kilpailun voittajaalgoritmiksi, ja se standardisoitiin SHA-perheen uusimmaksi jäseneksi (siis SHA-3).

Yksi syy siihen, miksi NIST valitsi Keccakin, johtuu sen innovatiivisesta rakenteesta, joka osoittautui turvallisemmaksi ja tehokkaammaksi kuin muut algoritmit. Teknisesti ottaen SHA-3-algoritmi luottaa ns. sienitoimintoihin (tai sienirakenteeseen) - toisin kuin SHA-1:n ja SHA-2:n käyttämä Merkle Damgård -rakenne.

Toistaiseksi SHA-2:ta pidetään edelleen turvallisena ja sitä käytetään laajalti. Esimerkiksi Bitcoin ja muut kryptovaluutat käyttävät SHA-256:ta, ja sillä on ratkaiseva rooli kaivosprosessissa. Saatamme nähdä SHA-3:n käytön lisääntyvän jatkossa, koska se näyttää olevan kaukana onnistuneesta hyökkäyksestä. Siitä huolimatta tulemme näkemään lisää kryptografisia hajautusalgoritmeja kehitettävän tulevina vuosina, kun kryptografian ala kehittyy ja uusia puutteita löydetään.

