---
keywords: Crypto
title: Nicht ausgegebene Transaktionsausgabe (UTXO)
description: Nicht ausgegebene Transaktionsausgabe (UTXO). Eine in einer Transaktion erstellte Ausgabe, auf die in einer zukünftigen Transaktion verwiesen werden muss, um Geld auszugeben.
---

# Nicht ausgegebene Transaktionsausgabe (UTXO)
Eine nicht verbrauchte Transaktionsausgabe (UTXO) bezieht sich auf eine Transaktionsausgabe, die als Eingabe in einer neuen Transaktion verwendet werden kann. Im Wesentlichen definieren UTXOs, wo jede Blockchain-Transaktion beginnt und endet. Das UTXO-Modell ist ein grundlegendes Element von Bitcoin und vielen anderen Kryptowährungen.

Mit anderen Worten, Kryptowährungstransaktionen bestehen aus Eingaben und Ausgaben. Jedes Mal, wenn eine Transaktion durchgeführt wird, nimmt ein Benutzer einen oder mehrere UTXOs, um als Eingabe(n) zu dienen. Als nächstes stellt der Benutzer seine digitale Signatur bereit, um das Eigentum an den Eingaben zu bestätigen, die schließlich zu Ausgaben führen. Die verbrauchten UTXOs gelten nun als „verbraucht“ und können nicht mehr verwendet werden. In der Zwischenzeit werden die Ausgaben der Transaktion zu neuen UTXOs – die später in einer neuen Transaktion ausgegeben werden können.

Das lässt sich wahrscheinlich besser an einem Beispiel erklären. Alice hat 0,45 BTC in ihrem Wallet. Dies ist kein Bruchteil einer Münze, wie wir es uns vorstellen könnten. Es ist eher eine Sammlung von UTXOs. Insbesondere zwei UTXOs im Wert von 0,4 BTC und 0,05 BTC – Ausgaben aus vergangenen Transaktionen. Stellen wir uns nun vor, dass Alice eine Zahlung von 0,3 BTC an Bob leisten muss.

Ihre einzige Möglichkeit besteht hier darin, die 0,4 BTC-Einheit aufzubrechen und 0,3 BTC an Bob und 0,1 BTC an sich selbst zurückzusenden. Normalerweise würde sie aufgrund von Mining-Gebühren weniger als 0,1 BTC zurückfordern, aber lasst uns vereinfachen und den Miner weglassen.

Alice erstellt eine Transaktion, die dem Netzwerk im Wesentlichen sagt: Nimm meine 0,4 BTC UTXO als Eingabe, zerlege sie, sende 0,3 BTC davon an Bobs Adresse und sende die 0,1 BTC an meine Adresse zurück. Die 0,4 BTC sind jetzt eine verbrauchte Ausgabe und können nicht wiederverwendet werden. Inzwischen sind zwei neue UTXOs entstanden (0,3 BTC und 0,1 BTC).

Beachten Sie, dass wir in diesem Beispiel einen UTXO aufgelöst haben, aber wenn Alice 0,42 BTC zahlen müsste, hätte sie ihre 0,4 BTC genauso gut mit weiteren 0,05 BTC kombinieren können, um einen UTXO im Wert von 0,42 BTC zu produzieren, während sie 0,03 BTC an sich selbst zurückgibt.

Zusammenfassend dient das UTXO-Modell als Mechanismus des Protokolls, um zu verfolgen, wo sich Münzen zu einem bestimmten Zeitpunkt befinden. In gewisser Weise funktionieren sie ähnlich wie Schecks: Sie sind an bestimmte Benutzer adressiert (oder besser gesagt an ihre öffentlichen [Adressen](/address) ). UTXOs können nicht teilweise ausgegeben werden – stattdessen müssen neue Checks aus dem alten erstellt und entsprechend weitergegeben werden.

