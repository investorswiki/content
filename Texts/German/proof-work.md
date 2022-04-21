---
keywords: Investing,Cryptocurrency,Bitcoin
title: Arbeitsnachweis (PoW)
description: Arbeitsnachweis beschreibt den Prozess, der es dem Bitcoin-Netzwerk ermöglicht, robust zu bleiben, indem der Prozess des Schürfens oder Aufzeichnens von Transaktionen erschwert wird.
---

# Arbeitsnachweis (PoW)
## Was ist ein Arbeitsnachweis (PoW)?

Proof of Work (PoW) beschreibt ein System, das einen nicht unerheblichen, aber machbaren Aufwand erfordert, um leichtfertige oder böswillige Nutzungen von Rechenleistung, wie das Versenden von Spam-E-Mails oder das Starten von Denial-of-Service-Angriffen, abzuwehren. Das Konzept wurde anschließend von Hal Finney im Jahr 2004 durch die Idee des „wiederverwendbaren Arbeitsnachweises“ unter Verwendung des SHA-256-Hashing-Algorithmus an die Sicherung von digitalem Geld angepasst.

Nach seiner Einführung im Jahr 2009 wurde Bitcoin die erste weit verbreitete Anwendung von Finneys PoW-Idee (Finney war auch der Empfänger der ersten Bitcoin-Transaktion). Der Arbeitsnachweis bildet auch die Grundlage für viele andere [Kryptenvorkommen](/cryptocurrency) und ermöglicht einen sicheren, dezentralen Konsens [.](/cryptocurrency)

## Arbeitsnachweis verstehen

Diese Erklärung konzentriert sich auf den Arbeitsnachweis, wie er im [Bitcoin](/bitcoin) -Netzwerk funktioniert. Bitcoin ist eine digitale Währung, die durch eine Art [verteiltes Ledger](/distributed-ledger-technology-dlt),. bekannt als „ [Blockchain](/blockchain) “, untermauert wird. Dieses Hauptbuch enthält eine Aufzeichnung aller Bitcoin-Transaktionen, die in aufeinanderfolgenden „Blöcken“ angeordnet sind, sodass kein Benutzer einen seiner Bestände zweimal ausgeben darf. Um Manipulationen zu verhindern, ist das Ledger öffentlich oder „verteilt“; eine geänderte Version würde schnell von anderen Benutzern abgelehnt werden.

Die Art und Weise, wie Benutzer Manipulationen in der Praxis erkennen, besteht in [Hashes](/hash),. langen Zahlenfolgen, die als Arbeitsnachweis dienen. Führen Sie einen bestimmten Datensatz durch eine Hash-Funktion (Bitcoin verwendet SHA-256), und es wird immer nur ein Hash generiert. Aufgrund des „Lawineneffekts“ führt jedoch selbst eine winzige Änderung an irgendeinem Teil der Originaldaten zu einem völlig unkenntlichen Hash. Unabhängig von der Größe des ursprünglichen Datensatzes hat der von einer bestimmten Funktion generierte Hash dieselbe Länge. Der Hash ist eine Einwegfunktion: Er kann nicht verwendet werden, um die Originaldaten zu erhalten, sondern nur um zu überprüfen, ob die Daten, die den Hash generiert haben, mit den Originaldaten übereinstimmen.

Für einen modernen Computer wäre es trivial, einen beliebigen Hash für eine Reihe von Bitcoin-Transaktionen zu generieren. Um den Prozess also in „Arbeit“ umzuwandeln, legt das Bitcoin-Netzwerk ein gewisses Maß an „Schwierigkeit“ fest. Diese Einstellung wird so angepasst, dass etwa alle 10 Minuten ein neuer Block „ [geschürft](/bitcoin-mining) “ wird – der Blockchain hinzugefügt wird, indem ein gültiger Hash generiert wird. Das Festlegen der Schwierigkeit wird erreicht, indem ein ["Ziel" für den Hash festgelegt wird](/target-hash) : Je niedriger das Ziel, desto kleiner die Menge gültiger Hashes und desto schwieriger ist es, einen zu generieren. In der Praxis bedeutet dies einen Hash, der mit einer sehr langen Folge von Nullen beginnt.

> Proof of Work wurde ursprünglich als Lösungsvorschlag für das wachsende Problem von Spam-E-Mails erstellt.

>

## Besondere Überlegungen

Da ein bestimmter Datensatz nur einen Hash generieren kann, wie stellen Miner sicher, dass sie einen Hash unter dem Ziel generieren? Sie ändern die Eingabe, indem sie eine Ganzzahl hinzufügen, die als [Nonce](/nonce) ("einmal verwendete Zahl") bezeichnet wird. Sobald ein gültiger Hash gefunden wurde, wird er an das Netzwerk gesendet und der Block wird der Blockchain hinzugefügt.

Mining ist ein Wettbewerbsprozess, aber eher eine Lotterie als ein Rennen. Im Durchschnitt wird alle zehn Minuten jemand einen akzeptablen Arbeitsnachweis erbringen, aber wer es sein wird, ist unklar. Miner schließen sich zusammen, um ihre Chancen auf das Mining von Blöcken zu erhöhen, was Transaktionsgebühren und für eine begrenzte Zeit eine Belohnung in Form neu erstellter Bitcoins generiert.

