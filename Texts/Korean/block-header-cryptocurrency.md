---
keywords: Investing,Cryptocurrency,Blockchain,Crypto
title: 블록 헤더(암호화폐)
description: 블록 헤더. 메타데이터와 블록 트랜잭션 요약을 포함하는 블록의 섹션입니다. 마이닝 시 해시된 정보입니다.
---

# 블록 헤더(암호화폐)
블록 헤더는 블록 의 나머지 부분에 대한 요약 역할을 하는 [블록 의 섹션입니다.](/block) 블록이 [채굴 된 시간과](/mining) [난이도](/difficulty),. 포함된 트랜잭션 의 [Merkle 루트 및](/merkle-tree) [nonce](/nonce) 와 같은 모든 [메타데이터 로 구성됩니다](/metadata). 또한 이전 블록의 [해시](/hash) 가 있으며, 이는 블록의 "체인"을 생성할 수 있게 해줍니다. 본질적으로 블록 헤더에는 원시 트랜잭션 자체의 목록이 아닌 모든 데이터가 포함됩니다.

블록 헤더는 채굴자가 블록을 유효하게 만들기 위해 해시하는 것입니다. 이것은 수천 개의 트랜잭션으로 구성될 수 있는 전체 블록을 해싱하는 것보다 훨씬 더 효율적입니다. 광부가 nonce를 변경하고 모든 시도에 대해 전체 2MB 블록을 다시 해시하는 것은 훨씬 더 성가신 일입니다. 예를 들어 고정 길이가 80바이트인 비트코인의 블록 헤더를 해싱하는 것과 이것을 비교하십시오.

블록 헤더는 마이닝 관점에서 훌륭하지만 크기가 작기 때문에 라이트 클라이언트에도 이상적입니다. 비트코인 블록체인은 스마트폰과 같은 장치가 저장하기에는 너무 큽니다. 체인에 1MB 블록이 100,000개 있으면 100GB의 공간을 소비하게 됩니다. 그러나 동일한 블록에 대한 블록 헤더만 있으면 0.008GB 또는 8MB만 차지합니다.

이러한 방식으로 대역폭이나 저장 공간이 더 적은 장치는 여전히 어느 정도 유효성 검사를 수행할 수 있습니다. Merkle 루트는 모든 트랜잭션을 캡슐화하기 때문에 나중에 트랜잭션이 특정 블록에 포함되었는지 여부를 확인할 수 있습니다. 이는 비용이 듭니다. 사용자는 여전히 제3자에게 필요한 정보를 제공해야 합니다. 즉, 사용자가 확인을 전혀 수행하지 않는 시스템보다 라이트 클라이언트가 더 좋습니다.

##하이라이트

- 채굴 보상에 대한 작업 증명을 만들기 위해 해시됩니다.

- 블록 헤더는 블록체인의 개별 블록을 식별합니다.

- 블록은 "제네시스 블록"을 시작으로 수직으로 레이어링됩니다.

- 비트코인 버전 번호는 프로토콜의 변경 사항을 추적하는 데 도움이 됩니다.

- 각 블록 헤더에는 세 가지 블록 메타데이터 세트와 여러 개별 구성요소가 포함됩니다.

