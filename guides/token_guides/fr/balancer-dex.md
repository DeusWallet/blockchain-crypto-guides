# Balancer en termes simples

[Balancer](https://balancer.exchange/) est un échange décentralisé (DEX) lancé en mars 2020. Il a commencé comme un projet de recherche par [BlockScience](https://block.science/) début 2018. L'équipe Balancer a développé un cadre mathématique qui permet à tout portefeuille de s'auto-rééquilibrer en continu tout en générant des frais, connu sous le nom de protocole Balancer. Le jeton Ethereum qui pilote ce protocole est BAL.

## Trading sur Balancer

Du point de vue d'un commerçant, Balancer est une plateforme permettant d'échanger des jetons Ethereum et ERC20 de manière décentralisée.

- **Trading efficace** : Balancer analyse tous les pools disponibles à la recherche des jetons demandés et répartit les ordres sur les pools les plus efficaces pour fournir les meilleurs prix.
- **Frais variables** : les frais de négociation diffèrent selon les pools et dépendent des jetons et des pools de liquidité impliqués.
- ** Slippage ** : des commandes plus importantes par rapport à la liquidité disponible entraînent un slippage plus élevé.
- **Incentives** : Balancer encourage des frais bas en distribuant des jetons BAL aux fournisseurs de liquidité.

## Fournir des liquidités

Comme Uniswap et Curve, Balancer permet aux utilisateurs de percevoir des frais sur leurs actifs inactifs basés sur Ethereum. Il offre des opportunités plus flexibles grâce à différents types de pools de liquidités.

- ** Pools de liquidités ** : les utilisateurs peuvent créer un nouveau pool ou ajouter des actifs aux pools existants.
- **Composition du pool** : chaque pool peut contenir 2 à 8 actifs, en maintenant un ratio spécifique entre eux.
- **Auto-Balancing** : les pools s'auto-équilibrent pour maintenir les ratios requis.
- **Dépôts flexibles** : contrairement à Uniswap, Balancer autorise les dépôts dans n'importe quel actif pris en charge par le pool.
- **Jetons de propriété du pool** : les fournisseurs reçoivent des jetons ERC-20 représentant leur part du pool, qui peuvent être utilisés pour retirer des liquidités.
- **Frais de transaction** : chaque pool fixe ses propres frais, des frais inférieurs permettant de gagner plus de jetons BAL.

## Types de piscines

1. **Piscines partagées** :
 - Correction des jetons, des poids et des frais définis lors de la création.
 - Aucun privilège particulier pour le créateur.
 - N'importe qui peut ajouter des liquidités et la propriété est suivie avec les Balancer Pool Tokens (BPT).

2. **Piscines privées** :
 - Contrôle total sur les paramètres pour le créateur (par exemple, jetons acceptés, poids, frais).
 - Seul le créateur peut apporter des liquidités.
 - Utile pour les fonds indiciels gérés.

3. **Piscines intelligentes** :
 - Propriété d'un contrat intelligent, pas d'une personne.
 - Acceptez la liquidité de toute personne avec des changements de paramètres flexibles.
 - Propriété suivie par les jetons ERC-20.

## Fonds indiciels

Balancer permet aux utilisateurs de créer des fonds indiciels personnels sans rééquilibrage complexe.

- ** Pools à équilibrage automatique ** : les investisseurs peuvent regrouper des actifs pour un investissement à long terme dans des pools à équilibrage automatique, gagnant des frais lorsque d'autres négocient par rapport à leur portefeuille.
- **Fonds indiciels personnalisés** : les utilisateurs peuvent créer ou investir dans des fonds indiciels auto-équilibrés.
- **Pools imbriqués** : les pools peuvent être constitués d'autres pools d'équilibrage.
- **Sans autorisation** : les pools ne peuvent pas être censurés ou modifiés une fois activés.

## Jeton d'équilibrage

Le token BAL, distribué aux fournisseurs de liquidité depuis le 1er juin 2020, sert également de token de gouvernance pour le protocole.

- **Approvisionnement total** : 100 millions de jetons BAL.
- **Distribution** : 25 millions aux fondateurs, développeurs, conseillers et investisseurs ; 75 millions aux fournisseurs de liquidités.

Des détails sur le modèle de gouvernance et la distribution des jetons peuvent être trouvés [ici](https://balancer.finance/2020/05/15/proposing-balancer-liquidity-mining/).

## Liens utiles

- [Livre blanc du projet](https://balancer.finance/whitepaper/)
- [Blog officiel](https://balancer.finance/blog-feed/)
- [Gestion du pool d'équilibreurs](https://pools.balancer.exchange/#/)