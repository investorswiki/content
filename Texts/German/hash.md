---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: Haschisch
description: Haschisch. Die Ausgabe, die von einer Hash-Funktion erzeugt wird, nachdem ein Datenelement zugeordnet wurde. Kann auch als Hashwert, Hashcode oder Digest bezeichnet werden.
---

# Haschisch
In der [Kryptographie](/cryptography) bezieht sich das Wort Hash auf die Ausgabe, die von einer Hash-Funktion erzeugt wird, nachdem ein Datenelement durch sie übermittelt (zugeordnet) wurde. Anders als einfach Hash kann die von Hash-Funktionen erzeugte Ausgabe auch als Hash-Wert, Hash-Code oder Digest bezeichnet werden.

Um besser zu verstehen, was ein Hash ist, lohnt es sich zu diskutieren, was Hash-Funktionen sind und wie sie funktionieren.

Hash-Funktionen sind mathematische [Algorithmen](/algorithm),. die einen Eingabewert beliebiger Größe in einen Ausgabewert (Hash) fester Größe umwandeln. In den meisten Fällen besteht die Ausgabe aus einer Hexadezimalzahl. Das bedeutet, dass der Hash oft als Kombination aus Zahlen (0 bis 9) und Buchstaben (a bis f) bezeichnet wird.

Wenn wir beispielsweise das Wort „Binance“ als Eingabewert verwenden und es durch eine SHA-256-Hash-Funktion abbilden, lautet der zurückgegebene Ausgabewert (oder Hash):

f1624fcc63b615ac0e95daf9ab78434ec2e8ffe402144dc631b055f711225191

Beachten Sie, dass es egal ist, wie oft wir diese Aktion ausführen, die Ausgabe ist immer dieselbe (solange sich die Eingabe nicht ändert).

Andererseits führt jede geringfügige Änderung an der Eingabe dazu, dass die Hash-Funktion einen völlig anderen Hash als Ausgabe zurückgibt. Wenn wir beispielsweise das Wort „binance“ anstelle von „Binance“ einreichen, hätten wir als Ergebnis den folgenden Hash:

59bba357145ca539dcd1ac957abc1ec5833319ddcae7f5e8b5da0c36624784b2

Hashes sind nützlich, um die Gültigkeit bestimmter Informationen zu überprüfen, ohne preiszugeben, um welche Informationen es sich handelt. In der Praxis können Hash-Funktionen auf verschiedene Szenarien angewendet werden. Einige Anwendungsfälle umfassen Datenbanksuchen, Analysen großer Dateien und Datenverwaltung.

In Kombination mit kryptografischen Techniken haben wir die sogenannten kryptografischen Hash-Funktionen. Diese werden in großem Umfang in der Informationssicherheit eingesetzt und sind ein wesentlicher Bestandteil der meisten Blockchain-Netzwerke.

Zum Beispiel hat die Bitcoin-Blockchain viele Operationen, die Hashing beinhalten, und diese sind entscheidend für den Mining-Prozess.

## Höhepunkte

- Ein Hash ist eine Funktion, die die verschlüsselten Anforderungen erfüllt, die zum Lösen einer Blockchain-Berechnung erforderlich sind.

- Ein Hash, wie ein Nonce oder eine Lösung, ist das Rückgrat des Blockchain-Netzwerks.

- Ein Hash wird basierend auf den im Blockheader enthaltenen Informationen entwickelt.

- Hashes haben eine feste Länge, da es fast unmöglich ist, die Länge des Hashs zu erraten, wenn jemand versucht, die Blockchain zu knacken.

- Dieselben Daten erzeugen immer denselben Hash-Wert.

## FAQ

### Wie wird ein Hashwert berechnet?

Eine Hash-Funktion verwendet komplexe mathematische Algorithmen, die Daten beliebiger Länge in Daten fester Länge (z. B. 256 Zeichen) umwandeln. Wenn Sie irgendwo in den Originaldaten ein Bit ändern, ändert sich der gesamte Hash-Wert, wodurch er nützlich ist, um die Genauigkeit digitaler Dateien und anderer Daten zu überprüfen.

### Wofür werden Hashes in Blockchains verwendet?

Hashes werden in mehreren Teilen eines Blockchain-Systems verwendet. Erstens enthält jeder Block den Hash des [Blockheaders](/block-header-cryptocurrency) des vorherigen Blocks, um sicherzustellen, dass nichts manipuliert wurde, wenn neue Blöcke hinzugefügt werden. Kryptowährungs-Mining mit [Proof-of-Work](/proof-work) (PoW) verwendet außerdem Hashing von zufällig generierten Zahlen, um zu einem bestimmten Hash-Wert zu gelangen, der eine Reihe führender Nullen enthält. Diese willkürliche Funktion ist ressourcenintensiv und macht es einem Angreifer schwer, das Netzwerk zu übernehmen.

### Was ist eine Hash-Funktion?

Hash-Funktionen sind mathematische Funktionen, die einen bestimmten Datensatz in eine Bitfolge fester Größe, auch als „Hash-Wert“ bekannt, umwandeln oder „abbilden“.

