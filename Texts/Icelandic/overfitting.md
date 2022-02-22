---
keywords: Business,Corporate Finance and Accounting,Financial Analysis
title: Yfirfitting
description: Overfitting er líkanavilla sem á sér stað þegar aðgerð er of nátengd takmörkuðu mengi gagnapunkta.
---

# Yfirfitting
## Hvað er offitting?

Overfitting er líkanavilla í tölfræði sem á sér stað þegar aðgerð er of nátengd takmörkuðu safni gagnapunkta. Fyrir vikið er líkanið aðeins gagnlegt með vísan til upphafsgagnasetts þess, en ekki annarra gagnasöfna.

Ofþurrkun á líkaninu fer almennt út í að búa til of flókið líkan til að útskýra sérkenni í gögnunum sem verið er að rannsaka. Í raun og veru eru gögnin sem rannsökuð eru oft með einhvers konar villu eða tilviljunarkennd hávaða. Þannig að tilraun til að gera líkanið í samræmi við örlítið ónákvæm gögn getur smitað líkanið af verulegum villum og dregið úr forspárkrafti þess.

## Skilningur á overfitting

Til dæmis er algengt vandamál að nota [tölvualgrím](/algorithm) til að leita í víðtækum gagnagrunnum með sögulegum markaðsgögnum til að finna mynstur. Með nægri rannsókn er oft hægt að þróa vandaðar setningar sem virðast spá fyrir um ávöxtun á [hlutabréfamarkaði](/stockmarket) með mikilli nákvæmni.

Hins vegar, þegar þær eru notaðar á gögn utan úrtaksins, gætu slíkar setningar líklega reynst aðeins ofhæfing líkans við það sem í raun og veru var tilviljun. Í öllum tilvikum er mikilvægt að prófa líkan gegn gögnum sem eru utan úrtaksins sem notað var til að þróa það.

## Hvernig á að koma í veg fyrir offitun

Leiðir til að koma í veg fyrir offitun eru meðal annars krossprófun, þar sem gögnin sem notuð eru til að þjálfa líkanið eru saxuð í fellingar eða skipting og líkanið er keyrt fyrir hverja fellingu. Síðan er heildarvillumatið meðaltal. Aðrar aðferðir fela í sér samsetningu: spár eru sameinaðar úr að minnsta kosti tveimur aðskildum gerðum, gagnaaukning, þar sem tiltækt gagnasett er gert til að líta fjölbreytt út, og gagnaeinföldun, þar sem líkanið er straumlínulagað til að forðast offitun.

> Fjármálasérfræðingar verða alltaf að vera meðvitaðir um hættuna af of- eða vanhæfingu líkans sem byggir á takmörkuðum gögnum. Hin fullkomna líkan ætti að vera í jafnvægi.

>

## Offitting í vélanámi

Offitting er einnig þáttur í vélanámi. Það gæti komið fram þegar vél hefur verið kennt að leita að tilteknum gögnum á einn hátt, en þegar sama ferli er beitt á nýtt safn af gögnum eru niðurstöðurnar rangar. Þetta er vegna villna í líkaninu sem var smíðað, þar sem það sýnir líklega litla hlutdrægni og mikla dreifni. Líkanið gæti hafa haft óþarfa eða skarast eiginleika, sem leiðir til þess að það varð óþarfa flókið og þar af leiðandi árangurslaust.

## Offitting vs undirfitting

Líkan sem er offitað getur verið of flókið, sem gerir það árangurslaust. En líkan getur líka verið vanhæft, sem þýðir að það er of einfalt, með of fáa eiginleika og of lítil gögn til að byggja upp áhrifaríkt líkan. Offitt líkan hefur litla hlutdrægni og mikla dreifni, en undirfit líkan er hið gagnstæða - það hefur mikla hlutdrægni og lítið dreifni. Að bæta fleiri eiginleikum við of einfalt líkan getur hjálpað til við að takmarka hlutdrægni.

## Dæmi um yfirklæðningu

Til dæmis, háskóli sem er að sjá brottfall úr háskóla sem er hærra en það sem hann vill, ákveður að hann vilji búa til líkan til að spá fyrir um líkurnar á því að umsækjandi komist alla leið til útskriftar.

Til að gera þetta þjálfar háskólinn líkan úr gagnasafni 5.000 umsækjenda og niðurstöður þeirra. Það keyrir síðan líkanið á upprunalegu gagnapakkanum - hópurinn 5.000 umsækjendur - og líkanið spáir fyrir um niðurstöðuna með 98% nákvæmni. En til að prófa nákvæmni þess keyra þeir líkanið líka á öðru gagnasafni - 5.000 fleiri umsækjendur. Hins vegar, að þessu sinni, er líkanið aðeins 50% nákvæmt, þar sem líkanið passaði of vel við þröngt gagnahlutmengi, í þessu tilviki, fyrstu 5.000 umsóknirnar.

## Hápunktar

- Overfitting er villa sem á sér stað í gagnalíkönum vegna þess að tiltekin aðgerð er samræmd of náið við lágmarks mengi gagnapunkta.

- Þegar líkan hefur verið í hættu vegna offitunar getur líkanið tapað gildi sínu sem forspártæki til að fjárfesta.

- Gagnalíkan getur líka verið vanhæft, sem þýðir að það er of einfalt, með of fáa gagnapunkta til að vera skilvirkt.

- Fjármálasérfræðingar eiga á hættu að ofmeta líkan sem byggir á takmörkuðum gögnum og lenda í gölluðum niðurstöðum.

- Offitting er algengara vandamál en undirfitting og kemur venjulega fram vegna þess að reynt er að forðast offitun.

