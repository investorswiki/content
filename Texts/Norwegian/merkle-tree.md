---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: merkle tre
description: merkle tre. En måte å organisere og strukturere store mengder data på for å gjøre det enklere å behandle. En hasj-basert datastruktur.
---

# merkle tre
Et Merkle-tre er en måte å organisere og strukturere store mengder data på for å gjøre det enklere å behandle. Når det gjelder kryptovaluta og [blokkjede](/blockchain),. brukes Merkle-treet til å strukturere transaksjonsdata på en måte som er mindre ressurskrevende.

Når en kryptovaluta-transaksjon gjøres i en Merkle-trestruktur, hashes den og får deretter en tilsvarende hashverdi. Etter at hver transaksjon er hash i Merkle-treet, blir hash-verdiene som produseres sammenkoblet med en annen hash-verdi og deretter hashe igjen. For eksempel er hash-verdiene 'AB' og 'AC' kombinert for å lage 'ABC'.

Denne prosessen med sammenkobling av hash-verdier gjentas til en endelig hash-verdi er produsert. Den endelige hashverdien, Merkle-roten, gir et sammendrag av alle transaksjonene den inneholder. Merkle rotsammendraget settes deretter inn i blokkoverskriften.

####Datasikkerhet

En Merkle-trestruktur gir en lett tilgjengelig oversikt over transaksjonene i en [blokk](/block). Så det er veldig enkelt å sjekke om dataene i en blokk har blitt endret eller tuklet med. Dette er sant fordi enhver endring i en transaksjon (eller andre relaterte data) i Merkle-treet vil føre til en helt annen tilsvarende Merkle-rot.

#### Effektiv bruk av ressurser

Hvis kryptovalutaer ikke brukte Merkle-trær, ville hver verifiseringsforespørsel innebære enorme mengder informasjon som ble sendt over nettverket. Å strukturere transaksjonsdata i et Merkle-tre er en langt mer effektiv ressursbruk. Validering av en transaksjon krever ikke en fullstendig kopi av hovedboken, da hash-transaksjonsdataene kan verifiseres i en Merkle-rot, noe som krever mye mindre informasjon som sendes over nodene og dermed mindre datakraft for å analysere den generelle dataintegriteten.

Med andre ord, en Merkle-trestruktur gjør det mulig for brukere å verifisere at en individuell transaksjon er inkludert i en blokk uten å måtte gå gjennom prosessen med å laste ned hele blokkjeden. Teknologien er et viktig verktøy for kryptovalutaer for å organisere transaksjonsdata og fungere like effektivt som de gjør. Uten Merkle-trær er det sannsynlig at den større etterspørselen etter ressurser vil føre til at færre [noder](/node) deltar i nettverket.

