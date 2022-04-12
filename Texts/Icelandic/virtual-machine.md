---
keywords: Crypto
title: Sýndarvél
description: Sýndarvél. Hermt tölvukerfi, eða dreifð kerfi sem er hannað til að endurtaka eiginleika arkitektúrs tölvunnar.
---

# Sýndarvél
Sýndarvél (VM) er forrit sem líkir eftir tölvukerfi. Það hefur sýndar örgjörva, minni og geymslu og virðist, utan frá, vera ekkert öðruvísi en líkamleg vél með sama vélbúnaði.

## Hvernig virkar sýndarvél?

Sýndarvél hefur stýrikerfi, skrár og forrit. Það virkar alveg eins og líkamleg tölva; það getur hýst vefsíður, keyrt forrit og verið á neti með öðrum kerfum. Ef hún er skoðuð á skjá birtist sýndarvélin sem gluggi sem keyrir innan eigin stýrikerfis tölvunnar.

Það hefur líka CPU, minni og geymslu, en þetta er hermt, ekki líkamlegt. Vegna þessa geta margar sýndarvélar lifað saman á einum netþjóni. Þegar þetta gerist notar þjónninn hugbúnað sem kallast hypervisor til að stjórna þeim. Hypervisorinn kortleggur sýndarvélbúnað VM við líkamlega íhluti á þjóninum.

Í þessari atburðarás gæti einn líkamlegur netþjónn verið með tvær, þrjár, fjórar eða jafnvel tíu sýndarvélar í gangi. Hins vegar er fjöldinn takmarkaður af tilföngum þjónsins - of margir VMs munu leiða til skertrar frammistöðu.

## Hvers vegna eru sýndarvélar notaðar?

Sýndarvélar eru sandkassar – stykki af sýndarrými þar sem hægt er að keyra kóða aðskilið frá restinni af kerfinu. Þetta gerir VMs tilvalin til að prófa nýjan hugbúnað eða keyra kóða sem gæti verið illgjarn.

Sýndarvélin getur keyrt annað eða eldra stýrikerfi til að gera notanda kleift að keyra hugbúnað sem virkar ekki á stýrikerfi tölvunnar. Til dæmis gæti einhver notað VM til að keyra Windows hugbúnað á Linux tæki. Til að ná þessu myndu þeir keyra sýndarvél sem keyrir Windows stýrikerfi á Linux kerfinu sínu.

## Lykildæmi: Ethereum sýndarvélin (EVM)

Hnútarnir á Ethereum netinu keyra allir Ethereum Virtual Machine (EVM), sem er notuð til að framkvæma snjalla samninga. Vegna þess að þetta gerist í sérstökum sandkassa veitir það umtalsverðan öryggisávinning fyrir Ethereum vettvanginn, sem gerir hann ónæm fyrir DDoS (Dreift afneitun á þjónustuárásum sem eru mikilvæg stefna fyrir marga tölvuþrjóta.

