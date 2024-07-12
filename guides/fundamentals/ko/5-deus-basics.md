# 데우스 지갑

이 섹션에서는 비수탁 지갑 앱을 사용할 때 실용적인 측면과 '알아야 할 사항'에 중점을 둘 것입니다.

사용자의 관점에서 비수탁 지갑 앱의 기본 기대치는 다음과 같아야 합니다.

1. **표준 준수 키 생성**: 지갑 앱은 표준 준수 방식으로 개인 키를 생성하여 안전과 다른 타사 지갑 앱과의 호환성을 보장해야 합니다.

2. **여러 암호화폐의 올바른 관리**: 지갑 앱은 각 암호화폐의 결제 주소를 올바르게 관리해야 하며, 예를 들어 사용자의 비트코인 ​​주소가 이더리움 주소와 다른지 확인해야 합니다.

3. **안전한 개인 키 저장소**: 지갑 앱은 문서화된 지침에 따라 개인 키를 저장해야 합니다. iOS 및 Android 지갑 앱은 모두 개인 키를 안전하게 유지하기 위해 운영 체제에서 제공하는 안전한 저장 메커니즘을 활용해야 합니다.

추가 기대치는 대상 사용자에 따라 달라질 수 있습니다. 예를 들어, 광범위한 개인 정보 보호를 원하는 사람은 대부분의 지갑 앱에서 사용할 수 없는 기능이 필요할 수 있습니다.

아래에서는 Deus 지갑 앱을 사용하여 비수탁 지갑 앱을 사용할 때 명심해야 할 몇 가지 중요한 사항을 강조하여 이러한 측면을 설명합니다.

### 1. 설정 / 복원

모든 비수탁형 지갑은 새 지갑을 설정하거나 기존 지갑을 마이그레이션하는 것부터 시작됩니다.

- **'지갑 만들기'** 버튼을 누르면 새로운 개인키가 생성되어 12단어로 표시되므로 백업이 필요합니다.
- **'지갑 복원'** 옵션은 이전에 Deus 또는 다른 표준 호환 지갑에서 생성된 기존 지갑을 복원합니다.

비수탁 지갑을 복원하는 데는 몇 분에서 몇 시간까지 걸릴 수 있습니다.

### 2. 인증 잠금

비수탁 지갑 앱에는 무단 액세스를 방지하기 위한 기본 조치가 포함되어야 합니다. 모바일 지갑과 하드웨어 지갑 모두 지갑에 액세스하는 데 필요한 잠금 해제 코드를 통해 이를 구현합니다.

이 조치는 누군가가 귀하의 지갑 장치에 물리적으로 접근하는 경우에도 귀하의 자금을 안전하게 유지하는 데 필수적입니다.

### 3. 지원되는 암호화폐

지갑이 처리할 수 있는 암호화폐가 많을수록 좋습니다. 여러 앱을 전환하는 것보다 하나의 앱 내에서 여러 암호화폐를 관리하는 것이 편리합니다.

지갑 앱은 또한 현재 암호화폐 가격을 표시해야 하며 USD 또는 EUR와 같은 친숙한 통화로 잔액을 표시해야 합니다. 이는 계산을 단순화하므로 결제 시 특히 유용합니다.

### 4. 코인 개요

각 암호화폐는 고유한 특성을 지닌 고유한 프로젝트입니다. 이러한 세부 사항을 이해하는 것은 암호화폐에 투자하려는 모든 사람에게 중요합니다.

기술적인 배경이 있는 사람들에게도 많은 프로젝트가 잘 알려지지 않은 채로 남아 있습니다. Deus는 다양한 암호화폐에 대한 포괄적인 개요를 간단한 용어로 제공하는 것을 목표로 합니다.

### 5. 차트 및 데이터

토큰의 과거 시장 환율을 표시하는 지갑을 선택하세요.

과거 가격은 암호화폐 가격이 어떻게 변했는지에 대한 개요를 제공하고 사용자가 과거 거래에 대한 과거 환율을 볼 수 있도록 합니다.

### 6. 멀티월렛

Deus를 포함한 일부 지갑은 단일 앱 내에서 무제한 지갑 생성을 허용합니다.

이 기능을 통해 사용자는 여러 암호화폐 포트폴리오를 쉽게 관리할 수 있습니다.

### 7. 개인정보 보호

비수탁 지갑의 개인 정보 보호 기능은 크게 다를 수 있습니다.

개인 정보 보호 기능을 위해 지갑을 평가할 때 다음 사항을 고려하십시오.

- **기본 사용자 데이터**: 지갑 디자인에 따라 공급자는 사용자의 IP 주소 및 위치와 같은 일부 식별 불가능한 데이터를 알고 있을 수 있습니다. 이 데이터가 서버에 저장되면 항상 데이터 유출 위험이 있습니다.

- **잔액 및 거래**: 일부 지갑에서는 사용자가 기존 지갑을 복원하거나 이전할 수 있습니다. 지갑 제공업체는 이 작업에 최적화된 특수 서버를 사용할 수 있으며, 이는 잠재적으로 사용자의 잔액 및 과거 거래에 대한 정보를 노출할 수 있습니다.

 이 문제를 해결하기 위해 Deus와 같은 지갑은 블록체인 네트워크 자체에서 직접 복원을 지원하여 공급자가 사용자의 잔액이나 거래에 대한 정보를 갖지 못하도록 합니다.

- **블록체인 개인정보 보호**: 다양한 블록체인은 다양한 수준의 개인정보 보호를 제공합니다. 비트코인 거래는 일반적으로 이더리움 거래보다 더 비공개적입니다. 일부 비수탁형 지갑에는 특정 블록체인의 개인정보 보호를 강화하는 기능이 포함되어 있습니다. 예를 들어, Deus는 비트코인 ​​거래를 단일 엔터티에 연결하는 것을 훨씬 더 어렵게 만드는 기능을 통합합니다.

사용자에 대한 최소한의 개인 정보 보호 요구 사항은 사용자에 대해 전혀 모르는 지갑이어야 합니다.

### 8. 검열 저항

암호화폐의 진화하는 법적 환경을 고려하여 다음과 같이 설계된 지갑 앱을 찾으십시오.

- 검열에 강하다
- 모든 지역에서 기능적
- 항상 거래 가능

진정한 비수탁형 지갑은 어디에서나 작동해야 하며 항상 거래에 접근할 수 있어야 합니다. 비수탁형 지갑이 해당 지역에서 차단된 경우 개인 키를 다른 비수탁형 지갑 앱으로 마이그레이션할 수 있습니다.