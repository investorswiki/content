---
keywords: Crypto
title: Zawinięty Eter (WETH)
description: Zawinięty Eter (WETH). Token ERC-20 reprezentujący Ether w stosunku 1:1. Umożliwia użytkownikom handel tokenami ETH na ERC-20 na zdecentralizowanych platformach.
---

# Zawinięty Eter (WETH)
Wrapped Ether (WETH) odnosi się do wersji etheru kompatybilnej z [ERC-20](/erc-20) (możliwe jest również owinięcie eteru innymi standardami ERC). WETH można utworzyć, wysyłając eter do inteligentnego kontraktu, w którym eter jest zawieszony, z kolei otrzymując token WETH ERC-20 w stosunku 1:1. Ten WETH można następnie odesłać z powrotem do tej samej inteligentnej umowy, aby „rozpakować” lub wymienić z powrotem na oryginalny eter w stosunku 1:1.

Ether, będący natywną walutą w blockchainie Ethereum, został stworzony przed wdrożeniem standardu ERC-20 i innych standardów; w związku z tym sam ether nie jest kompatybilny z ERC-20 i nie może być wymieniany bezpośrednio na inne tokeny ERC-20 w sposób zdecentralizowany bez pośrednictwa zaufanej strony trzeciej lub dodawania złożonych implementacji technicznych. Zamiast wdrażać dwa interfejsy (jeden dla etheru, a drugi dla tokenów ERC-20) w ramach tej samej inteligentnej umowy prowadzącej do niepotrzebnych komplikacji, programiści postanowili „opakować” ether, aby zaktualizować go do standardu ERC-20, aby wygodnie obsługiwać WETH i inne ERC-20 w ramach tej samej umowy. Owijanie etheru umożliwia bezpośrednią, bezproblemową wymianę pomiędzy tokenami ether i ERC-20 bez potrzeby korzystania z zaufanej strony trzeciej i bez ponoszenia niepotrzebnego ryzyka, takiego jak nieoczekiwane błędy podczas transakcji wynikających ze złożonych wdrożeń. Wiele [zdecentralizowanych aplikacji opartych na Ethereum (dApps)](/decentralized-applications-dapps),. takich jak [zdecentralizowane](/decentralized-exchange) platformy wymiany, używa WETH zamiast etheru, aby ułatwić bezpośredni i zdecentralizowany handel peer to peer między etherem w „opakowanej formie” a tokenami ERC-20 w ramach tego samego standardu technicznego. Ostatnie osiągnięcia starają się mieć kanoniczny standard WETH, który mógłby być używany przez wszystkie dApps oparte na Ethereum.

