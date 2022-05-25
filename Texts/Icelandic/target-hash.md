---
keywords: Investing,Cryptocurrency,Altcoins
title: Target Hash
description: Markmiðjakássa setur erfiðleikana fyrir námuvinnslu dulritunargjaldmiðla með því að nota sönnunarhæfni (PoW) blockchain kerfi.
---

# Target Hash
## Hvað er markhash?

Í námuvinnslu dulritunargjaldmiðla er markkássa tölugildi sem hashed [blokkarhaus](/block-header-cryptocurrency) verður að vera minni en eða jafn til þess að ný blokk sé veitt námumanni. Blokkhausar auðkenna einstakar blokkir í blockchain.

Námuvinnsla dulritunargjaldmiðla vísar til þess að safna dulritunargjaldmiðli sem verðlaun fyrir vinnu sem þú lýkur. Eðli þessarar vinnu er að sannreyna lögmæti viðskipta tiltekins cryptocurrency. Á þennan hátt eru námuverkamenn í dulritunargjaldmiðlum í meginatriðum endurskoðendur. Þegar þú dregur, geturðu unnið þér inn dulritunargjaldmiðil án þess að þurfa að leggja niður peninga fyrir það.

Markhashið er notað til að ákvarða erfiðleika inntaksins og hægt er að stilla það til að tryggja að blokkir séu unnar á skilvirkan hátt. Til dæmis eru markhass notaðir í dulritunargjaldmiðlum sem nota sönnunarprófunarkerfi (PoW) til að stilla núverandi [námuvinnslu erfiða](/difficulty-cryptocurrencies) [y](/difficulty-cryptocurrencies) (þar á meðal Bitcoin). Ef dulritunargjaldmiðill notar annað kerfi til námuvinnslu gæti verið að það þurfi ekki markhash.

## Hvernig markhash virkar

[Dulritunargjaldmiðlar](/cryptocurrency) treysta á notkun [blockchains](/blockchain) sem innihalda sögu allra viðskipta dulritunargjaldmiðilsins. Þessar færslur eru [þjakaðar](/hash),. eða dulkóðaðar, í röð af tölustöfum. Hashing felur í sér að taka gagnastreng af hvaða lengd sem er og keyra það í gegnum reiknirit til að framleiða úttak með fastri lengd. Úttakið verður alltaf jafn langt, óháð því hversu stórt eða lítið inntakið er (þó að fjöldi breytinga á kjötkássa sé stjarnfræðilega mikill). Hver blokk mun innihalda kjötkássa fyrri blokkarhaussins.

Staðfesting og kóðun blockchain er vísað til sem [námuvinnslu](/bitcoin-mining). Námuvinnsla felur í sér notkun á tölvum til að keyra kjötkássa reiknirit til að vinna úr nýjustu blokkinni; upplýsingarnar sem notandi þarf til að grafa er að finna í haus blokkarinnar. Dulritunargjaldmiðilsnetið setur markgildi fyrir þetta kjötkássa - kallað markkássa - og námumenn reyna að ákvarða hvert þetta gildi er með því að prófa öll möguleg gildi.

Blokkhausinn inniheldur blokkarútgáfunúmerið, tímastimpil, kjötkássa sem notað var í fyrri blokk, kjötkássa [Merkle Roo](/merkle-root-cryptocurrency) [t](/merkle-root-cryptocurrency),. [nonce](/nonce) og markhash. Kubburinn er myndaður með því að taka kjötkássa af innihaldi blokkarinnar, bæta við handahófskenndri tölustreng (nonce) og hassa blokkina aftur.

Ef kjötkássa uppfyllir kröfur markmiðsins, þá er blokkinni bætt við blockchain. Að hjóla í gegnum lausnir til að giska á ómerkið er vísað til sem [vinnusönnun](/proof-work) (PoW) og námumaðurinn sem getur fundið verðmæti fær blokkina og greidd í dulritunargjaldmiðli.

## Sérstök atriði

### Markmiðjakássa fyrir Bitcoin

Bitcoin notar SHA-256 kjötkássa reiknirit. Þetta reiknirit býr til sannanlega tilviljunarkenndar tölur á þann hátt sem krefst fyrirsjáanlegs magns af tölvuvinnsluorku.

Að náma blokk krefst þess að námumaðurinn framleiði gildi (nonce) sem, eftir að hafa verið hashed (dulkóðuð), er minna en eða jafnt því sem notað er í nýjustu blokkinni sem bitcoin netkerfið samþykkti. Þessi tala er á milli 0- (minnsti valkosturinn) og 256-bita (stærsti valkosturinn) en ólíklegt er að það verði nokkurn tíma hámarksfjöldi.

Vegna þess að markkássa gæti verið gríðarlegur fjöldi gæti námumaðurinn þurft að prófa mikinn fjölda gilda áður en hann nær árangri. Misheppnaður námuverkamaður þarf að bíða eftir næstu blokk (þess vegna er námumönnum sem finna kjötkássalausn líkt við sigurvegara í keppni eða lottói).

Markhashið er stillt reglulega. Hash-aðgerðirnar sem notaðar eru til að búa til nýja markið hafa sérstaka eiginleika sem eru hannaðar til að gera blockchain (og dulritunargjaldmiðil hennar) örugga. Þetta ferli er deterministic, sem þýðir að það mun gefa sömu niðurstöðu í hvert sinn sem sama inntak er notað. Það er nógu hratt til að það taki ekki of langan tíma að skila kjötkássa fyrir inntakið. Það gerir einnig mjög erfitt að ákvarða inntakið, sérstaklega fyrir stórar tölur, og gerir litlar breytingar á inntakinu sem leiða til mjög mismunandi kjötkássaúttaks.

## Hápunktar

- Target hashes eru notaðir í dulritunargjaldmiðlum sem nota proof-of-work (PoW) kerfi til að stilla núverandi námuerfiðleika (þar á meðal Bitcoin); ef dulritunargjaldmiðill notar annað kerfi til námuvinnslu, gæti það ekki þurft markhash.

- Í námuvinnslu dulritunargjaldmiðla er markkássa tölugildi sem hashed blokkarhaus (sem er notaður til að bera kennsl á einstakar blokkir í blokkakeðju) verður að vera minna en eða jafnt til þess að ný blokk sé veitt námumanni.

- Bitcoin netið aðlagar erfiðleika námuvinnslu með því að hækka eða lækka markhasið til að varðveita að meðaltali 10 mínútna bil á milli nýrra blokka.

