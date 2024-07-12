# Synthetix einfach erklärt

[Synthetix](https://synthetix.io/) ist eine dezentrale Plattform auf Ethereum für den Handel mit synthetischen Vermögenswerten, die als Synths bezeichnet werden.

> Synths sind ERC-20-Token, die Kryptowährungen, Aktien, Fiat-Währungen, Edelmetalle und andere handelbare Vermögenswerte repräsentieren.

Diese Synths sind so konzipiert, dass sie den Preis des Vermögenswerts widerspiegeln, den sie repräsentieren, jedoch ohne dessen andere Eigenschaften.

Beispielsweise ist sBTC ein synthetischer Bitcoin-Token, der auf Synthetix zum aktuellen Bitcoin-Preis gehandelt werden kann.

Ebenso hat ein sMKR-Token denselben Preis wie ein echter [MKR](../../token_guides/de/makerdao.md)-Token, beinhaltet jedoch keine Stimmrechte.

- Der Besitz von Synth-Token bietet die gleiche Preisexposition wie der Besitz der tatsächlichen Token, die sie repräsentieren.
- Benutzer können über die Preisbewegungen verschiedener Finanzinstrumente spekulieren, ohne den tatsächlichen Vermögenswert zu besitzen.
- Synth-Assets können zwischen Benutzern übertragen und an dezentralen Börsen gehandelt werden.

Zusammenfassend ermöglicht Synthetix die Erstellung von Ethereum-basierten ERC-20-Token, die reale Assets darstellen.

> Jedes Asset mit einem Preis-Feed kann potenziell als Synth-Asset zu Synthetix hinzugefügt werden.

Zurzeit sind unter anderem Kryptowährungen, Aktien und Edelmetalle verfügbar. Synthetix beabsichtigt, sein Angebot um weitere Assets zu erweitern, die üblicherweise auf traditionellen Märkten zu finden sind, wie z. B. Aktien.

## Unterstützte Synths

Die Synthetix-Plattform unterstützt derzeit rund zwei Dutzend verschiedene Synths, mit Potenzial für viele weitere.

> Jedes Asset mit einem Marktpreis kann zu Synthetix hinzugefügt werden, solange ein Preis-Feed und die Zustimmung der Community vorhanden sind.

Zurzeit gibt es zwei Arten von Synth-Assets:

1. **Standard-Synths**

Diese verfolgen den Preis des Assets, das sie darstellen, und eignen sich für diejenigen, die bei den Assets Long-Positionen eingehen möchten.
- sUSD: synthetischer USD
- sEUR: synthetischer EUR
- sAUD: synthetischer AUS-Dollar
- sBTC: synthetischer Bitcoin
- sETH: synthetischer Ether
- sMKR: synthetischer Maker
- sBNB: synthetischer BNB
- sXTZ: synthetischer Tezos
- sADA: synthetischer Cardano
- sXRP: synthetischer Ripple
- sLTC: synthetischer Litecoin
- sBCH: synthetischer Bitcoin Cash
- sXAU: synthetische Goldunze
- sXAG: synthetische Silberunze
- sDEFI: synthetischer DEFI-Index
- sLINK: synthetischer Chainlink

2. **Inverse Synths**

Diese ermöglichen es Benutzern, den Preis eines Vermögenswerts zu shorten und umgekehrt von der Preisabwertung zu profitieren.
- iBTC: inverses Bitcoin
- iETH: inverses Ethereum
- iBNB: inverses Binance
- iXTZ: inverses Tezos
- iADA: inverses Cardano
- iXRP: inverses Ripple
- iLTC: inverses Litecoin
- iBCH: inverses Bitcoin Cash
- iDEFI: inverses DEFI Index
- iLINK: inverses Chainlink

Synths werden rund um die Uhr auf der nicht verwahrten [Synthetix.Exchange](https://synthetix.exchange) gehandelt, sodass jeder im [Ethereum-Ökosystem](../../token_guides/de/ethereum.md) bei verschiedenen Vermögenswerten Long- oder Short-Positionen eingehen kann.

## Wie Synths erstellt werden

Um Synthetix zu verstehen, ist es wichtig zu wissen, wie neue Synths erstellt und aus dem Verkehr gezogen werden.

1. Synthetix ermöglicht es Benutzern, sUSD-Token (synthetische USD) zu erstellen, indem sie ihre SNX-Token mit einer Besicherungsquote von 600 % in einen Smart Contract [sperren](https://mintr.synthetix.io/).
2. Um 1000 sUSD-Token zu erstellen, muss ein Benutzer SNX-Token im Wert von mindestens 6000 USD sperren. Diese Token werden zurückgegeben, wenn der Benutzer den geliehenen Betrag zurückzahlt.
3. Nach der Erstellung können sUSD-Token an der Synthetix-Börse zu aktuellen Marktpreisen gegen andere Synth-Assets gehandelt werden.
4. Aufträge an der Synthetix-Börse erfolgen sofort und werden zu Marktpreisen ausgeführt.
5. Händler handeln immer gegen die Börse, wodurch das vom Benutzer erhaltene Asset zerstört und das vom Benutzer gekaufte Asset erstellt wird.
6. Wenn Sie beispielsweise sBTC kaufen, wenn Bitcoin 10.000 USD wert ist, werden 10.000 sUSD zerstört und 1 sBTC erstellt.

Dieser Prozess stellt sicher, dass jedes Synth-Asset durch SNX-Token gedeckt ist.

Spekulanten können auch bestehende sUSD oder sETH an einer [dezentralen Börse](../../defi/de/3-decentralized-exchanges.md) wie [Uniswap](../../token_guides/de/uniswap.md) mit ETH kaufen.

## Wie Synths gehandelt werden

Das Synthetix-Ökosystem umfasst eine eigene dezentrale Börse, [Synthetix.Exchange](https://synthetix.exchange), für den Handel mit Synths.

- Im Gegensatz zu anderen dezentralen Börsen erfordert Synthetix.Exchange keine Liquiditätsabgleichmechanismen wie Auftragsbücher oder [Liquiditätspools](../../defi/de/3-decentralized-exchanges.md).
- Alle Aufträge werden garantiert innerhalb von Sekunden zu Marktpreisen ausgeführt.
- Die Handelsgebühren liegen zwischen 0,1 % und 1 % (normalerweise 0,3 %) und gehen an diejenigen, die sUSD-Token erstellen, indem sie ihre SNX-Token als Sicherheit sperren.

Der Handel auf Synthetix.Exchange ist oft günstiger, insbesondere bei großen Aufträgen, was einen wirtschaftlichen Anreiz bietet, es gegenüber anderen dezentralen Börsen wie [Uniswap](../../token_guides/de/uniswap.md) oder [Curve](../../token_guides/de/curve-finance.md) zu verwenden.

## Warum Synths erstellen?

Der Handel mit Synths ist günstiger und bietet Zugang zu jedem handelbaren Vermögenswert der Welt, alles auf der Ethereum-Blockchain. Dies schafft starkeg Anreize für Spekulanten, Synths statt der eigentlichen Vermögenswerte zu handeln.

Die Besicherungsquote von 600 % schützt die Stabilität der Synth-Vermögenswerte vor SNX-Preisschwankungen.

Diejenigen, die ihre SNX in der Plattform sperren, um neue Synths zu erstellen, erhalten zwei Arten von Belohnungen:
1. **SNX-Staking-Belohnungen**: Entstanden durch die inflationäre Geldpolitik von SNX. Zwischen März 2019 und August 2023 wird das gesamte SNX-Angebot von 100 Millionen auf 260,3 Millionen steigen, mit einer wöchentlichen Verfallsrate von 1,25 %.
2. **Börsengebühren**: Gebühren aus dem Handel mit Synths auf [Synthetix.Exchange](https://synthetix.exchange/#/) gehen in einen Gebührenpool, der für SNX-Staker wöchentlich zur Verfügung steht.

SNX-Staker schaffen eine Schuldenposition, wenn sie ihre Token sperren. Diese Schulden beginnen mit der Menge der geprägten sUSD und ändern sich basierend auf den Preisbewegungen aller anderen Synth-Assets.

- Wenn alle Synths sBTC wären und der BTC-Preis halbiert würde, würde sich die Gesamtschuld halbieren und auch die Schulden jedes Stakers würden sich halbieren.
- Umgekehrt würden sich die Schulden jedes Stakers um ein Viertel erhöhen, wenn nur 50 % sBTC wären und der BTC-Preis verdoppelt würde.

Auf diese Weise fungieren SNX-Staker als gepoolte Gegenpartei für alle Synth-Börsen und tragen das Risiko der Gesamtsystemschuld.

## Synthetix-Statistiken

Aktuelle Statistiken zur Synthetix-Plattform, einschließlich der Höhe der gesperrten Mittel und der Anzahl der im Umlauf befindlichen Synths, finden Sie in der Synthetix-Übersicht auf [DeFi Pulse](https://dashboard.synthetix.io).

Stand 9. September 2020:
- Gesamt gesperrt (in USD): 650,2 Mio. $
- Gesamt gesperrt (in ETH): 1,9 Mio. ETH
- Gesamt gesperrt (in BTC): 63,3 Tsd. BTC
- Gesamt gesperrt (in SNX): 141 Mio. SNX
- % des gesperrten SNX-Angebots: 70,36 %