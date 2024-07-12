# Synthetix expliqué simplement

[Synthetix](https://synthetix.io/) est une plateforme décentralisée sur Ethereum pour le trading d'actifs synthétiques, connue sous le nom de Synths.

> Les synthés sont des jetons ERC-20 représentant des crypto-monnaies, des actions, des monnaies fiduciaires, des métaux précieux et d'autres actifs négociables.

Ces synthés sont conçus pour refléter le prix de l'actif qu'ils représentent, mais sans aucune de ses autres caractéristiques.

Par exemple, sBTC est un jeton Bitcoin synthétique qui peut être échangé sur Synthetix au prix Bitcoin actuel.

De même, un token sMKR a le même prix qu'un token [MKR](../../token_guides/fr/makerdao.md) réel, mais n'inclut pas les droits de vote.

- Posséder des jetons de synthèse offre la même exposition au prix que posséder les jetons réels qu'ils représentent.
- Les utilisateurs peuvent spéculer sur les mouvements de prix de divers instruments financiers sans détenir l'actif réel.
- Les actifs Synth peuvent être transférés entre utilisateurs et échangés sur des bourses décentralisées.

En résumé, Synthetix permet la création de jetons ERC-20 basés sur Ethereum qui représentent des actifs du monde réel.

> Tout actif avec un flux de prix peut potentiellement être ajouté à Synthetix en tant qu'actif de synthèse.

Actuellement, les actifs synthétiques disponibles comprennent les crypto-monnaies, les actions et les métaux précieux. Synthetix vise à élargir son offre pour inclure davantage d'actifs que l'on trouve couramment sur les marchés traditionnels, tels que les actions.

## Synthés pris en charge

La plate-forme Synthetix prend actuellement en charge environ deux douzaines de synthés différents, avec un potentiel pour bien d'autres.

> Tout actif ayant un prix de marché peut être ajouté à Synthetix, à condition qu'il y ait un flux de prix et l'approbation de la communauté.

Actuellement, il existe deux types d'actifs de synthétiseur :

1. **Synthés standards**

 Ceux-ci suivent le prix de l’actif qu’ils représentent, ce qui convient à ceux qui cherchent à investir longtemps sur ces actifs.
 - sUSD : USD synthétique
 - sEUR : EUR synthétique
 - sAUD : dollar australien synthétique
 - sBTC : Bitcoin synthétique
 - sETH : Ether synthétique
 - sMKR : Créateur synthétique
 - sBNB : BNB synthétique
 - sXTZ : Tezos synthétiques
 - sADA : Cardano synthétique
 - sXRP : Ripple synthétique
 - sLTC : Litecoin synthétique
 - sBCH : Bitcoin Cash synthétique
 - sXAU : once d'or synthétique
 - sXAG : once d'argent synthétique
 - sDEFI : Indice synthétique DEFI
 - sLINK : Chainlink synthétique

2. **Synthés inverses**

 Ceux-ci permettent aux utilisateurs de vendre à découvert le prix d’un actif, profitant inversement de la dépréciation du prix.
 - iBTC : Bitcoin inversé
 - iETH : Ethereum inverse
 - iBNB : Binance inversée
 - iXTZ : Tezos inversés
 - iADA : Cardano inversé
 - iXRP : ondulation inversée
 - iLTC : Litecoin inversé
 - iBCH : Bitcoin Cash inversé
 - iDEFI : indice DEFI inversé
 - iLINK : Chainlink inversé

Les synthés sont négociés 24h/24 et 7j/7 sur le [Synthetix.Exchange](https://synthetix.exchange) non dépositaire, permettant à toute personne de l'[écosystème Ethereum](../../token_guides/fr/ethereum.md) de prendre des positions longues ou courtes sur divers actifs.

## Comment les synthés sont créés

Pour comprendre Synthetix, il est important de savoir comment les nouveaux synthés sont créés et retirés de la circulation.

1. Synthetix permet aux utilisateurs de créer des jetons sUSD (USD synthétiques) en [verrouillant](https://mintr.synthetix.io/) leurs jetons SNX dans un contrat intelligent avec un taux de garantie de 600 %.
2. Pour créer 1 000 jetons sUSD, un utilisateur doit verrouiller au moins 6 000 $ de jetons SNX. Ces jetons sont restitués lorsque l'utilisateur rembourse le montant emprunté.
3. Une fois créés, les jetons sUSD peuvent être échangés sur la bourse Synthetix contre d'autres actifs de synthèse aux prix actuels du marché.
4. Les ordres sur la bourse Synthetix sont instantanés et exécutés aux prix du marché.
5. Les traders négocient toujours contre la bourse, ce qui détruit l'actif reçu de l'utilisateur et crée l'actif acheté par l'utilisateur.
6. Par exemple, acheter du sBTC alors que Bitcoin coûte 10 000 $ implique de détruire 10 000 sUSD et de créer 1 sBTC.

Ce processus garantit que chaque actif de synthétiseur est soutenu par des jetons SNX.

Les spéculateurs peuvent également acheter des sUSD ou des sETH existants sur un [échange décentralisé](../../defi/fr/3-decentralized-exchanges.md) comme [Uniswap](../../token_guides/fr/uniswap. md) en utilisant ETH.

## Comment les synthés sont échangés

L'écosystème Synthetix comprend son propre échange décentralisé, [Synthetix.Exchange](https://synthetix.exchange), pour échanger des synthés.

- Contrairement à d'autres bourses décentralisées, Synthetix.Exchange ne nécessite pas de mécanismes d'appariement de liquidité comme les carnets de commandes ou les [pools de liquidité](../../defi/fr/3-decentralized-exchanges.md).
- Tous les ordres sont garantis d'être exécutés aux prix du marché en quelques secondes.
- Les frais de négociation varient de 0,1 % à 1 % (généralement 0,3 %) et vont à ceux qui créent des jetons sUSD en verrouillant leurs jetons SNX comme garantie.

Le trading sur Synthetix.Exchange est souvent moins cher, en particulier pour les commandes importantes, ce qui constitue une incitation économique à l'utiliser par rapport à d'autres échanges décentralisés comme [Uniswap](../../token_guides/fr/uniswap.md) ou [Curve](. ./../token_guides/fr/curve-finance.md).

## Pourquoi créer des synthés ?

Le trading de synthés est moins cher et offre une exposition à n’importe quel actif négociable dans le monde, le tout sur la blockchain Ethereum. Cela crée une forte g des incitations pour les spéculateurs à échanger des synthés plutôt que des actifs réels.

Le taux de garantie de 600 % protège la stabilité des actifs synthétisés contre les fluctuations des prix du SNX.

Ceux qui verrouillent leur SNX sur la plateforme pour créer de nouveaux synthés reçoivent deux types de récompenses :
1. **SNX Staking Rewards** : Créé grâce à la politique monétaire inflationniste de SNX. Entre mars 2019 et août 2023, l'offre totale de SNX passera de 100 millions à 260,3 millions, avec un taux de décroissance hebdomadaire de 1,25 %.
2. **Frais d'échange** : les frais de trading de synthés sur [Synthetix.Exchange](https://synthetix.exchange/#/) sont versés à un pool de frais, que les joueurs de SNX peuvent réclamer chaque semaine.

Les intervenants SNX créent une position de dette lorsqu'ils verrouillent leurs jetons. Cette dette commence par le montant de sUSD émis et change en fonction des mouvements de prix de tous les autres actifs synthétiques.

- Si le prix de tous les synthés était sBTC et BTC réduit de moitié, la dette totale diminuerait de moitié, et la dette de chaque acteur diminuerait également de moitié.
- À l'inverse, si seulement 50 % du prix du sBTC et du BTC doublait, la dette de chaque intervenant augmenterait d'un quart.

De cette manière, les intervenants de SNX agissent comme une contrepartie commune à tous les échanges de synthés, supportant le risque de la dette globale du système.

## Statistiques Synthetix

Pour les statistiques actuelles sur la plateforme Synthetix, y compris le montant des fonds bloqués et le nombre de synthés en circulation, visitez l'aperçu de Synthetix sur [DeFi Pulse](https://dashboard.synthetix.io).

Au 9 septembre 2020 :
- Total bloqué (en USD) : 650,2 millions de dollars
- Total verrouillé (en ETH) : 1,9 M ETH
- Total verrouillé (en BTC) : 63,3K BTC
- Total verrouillé (en SNX) : 141M SNX
- % de l'approvisionnement SNX bloqué : 70,36 %