## 5. Bancor DEX

[Bancor](https://www.bancor.network/) é uma bolsa descentralizada semelhante ao Uniswap, fornecendo uma plataforma para negociação de tokens baseados em Ethereum. Bancor apresenta um token nativo chamado Bancor Network Token (BNT). Embora os comerciantes não precisem deter BNT, os fornecedores de liquidez devem deter BNT para criar ou contribuir para um pool de liquidez.

### Incentivos para Provedores de Liquidez

- **Pools de liquidez de token único**: O Bancor V2 permite que os provedores de liquidez entrem em um pool com apenas um token, eliminando a necessidade de um depósito de liquidez bilateral.
- **Acumulação de taxas**: os tokens do pool de liquidez no Bancor acumulam valor através da cobrança de taxas de negociação, semelhante a outros DEXes.
- **Recompensas Adicionais**: Além das taxas de negociação, as recompensas do pool podem vir do Protocolo Bancor por meio da inflação de tokens BNT e de projetos de tokens por meio de programas de incentivo de provedores de liquidez.
- **Token Intermediário**: Cada pool de liquidez no Bancor mantém BNT em suas reservas junto com o token base que recebe liquidez. O BNT atua como intermediário, conectando pools dentro da rede e entre blockchains. Por exemplo, uma negociação de DAI para BAT segue o caminho: DAI > BNT > BAT.

Para mais detalhes sobre a mecânica do Bancor, consulte a [documentação oficial](https://support.bancor.network/hc/en-us/sections/360000256751-Bancor-Network).

### Incidente de segurança

Em julho de 2018, o Bancor sofreu um hack que resultou na perda de US$ 23,5 milhões em ativos criptográficos (ETH, NPXS e BNT). A violação ocorreu devido a uma carteira comprometida usada para atualizar contratos inteligentes. Em resposta, o Bancor encerrou temporariamente a bolsa e congelou o BNT, embora não tenha conseguido congelar o ETH e o NPXS perdidos. Este incidente destacou preocupações sobre a verdadeira descentralização da bolsa. Charlie Lee, criador do Litecoin, criticou o Bancor, afirmando que "Uma bolsa não é descentralizada se puder perder fundos de clientes OU se puder congelar fundos. O Bancor pode fazer as duas coisas."