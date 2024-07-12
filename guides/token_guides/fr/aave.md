# Aave en termes simples

[Aave](https://app.aave.com/) est un service décentralisé et non dépositaire sur la blockchain Ethereum qui permet aux utilisateurs de prêter et d'emprunter des actifs de crypto-monnaie basés sur Ethereum. Lancé en janvier 2020, Aave s’est rapidement développé, attirant près de 2 milliards de dollars de crypto-monnaie en seulement huit mois.

## Comment fonctionne Aave

- **Déposants** : les utilisateurs fournissent des liquidités en déposant leurs crypto-monnaies dans des pools de prêt décentralisés, gagnant des intérêts en retour.
- **Emprunteurs** : les utilisateurs peuvent emprunter à ces pools de prêts en payant des frais.
- **Fonctionnalité unique** : contrairement à d'autres services comme [Compound](../../token_guides/fr/compound.md) ou [MakerDAO](../../token_guides/fr/makerdao.md), Aave permet d'emprunter sans garantie.
- **Taux d'intérêt** : généralement plus élevés que ceux des autres plateformes.
- **Sécurité** : les contrats intelligents d'Aave sont non dépositaires et décentralisés, ce qui signifie que l'équipe Aave ne peut pas accéder aux fonds des utilisateurs.

## Actifs pris en charge

Depuis septembre 2020, Aave prend en charge le prêt et l’emprunt de 20 jetons de crypto-monnaie différents basés sur Ethereum :

- [Pièce USD (USDC)](https://app.aave.com/reserve-overview/USDC?pool=Aave)
- [Tether (USDT)](https://app.aave.com/reserve-overview/USDT?pool=Aave)
- [Vrai USD (TUSD)](https://app.aave.com/reserve-overview/TUSD?pool=Aave)
- [Dai (DAI)](https://app.aave.com/reserve-overview/DAI?pool=Aave)
- [sUSD](https://app.aave.com/reserve-overview/SUSD?pool=Aave)
- [Binance (BUSD)](https://app.aave.com/reserve-overview/BUSD?pool=Aave)
- [Ethereum (ETH)](https://app.aave.com/reserve-overview/ETH?pool=Aave)
- [ETHLend (LEND)](https://app.aave.com/reserve-overview/LEND?pool=Aave)
- [YFI](https://app.aave.com/reserve-overview/YFI?pool=Aave)
- [Jeton d'attention de base (BAT)](https://app.aave.com/reserve-overview/BAT?pool=Aave)
- [EnjinCoin (ENJ)](https://app.aave.com/reserve-overview/ENJ?pool=Aave)
- [REN](https://app.aave.com/reserve-overview/REN?pool=Aave)
- [Réseau Kyber (KNC)](https://app.aave.com/reserve-overview/KNC?pool=Aave)
- [ChainLink (LIEN)](https://app.aave.com/reserve-overview/LINK?pool=Aave)
- [Decentraland (MANA)](https://app.aave.com/reserve-overview/MANA?pool=Aave)
- [Maker (MKR)](https://app.aave.com/reserve-overview/MKR?pool=Aave)
- [Augur (REP)](https://app.aave.com/reserve-overview/REP?pool=Aave)
- [Synthetix (SNX)](https://app.aave.com/reserve-overview/SNX?pool=Aave)
- [Pièce WBTC (wBTC)](https://app.aave.com/reserve-overview/WBTC?pool=Aave)
- [0x (ZRX)](https://app.aave.com/reserve-overview/ZRX?pool=Aave)

Chaque actif a des exigences spécifiques en matière d’emprunt et de prêt. Le contrôle des crypto-monnaies prises en charge sera éventuellement transféré aux détenteurs de jetons Aave.

## Prêts sur Aave

- **Gagner des intérêts** : les prêteurs gagnent des intérêts sur les actifs déposés.
- **Sécurité** : les dépôts sont garantis par les garanties fournies par les emprunteurs.
- **aTokens** : les prêteurs reçoivent des aTokens, qui rapportent des intérêts et peuvent être utilisés pour retirer des dépôts ainsi que des revenus. Les aTokens sont rattachés à 1:1 à l'actif sous-jacent.

## Emprunter sur Aave

- **Exigences en matière de garantie** : L'emprunt nécessite une garantie sous la forme d'une autre crypto-monnaie.
- **Ratio prêt/valeur (LTV)** : représente le pouvoir d'emprunt maximum (par exemple, 75 % du LTV signifie emprunter jusqu'à 75 % de la valeur de la garantie).
- **Taux d'intérêt** : les emprunteurs peuvent choisir entre des taux fixes ou variables.
- **Maintien de la garantie** : les emprunteurs doivent s'assurer que la valeur de la garantie reste supérieure au minimum requis pour éviter la liquidation.

## Prêts Flash

Les prêts flash sont uniques à Aave, permettant aux utilisateurs d'emprunter sans garantie :

- **Mécanisme** : empruntez des actifs en une seule transaction et restituez-les avant la fin de la transaction.
- **Frais** : Des frais de 0,09 % sont facturés sur les prêts flash.

Les prêts flash sont principalement utilisés par les programmeurs pour des activités telles que l'arbitrage et le refinancement.

## Gouvernance Aave

Aave vise à devenir une organisation autonome décentralisée (DAO) entièrement gérée par la communauté :

- **Jeton AAVE** : utilisé pour voter sur les améliorations du protocole et les décisions de gouvernance.
- **Incentives** : les détenteurs de jetons AAVE reçoivent des récompenses et peuvent participer à la gouvernance.
- **Fonds d'urgence** : protège les actifs des prêteurs en cas d'événements inattendus.
- **Jeton déflationniste** : Une partie des frais est utilisée pour racheter et graver des jetons AAVE.

## Présentation d'Aave 2.0

Aave 2.0, annoncé le 14 août 2020, introduit plusieurs nouvelles fonctionnalités :

- **Payer avec garantie** : simplifie les transactions de remboursement de prêt.
- **Taux fixes** : offre une prévisibilité des taux de prêt et d'emprunt.
- **Coûts de transaction inférieurs** : réduit les coûts des interactions avec la plateforme.
- **Fonctionnalités de trading** : permet aux utilisateurs d'échanger des positions de dette et des actifs déposés dans les crypto-monnaies prises en charge.

## Des risques

Comme pour tout service DeFi, il existe des risques associés aux bugs des contrats intelligents. Aave a fait auditer ses contrats et propose un programme de bug bounty permettant aux membres de la communauté de signaler les vulnérabilités.

## Liens utiles

- [Portail Aave officiel](https://app.aave.com/)
- [Blog officiel d'Aave](https://medium.com/aave)
- [Documents portail de tion](https://docs.aave.com/portal/)
- [Portail de gouvernance](https://governance.aave.com)