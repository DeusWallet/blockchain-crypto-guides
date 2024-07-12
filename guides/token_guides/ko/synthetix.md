# 신세틱스(Synthetix)를 간단하게 설명하다

[Synthetix](https://synthetix.io/)는 Synths라고 알려진 합성 자산을 거래하기 위한 이더리움의 분산형 플랫폼입니다.

> 신스는 암호화폐, 주식, 명목화폐, 귀금속 및 기타 거래 가능한 자산을 나타내는 ERC-20 토큰입니다.

이러한 신스는 자신이 대표하는 자산의 가격을 반영하도록 설계되었지만 다른 특성은 없습니다.

예를 들어, sBTC는 Synthetix에서 현재 비트코인 ​​가격으로 거래될 수 있는 합성 비트코인 ​​토큰입니다.

마찬가지로 sMKR 토큰은 실제 [MKR](../../token_guides/ko/makerdao.md) 토큰과 가격이 동일하지만 투표권은 포함되지 않습니다.

- 신디사이저 토큰을 소유하는 것은 그들이 대표하는 실제 토큰을 소유하는 것과 동일한 가격 노출을 제공합니다.
- 사용자는 실제 자산을 보유하지 않고도 다양한 금융상품의 가격 변동을 추측할 수 있습니다.
- 합성 자산은 사용자 간에 전송될 수 있으며 분산형 거래소에서 거래될 수 있습니다.

요약하면 Synthetix를 사용하면 실제 자산을 나타내는 Ethereum 기반 ERC-20 토큰을 생성할 수 있습니다.

> 가격 피드가 있는 모든 자산은 잠재적으로 Synthetix에 신디사이저 자산으로 추가될 수 있습니다.

현재 사용 가능한 합성 자산에는 암호화폐, 주식 및 귀금속이 포함됩니다. Synthetix는 주식과 같이 전통적인 시장에서 일반적으로 발견되는 더 많은 자산을 포함하도록 서비스를 확장하는 것을 목표로 합니다.

## 지원되는 신디사이저

Synthetix 플랫폼은 현재 약 24개의 다양한 신디사이저를 지원하며 더 많은 신디사이저를 지원합니다.

> 가격 피드와 커뮤니티 승인이 있는 한 시장 가격이 있는 모든 자산을 Synthetix에 추가할 수 있습니다.

현재 신디사이저 자산에는 두 가지 유형이 있습니다.

1. **표준 신디사이저**

 이는 자신이 대표하는 자산의 가격을 추적하므로 자산을 오래 보유하려는 사람들에게 적합합니다.
 - sUSD: 합성 USD
 - sEUR: 합성 EUR
 - sAUD: 합성 AUSDollar
 - sBTC: 합성 비트코인
 - sETH: 합성 에테르
 - smKR: 합성 메이커
 - sBNB: 합성 BNB
 - sXTZ: 합성 테조스
 - sADA: 합성 카르다노
 - sXRP: 합성 리플
 - sLTC: 합성 라이트코인
 - sBCH: 합성 비트코인 ​​캐시
 - sXAU: 합성 골드 온스
 - sXAG: 합성 은온스
 - sDEFI: 합성 DEFI 지수
 - sLINK: 합성 체인링크

2. **역합성**

 이를 통해 사용자는 자산 가격을 매도하여 가격 하락으로 인한 역 이익을 얻을 수 있습니다.
 - iBTC: 인버스 비트코인
 - iETH: 역 이더리움
 - iBNB: 인버스 바이낸스
 - iXTZ: 역 테조스
 - iADA: 역 카르다노
 - iXRP: 역 리플
 - iLTC: 역라이트코인
 - iBCH: 인버스 비트코인 ​​캐시
 - iDEFI: 역 DEFI 지수
 - iLINK: 역체인링크

신스는 비수탁형 [Synthetix.Exchange](https://synthetix.exchange)에서 연중무휴 24시간 거래되므로 [이더리움 생태계](../../token_guides/ko/ethereum.md)의 모든 사용자가 다음을 수행할 수 있습니다. 다양한 자산에 대해 롱 또는 숏 포지션을 취하세요.

## 신디사이저가 생성되는 방법

Synthetix를 이해하려면 새로운 신디사이저가 어떻게 생성되고 유통에서 제거되는지 아는 것이 중요합니다.

1. Synthetix를 사용하면 사용자는 600% 담보 비율로 SNX 토큰을 스마트 계약에 [고정](https://mintr.synthetix.io/)하여 sUSD(합성 USD) 토큰을 생성할 수 있습니다.
2. 1000 sUSD 토큰을 생성하려면 사용자는 최소 $6000 상당의 SNX 토큰을 잠가야 합니다. 이 토큰은 사용자가 빌린 금액을 상환할 때 반환됩니다.
3. 일단 생성된 sUSD 토큰은 Synthetix 거래소에서 현재 시장 가격으로 다른 신디사이저 자산과 거래될 수 있습니다.
4. Synthetix 거래소의 주문은 즉시 이루어지며 시장 가격으로 실행됩니다.
5. 거래자는 항상 거래소를 상대로 거래하는데, 거래소는 사용자로부터 받은 자산을 파괴하고 사용자가 구매한 자산을 생성합니다.
6. 예를 들어, 비트코인이 $10,000일 때 sBTC를 구매하려면 10,000 sUSD를 소각하고 1 sBTC를 생성해야 합니다.

이 프로세스는 모든 신디사이저 자산이 SNX 토큰으로 뒷받침되도록 보장합니다.

투기꾼은 [Uniswap](../../token_guides/ko/uniswap과 같은 [분산형 거래소](../../defi/ko/3-decentralized-exchanges.md)에서 기존 sUSD 또는 sETH를 구매할 수도 있습니다. md) ETH를 사용합니다.

## 신디사이저 거래 방법

Synthetix 생태계에는 신디사이저 거래를 위한 자체 분산형 거래소인 [Synthetix.Exchange](https://synthetix.exchange)가 포함되어 있습니다.

- 다른 분산형 거래소와 달리 Synthetix.Exchange는 주문서나 [유동성 풀](../../defi/ko/3-decentralized-exchanges.md)과 같은 유동성 매칭 메커니즘을 요구하지 않습니다.
- 모든 주문은 몇 초 내에 시장 가격으로 실행되도록 보장됩니다.
- 거래 수수료는 0.1% ~ 1%(일반적으로 0.3%) 범위이며 SNX 토큰을 담보로 잠가서 sUSD 토큰을 생성하는 사람들에게 돌아갑니다.

Synthetix.Exchange에서의 거래는 특히 대량 주문의 경우 더 저렴하며 [Uniswap](../../token_guides/ko/uniswap.md) 또는 [Curve](. ./../token_guides/ko/curve-finance.md).

## 신디사이저를 만드는 이유는 무엇입니까?

신디사이저 거래는 더 저렴하며 이더리움 블록체인에서 전 세계 모든 거래 가능한 자산에 대한 노출을 제공합니다. 이것은 스트론을 생성합니다 g 투기꾼이 실제 자산이 아닌 신디사이저를 거래하도록 하는 인센티브.

600% 담보 비율은 SNX 가격 변동으로부터 신디사이저 자산의 안정성을 보호합니다.

새로운 신디사이저를 만들기 위해 SNX를 플랫폼에 고정한 사람들은 두 가지 유형의 보상을 받습니다:
1. **SNX 스테이킹 보상**: SNX의 인플레이션 통화 정책을 통해 생성됩니다. 2019년 3월부터 2023년 8월 사이에 총 SNX 공급량은 1억 개에서 2억 6,030만 개로 증가하며 주간 감소율은 1.25%입니다.
2. **교환 수수료**: [Synthetix.Exchange](https://synthetix.exchange/#/)에서 신디사이저 거래 수수료는 SNX 스테이커가 매주 청구할 수 있는 수수료 풀로 이동합니다.

SNX 스테이커는 토큰을 잠글 때 부채 포지션을 생성합니다. 이 부채는 발행된 sUSD의 양으로 시작되며 다른 모든 신디사이저 자산의 가격 변동에 따라 변경됩니다.

- 모든 신디사이저가 sBTC이고 BTC 가격이 절반으로 줄어들면 총 부채는 절반으로 줄어들고 각 스테이커의 부채도 절반으로 줄어듭니다.
- 반대로, 50%만 sBTC이고 BTC의 가격이 두 배가 되면 각 스테이커의 부채는 1/4씩 증가합니다.

이러한 방식으로 SNX 스테이커는 전체 시스템 부채의 위험을 감수하면서 모든 신디사이저 거래소에 대한 공동 거래 상대방 역할을 합니다.

## 신세틱스 통계

잠긴 자금의 양과 유통 중인 신디사이저의 수를 포함한 Synthetix 플랫폼의 현재 통계를 보려면 [DeFi Pulse](https://dashboard.synthetix.io)의 Synthetix 개요를 방문하세요.

2020년 9월 9일 현재:
- 총 잠금(USD): $650.2M
- 총 잠긴 수량(ETH 기준): 190만 ETH
- 총 잠김(BTC): 63.3K BTC
- 총 잠긴 수량(SNX 기준): 141M SNX
- SNX 공급 잠김 비율: 70.36%