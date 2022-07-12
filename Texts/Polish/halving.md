---
keywords: Crypto
title: Halving
description: Połowa. Kiedy nagroda blokowa zasobu kryptograficznego spada do połowy tego, co było wcześniej; służy to do tworzenia malejącej stopy emisji.
---

# Halving
W przestrzeni kryptowalut termin halving odnosi się do procesu, który zmniejsza wskaźnik emisji nowych monet. Mówiąc dokładniej, zmniejszenie o połowę to okresowe zmniejszanie dotacji blokowej udzielanej górnikom. Halving zapewnia, że zasób kryptograficzny będzie podążał za stałym wskaźnikiem emisji, aż do ostatecznego osiągnięcia [maksymalnej podaży .](/maximum-supply)

Jeśli chodzi o Bitcoin, monety informacyjne są generowane w sposób ciągły w ramach [nagrody blokowej](/block-reward) (na którą składa się dotacja blokowa plus opłaty transakcyjne). Tak więc za każdym razem, gdy górnik z powodzeniem „odkryje” i zatwierdzi nowy [blok](/block),. zarabia nowo utworzone monety jako rekompensatę za swoją pracę.

Tak więc proces [wydobycia](/mining) jest tym, co wprowadza nowe [Bitcoiny](/bitcoin) do systemu i odbywa się to w przewidywalnym i kontrolowanym tempie. Nowe bloki Bitcoin są wydobywane średnio co 10 minut, a dotacja blokowa podlega kontrolowanej szybkości rozpadu. W związku z tym zmniejszenie o połowę zapewnia, że dotacja blokowa będzie się zmniejszać o 50% co 210 000 bloków (mniej więcej co cztery lata).

Począwszy od [bloku genezy](/genesis-block),. dotacja blokowa Bitcoina została początkowo ustalona na 50 BTC. Następnie została zmniejszona do 25 BTC w 2012 r. i do 12,5 BTC w 2016 r. Oczekuje się, że kolejny halving nastąpi około maja 2020 r., zmniejszając dotację blokową do 6,25 BTC. Po wystąpieniu 32 halvingów proces zatrzymuje się i nie zostanie utworzonych więcej bitcoinów. W tym momencie zostanie osiągnięta maksymalna podaż 21 milionów BTC.

[Śledź wraz z Bitcoin Halving](/halving)

Halving jest ważną częścią protokołu Bitcoin, a ponieważ kod jest open-source, każdy może go zobaczyć. Na przykład implementacja Bitcoin Core jest dostępna na [GitHub](/github),. a jedna z sekcji kodu, która definiuje dotację blokową, wygląda tak:

CAmount GetBlockSubsidy (int nHeight, const Consensus::Params& consensusParams)

{

int halvings = nHeight / consensusParams.nSubsidyHalvingInterval;

// Wymuś nagrodę za blok do zera, gdy przesunięcie w prawo jest niezdefiniowane.

jeśli (połowy >= 64)

zwróć 0;

CAmount nSubsidy = 50 * MONETA;

// Dotacja jest zmniejszana o połowę co 210 000 bloków, co nastąpi mniej więcej co 4 lata.

nDotacja >>= połówki;

powrót nDotacja;

}

