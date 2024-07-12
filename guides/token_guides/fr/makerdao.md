# MakerDAO et DAI en termes simples

Commençons par une brève introduction à la finance décentralisée, communément appelée DeFi.

[Bitcoin](bitcoin.md) était la blockchain pionnière, permettant la finance décentralisée en permettant à quiconque d'envoyer, de recevoir et de détenir du Bitcoin sans intermédiaires comme les banques. Cependant, la blockchain de Bitcoin se limite à de simples transferts entre adresses.

Ethereum a développé ce concept en permettant des transferts conditionnels, ouvrant la voie à des contrats programmables sur la blockchain. Cette innovation a donné naissance à la Finance Décentralisée (DeFi).

> **La blockchain Ethereum prend en charge une logique complexe dans les transactions, permettant aux développeurs de créer des services publics autonomes qui fonctionnent sans interférence externe. Ces services restent fonctionnels et accessibles tant que la blockchain Ethereum est active.**

DeFi fait généralement référence aux services financiers construits sur la blockchain Ethereum ou sur des plateformes similaires comme EOSIO. La plupart des grands projets DeFi fonctionnent actuellement sur Ethereum.

Pour plus de détails sur Ethereum et les projets DeFi existants, consultez notre [Guide Ethereum](ethereum.md).

## 1. Présentation de MakerDAO

MakerDAO est l'un des premiers projets DeFi sur Ethereum.

Il gère plus d'un demi-milliard de dollars via un ensemble automatisé de règles (Smart Contracts) appelé Maker Protocol.

> **Un Smart Contract est un programme basé sur une blockchain qui fonctionne de manière transparente et est généralement immuable. Tout le monde peut vérifier sa fonctionnalité.**

MakerDAO, lancé en 2014, est régi par un groupe mondial et décentralisé d'entités allant des organisations aux individus.

> **MakerDAO fournit une facilité de prêt sur Ethereum où les utilisateurs peuvent emprunter de la crypto-monnaie pour une somme modique.**

La gouvernance est assurée par le vote des détenteurs de jetons MKR. La valeur des jetons MKR dépend des services publics proposés par MakerDAO.

### 1.1 DAO expliqué

Une Organisation Autonome Décentralisée (DAO) est un projet ou une organisation présentant les caractéristiques suivantes :

- Contrôlé par un groupe distribué d'entités
- Gouverné par la propriété de jetons
- Fonctionne sur une blockchain publique
- Opérations transparentes et vérifiables
- Aucune présence physique officielle

> **Contrairement aux entreprises traditionnelles, les DAO fonctionnent sur la base de règles précodées sur la blockchain, sans possibilité d'interférence.**

### 1.2 DAI en tant que service

Le produit principal de MakerDAO est le stablecoin DAI, qui maintient une valeur proche de 1 USD. Les services de MakerDAO tournent autour du stablecoin DAI.

> **Un stablecoin est une crypto-monnaie liée à une référence externe, généralement l'USD, l'EUR ou l'or.**

Les utilisateurs peuvent verrouiller Ether comme garantie pour générer du DAI. La garantie est restituée lors du remboursement du prêt avec frais.

- Un nouveau DAI entre en circulation lorsqu'un prêt est émis, soutenu par une garantie d'une valeur de 150 % du prêt.
- La garantie est libérée lorsque le prêt et les frais sont remboursés, et le DAI restitué est détruit.

Le protocole Maker garantit que DAI maintient son ancrage à 1 USD via divers mécanismes.

> **DAI est un stablecoin sans confiance, soutenu par des garanties vérifiables. Contrairement aux pièces stables centralisées comme [Tether](tether.md), elle ne nécessite pas de confiance dans une entité centrale.**

### 1.3 Gouvernance MakerDAO

MakerDAO est régi par les détenteurs de jetons MKR par le biais de propositions formelles et de votes. Les modifications apportées au protocole Maker sont mises en œuvre uniquement via ce processus.

Les détenteurs de jetons MKR bénéficient financièrement de la croissance de MakerDAO, car la demande de jetons MKR augmente avec l'utilisation des services MakerDAO.

> **Les détenteurs de MKR partagent les risques financiers associés à la stabilité du DAI. Tout problème de stabilité du DAI a un impact direct sur le prix du jeton MKR, car de nouveaux jetons MKR devront peut-être être créés et vendus pour couvrir les pertes.**

