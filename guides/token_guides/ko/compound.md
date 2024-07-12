# 간단하게 설명하는 화합물

[Compound](https://app.compound.finance)는 암호화폐 대출자와 대출자를 연결하는 분산형 플랫폼입니다.

작동 방식은 다음과 같습니다.

- **대출**: 암호화폐 소유자는 스마트 계약을 통해 자신의 자산을 컴파운드의 유동성 풀에 예치하고 이자를 얻습니다.

- **차입**: 차용자는 다른 암호화폐로 담보를 제공하여 컴파운드에 신용을 요청합니다.

대출과 차용 모두 일반 사용자와 스마트 계약에 접근할 수 있으므로 DeFi 엔지니어는 다른 DeFi 플랫폼의 유동성에 접근하는 서비스를 만들 수 있습니다.

컴파운드는 8가지 암호화폐를 지원합니다:

- [래핑된 BTC(WBTC)](https://compound.finance/markets/WBTC)
- [이더리움(ETH)](https://compound.finance/markets/ETH)
- [USD 코인(USDC)](https://compound.finance/markets/USDC)
- [테더(USDT)](https://compound.finance/markets/USDT)
- [다이(DAI)](https://compound.finance/markets/DAI)
- [어거(REP)](https://compound.finance/markets/REP)
- [0x(ZRX)](https://compound.finance/markets/ZRX)
- [베이직 어텐션 토큰(BAT)](https://compound.finance/markets/BAT)

각 암호화폐에는 이자율 및 담보 요소를 포함한 특정 차용 및 대출 요구 사항이 있습니다.

- **이자율**: 각 암호화폐에 대한 시장 공급과 수요에 따라 금리가 변동됩니다.

- **담보 요소**: 차용에 필요한 담보 금액을 결정합니다. 예를 들어, 70% 요소는 사용자가 담보 가치의 최대 70%를 빌릴 수 있음을 의미합니다.

사용자는 컴파운드 웹사이트에서 총 대출 기관, 대출자 및 대출 가능한 자산을 볼 수 있습니다.

## 컴파운드 대출

빌리기 위해 사용자는 다른 암호화폐로 담보를 제공합니다. 빌릴 수 있는 최대 금액은 해당 담보의 준비율에 따라 달라집니다.

- **수수료**: 차입 시 시장 상황에 따라 이자가 발생합니다.

- **상환**: 상환되면 차용인은 담보를 인출할 수 있습니다. 다만, 차입잔액이 허용한도를 초과할 경우 해당 계좌는 부실상태가 되어 청산될 수 있습니다.

## 복합 대출

대출 기관은 언제든지 자산(이자 포함)을 인출할 수 있습니다. 그들은 교환으로 cToken을 받습니다. 이는 예금을 나타내며 시간이 지남에 따라 이자가 발생합니다.

- **cTokens**: 이 ERC20 토큰은 기본 자산으로 상환될 수 있습니다. 이자는 지속적으로 발생하여 시간이 지남에 따라 cToken의 가치가 증가합니다.

## 복합 거버넌스

2020년 5월부터 컴파운드는 COMP 토큰을 사용하여 커뮤니티 거버넌스를 채택했습니다.

- **제안 및 투표**: COMP 보유자는 지원되는 담보 자산 및 이자율과 같은 플랫폼 결정에 대해 제안하고 투표할 수 있습니다.

- **토큰 배포**: COMP 토큰은 암호화폐를 공급하거나 빌리는 활성 사용자에게 배포되며 각 그룹에 50%가 할당됩니다.

컴파운드는 사용자가 거버넌스 결정에 참여하여 COMP를 획득함으로써 모든 플랫폼 측면을 분산시키는 것을 목표로 합니다.

자세한 내용을 보려면 다음을 방문하세요.

- [컴파운드 공식 홈페이지](https://compound.finance)
- [거버넌스 제안](https://compound.finance/governance/proposals)
- [화합물 소유자 리더보드](https://compound.finance/governance/leaderboard)
- [프로젝트 문서](https://compound.finance/docs)