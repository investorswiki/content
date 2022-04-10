---
keywords: Investing,Cryptocurrency,Cryptocurrency Strategy and Education,Strategy and Education
title: Merkle Root (dulkóðunargjaldmiðill)
description: Merkle rót inniheldur upplýsingar um hvert einasta viðskiptakássa sem var einhvern tíma á tiltekinni blokk í blockchain.
---

# Merkle Root (dulkóðunargjaldmiðill)
## Hvað er Merkle rót?

Merkle rót er [kjötkássa](/hash) allra kjötkássa allra viðskipta sem eru hluti af blokk í [blockchain](/blockchain) neti.

## Að skilja Merkle rót

Blockchain samanstendur af ýmsum kubbum sem tengjast hver öðrum (þess vegna nafnið blockchain). Hash-tré, eða [Merkle-tréð](/merkle-tree),. umritar blockchain gögnin á skilvirkan og öruggan hátt. Það gerir skjóta sannprófun á blockchain gögnum, auk skjótrar flutnings á miklu magni af gögnum frá einum tölvuhnút til annars á jafningja-til-jafningja blockchain netinu.

Sérhver viðskipti sem eiga sér stað á blockchain netinu hafa kjötkássa tengt því. Hins vegar eru þessi kjötkássa ekki geymd í röð á reitnum, frekar í formi trjálíkrar uppbyggingu þannig að hvert kjötkássa er tengt foreldri sínu í kjölfar tréslíkra foreldra og barns.

Þar sem það eru fjölmargar færslur geymdar á tiltekinni blokk, eru öll færslukássa í blokkinni einnig hashed, sem leiðir til Merkle rótar.

Íhugaðu til dæmis sjö færslublokk. Á lægsta stigi (kallað laufstig) verða fjórar viðskiptakássar. Á stigi eitt fyrir ofan laufstigið verða tvö færslukássa, sem hver um sig mun tengjast tveimur kjötkássa sem eru fyrir neðan þau á blaðastigi. Efst (stig tvö) verður síðasta viðskiptakássið sem kallast rót og það mun tengjast tveimur kjötkássa fyrir neðan það (á stigi eitt).

Í raun færðu tvíundartré á hvolfi, þar sem hver hnútur trésins tengist aðeins tveimur hnútum fyrir neðan það (þess vegna nafnið "tvíundartré"). Það er með eitt rótarhass efst, sem tengist tveimur kjötkássa á stigi eitt, sem hvert um sig tengist aftur við tvö kjötkássa á stigi þrjú (blaðastig), og uppbyggingin heldur áfram eftir fjölda viðskiptakássa.

<!--AAFEB15A7406E8DD3ABDD652D7C85823-->

Kjötkássa byrjar á neðsta stigi (blaðastigi) hnútum og öll fjögur kjötkássa eru innifalin í kjötkássa hnúta sem eru tengdir við það á stigi eitt. Á sama hátt heldur kjötkássa áfram á stigi eitt, sem leiðir til þess að kjötkássa af kjötkássa nær á hærra stig, þar til það nær einu efstu rótarkjassanum.

Þetta rót kjötkássa er kallað Merkle rót, og vegna trjálíkrar tengingar kjötkássa inniheldur það allar upplýsingar um hvert einasta viðskiptakássa sem er til á reitnum. Það býður upp á eins punkta kjötkássagildi sem gerir kleift að staðfesta allt sem er til staðar á þeim reit.

Til dæmis, ef maður þarf að staðfesta færslu sem segist hafa komið úr blokk #137, þá þarf hann aðeins að athuga Merkle tré blokkarinnar, án þess að hafa áhyggjur af því að sannreyna neitt á öðrum kubbum á blokkinni, eins og blokk #136 eða blokk # 138.

<!--4861E8697637B7236BF11AA57D958059-->

Sláðu inn Merkle rótina, sem flýtir enn frekar fyrir sannprófun. Þar sem það ber allar upplýsingar um allt tréð, þarf aðeins að sannreyna þessi viðskiptakássa, systkinahnút þess (ef hann er til), og halda síðan áfram upp þar til hann nær toppnum.

Í meginatriðum, Merkle tré og Merkle rót vélbúnaður draga verulega úr magni kjötkássa sem á að framkvæma, sem gerir hraðari sannprófun og viðskipti.

## Hápunktar

- Merkle rætur eru miðlægar í útreikningum sem þarf til að viðhalda dulritunargjaldmiðlum eins og bitcoin og eter.

- Merkle rætur eru notaðar í dulritunargjaldmiðli til að tryggja að gagnablokkir sem sendar eru á milli jafningja á jafningjaneti séu heilar, óskemmdar og óbreyttar.

- Merkle rót er einföld stærðfræðileg leið til að sannreyna gögnin um Merkle tré.

