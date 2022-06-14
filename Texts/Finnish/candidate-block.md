---
keywords: Crypto
title: Ehdokas Block
description: Ehdokas Block. Kaivossolmun (kaivostyöntekijä) luoma väliaikainen lohko, joka lisätään lohkoketjuun lohkopalkkioiden saamiseksi.
---

# Ehdokas Block
Muutamalla sanalla ehdokaslohko on lohko, jota kaivossolmu (kaivosmies) yrittää louhia saadakseen lohkopalkkion. Joten ehdokaslohko voidaan kuvata väliaikaiseksi lohkoksi, jonka verkko joko vahvistaa tai hylkää. Kaivostyöntekijät kilpailevat keskenään vahvistaakseen seuraavan lohkon ja lisätäkseen sen lohkoketjuun, mutta ensin heidän on luotava ehdokaslohko osallistuakseen kaivoskilpailuun.

Kaivostyöntekijät luovat ehdokaslohkoja keräämällä ja järjestämällä useita vahvistamattomia tapahtumia muistivarannosta. Transaktiot tiivistetään sitten muodostamaan [Merkle-puurakenne](/merkle-tree),. joka lopulta tuottaa Merkle-juuren (tai juurihajasteen). Merkle-juuri on yksittäinen tiiviste, joka edustaa kaikkia kyseisen puun aikaisempia tiivisteitä ja siten kaikkia kyseiseen lohkoon sisältyviä tapahtumia.

- yhdessä edellisen lohkon tiivisteen ja [nonce -nimisen satunnaisluvun kanssa](/nonce) - lisätään sitten lohkon otsikkoon. Lohkon otsikko tiivistää sitten kaivostyöntekijän luoden tulosteen, joka perustuu näihin komponentteihin (juuritiiviste, edellisen lohkon hash ja nonce) sekä muutama muu elementti. Tuloksena oleva tulos on lohkohajautus, ja se toimii äskettäin luodun lohkon (kandidaattilohkon) yksilöllisenä tunnisteena.

Jotta tulos olisi kelvollinen, sen on aloitettava tietyllä määrällä nollia (pienempi kuin protokollan määrittelemä tavoitearvo). Tämä tarkoittaa, että louhintaprosessi perustuu useisiin yrityksiin (yritys ja virhe), koska louhintasolmujen on suoritettava lukemattomia hajautustoimintoja erilaisilla nonce-arvoilla, kunnes kelvollinen lohkotiiviste on lopulta tuotettu. Tuotettu lohkohajautus todistaa, että kaivosmies teki työnsä (siis työtodistus).

Kun kaivosmies löytää kelvollisen lohkohajasteen, hänen ehdokaslohkonsa lähetetään muille verkon solmuille, jotka varmistavat tiivisteen aitouden. Jos kaikki on kunnossa, ehdokaslohko tallennetaan sitten lohkoketjuun. Tässä vaiheessa kukin validoiva solmu päivittää kopionsa lohkoketjun tiedoista vastaamaan äskettäin louhittua lohkoa, ja kaivostyöntekijä saa lohkopalkkion.

