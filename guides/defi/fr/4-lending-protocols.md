# Pools de prêts

Les pools de prêt sont des services DeFi qui facilitent les prêts et emprunts de cryptomonnaies sans dépôt.

## Emprunt

Les services d’emprunt permettent aux utilisateurs d’emprunter de la cryptomonnaie à partir d’un contrat intelligent en fournissant une garantie dans une autre cryptomonnaie. Cela permet aux emprunteurs d’accéder à des liquidités sans vendre leur cryptomonnaie. Les emprunteurs peuvent rembourser le prêt à tout moment pour récupérer leur garantie.

## Prêts

Les services de prêt permettent aux détenteurs de crypto-monnaie de prêter des actifs à un contrat intelligent et de gagner des intérêts. Les prêteurs peuvent retirer leurs dépôts ainsi que les intérêts courus à tout moment.

En règle générale, les acteurs du marché empruntent des actifs à un contrat intelligent pour utiliser ces fonds dans des activités qui génèrent des rendements supérieurs au coût d'emprunt. Par exemple, quelqu’un peut emprunter une crypto-monnaie à un service DeFi et la prêter à un autre service offrant des rendements plus élevés.

## Prêts garantis

- Les emprunteurs doivent fournir une autre cryptomonnaie en garantie, souvent bien plus que le montant emprunté.
- Des garanties élevées sont nécessaires pour protéger les prêteurs si la valeur de la garantie chute fortement.
- Si la valeur de la garantie tombe en dessous du niveau requis, le contrat intelligent tentera de liquider la garantie pour racheter les actifs prêtés.

Les emprunteurs sont incités à rembourser le prêt et à empêcher la liquidation des garanties pour éviter de perdre une partie de leurs garanties.

## Prêts Flash

Les prêts flash sont une forme d’emprunt de cryptomonnaies qui n’implique aucune garantie.

> Un prêt flash permet à l'emprunteur d'obtenir des fonds sans aucune garantie, à condition de rembourser le prêt dans le cadre d'une même opération.

Les prêts flash sont actuellement réservés à ceux qui ont une connaissance approfondie de l’écosystème. Voici un exemple de la façon dont les prêts flash peuvent être utilisés :

1. Souscrivez un prêt flash (en tokenX) depuis un contrat intelligent.
2. Échangez le tokenX emprunté contre le tokenB sur DEX1.
3. Convertissez tokenB en tokenC sur DEX2.
4. Convertissez tokenC en tokenA sur DEX3.
5. Remboursez le prêt flash au contrat intelligent.

Si une étape de la chaîne de transaction échoue, les étapes précédentes sont annulées et la transaction échoue comme si elle n'avait jamais eu lieu.

> N'importe qui peut utiliser les prêts flash pour emprunter autant que nécessaire sans garantie, à condition que le prêt soit restitué dans le cadre de la même transaction.

Les prêts flash permettent des transactions financières simultanées : emprunter des fonds, effectuer plusieurs transactions d'arbitrage sur plusieurs plateformes DeFi et rembourser le prêteur d'origine, le tout en une seule fois.

## 1. Composé

Compound est un service décentralisé populaire pour emprunter et prêter de la cryptomonnaie.

Les prêts [Compound Finance](https://compound.finance/markets) nécessitent généralement des garanties, qui peuvent aller de 0 à 90 % de l'actif emprunté. Chaque actif sur Compound a une exigence de garantie différente.

Lire : [Composé en termes simples](../../token_guides/fr/compound.md)

## 2. Aave

[Aave](https://app.aave.com/home) donne accès à des prêts flash garantis et non garantis.

Les prêts flash proviennent d'un pool de liquidités financé par d'autres utilisateurs. Aave facture des frais de 0,09 % sur les prêts flash. Pour les prêts garantis, des frais de 0,01 % du montant du prêt sont perçus lors de l’octroi du prêt.

Lire : [Aave en termes simples](../../token_guides/fr/aave.md)

## 3. Oasis

[Oasis](https://oasis.app/) est un DEX développé par MakerDAO qui facilite le prêt et l'emprunt du stablecoin DAI.

- Les utilisateurs peuvent emprunter du DAI aux contrats intelligents MakerDAO, qui créent un nouveau DAI en échange d'une garantie en crypto-monnaie (généralement 150 % de la valeur du prêt).
- Lorsque les jetons DAI sont restitués, la garantie est remboursée à l'emprunteur et les jetons DAI restitués sont détruits par le contrat intelligent.

Lire : [MakerDAO en termes simples](../../token_guides/fr/makerdao.md)

## Des risques

Comme pour les autres services DeFi, il existe toujours un risque de piratage ou d'exploitation qui pourrait drainer le pool de liquidités du service de prêt, entraînant la perte de leurs actifs par les prêteurs. Par conséquent, les prêteurs ne devraient engager que les fonds qu’ils peuvent se permettre de perdre.