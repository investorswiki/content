---
keywords: Crypto
title: Éter Envolto (WETH)
description: Éter Envolvido (WETH). Token ERC-20 representando Ether na proporção de 1:1. Ele permite que os usuários negociem tokens ETH para ERC-20 em plataformas descentralizadas.
---

# Éter Envolto (WETH)
Wrapped Ether (WETH) refere-se à versão de éter compatível [com ERC-20](/erc-20) (envolvendo o éter com outros padrões ERC também é possível). WETH pode ser criado enviando ether para um contrato inteligente onde o ether é colocado em espera, recebendo por sua vez o token WETH ERC-20 na proporção de 1:1. Este WETH pode posteriormente ser enviado de volta para o mesmo contrato inteligente para ser “desembrulhado” ou resgatado pelo éter original na proporção de 1: 1.

O Ether, sendo a moeda nativa na blockchain Ethereum, foi criado antes do padrão ERC-20 e outros padrões foram implementados; portanto, o próprio ether não é compatível com ERC-20 e não pode ser trocado diretamente por outros tokens ERC-20 de maneira descentralizada sem a mediação de um terceiro confiável ou a adição de implementações técnicas complexas. Em vez de implementar duas interfaces (uma para ether e outra para tokens ERC-20) dentro do mesmo contrato inteligente, levando a complexidades desnecessárias, os desenvolvedores decidiram “empacotar” o ether para atualizá-lo para o padrão ERC-20 para lidar convenientemente com WETH e outros ERC-20 dentro do mesmo contrato. O encapsulamento de éter permite a troca direta e contínua entre tokens ether e ERC-20 sem a necessidade de um terceiro confiável e sem incorrer em riscos desnecessários, como erros inesperados durante transações resultantes de implementações complexas. Muitos aplicativos descentralizados baseados em Ethereum [(dApps)](/decentralized-applications-dapps),. como plataformas [de câmbio descentralizadas](/decentralized-exchange),. usam WETH no lugar de ether para facilitar a negociação direta e descentralizada entre ether em “formato encapsulado” e tokens ERC-20 sob o mesmo padrão técnico. Desenvolvimentos recentes estão tentando ter um padrão WETH canônico que possa ser usado por todos os dApps baseados em Ethereum.

