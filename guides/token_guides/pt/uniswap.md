# Uniswap explicado de forma simples

[Uniswap](https://uniswap.info/home) é uma bolsa de criptomoedas descentralizada, ponto a ponto, para negociação de tokens Ethereum e baseados em Ethereum.

Uniswap está entre as primeiras [trocas descentralizadas](../../defi/pt/3-decentralized-exchanges.md) no Ethereum e tem vários recursos principais:

- Os contratos inteligentes do Uniswap gerenciam centenas de milhões de dólares em criptomoedas de forma autônoma e descentralizada.
- É considerada uma das bolsas genuinamente descentralizadas, o que significa que as operadoras não podem censurar os utilizadores ou encerrar o serviço.
- Possui o maior volume de negociação entre as bolsas descentralizadas, superando muitas bolsas centralizadas.
- O Uniswap lista vários pares de negociação de criptomoedas e possui uma política de listagem de tokens gratuita, permitindo que qualquer pessoa liste qualquer token e forneça liquidez.
- Utiliza uma fórmula matemática simples e tokens disponíveis em seu pool de liquidez para determinar os preços dos ativos e executar negociações. Mais detalhes podem ser encontrados [aqui](https://uniswap.org/docs/v2/protocol-overview/how-uniswap-works) e [aqui](https://uniswap.org/docs/v2/core- conceitos/trocas/).
- Existem duas versões, Uniswap V1 e a mais recente Uniswap V2. Seguindo os princípios do DeFi, as versões anteriores do Uniswap não podem ser encerradas.
- O Uniswap V3 está sendo desenvolvido para melhorar ainda mais vários elementos da troca.

Hoje, o Uniswap é um dos maiores DEXes, com [mais de US$ 100 milhões](https://migrate.uniswap.info/home) em volume de negociação de 24 horas.

## Negociação no Uniswap

Você pode acessar a interface de negociação do Uniswap por meio de seu front-end público em [uniswap.org](https://app.uniswap.org/#/swap).

- Há uma taxa de serviço de 0,03% para execução de transações.
- Geralmente é mais barato negociar entre a moeda ETH nativa do Ethereum e tokens ERC20 baseados em Ethereum do que entre tokens ERC20.
- O design de contrato inteligente do Uniswap permite taxas de transação Ethereum mais baixas em comparação com outras bolsas descentralizadas.
- Os traders podem sofrer uma derrapagem significativa de preços (desvio do preço de mercado) para encomendas maiores.
- Negociar pares com mais liquidez proporcionará melhores preços para ordens maiores do que aquelas com menos liquidez.
- Grandes pools de liquidez são essenciais para que o Uniswap funcione bem e permita grandes negociações.

Você pode ver todos os pares de negociação no Uniswap e seus respectivos pools de liquidez [aqui](https://uniswap.info/pairs).

## Provedores de Liquidez

O Uniswap foi um dos primeiros projetos a introduzir a criação de mercado automatizada por meio de pools de liquidez.

- Cada par de negociação no Uniswap possui seu próprio pool de liquidez, que qualquer pessoa pode criar ou ingressar.
- Para ingressar em um pool de liquidez, os usuários devem depositar dois tokens envolvidos no par de negociação.
- Os provedores de liquidez devem depositar quantidades iguais de ambos os tokens com base nos preços atuais de mercado.
- Por exemplo, o par de negociação [ETHUSDT](https://uniswap.info/pair/0x0d4a11d5eeaac28ec3f61d100daf4d40471f1852) requer depósitos de tokens ETH e USDT.
- Os fornecedores de liquidez ganham uma parte das taxas de negociação relativas ao valor dos seus activos depositados.
- Os provedores recebem tokens específicos do pool que representam sua parcela de ativos no pool.
- Os fornecedores de liquidez podem retirar os seus activos e ganhos a qualquer momento.

## Lucratividade do pool

Embora os pools de liquidez do Uniswap possam parecer uma forma garantida de obter renda passiva colocando ativos de criptomoeda ociosos para funcionar, existem riscos:

> O valor cumulativo dos ativos depositados pode diminuir apesar do ganho de taxas de negociação.

Para compreender por que razão a participação de um fornecedor de liquidez pode diminuir, apesar do rendimento proveniente de taxas, considere a fórmula que rege a negociação Uniswap. Esta fórmula simples é explicada [aqui](https://medium.com/@pintail/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2) junto com fatores a serem considerados ao avaliar pools de liquidez.

Uma regra geral para fornecedores de liquidez: qualquer alteração de preço nos ativos depositados pode reduzir o valor da participação em comparação com apenas a detenção dos ativos originais.

> Portanto, os pools de liquidez que envolvem ativos estáveis, como stablecoins, provavelmente terão melhor desempenho.

Dado que as alterações nos preços dos activos desempenham um papel crucial no cálculo dos lucros, prever os retornos futuros pode ser complexo.

##Token Uniswap

Em setembro de 2020, a Uniswap [apresentou](https://uniswap.org/blog/uni/) seu token de governança nativo, UNI.

O principal caso de utilização da UNI é participar na tomada de decisões e noutros aspectos de governação, tais como a gestão de fundos no tesouro comunitário.