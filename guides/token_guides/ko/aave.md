# 간단히 말해서 Aave

[Aave](https://app.aave.com/)는 사용자가 이더리움 기반 암호화폐 자산을 빌려주고 빌릴 수 있는 이더리움 블록체인의 비수탁형 분산형 서비스입니다. 2020년 1월에 출시된 Aave는 빠르게 성장하여 단 8개월 만에 거의 20억 달러 상당의 암호화폐를 유치했습니다.

## Aave 작동 방식

- **예금자**: 사용자는 암호화폐를 분산형 대출 풀에 예치하여 유동성을 제공하고 그 대가로 이자를 얻습니다.
- **차용자**: 사용자는 수수료를 지불하여 이러한 대출 풀에서 빌릴 수 있습니다.
- **독특한 기능**: [Compound](../../token_guides/ko/compound.md) 또는 [MakerDAO](../../token_guides/ko/makerdao.md)와 같은 다른 서비스와 달리, Aave는 담보 없이 대출을 허용합니다.
- **이자율**: 일반적으로 다른 플랫폼보다 높습니다.
- **보안**: Aave의 스마트 계약은 비수탁형 및 분산형이므로 Aave 팀이 사용자 자금에 접근할 수 없습니다.

## 지원되는 자산

2020년 9월 현재 Aave는 20개의 이더리움 기반 암호화폐 토큰 대여 및 차용을 지원합니다.

- [USD 코인(USDC)](https://app.aave.com/reserve-overview/USDC?pool=Aave)
- [테더(USDT)](https://app.aave.com/reserve-overview/USDT?pool=Aave)
- [트루USD(TUSD)](https://app.aave.com/reserve-overview/TUSD?pool=Aave)
- [다이(DAI)](https://app.aave.com/reserve-overview/DAI?pool=Aave)
- [sUSD](https://app.aave.com/reserve-overview/SUSD?pool=Aave)
- [바이낸스(BUSD)](https://app.aave.com/reserve-overview/BUSD?pool=Aave)
- [이더리움(ETH)](https://app.aave.com/reserve-overview/ETH?pool=Aave)
- [ETHLend(LEND)](https://app.aave.com/reserve-overview/LEND?pool=Aave)
- [YFI](https://app.aave.com/reserve-overview/YFI?pool=Aave)
- [베이직 어텐션 토큰(BAT)](https://app.aave.com/reserve-overview/BAT?pool=Aave)
- [EnjinCoin(ENJ)](https://app.aave.com/reserve-overview/ENJ?pool=Aave)
- [REN](https://app.aave.com/reserve-overview/REN?pool=Aave)
- [카이버 네트워크(KNC)](https://app.aave.com/reserve-overview/KNC?pool=Aave)
- [체인링크(링크)](https://app.aave.com/reserve-overview/LINK?pool=Aave)
- [디센트럴랜드(MANA)](https://app.aave.com/reserve-overview/MANA?pool=Aave)
- [메이커(MKR)](https://app.aave.com/reserve-overview/MKR?pool=Aave)
- [어거(REP)](https://app.aave.com/reserve-overview/REP?pool=Aave)
- [신세틱스(SNX)](https://app.aave.com/reserve-overview/SNX?pool=Aave)
- [WBTC 코인(wBTC)](https://app.aave.com/reserve-overview/WBTC?pool=Aave)
- [0x(ZRX)](https://app.aave.com/reserve-overview/ZRX?pool=Aave)

각 자산에는 특정 차입 및 대출 요구 사항이 있습니다. 지원되는 암호화폐에 대한 통제권은 결국 Aave 토큰 보유자에게 이전됩니다.

## Aave 대출

- **이자 수익**: 대출 기관은 예치된 자산에 대해 이자를 얻습니다.
- **담보**: 예금은 차주가 제공하는 담보로 보장됩니다.
- **aTokens**: 대출 기관은 이자를 받고 수입과 함께 예금을 인출하는 데 사용할 수 있는 aToken을 받습니다. aToken은 기본 자산에 1:1로 고정됩니다.

## Aave에서 대출하기

- **담보 요건**: 차용에는 다른 암호화폐 형태의 담보가 필요합니다.
- **LTV(대출 가치) 비율**: 최대 차입력을 나타냅니다. (예: LTV 75%는 담보 가치의 최대 75%까지 차입한다는 의미입니다.)
- **이자율**: 차용자는 고정 이자율과 변동 이자율 중에서 선택할 수 있습니다.
- **담보 유지**: 차용자는 담보 가치가 청산을 방지하는 데 필요한 최소 금액 이상으로 유지되도록 해야 합니다.

## 플래시 대출

플래시 대출은 Aave의 고유한 기능으로 사용자가 담보 없이 빌릴 수 있습니다.

- **메커니즘**: 한 번의 거래 내에서 자산을 빌리고 거래가 끝나기 전에 반환합니다.
- **수수료**: 플래시론에는 0.09%의 수수료가 부과됩니다.

플래시 대출은 주로 프로그래머가 차익거래 및 재융자 같은 활동에 사용합니다.

## Aave 거버넌스

Aave는 완전히 커뮤니티가 관리하는 분산형 자율 조직(DAO)이 되는 것을 목표로 합니다.

- **AAVE 토큰**: 프로토콜 개선 및 거버넌스 결정에 대한 투표에 사용됩니다.
- **인센티브**: AAVE 토큰 보유자는 보상을 받고 거버넌스에 참여할 수 있습니다.
- **긴급 자금**: 예상치 못한 상황이 발생할 경우 대출 기관의 자산을 보호합니다.
- **디플레이션 토큰**: 수수료의 일부는 AAVE 토큰을 다시 구매하고 소각하는 데 사용됩니다.

## 에이브 2.0을 소개합니다

2020년 8월 14일에 발표된 Aave 2.0에는 몇 가지 새로운 기능이 도입되었습니다.

- **담보로 지불**: 대출 상환 거래를 단순화합니다.
- **고정 금리**: 대출 및 차입 금리에 대한 예측 가능성을 제공합니다.
- **거래 비용 절감**: 플랫폼 상호 작용 비용을 절감합니다.
- **거래 기능**: 사용자는 지원되는 암호화폐 전체에서 부채 포지션과 예치된 자산을 거래할 수 있습니다.

## 위험

모든 DeFi 서비스와 마찬가지로 스마트 계약 버그와 관련된 위험이 있습니다. Aave는 계약 감사를 받았으며 커뮤니티 구성원이 취약점을 보고할 수 있도록 버그 포상금 프로그램을 제공합니다.

## 유용한 링크

- [Aave 공식 포털](https://app.aave.com/)
- [Aave 공식 블로그](https://medium.com/aave)
- [다큐멘타 포털](https://docs.aave.com/portal/)
- [거버넌스 포털](https://governance.aave.com)