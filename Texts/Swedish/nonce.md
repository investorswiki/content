---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Nonce
description: I blockchain-teknik betyder nonce ett nummer som läggs till ett hashat eller krypterat block som, när det omhashas, uppfyller svårighetsnivåbegränsningarna. Blockchain-gruvarbetare strävar efter att lösa problemet.
---

# Nonce
En nonce hänvisar till ett tal eller värde som bara kan användas en gång. Nonces används ofta på autentiseringsprotokoll och kryptografiska hashfunktioner. I samband med blockchain-teknik hänvisar en nonce till ett pseudoslumptal som används som en räknare under gruvdriften.

Till exempel måste Bitcoin-gruvarbetare försöka gissa ett giltigt nonce eftersom de utför flera försök att beräkna en blockhash som uppfyller vissa krav (dvs. som börjar med ett visst antal nollor). När man tävlar om att bryta ett nytt block, får den första gruvarbetaren som hittar ett nonce som resulterar i en giltig blockhash rätten att lägga till nästa block i [blockkedjan](/blockchain) - och belönas för att göra det.

Med andra ord består gruvdriftsprocessen av att gruvarbetare utför en myriad av hashfunktioner med många olika nonce-värden tills en giltig utdata produceras. Om hash-utdata från en gruvarbetare faller under den förutbestämda tröskeln anses blocket vara giltigt och läggs till blockkedjan. Om utgången inte är giltig fortsätter gruvarbetaren att försöka med olika nonce-värden. När ett nytt block är framgångsrikt minerat och validerat, börjar processen om.

Inom Bitcoin - och de flesta Proof of Work-system - är nonce bara ett slumpmässigt tal som gruvarbetare använder för att iterera resultatet av sina hashberäkningar. Gruvarbetare använder en trial and error-metod, där varje beräkning tar ett nytt nonce-värde. De gör det eftersom sannolikheten att gissa en giltig nonce är nära noll.

Det genomsnittliga antalet hashförsök justeras automatiskt av protokollet för att säkerställa att varje nytt block genereras - i genomsnitt - var tionde minut. Denna process är känd som svårighetsjustering och är det som bestämmer gruvtröskeln (dvs. hur många nollor som blockhashen behöver börja med för att anses giltig). Svårigheten att bryta ett nytt block är relaterat till mängden hashkraft (hashhastighet) som är ansluten till ett blockkedjesystem. Ju mer hashkraft dedikerad till nätverket, desto högre kommer tröskeln att vara, vilket innebär att mer beräkningskraft kommer att krävas för att vara en konkurrenskraftig och framgångsrik gruvarbetare. Om gruvarbetare däremot bestämmer sig för att sluta bryta kommer svårigheten att justeras och tröskeln kommer att sjunka, så det kommer att krävas mindre hashkraft för att bryta, men protokollet kommer att se till att blockgenereringen följer ett 10-minutersschema, oavsett .

## Höjdpunkter

- Gruvarbetare öppnar nya block genom att generera en nonce som gör att hashen de skapar mindre än hashen från blocket de validerar.

- Nonce, ett "nummer som bara används en gång," hänvisar till det nummer som en blockchain-gruvarbetare behöver upptäcka innan han löser ett block i blockkedjan.

- När gruvarbetaren löst hashen får de blockbelöningen.

## Vanliga frågor

### Hur används nonces?

I kryptovaluta används nonces som numret som används i en hash för att verifiera transaktionerna och andra data som finns i ett block.

### Vad står Nonce för?

I kryptovaluta är en nonce en förkortning för "number only used once", vilket är ett nummer som läggs till ett hashat – eller krypterat – block i en blockkedja som, när det omhashasas, uppfyller svårighetsnivåbegränsningarna. Nonce är numret som blockchain-gruvarbetare löser för att få blockbelöningen.

### Vad är en Blockchain Nonce?

En blockchain nonce är ett nummer som läggs till ett hashat – eller krypterat – block i en blockchain.