Il existe actuellement plus d'un million de jetons MKR, avec une capitalisation boursière supérieure à un demi-milliard de dollars. Les jetons MKR sont échangés sur des bourses de crypto-monnaie et peuvent être stockés dans des portefeuilles compatibles Ethereum.

### 1.4 Acteurs clés

MakerDAO comprend des entités comme la Maker Foundation, qui a initialement construit le protocole Maker et collabore désormais avec la communauté pour parvenir à une décentralisation complète. La Maker Foundation supervise certains aspects organisationnels, notamment les réunions de gouvernance et de risque.

La Fondation DAI gère les principaux actifs incorporels de MakerDAO, tels que les marques déposées et les droits d'auteur des codes, sur la base de statuts stricts.

## 2. Services MakerDAO

Le produit principal de MakerDAO est le stablecoin DAI, autour duquel sont construits ses services destinés au public. Ces services comprennent :

- Oasis : un échange décentralisé de cryptomonnaies
- Facilités de prêt via le protocole Maker
- Épargne DAI avec intérêts

### 2.1 Échange Oasis

Oasis est une plateforme décentralisée d'échange de jetons basés sur Ethereum, y compris DAI.

La plateforme fonctionne entièrement sur la blockchain Ethereum, accessible via un [site web](https://oasis.app) ou directement via des interactions blockchain. Les utilisateurs ont besoin d'un portefeuille Ethereum pris en charge, comme [Metamask](https://metamask.io), pour déposer ou retirer des fonds.

### 2.2 Emprunter du DAI

MakerDAO permet aux utilisateurs d'emprunter du DAI contre des garanties en Ether et autres Il prend en charge les jetons tels que BAT, wBTC et USDC.

- **Ratio de garantie** : nécessite généralement 150 % du montant du prêt en garantie.
- **Vault Health** : les utilisateurs doivent maintenir le ratio de garantie pour éviter la liquidation.
- **Liquidation** : Si le ratio de garantie tombe en dessous du niveau requis, des garanties sont mises aux enchères pour couvrir la dette et les pénalités.
- **Frais de stabilité** : frais annuels payés pour récupérer la garantie, déterminés par les détenteurs de MKR.

### 2.3 Prêt DAI

Les utilisateurs peuvent déposer du DAI dans le protocole Maker et gagner des intérêts, connus sous le nom de taux d'épargne DAI (DSR). Il n'y a aucune limite ou contrainte sur les dépôts ou les retraits.

Le DSR est financé par les frais de stabilité collectés auprès des emprunteurs et est décidé par les détenteurs de MKR.

## 3. Stabilité du DAI

MakerDAO maintient la stabilité des prix de DAI grâce à des mécanismes contrôlant l'offre et la demande.

### 3.1 Prix DAI

MakerDAO ajuste le taux d'épargne DAI et les frais de stabilité pour influencer le prix du marché du DAI.

- **Pour augmenter le prix du DAI** : augmentez le DSR ou les frais de stabilité pour stimuler la demande ou réduire l'offre.
- **Pour diminuer le prix du DAI** : diminuez le DSR ou les frais de stabilité pour réduire la demande ou augmenter l'offre.

### 3.2 DAI contre MKR

Le protocole Maker garantit que DAI est soutenu par des garanties suffisantes. En cas de baisse significative de la valeur de la garantie, de nouveaux jetons MKR sont émis et vendus pour couvrir les déficits, encourageant ainsi la bonne gouvernance des détenteurs de MKR.

> **Les détenteurs de MKR supportent les risques financiers liés à la stabilité du DAI, avec une dilution potentielle de la valeur du MKR en cas de mauvaise gouvernance.**

### 3.3 Prix du Maker (MKR)

La valeur des jetons MKR est liée à la gouvernance et au succès de MakerDAO. Une gouvernance efficace peut accroître la valeur du MKR, tandis qu’une mauvaise gouvernance peut la diluer.

Une utilisation accrue des services MakerDAO augmente la demande de jetons MKR, réduisant potentiellement l'offre grâce aux rachats de frais.

## Conclusion

MakerDAO est un projet DeFi de premier plan et un pionnier de la gouvernance DAO. Il a démontré la viabilité du modèle DAO, permettant à chacun de participer à la gouvernance. Les premiers investisseurs dans MakerDAO ont enregistré des rendements importants, mais des incertitudes et des risques futurs demeurent.

Dans l’ensemble, MakerDAO représente une expérience réussie en matière de finance et de gouvernance décentralisées, avec son approche innovante des prêts, des pièces stables et une prise de décision pilotée par la communauté.