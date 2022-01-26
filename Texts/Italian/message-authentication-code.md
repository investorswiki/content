---
keywords: Personal Finance,Banking
title: Codice di autenticazione del messaggio (MAC)
description: Un codice di autenticazione del messaggio (MAC), o tag, è un codice di sicurezza che viene digitato dall&#39;utente di un computer per accedere ad account o portali.
---

# Codice di autenticazione del messaggio (MAC)
## Che cos'è un codice di autenticazione del messaggio?

Un codice di autenticazione del messaggio (MAC), o **tag,** è un codice di sicurezza che viene digitato dall'utente di un computer per accedere ad account o portali. Questo codice è allegato al messaggio o alla richiesta inviata dall'utente. I codici di autenticazione del messaggio (MAC) allegati al messaggio devono essere riconosciuti dal sistema ricevente per consentire all'utente l'accesso.

## Comprensione del codice di autenticazione del messaggio (MAC)

I codici di autenticazione dei messaggi (MAC) sono comunemente utilizzati nei [trasferimenti elettronici di fondi](/electronic-funds-transfer-act) (EFT) per mantenere l'integrità delle informazioni. Confermano che un messaggio è autentico; che proviene davvero, in altre parole, dal mittente dichiarato e non ha subito modifiche lungo il percorso. Un verificatore che possiede anche la chiave può utilizzarla per identificare le modifiche al contenuto del messaggio in questione.

I codici di autenticazione dei messaggi sono generalmente richiesti per accedere a qualsiasi tipo di conto finanziario. Banche, società di intermediazione, società fiduciarie e qualsiasi altra compagnia di deposito, investimento o assicurazione che offre l'accesso online può utilizzare questi codici. Sono una componente vitale della crittografia finanziaria.

## Algoritmi utilizzati per generare MAC

Tipicamente, tre algoritmi comprendono un MAC: un algoritmo di generazione delle chiavi, un algoritmo di firma e un algoritmo di verifica. L'algoritmo di generazione della chiave sceglie una chiave a caso. L'algoritmo di firma invia un tag quando viene fornita la chiave e il messaggio. L'algoritmo di verifica viene utilizzato per verificare l'autenticità del messaggio quando viene fornita la chiave e il tag; restituirà un messaggio di **accettato** se il messaggio e il tag sono autentici e inalterati, ma in caso contrario restituirà un messaggio di **rifiutato.**

Ad esempio, il mittente invia un messaggio, come un EFT, tramite l'algoritmo MAC, che genera una chiave e allega un tag dati MAC al messaggio. Il destinatario riceve il messaggio, lo esegue indietro tramite l'algoritmo MAC con la stessa chiave e ottiene un secondo tag di dati. Confronteranno quindi questo tag di dati MAC con il primo allegato al messaggio quando è stato trasmesso. Se il codice è lo stesso a entrambe le estremità, il destinatario può tranquillamente presumere che l'integrità dei dati del messaggio sia intatta. In caso negativo, tuttavia, significa che il messaggio è stato alterato, manomesso o contraffatto.

Tuttavia, il messaggio stesso dovrebbe contenere alcuni dati che garantiscono che questo messaggio possa essere inviato solo una volta. Ad esempio, è possibile utilizzare un MAC, un timestamp o un numero di sequenza una tantum per garantire che il messaggio possa essere inviato una sola volta. In caso contrario, il sistema potrebbe essere vulnerabile a un replay attack, in cui un utente malintenzionato intercetta il messaggio dopo che è stato decodificato e lo ritrasmette in un secondo momento, replicando i risultati originali e infiltrandosi nel sistema.

## Codici di integrità dei messaggi (MIC)

A volte, al posto di MAC verrà utilizzato il termine codice di integrità del messaggio (MIC). Questo viene fatto più spesso nel settore delle comunicazioni, dove MAC tradizionalmente significa indirizzo di controllo dell'accesso ai media (indirizzo MAC). Tuttavia, MIC può essere utilizzato anche per fare riferimento a **message digest,** che non utilizza chiavi segrete allo stesso modo di un MAC e non può offrire lo stesso livello di sicurezza senza ulteriore crittografia.

