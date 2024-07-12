# Balancer in einfachen Worten

[Balancer](https://balancer.exchange/) ist eine dezentrale Börse (DEX), die im März 2020 gestartet wurde. Sie begann Anfang 2018 als Forschungsprojekt von [BlockScience](https://block.science/). Das Balancer-Team entwickelte ein mathematisches Framework, das es jedem Portfolio ermöglicht, sich kontinuierlich selbst auszugleichen und gleichzeitig Gebühren zu generieren, das sogenannte Balancer-Protokoll. Der Ethereum-Token, der dieses Protokoll antreibt, ist BAL.

## Handel auf Balancer

Aus der Sicht eines Händlers ist Balancer eine Plattform zum dezentralen Austausch von Ethereum- und ERC20-Token.

- **Effizienter Handel**: Balancer durchsucht alle verfügbaren Pools nach den angeforderten Token und verteilt Aufträge auf die effizientesten Pools, um die besten Preise zu erzielen.
- **Variable Gebühren**: Die Handelsgebühren unterscheiden sich zwischen den Pools und hängen von den beteiligten Token und Liquiditätspools ab.
- **Slippage**: Größere Aufträge im Verhältnis zur verfügbaren Liquidität führen zu höherem Slippage.
- **Anreize**: Balancer fördert niedrige Gebühren, indem es BAL-Token an Liquiditätsanbieter verteilt.

## Bereitstellung von Liquidität

Wie Uniswap und Curve ermöglicht Balancer Benutzern, Gebühren für ihre ungenutzten Ethereum-basierten Vermögenswerte zu verdienen. Es bietet flexiblere Möglichkeiten durch verschiedene Arten von Liquiditätspools.

- **Liquiditätspools**: Benutzer können einen neuen Pool erstellen oder Vermögenswerte zu vorhandenen Pools hinzufügen.
- **Poolzusammensetzung**: Jeder Pool kann 2-8 Vermögenswerte enthalten, wobei ein bestimmtes Verhältnis zwischen ihnen eingehalten wird.
- **Automatischer Ausgleich**: Pools gleichen sich selbst aus, um die erforderlichen Verhältnisse einzuhalten.
- **Flexible Einzahlungen**: Im Gegensatz zu Uniswap ermöglicht Balancer Einzahlungen in jeden vom Pool unterstützten Vermögenswert.
- **Pool-Eigentumstoken**: Anbieter erhalten ERC-20-Token, die ihren Anteil am Pool darstellen und zum Abheben von Liquidität verwendet werden können.
- **Transaktionsgebühren**: Jeder Pool legt seine eigenen Gebühren fest, wobei niedrigere Gebühren mehr BAL-Token einbringen.

## Pooltypen

1. **Gemeinsame Pools**:
- Feste Token, Gewichte und Gebühren, die bei der Erstellung festgelegt werden.
- Keine Sonderrechte für den Ersteller.
- Jeder kann Liquidität hinzufügen, und der Besitz wird mit Balancer Pool Tokens (BPT) verfolgt.

2. **Private Pools**:
- Vollständige Kontrolle über Parameter für den Ersteller (z. B. akzeptierte Token, Gewichte, Gebühren).
- Nur der Ersteller kann Liquidität bereitstellen.
- Nützlich für verwaltete Indexfonds.

3. **Smart Pools**:
- Im Besitz eines Smart Contracts, nicht einer Person.
- Akzeptieren Sie Liquidität von jedem mit flexiblen Parameteränderungen.
- Besitz wird durch ERC-20-Token verfolgt.

## Indexfonds

Balancer ermöglicht es Benutzern, persönliche Indexfonds ohne komplexes Rebalancing einzurichten.

- **Selbstausgleichende Pools**: Anleger können Vermögenswerte für langfristige Investitionen in automatisch ausgleichende Pools gruppieren und Gebühren verdienen, wenn andere gegen ihr Portfolio handeln.
- **Benutzerdefinierte Indexfonds**: Benutzer können selbstausgleichende Indexfonds erstellen oder in diese investieren.

- **Verschachtelte Pools**: Pools können aus anderen Balancer-Pools bestehen.

- **Erlaubnisfrei**: Pools können nach der Aktivierung nicht zensiert oder geändert werden.

## Balancer-Token

Der BAL-Token, der seit dem 1. Juni 2020 an Liquiditätsanbieter verteilt wird, dient auch als Governance-Token für das Protokoll.

- **Gesamtangebot**: 100 Millionen BAL-Token.

- **Verteilung**: 25 Millionen an Gründer, Entwickler, Berater und Investoren; 75 Millionen an Liquiditätsanbieter.

Einzelheiten zum Governance-Modell und zur Token-Verteilung finden Sie [hier](https://balancer.finance/2020/05/15/proposing-balancer-liquidity-mining/).

## Nützliche Links

- [Projekt-Whitepaper](https://balancer.finance/whitepaper/)
- [Offizieller Blog](https://balancer.finance/blog-feed/)
- [Balancer Pool Management](https://pools.balancer.exchange/#/)