Proof of Work macht es extrem schwierig, irgendeinen Aspekt der Blockchain zu ändern, da eine solche Änderung das Re-Mining aller nachfolgenden Blöcke erfordern würde. Es macht es auch für einen Benutzer oder eine Gruppe von Benutzern schwierig, die Rechenleistung des Netzwerks zu monopolisieren, da die Maschinen und die Leistung, die zum Ausführen der Hash-Funktionen erforderlich sind, teuer sind.

> Wenn ein Teil eines Mining-Netzwerks beginnt, einen alternativen Arbeitsnachweis zu akzeptieren, wird dies als [Hard Fork bezeichnet](/hard-fork).

>

## Beispiel eines Arbeitsnachweises

Der Arbeitsnachweis erfordert, dass ein Computer zufällig Hash-Funktionen ausführt, bis er zu einer Ausgabe mit der korrekten Mindestanzahl führender Nullen gelangt. Zum Beispiel ist der Hash für Block #660000, der am 4. Dezember 2020 abgebaut wurde, 00000000000000000008eddcaf078f12c69a439dde30dbb5aac3d9d94e9c18f6. Die Blockbelohnung für diesen erfolgreichen Hash betrug 6,25 BTC.

Dieser Block enthält immer 745 Transaktionen mit etwas mehr als 1.666 Bitcoins sowie den Header des vorherigen Blocks. Wenn jemand versuchte, einen Transaktionsbetrag auch nur um 0,000001 Bitcoin zu ändern, wäre der resultierende Hash nicht erkennbar, und das Netzwerk würde den Betrugsversuch ablehnen.

## Häufig gestellte Fragen zum Arbeitsnachweis

### Was bedeutet Arbeitsnachweis?

PoW verlangt von Knoten in einem Netzwerk, dass sie nachweisen, dass sie Rechenleistung (dh Arbeit) aufgewendet haben, um auf dezentralisierte Weise einen Konsens zu erzielen und zu verhindern, dass schlechte Akteure das Netzwerk übernehmen.

### Wie validiert ein Proof of Work eine Krypto-Transaktion?

Die Arbeit selbst ist willkürlich. Bei Bitcoin handelt es sich um Iterationen von SHA-256-Hashing-Algorithmen. Der „Gewinner“ einer Hashing-Runde hingegen aggregiert und zeichnet Transaktionen aus dem Mempool in den nächsten Block auf. Da der „Gewinner“ zufällig proportional zur geleisteten Arbeit ausgewählt wird, wird jeder im Netzwerk dazu angeregt, ehrlich zu handeln und nur echte Transaktionen aufzuzeichnen.

### Warum brauchen Kryptowährungen einen Arbeitsnachweis?

Da sie von Natur aus dezentral und Peer-to-Peer sind, erfordern Blockchains wie Kryptowährungsnetzwerke einen Weg, um sowohl Konsens als auch Sicherheit zu erreichen. Proof of Work ist eine solche Methode, die es zu ressourcenintensiv macht, zu versuchen, das Netzwerk zu überholen. Es gibt auch andere Nachweismechanismen, die weniger ressourcenintensiv sind, aber andere Nachteile oder Fehler aufweisen, wie z. B. [Proof](/proof-stake-pos) [of Stake (PoS)](/proof-stake-pos) und [Proof of Burn](/proof-burn-cryptocurrency). Ohne einen Beweismechanismus wären das Netzwerk und die darin gespeicherten Daten anfällig für Angriffe oder Diebstahl.

### Verwendet Bitcoin Proof of Work?

Ja. Es verwendet einen PoW-Algorithmus, der auf der SHA-256-Hashing-Funktion basiert, um Transaktionen zu validieren und zu bestätigen sowie neue Bitcoins in Umlauf zu bringen.

### Wie unterscheidet sich Proof of Stake (PoS) von PoW?

PoS ist ein Konsensmechanismus, der zufällig den Knoten zuweist, der Blocktransaktionen abbaut oder validiert, je nachdem, wie viele Coins dieser Knoten hält. Je mehr Token in einer Wallet aufbewahrt werden, desto mehr Mining-Power wird ihr effektiv gewährt. Während PoS weitaus weniger ressourcenintensiv ist, weist es mehrere andere Mängel auf, darunter eine größere Wahrscheinlichkeit eines [51-prozentigen Angriffs](/51-attack) bei kleineren Altcoins und Anreize, Token zu horten und sie nicht zu verwenden.

## Höhepunkte

- Proof of Stake (POS) war einer von mehreren neuartigen Konsensmechanismen, die als Alternative zum Proof of Work geschaffen wurden.

- Proof of Work (PoW) ist ein dezentraler Konsensmechanismus, der von den Mitgliedern eines Netzwerks verlangt, dass sie sich bemühen, ein willkürliches mathematisches Rätsel zu lösen, um zu verhindern, dass jemand das System spielt.

- Der Nachweis der Arbeit im großen Maßstab erfordert enorme Energiemengen, die nur zunehmen, wenn mehr Bergleute dem Netzwerk beitreten.

- Aufgrund des Arbeitsnachweises können Bitcoin- und andere Kryptowährungstransaktionen Peer-to-Peer auf sichere Weise verarbeitet werden, ohne dass ein vertrauenswürdiger Dritter erforderlich ist.

- Proof of Work wird häufig beim Kryptowährungs-Mining verwendet, um Transaktionen zu validieren und neue Token zu schürfen.

