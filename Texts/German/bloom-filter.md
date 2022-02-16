---
keywords: Crypto
title: Blütenfilter
description: Blütenfilter. Eine Datenstruktur, die verwendet werden kann, um den Benutzer darüber zu informieren, ob ein bestimmtes Element Teil einer Menge von Elementen ist
---

# Blütenfilter
Ein Bloom-Filter ist eine Datenstruktur, die verwendet werden kann, um den Benutzer darüber zu informieren, ob ein bestimmtes Element Teil eines Satzes ist. Obwohl es nicht mit Sicherheit sagen kann, ob ein Element in der Menge enthalten ist, kann es mit Sicherheit sagen, ob das Element nicht vorhanden ist.

Bloom-Filter wurden 1970 von Burton Howard Bloom entwickelt und sind aufgrund ihrer effizienten Raumnutzung ein attraktives Angebot für eine Reihe von Anwendungen. In einigen Kryptowährungen (insbesondere Bitcoin) spielen sie eine wesentliche Rolle bei der vereinfachten Zahlungsprüfung oder SPV.

Bei Verwendung eines SPV-Clients können Benutzer mit dem Bitcoin-Netzwerk interagieren, ohne einen vollständigen Knoten auszuführen. Full Nodes haben bestimmte Speicher- und Rechenanforderungen, die sie unhandlich machen, um sie auf leistungsschwachen Geräten wie Smartphones auszuführen. SPV-Clients hingegen fragen Full Nodes einfach nach Informationen ab, die für die Brieftasche(n) des Benutzers relevant sind.

Die einfachste Lösung, um diese Daten an den Benutzer weiterzuleiten, wäre, Full Nodes auf die Schlüssel des Clients aufmerksam zu machen, sodass nur relevante Transaktionen an sie gesendet werden. Offensichtlich ist dies eine unterdurchschnittliche Lösung, da die Privatsphäre des Kunden geopfert würde. Andererseits wäre es eine Verschwendung von Bandbreite, alle Transaktionen herunterzuladen, nur um die Mehrheit von ihnen zu verwerfen. Geben Sie Bloom-Filter ein.

Lassen Sie uns veranschaulichen. Angenommen, ein Kunde, Alice, hat eine Transaktion mit hohem Wert, von der Bob, der einen Full Node betreibt, nicht wissen soll. Sie konstruiert einen Bloom-Filter, den wir als 10x1-Raster veranschaulichen:

Sie leitet die Transaktionsdaten, an denen sie interessiert ist, durch zwei verschiedene Hash-Funktionen, die zwei Zahlen zwischen 0 und 9 ausgeben. Nennen wir sie 4 und 7. Sie sendet den Filter an Bob.

Wenn Sie sich dieses Raster ansehen, haben Sie keine Ahnung, welche Daten Alice an den Filter weitergegeben hat. Wenn Sie einen Satz hätten, in dem die Daten enthalten waren, könnten Sie ihn hashen und mit dem Filter vergleichen – wenn es eine Übereinstimmung gibt, besteht die Möglichkeit, dass es sich um die von Alice angeforderten Informationen handelt.

Gleichzeitig gibt es wahrscheinlich viele Eingaben, die auf 4 und 7 abgebildet werden, sodass Bob nicht bestimmen kann, an welchem Teil der Daten Alice interessiert ist. Er gibt einfach alle Übereinstimmungen zurück und Alice filtert sie auf ihrer Seite.

Das ist natürlich eine grobe Vereinfachung, aber es demonstriert das Konzept: Bloom-Filter verschleiern die wahren Interessen des Kunden. Es ist keine perfekte Methode (es gibt immer noch Bedenken hinsichtlich der Privatsphäre), aber es ist eine Verbesserung gegenüber einer nicht abgeschirmten Anfrage an einen Knoten.

