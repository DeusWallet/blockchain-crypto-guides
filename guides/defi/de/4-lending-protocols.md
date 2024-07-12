# Kreditpools

Kreditpools sind DeFi-Dienste, die das Verleihen und Ausleihen von Kryptowährungen ohne Verwahrung ermöglichen.

## Ausleihen

Ausleihdienste ermöglichen es Benutzern, Kryptowährungen von einem Smart Contract auszuleihen, indem sie Sicherheiten in einer anderen Kryptowährung stellen. Dadurch erhalten Kreditnehmer Zugang zu Liquidität, ohne ihre Kryptowährung verkaufen zu müssen. Kreditnehmer können den Kredit jederzeit zurückzahlen, um ihre Sicherheiten zurückzuerhalten.

## Ausleihen

Ausleihdienste ermöglichen es Inhabern von Kryptowährungen, Vermögenswerte an einen Smart Contract auszuleihen und Zinsen zu verdienen. Kreditgeber können ihre Einlagen zusammen mit den aufgelaufenen Zinsen jederzeit abheben.

Normalerweise leihen sich Marktteilnehmer Vermögenswerte von einem Smart Contract, um diese Mittel für Aktivitäten zu verwenden, die höhere Renditen als die Kreditkosten erzielen. Beispielsweise könnte jemand eine Kryptowährung von einem DeFi-Dienst ausleihen und sie an einen anderen Dienst verleihen, der höhere Renditen bietet.

## Besicherte Kredite

- Kreditnehmer müssen eine andere Kryptowährung als Sicherheit stellen, oft deutlich mehr als den geliehenen Betrag.
- Hohe Sicherheiten sind notwendig, um Kreditgeber zu schützen, wenn der Wert der Sicherheiten stark sinkt.
- Wenn der Wert der Sicherheiten unter das erforderliche Niveau fällt, versucht der Smart Contract, die Sicherheiten zu liquidieren, um die verliehenen Vermögenswerte zurückzukaufen.

Kreditnehmer werden dazu angehalten, den Kredit zurückzuzahlen und die Liquidation der Sicherheiten zu verhindern, um den Verlust eines Teils ihrer Sicherheiten zu vermeiden.

## Flash Loans

Flash Loans sind eine Form der Kreditaufnahme in Kryptowährungen, die keine Sicherheiten erfordert.

> Ein Flash Loan ermöglicht es dem Kreditnehmer, Mittel ohne Sicherheiten zu erhalten, sofern er den Kredit innerhalb derselben Transaktion zurückzahlt.

Flash Loans sind derzeit auf Personen mit fundierten Kenntnissen des Ökosystems beschränkt. Im Folgenden finden Sie ein Beispiel für die Nutzung von Flash Loans:

1. Nehmen Sie einen Flash Loan (in TokenX) von einem Smart Contract auf.

2. Tauschen Sie den geliehenen TokenX gegen TokenB auf DEX1.

3. Wandeln Sie TokenB in TokenC auf DEX2 um.

4. Wandeln Sie TokenC in TokenA auf DEX3 um.

5. Zahlen Sie den Flash Loan an den Smart Contract zurück.

Wenn ein Schritt in der Transaktionskette fehlschlägt, werden die vorhergehenden Schritte rückgängig gemacht und die Transaktion schlägt fehl, als ob sie nie stattgefunden hätte.

> Jeder kann Flash Loans verwenden, um so viel wie nötig ohne Sicherheiten zu leihen, vorausgesetzt, das Darlehen wird innerhalb derselben Transaktion zurückgezahlt.

Flash Loans ermöglichen gleichzeitige Finanztransaktionen: Geld leihen, mehrere Arbitrage-Geschäfte über mehrere DeFi-Plattformen hinweg tätigen und den ursprünglichen Kreditgeber zurückzahlen – alles auf einmal.

## 1. Compound

Compound ist ein beliebter dezentraler Dienst zum Leihen und Verleihen von Kryptowährungen.

[Compound Finance](https://compound.finance/markets)-Kredite erfordern normalerweise Sicherheiten, die zwischen 0 und 90 % des geliehenen Vermögenswerts liegen können. Jeder Vermögenswert auf Compound hat eine andere Sicherheitenanforderung.

Lesen Sie: [Compound in einfachen Worten](../../token_guides/de/compound.md)

## 2. Aave

[Aave](https://app.aave.com/home) bietet Zugang zu besicherten und unbesicherten Flash-Darlehen.

Flash-Darlehen stammen aus einem Liquiditätspool, der von anderen Benutzern finanziert wird. Aave erhebt eine Gebühr von 0,09 % auf Flash-Darlehen. Für besicherte Darlehen wird bei der Kreditvergabe eine Gebühr von 0,01 % des Darlehensbetrags erhoben.

Lesen Sie: [Aave in einfachen Worten](../../token_guides/de/aave.md)

## 3. Oasis

[Oasis](https://oasis.app/) ist ein von MakerDAO entwickelter DEX, der das Verleihen und Ausleihen der DAI-Stablecoin erleichtert.

- Benutzer können DAI von MakerDAO-Smart Contracts leihen, die neue DAI im Austausch gegen eine Kryptowährungssicherheit (normalerweise 150 % des Kreditwerts) erstellen.
- Wenn DAI-Token zurückgegeben werden, wird die Sicherheit an den Kreditnehmer zurückgezahlt und die zurückgegebenen DAI-Token werden vom Smart Contract vernichtet.

Lesen Sie: [MakerDAO in einfachen Worten](../../token_guides/de/makerdao.md)

## Risiken

Wie bei anderen DeFi-Diensten besteht immer das Risiko eines Hacks oder Exploits, der den Liquiditätspool des Kreditdienstes erschöpfen und dazu führen könnte, dass Kreditgeber ihre Vermögenswerte verlieren. Daher sollten Kreditgeber nur Gelder bereitstellen, deren Verlust sie sich leisten können.