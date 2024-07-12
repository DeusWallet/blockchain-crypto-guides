# Synthetix explicado de forma simples

[Synthetix](https://synthetix.io/) é uma plataforma descentralizada no Ethereum para negociação de ativos sintéticos, conhecida como Synths.

> Sintetizadores são tokens ERC-20 que representam criptomoedas, ações, moedas fiduciárias, metais preciosos e outros ativos negociáveis.

Esses Synths são projetados para espelhar o preço do ativo que representam, mas sem nenhuma de suas outras características.

Por exemplo, sBTC é um token Bitcoin sintético que pode ser negociado na Synthetix ao preço atual do Bitcoin.

Da mesma forma, um token sMKR tem o mesmo preço que um token real [MKR](../../token_guides/pt/makerdao.md), mas não inclui direitos de voto.

- Possuir tokens de sintetizador oferece a mesma exposição de preço que possuir os tokens reais que eles representam.
- Os utilizadores podem especular sobre os movimentos de preços de vários instrumentos financeiros sem deter o ativo real.
- Os ativos Synth podem ser transferidos entre usuários e negociados em bolsas descentralizadas.

Em resumo, Synthetix permite a criação de tokens ERC-20 baseados em Ethereum que representam ativos do mundo real.

> Qualquer ativo com feed de preço pode ser potencialmente adicionado ao Synthetix como um ativo de sintetizador.

Atualmente, os ativos de sintetizadores disponíveis incluem criptomoedas, ações e metais preciosos. A Synthetix pretende expandir suas ofertas para incluir mais ativos comumente encontrados em mercados tradicionais, como ações.

## Sintetizadores Suportados

A plataforma Synthetix suporta atualmente cerca de duas dúzias de sintetizadores diferentes, com potencial para muitos mais.

> Qualquer ativo com preço de mercado pode ser adicionado ao Synthetix, desde que haja um feed de preço e aprovação da comunidade.

Atualmente, existem dois tipos de ativos de sintetizador:

1. **Sintetizadores padrão**

 Eles rastreiam o preço do ativo que representam, adequado para quem deseja operar comprado nos ativos.
 - sUSD: USD sintético
 - sEUR: EUR sintético
 - sAUD: AUSDollar sintético
 - sBTC: Bitcoin sintético
 - sETH: éter sintético
 - sMKR: fabricante sintético
 -sBNB: BNB sintético
 - sXTZ: Tezos sintético
 - sADA: Cardano sintético
 - sXRP: ondulação sintética
 - sLTC: Litecoin sintético
 - sBCH: Bitcoin Cash sintético
 - sXAU: onça de ouro sintética
 - sXAG: onça de prata sintética
 - sDEFI: Índice DEFI sintético
 - sLINK: Chainlink sintético

2. **Sintetizadores Inversos**

 Isso permite que os usuários vendam a descoberto o preço de um ativo, lucrando inversamente com a depreciação do preço.
 - iBTC: Bitcoin inverso
 - iETH: Ethereum inverso
 - iBNB: Binance inverso
 - iXTZ: Tezos inverso
 - iADA: Cardano inverso
 - iXRP: ondulação inversa
 - iLTC: Litecoin inverso
 - iBCH: Bitcoin Cash inverso
 - iDEFI: índice DEFI inverso
 - iLINK: Chainlink inverso

Os sintetizadores são negociados 24 horas por dia, 7 dias por semana no [Synthetix.Exchange](https://synthetix.exchange) sem custódia, permitindo que qualquer pessoa no [ecossistema Ethereum](../../token_guides/pt/ethereum.md) operar comprado ou vendido em vários ativos.

## Como os sintetizadores são criados

Para entender o Synthetix, é importante saber como novos sintetizadores são criados e retirados de circulação.

1. Synthetix permite que os usuários criem tokens sUSD (USD sintético) [bloqueando](https://mintr.synthetix.io/) seus tokens SNX em um contrato inteligente com uma taxa de garantia de 600%.
2. Para criar 1.000 tokens sUSD, o usuário deve bloquear pelo menos US$ 6.000 em tokens SNX. Esses tokens são devolvidos quando o usuário reembolsa o valor emprestado.
3. Uma vez criados, os tokens sUSD podem ser negociados na bolsa Synthetix por outros ativos sintéticos aos preços atuais de mercado.
4. As ordens na bolsa Synthetix são instantâneas e executadas a preços de mercado.
5. Os traders sempre negociam contra a bolsa, o que destrói o ativo recebido do usuário e cria o ativo comprado pelo usuário.
6. Por exemplo, comprar sBTC quando o Bitcoin custa US$ 10.000 envolve destruir 10.000 sUSD e criar 1 sBTC.

Este processo garante que cada ativo de sintetizador seja respaldado por tokens SNX.

Os especuladores também podem comprar sUSD ou sETH existentes em uma [bolsa descentralizada](../../defi/pt/3-decentralized-exchanges.md) como [Uniswap](../../token_guides/pt/uniswap. md) usando ETH.

## Como os sintetizadores são negociados

O ecossistema Synthetix inclui sua própria bolsa descentralizada, [Synthetix.Exchange](https://synthetix.exchange), para negociação de sintetizadores.

- Ao contrário de outras bolsas descentralizadas, Synthetix.Exchange não requer mecanismos de correspondência de liquidez, como livros de pedidos ou [pools de liquidez](../../defi/pt/3-decentralized-exchanges.md).
- Todas as ordens têm garantia de execução a preços de mercado em segundos.
- As taxas de negociação variam de 0,1% a 1% (normalmente 0,3%) e vão para aqueles que criam tokens sUSD bloqueando seus tokens SNX como garantia.

Negociar no Synthetix.Exchange costuma ser mais barato, especialmente para pedidos grandes, proporcionando um incentivo econômico para usá-lo em vez de outras bolsas descentralizadas como [Uniswap](../../token_guides/pt/uniswap.md) ou [Curve](. ./../token_guides/pt/curve-finance.md).

## Por que criar sintetizadores?

A negociação de sintetizadores é mais barata e oferece exposição a qualquer ativo negociável do mundo, tudo na blockchain Ethereum. Isso cria forte g incentivos para os especuladores negociarem Synths em vez dos activos reais.

O índice de garantia de 600% protege a estabilidade dos ativos de sintetizadores contra flutuações de preços SNX.

Aqueles que bloqueiam seu SNX na plataforma para criar novos sintetizadores recebem dois tipos de recompensas:
1. **SNX Staking Rewards**: Criado por meio da política monetária inflacionária do SNX. Entre março de 2019 e agosto de 2023, a oferta total de SNX aumentará de 100 milhões para 260,3 milhões, com uma taxa de decaimento semanal de 1,25%.
2. **Taxas de câmbio**: As taxas de negociação de sintetizadores no [Synthetix.Exchange](https://synthetix.exchange/#/) vão para um pool de taxas, disponível para os stakers SNX reivindicarem semanalmente.

Os stakers SNX criam uma posição de dívida quando bloqueiam seus tokens. Essa dívida começa como o valor de sUSD cunhado e muda com base nos movimentos de preços de todos os outros ativos sintéticos.

- Se todos os sintetizadores fossem sBTC e o preço do BTC fosse reduzido pela metade, a dívida total cairia pela metade e a dívida de cada staker também cairia pela metade.
- Por outro lado, se apenas 50% do sBTC e do BTC dobrassem de preço, a dívida de cada participante aumentaria em um quarto.

Desta forma, os stakers SNX atuam como uma contraparte conjunta de todas as exchanges de sintetizadores, assumindo o risco da dívida geral do sistema.

## Estatísticas do Synthetix

Para estatísticas atuais da plataforma Synthetix, incluindo a quantidade de fundos bloqueados e o número de sintetizadores em circulação, visite a visão geral do Synthetix em [DeFi Pulse](https://dashboard.synthetix.io).

Em 9 de setembro de 2020:
- Total bloqueado (em dólares americanos): $ 650,2 milhões
- Total bloqueado (em ETH): 1,9 milhões de ETH
- Total bloqueado (em BTC): 63,3 mil BTC
- Total bloqueado (em SNX): 141M SNX
- % do fornecimento SNX bloqueado: 70,36%