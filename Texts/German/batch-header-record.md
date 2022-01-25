---
keywords: Personal Finance,Banking
title: Chargenkopfsatz
description: Ein Stapelkopfsatz ist ein Standarddatensatz mit Informationen zur Übertragung einer Gruppe von Daten (eines Stapels), normalerweise im Bankenbereich.
---

# Chargenkopfsatz
## Was ist ein Chargenkopfsatz?

Ein Stapelkopfsatz ist eine Standard-Metainformation bezüglich der Übertragung einer Gruppe von Daten (eines Stapels), normalerweise im Bankenbereich. Der Stapelkopfsatz identifiziert den Ursprung einer Transaktion und fasst die beteiligten Belastungen und Gutschriften zusammen, was für die erfolgreiche Verarbeitung des Stapels entscheidend ist. Dies ist eine Schlüsselkomponente der [Stapelverarbeitung](/batch-processing).

Obwohl der Stapelkopfsatz hauptsächlich in Banktransaktionen verwendet wird, wird er auch bei anderen wichtigen Übertragungen verwendet, z. B. zwischen Unternehmen, Abteilungen und Krankenhäusern.

## Funktionsweise von Chargenkopfdatensätzen

Im Bankwesen wird der Batch-Header-Datensatz im [Automated Clearing House](/ach) (ACH) verwendet, bei dem es sich um ein Batch-orientiertes elektronisches Überweisungssystem handelt. Zu Beginn erhält die Transaktion einen Dateikopfdatensatz, um den Ursprung und die Eigenschaften der Datei zu identifizieren. Darauf folgen mehrere Chargen mit jeweils einem eigenen Chargenkopfsatz. In Kombination mit den Buchungsdetaildatensätzen beschreibt der Chargenkopfdatensatz die Transaktion vollständig.

Jeder Stapel enthält auch Eintragsdetaildatensätze, denen je nach Bedarf oder je nach verwendetem SEC-Code ein oder mehrere Nachtragsdatensätze folgen können.

Stapelverarbeitung ist die Verarbeitung von [Transaktionen](/transaction) in einer Gruppe oder einem Stapel. Sobald die Stapelverarbeitung läuft, ist keine Benutzerinteraktion erforderlich. Dies unterscheidet die Stapelverarbeitung von der Transaktionsverarbeitung, bei der Transaktionen einzeln verarbeitet werden und eine Benutzerinteraktion erforderlich ist.

Während die [Batch-Verarbeitung](/batch-processing) jederzeit ausgeführt werden kann, eignet sie sich besonders für die End-of-Cycle-Verarbeitung, beispielsweise für die Verarbeitung von Bankberichten am Ende eines Tages oder die Erstellung monatlicher oder zweiwöchentlicher [Gehaltsabrechnungen](/payroll).

## Im Batch-Header-Datensatz enthaltene Informationen

In der Regel beginnt ein Stapelkopfdatensatz mit einem Datensatztypcode, einem numerischen Code, der angibt, dass es sich bei dem Datensatz um einen Stapelkopfdatensatz handelt. Der Chargenkopfsatz identifiziert auch die Firma oder Organisation, von der die nachfolgende Charge stammt. Es wird auch den Zweck der im Stapel gefundenen Einträge identifizieren. Beispielsweise könnte ein Urheber einen Code wie „Gehalt“ oder „Stromrechnung“ in den Stapelkopfcode aufnehmen, um den Zweck der in den Stapeleinträgen zu beschreibenden Transaktionen anzugeben.

Der Chargenkopfcode gibt außerdem das effektive Eingabedatum aller in der Charge enthaltenen Transaktionen an. Diese Daten gelten für alle Erfassungsdetaildatensätze im Stapel.

Wenn der Ersteller das effektive Eingangsdatum oder die Daten zum Zweck ändern oder ändern möchte, muss er einen neuen Stapel erstellen, um diese Daten unter dem Stapelkopfdatensatz zu klassifizieren. Wenn ein Ersteller beispielsweise Zahlungen sowohl für das reguläre Gehalt als auch für Mitarbeiterboni verarbeiten möchte, muss er zwei Stapel mit zwei Stapelkopfdatensätzen erstellen, einen für „Lohnabrechnung“ und einen für „Prämien“. Die im Chargenkopfdatensatz enthaltenen Informationen sind für die effiziente und genaue Verarbeitung der Charge von wesentlicher Bedeutung.

> Herman Hollerith (1860-1929) wird die Entwicklung der Lochkarte um 1890 zugeschrieben, als er als Statistiker für das US Census Bureau angestellt war. Diese Lochkarte wurde rund 50 Jahre später zur Keimzelle einer weit verbreiteten Stapelverarbeitung.

>

## Höhepunkte

- Im Bankwesen werden zur effizienteren Verarbeitung und Verrechnung oft mehrere Transaktionen in einem Stapel gebündelt.

- Der Batch-Header-Datensatz sind die Informationen und Metadaten zu einem bestimmten Transaktions-Batch, die beim ACH-Clearing verwendet werden.

- Chargen können im Kopfsatz für Zwecke wie Gehälter oder Verbindlichkeiten gekennzeichnet werden.

