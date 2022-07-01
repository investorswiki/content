---
keywords: Investing,Fundamental Analysis,Tools for Fundamental Analysis,Tools
title: Wilcoxon test
description: Wilcoxon-testet, som refererar till antingen rangsummetestet eller det signerade rangtestet, är ett icke-parametriskt test som jämför två parade grupper.
---

# Wilcoxon test
## Vad är Wilcoxon-testet?

Wilcoxon-testet, som kan referera till antingen rangsummetestet eller den signerade rangtestversionen, är ett icke-parametriskt statistiskt test som jämför två parade grupper. Testerna beräknar i huvudsak skillnaden mellan uppsättningar av par och analyserar dessa skillnader för att fastställa om de är [statistiskt](/statistical-significance) [signifikant](/statistical-significance) olika från varandra.

## Förstå Wilcoxon-testet

Rangsumman och undertecknade rangtest föreslogs båda av den amerikanske statistikern Frank Wilcoxon i en banbrytande forskningsartikel publicerad 1945. Testerna lade grunden för [hypotestestning](/hypothesistesting) av icke- [parametrisk statistik](/nonparametric-statistics),. som används för befolkningsdata som kan rangordnas men som inte har numeriska värden, som kundnöjdhet eller musikrecensioner. Icke-parametriska distributioner har inga parametrar och kan inte definieras av en ekvation som parametriska distributioner kan.

De typer av frågor som Wilcoxon-testet kan hjälpa till att besvara inkluderar saker som:

- Skiljer sig provresultaten från 5:e till 6:e klass för samma elever?

- Har ett visst läkemedel en effekt på hälsan när det testas på samma individer?

Dessa modeller antar att data kommer från två matchade, eller beroende, populationer, som följer samma person eller aktie genom tid eller plats. Uppgifterna antas också vara kontinuerliga i motsats till diskreta. Eftersom det är ett icke-parametriskt test, kräver det inte en särskild sannolikhetsfördelning av den beroende variabeln i analysen.

## Typer av Wilcoxon-testet

- Wilcoxons rangsummetest kan användas för att testa [nollhypotesen](/null_hypothesis) att två populationer har samma kontinuerliga fördelning. En nollhypotes är ett statistiskt test som säger att det inte finns någon signifikant skillnad mellan två populationer eller variabler. De basantaganden som krävs för att använda rangsummetestet är att data är från samma population och är parade, data kan mätas på åtminstone en intervallskala och data valdes slumpmässigt och oberoende.

- Wilcoxon signed rank test antar att det finns information om storleken och tecken på skillnaderna mellan parade observationer. Som den icke-parametriska motsvarigheten till den parade elevens t-test kan den signerade rangen användas som ett alternativ till [t-testet](/t-test) när populationsdata inte följer en [normalfördelning](/normaldistribution).

## Beräknar en Wilcoxon-teststatistik

Stegen för att komma fram till en Wilcoxon signerad rankteststatistik, **W,** är följande:

1. För varje objekt i ett urval av **n** objekt, erhåll en skillnadspoäng, D~i~, mellan två mätningar (dvs subtrahera den ena från den andra).

1. Försumma sedan positiva eller negativa tecken och få en uppsättning **n** absoluta skillnader |D~i~|.

1. Utelämna skillnadspoäng på noll, vilket ger dig en uppsättning **n** absoluta skillnadspoäng som inte är noll, där **n' ≤ n**. Således blir **n'** den faktiska urvalsstorleken.

1. Tilldela sedan rangorden R~i~ från 1 till **n** till var och en av |D~i~| så att den minsta absoluta skillnadspoängen får rang 1 och den största får rang **n**. Om två eller flera |D~i~| är lika, tilldelas de var och en den genomsnittliga rangordningen för de rangordningar som de skulle ha tilldelats individuellt om kopplingar i data inte hade inträffat.

1. Tilldela nu symbolen "+" eller "–" till var och en av **n**-rangerna R~i~, beroende på om D~i~ ursprungligen var positiv eller negativ.

1. Wilcoxon-teststatistiken **W** erhålls därefter som summan av de positiva rangorden.

I praktiken utförs detta test med hjälp av programvara för statistisk analys eller ett kalkylblad.

## Höjdpunkter

– Båda versionerna av modellen utgår från att paren i data kommer från beroende populationer, det vill säga följer samma person eller aktiekurs genom tid eller plats.

- Målet med testet är att avgöra om två eller flera uppsättningar av par skiljer sig från varandra på ett statistiskt signifikant sätt.

- Wilcoxon-testet jämför två parade grupper och kommer i två versioner, rangsummetestet och signerat rangtest.

