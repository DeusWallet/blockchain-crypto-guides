# 개인 키

앞서 다루었듯이 정품 암호화폐 지갑은 일정량의 암호화폐를 제어하는 ​​암호화 키를 저장합니다. 이 암호화 키를 통해 지갑 앱은 사용자가 소유한 암호화폐의 양을 확인하고 지갑과 관련된 과거 거래를 파생할 수 있습니다. 이 암호화 키를 일반적으로 개인 키라고 합니다.

> **지갑 앱은 기본적으로 개인 키를 저장하므로 일정량의 암호화폐를 제어할 수 있습니다.**
>
> **비수탁형 지갑 앱은 개인 키를 사용하여 블록체인에서 암호화폐 잔액과 과거 거래를 검색합니다.**

우리는 개인 키의 기술적 작동을 탐구하지 않을 것입니다. 개인 키는 앞서 논의한 암호화 키를 의미한다는 점만 알아두세요. 개인 키의 보안 측면과 관련 고려 사항을 살펴보겠습니다.

## 1. 키를 비공개로 유지하세요

사기꾼은 종종 지갑 지원 팀을 사칭하여 사용자를 속여 개인 키를 공유하도록 합니다. 키를 공유하면 사기꾼이 귀하의 자금을 훔칠 수 있습니다.

> **개인 키를 누구와도 공유할 타당한 이유가 전혀 없습니다. 이는 모든 지갑에 적용됩니다.**
>
> **지갑 앱을 만든 사람들과 대화할 때에도 개인 키를 절대 공개하지 마세요.**

귀하의 자금 소유권을 의도적으로 다른 사람에게 양도하려는 경우에만 개인 키를 공개할 수 있습니다. 거의 모든 비수탁형 지갑은 앱 내에서 개인 키에 액세스하고 볼 수 있는 방법을 제공합니다.

## 2. 개인 키를 백업하세요

대부분의 비수탁 지갑 앱은 설정 중에 개인 키를 표시하고 사용자에게 이를 적어서 오프라인으로 안전하게 저장하라는 메시지를 표시합니다.

> **개인 키는 지갑 앱이 설치된 기기가 도난당하거나 작동이 중단되는 등의 이유로 기기에 접근할 수 없는 경우 지갑에 대한 액세스를 복원할 수 있는 유일한 방법입니다.**

개인 키 백업을 단순화하기 위해 블록체인 엔지니어는 이를 12~24개의 일반 단어 집합으로 변환하는 방법을 고안했습니다. 대부분의 비수탁 지갑은 사람이 읽을 수 있는 형식으로 개인 키를 표시합니다.

개인 키를 주의 깊게 백업하여 오타가 없도록 하세요. 단어의 올바른 순서가 중요합니다.

> **개인 키를 분실하거나 노출하는 경우 다른 사람이 귀하의 암호화폐를 통제할 수 있습니다.**

비수탁 지갑은 오타가 있는 경우 경고를 표시할 수 있지만 잘못된 단어 순서로 인해 귀하의 지갑이 아닌 다른 무작위 지갑이 복원됩니다.

## 3. 개인 키 생성

비수탁 지갑을 설정하면 앱이 무작위로 안전한 개인 키를 생성합니다. 키가 진정으로 안전하려면 무작위여야 합니다.

> **비수탁형 지갑이 진정한 무작위 키를 생성하지 않으면 안전하지 않습니다.**

이것이 비수탁 지갑이 제3자의 조사를 위해 코드를 공개해 두는 이유입니다. [WalletScrutiny.com](https://walletscrutiny.com)과 같은 웹사이트에서는 Google Play의 지갑이 공개적으로 공유되는 버전과 동일한 코드를 사용하는지 확인합니다.

좋은 비수탁형 지갑은 공개적으로 문서화된 보안 지침과 지갑 표준을 준수해야 합니다.

## 4. 하나의 열쇠, 많은 동전

단일 개인 키로 여러 암호화폐의 잔액을 제어할 수 있습니다. 지갑 앱은 하나의 키를 사용하여 지원되는 모든 암호화폐의 잔액을 자동으로 찾을 수 있습니다.

예를 들어, [Deus Wallet](https://deuswallet.com)에서 지갑을 생성하면 사용자는 지원되는 모든 암호화폐에 대해 단일 개인 키를 얻게 됩니다.

동일한 개인 키는 각각 자체 잔액과 거래가 있는 여러 암호화폐를 제어합니다.

## 5. 잔액 및 거래

여러 암호화폐에 대한 개인 키를 처리하기 위해 엔지니어가 설계한 표준이 있습니다. 이러한 표준은 지갑 앱이 개인 키를 관리하는 방법을 정의합니다.

> **지갑은 개인 키를 사용하여 각 암호화폐에 대한 지불 주소를 알아냅니다. 결제 주소는 암호화폐를 받기 위해 다른 사람과 공유하는 주소입니다.**

개인 키를 보면 지갑 앱이 비트코인, 이더리움 및 기타 암호화폐에 대한 주소를 알아낼 수 있습니다. 암호화폐마다 주소가 다릅니다.

개인 키를 다른 표준 호환 지갑으로 가져오면 동일한 주소가 파생됩니다.

> **개인 키가 표준 준수 방식으로 생성된 경우 다른 표준 준수 지갑은 지원되는 각 암호화폐에 대한 지불 주소와 과거 거래를 올바르게 파생해야 합니다.**

앱이 주소를 알게 되면 관련 블록체인에 연결하여 해당 주소와 관련된 거래를 검색하고 잔액과 과거 거래를 표시합니다.

## 6. 지갑 간 이동

좋은 비수탁 지갑은 지갑 간 개인 키 마이그레이션을 허용합니다. 하나의 비수탁 지갑 앱에서 생성된 개인 키는 다른 앱과 호환되어야 합니다.

> **사용자는 단일 지갑 제공업체로 제한되어서는 안 되며 다른 비수탁 지갑 앱으로 쉽게 마이그레이션할 수 있어야 합니다.**

휴대폰이 고장나거나 지갑 앱이 작동하지 않더라도 자금은 안전합니다. 몇 년이 지난 후에도 개인 키를 사용하여 암호화폐에 대한 액세스를 복원할 수 있습니다.

지갑을 선택할 때 표준을 준수하고 개인 키 가져오기/내보내기를 지원하는 지갑을 찾으세요.

> **아니요 te: 개인 키를 마이그레이션할 때 대상 지갑은 해당 키로 제어되는 모든 암호화폐를 지원해야 합니다.**

개인 키에 비트코인과 이더리움 잔액이 있지만 대상 지갑이 비트코인만 지원하는 경우 이더리움 잔액이 표시되지 않습니다. 이는 여전히 귀하의 것이며 다른 지갑에서 접근할 수 있습니다.