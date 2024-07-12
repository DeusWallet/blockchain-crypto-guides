# Pools de empréstimos

Pools de empréstimos são serviços DeFi que facilitam empréstimos e empréstimos de criptomoedas sem custódia.

## Empréstimo

Os serviços de empréstimo permitem que os usuários tomem emprestadas criptomoedas de um contrato inteligente, fornecendo garantias em outra criptomoeda. Isso permite que os mutuários acessem liquidez sem vender suas criptomoedas. Os mutuários podem reembolsar o empréstimo a qualquer momento para recuperar suas garantias.

## Empréstimo

Os serviços de empréstimo permitem que os detentores de criptomoedas emprestem ativos para um contrato inteligente e ganhem juros. Os credores podem sacar seus depósitos juntamente com os juros acumulados a qualquer momento.

Normalmente, os participantes do mercado tomam emprestado ativos de um contrato inteligente para utilizar esses fundos em atividades que rendem retornos mais elevados do que o custo do empréstimo. Por exemplo, alguém pode pedir emprestada uma criptomoeda de um serviço DeFi e emprestá-la a outro serviço que ofereça retornos mais elevados.

## Empréstimos garantidos

- Os mutuários devem apresentar outra criptomoeda como garantia, muitas vezes significativamente maior do que o valor emprestado.
- São necessárias garantias elevadas para proteger os credores se o valor da garantia cair drasticamente.
- Se o valor da garantia cair abaixo do nível exigido, o contrato inteligente tentará liquidar a garantia para recomprar os ativos emprestados.

Os mutuários são incentivados a reembolsar o empréstimo e a evitar a liquidação das garantias, para evitar a perda de parte das suas garantias.

## Empréstimos instantâneos

Os empréstimos instantâneos são uma forma de empréstimo em criptomoeda que não envolve garantias.

> Um empréstimo rápido permite ao mutuário obter fundos sem qualquer garantia, desde que reembolse o empréstimo na mesma transação.

Os empréstimos rápidos estão atualmente limitados àqueles com conhecimento profundo do ecossistema. A seguir está um exemplo de como os empréstimos instantâneos podem ser utilizados:

1. Faça um empréstimo rápido (em tokenX) de um contrato inteligente.
2. Troque o tokenX emprestado pelo tokenB em DEX1.
3. Converta tokenB em tokenC em DEX2.
4. Converta tokenC em tokenA em DEX3.
5. Reembolsar o empréstimo rápido do contrato inteligente.

Se qualquer etapa da cadeia de transação falhar, as etapas anteriores serão revertidas e a transação falhará como se nunca tivesse acontecido.

> Qualquer pessoa pode usar empréstimos rápidos para emprestar o quanto for necessário sem garantia, desde que o empréstimo seja devolvido na mesma transação.

Os empréstimos instantâneos permitem transações financeiras simultâneas: tomar empréstimos de fundos, realizar diversas negociações de arbitragem em diversas plataformas DeFi e reembolsar o credor original – tudo de uma só vez.

## 1. Composto

Compound é um serviço descentralizado popular para empréstimos e empréstimos de criptomoedas.

Os empréstimos [Compound Finance](https://compound.finance/markets) normalmente exigem garantias, que podem variar de 0 a 90% do ativo emprestado. Cada ativo no Compound tem uma exigência de garantia diferente.

Leia: [Composto em termos simples](../../token_guides/pt/compound.md)

## 2. Aave

[Aave](https://app.aave.com/home) fornece acesso a empréstimos instantâneos com e sem garantia.

Os empréstimos instantâneos são provenientes de um pool de liquidez financiado por outros usuários. Aave cobra uma taxa de 0,09% sobre empréstimos instantâneos. Para empréstimos garantidos, uma taxa de 0,01% do valor do empréstimo é cobrada na originação do empréstimo.

Leia: [Aave em termos simples](../../token_guides/pt/aave.md)

## 3. Oásis

[Oasis](https://oasis.app/) é um DEX desenvolvido pela MakerDAO que facilita o empréstimo e empréstimo do stablecoin DAI.

- Os usuários podem emprestar DAI de contratos inteligentes MakerDAO, que criam um novo DAI em troca de uma garantia em criptomoeda (normalmente 150% do valor do empréstimo).
- Quando os tokens DAI são devolvidos, a garantia é devolvida ao mutuário e os tokens DAI devolvidos são destruídos pelo contrato inteligente.

Leia: [MakerDAO em termos simples](../../token_guides/pt/makerdao.md)

## Riscos

Tal como acontece com outros serviços DeFi, existe sempre o risco de um hack ou exploração que possa esgotar o pool de liquidez do serviço de empréstimo, fazendo com que os credores percam os seus ativos. Portanto, os credores só devem comprometer fundos que possam perder.