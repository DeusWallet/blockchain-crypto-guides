# Balanceador em termos simples

[Balancer](https://balancer.exchange/) é uma bolsa descentralizada (DEX) lançada em março de 2020. Começou como um projeto de pesquisa da [BlockScience](https://block.science/) no início de 2018. A equipe do Balancer desenvolveu uma estrutura matemática que permite que qualquer portfólio se auto-reequilibre continuamente enquanto gera taxas, conhecido como protocolo Balancer. O token Ethereum que conduz este protocolo é BAL.

## Negociação no Balanceador

Do ponto de vista do trader, o Balancer é uma plataforma para troca de tokens Ethereum e ERC20 de forma descentralizada.

- **Negociação Eficiente**: O Balanceador verifica todos os pools disponíveis em busca dos tokens solicitados e distribui os pedidos pelos pools mais eficientes para fornecer os melhores preços.
- **Taxas Variáveis**: As taxas de negociação diferem entre os pools e dependem dos tokens e dos pools de liquidez envolvidos.
- **Slippage**: Pedidos maiores em relação à liquidez disponível resultam em maior slippage.
- **Incentivos**: O Balancer incentiva taxas baixas distribuindo tokens BAL para provedores de liquidez.

## Fornecendo Liquidez

Assim como o Uniswap e o Curve, o Balancer permite que os usuários ganhem taxas sobre seus ativos ociosos baseados em Ethereum. Oferece oportunidades mais flexíveis através de diferentes tipos de pools de liquidez.

- **Pools de liquidez**: os usuários podem criar um novo pool ou adicionar ativos a pools existentes.
- **Composição do Pool**: Cada pool pode conter de 2 a 8 ativos, mantendo uma proporção específica entre eles.
- **Balanceamento automático**: agrupa o autobalanceamento para manter as proporções exigidas.
- **Depósitos flexíveis**: Ao contrário do Uniswap, o Balancer permite depósitos em qualquer ativo suportado pelo pool.
- **Tokens de propriedade do pool**: os provedores recebem tokens ERC-20 representando sua parcela do pool, que podem ser usados ​​para retirar liquidez.
- **Taxas de transação**: Cada pool define suas próprias taxas, com taxas mais baixas gerando mais tokens BAL.

## Tipos de piscina

1. **Grupos Compartilhados**:
 - Tokens, pesos e taxas fixos definidos na criação.
 - Sem privilégios especiais para o criador.
 - Qualquer pessoa pode adicionar liquidez e a propriedade é rastreada com Balancer Pool Tokens (BPT).

2. **Piscinas Privadas**:
 - Controle total sobre os parâmetros do criador (por exemplo, tokens aceitos, pesos, taxas).
 - Somente o criador pode fornecer liquidez.
 - Útil para fundos de índice gerenciados.

3. **Piscinas Inteligentes**:
 - Propriedade de um contrato inteligente, não de uma pessoa.
 - Aceite liquidez de qualquer pessoa com alterações flexíveis de parâmetros.
 - Propriedade rastreada por tokens ERC-20.

## Fundos de índice

O Balancer permite que os usuários configurem fundos de índice pessoal sem reequilíbrio complexo.

- **Pools com balanceamento automático**: Os investidores podem agrupar ativos para investimento de longo prazo em pools com balanceamento automático, ganhando taxas à medida que outros negociam em relação ao seu portfólio.
- **Fundos de índice personalizados**: os usuários podem criar ou investir em fundos de índice com equilíbrio automático.
- **Pools aninhados**: os pools podem consistir em outros pools do Balanceador.
- **Sem permissão**: Pools não podem ser censurados ou alterados depois de ativados.

## Token do balanceador

O token BAL, distribuído aos provedores de liquidez desde 1º de junho de 2020, também serve como token de governança do protocolo.

- **Fornecimento total**: 100 milhões de tokens BAL.
- **Distribuição**: 25 milhões para fundadores, desenvolvedores, consultores e investidores; 75 milhões para provedores de liquidez.

Detalhes sobre o modelo de governança e distribuição de tokens podem ser encontrados [aqui](https://balancer.finance/2020/05/15/proposing-balancer-liquidity-mining/).

## Links Úteis

- [Documento técnico do projeto](https://balancer.finance/whitepaper/)
- [Blog Oficial](https://balancer.finance/blog-feed/)
- [Gerenciamento de pool de balanceadores](https://pools.balancer.exchange/#/)