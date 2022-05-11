---
keywords: Crypto
title: Halbierung
description: Halbierung. Wenn die Blockbelohnung eines Krypto-Assets auf die Hälfte des vorherigen Werts sinkt; Dies wird verwendet, um eine abnehmende Emissionsrate zu erzeugen.
---

# Halbierung
Im Bereich der Kryptowährungen bezieht sich der Begriff Halbierung auf einen Prozess, der die Ausgaberate neuer Coins reduziert. Genauer gesagt ist die Halbierung die periodische Reduzierung der Blocksubventionen, die Minern gewährt werden. Die Halbierung stellt sicher, dass ein Krypto-Asset einer konstanten Ausgaberate folgt, bis schließlich sein [maximales Angebot](/maximum-supply) erreicht ist.

Bei Bitcoin werden im Rahmen der [Blockbelohnung](/block-reward) (die sich aus der Blocksubvention plus Transaktionsgebühren zusammensetzt) kontinuierlich neue Coins generiert. Jedes Mal, wenn ein Miner erfolgreich einen neuen [Block „entdeckt“ und validiert](/block),. verdient er neu erstellte Coins als Vergütung für seine Arbeit.

Der [Mining-](/mining) Prozess führt also neue [Bitcoins](/bitcoin) in das System ein, und dies geschieht in einem vorhersehbaren und kontrollierten Tempo. Neue Bitcoin-Blöcke werden im Durchschnitt alle 10 Minuten abgebaut, und die Blocksubvention folgt einer kontrollierten Abnahmerate. Dementsprechend sorgt die Halbierung dafür, dass die Blockförderung alle 210.000 Blöcke (etwa alle vier Jahre) um 50 % sinkt.

Beginnend mit dem [Genesis](/genesis-block) -Block wurde die Blocksubvention von Bitcoin zunächst auf 50 BTC festgelegt. Dann wurde sie auf 25 BTC im Jahr 2012 und auf 12,5 BTC im Jahr 2016 reduziert. Die folgende Halbierung wird voraussichtlich um den Mai 2020 herum stattfinden, wodurch die Blocksubvention auf 6,25 BTC reduziert wird. Sobald 32 Halbierungen stattgefunden haben, stoppt der Prozess und es werden keine Bitcoins mehr erstellt. An diesem Punkt wird das maximale Angebot von 21 Millionen BTC erreicht.

[Folgen Sie dem Bitcoin Halving](/halving)

Die Halbierung ist ein wichtiger Bestandteil des Bitcoin-Protokolls und da der Code Open Source ist, kann ihn jeder sehen. Beispielsweise ist die Bitcoin Core-Implementierung auf [GitHub verfügbar](/github),. und einer der Codeabschnitte, der die Blocksubvention definiert, sieht folgendermaßen aus:

CAmount GetBlockSubsidy(int nHeight, const Konsens::Params& KonsensParams)

{

int Halbierungen = nHeight / ConsensusParams.nSubsidyHalvingInterval;

// Blockbelohnung auf Null setzen, wenn Rechtsverschiebung nicht definiert ist.

if (Halbierungen >= 64)

0 zurückgeben;

CAmount nSubsidy = 50 * COIN;

// Die Subvention wird alle 210.000 Blöcke halbiert, was ungefähr alle 4 Jahre der Fall sein wird.

nSubvention >>= Halbierungen;

zurück nSubvention;

}

