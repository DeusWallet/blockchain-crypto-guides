# Aave en términos simples

[Aave](https://app.aave.com/) es un servicio descentralizado y sin custodia en la cadena de bloques Ethereum que permite a los usuarios prestar y pedir prestado activos de criptomonedas basados ​​en Ethereum. Lanzado en enero de 2020, Aave ha crecido rápidamente, atrayendo casi 2 mil millones de dólares en criptomonedas en solo ocho meses.

## Cómo funciona Aave

- **Depositantes**: los usuarios proporcionan liquidez depositando sus criptomonedas en grupos de préstamos descentralizados, ganando intereses a cambio.
- **Prestatarios**: los usuarios pueden pedir prestado de estos grupos de préstamos pagando una tarifa.
- **Función única**: a diferencia de otros servicios como [Compound](../../token_guides/es/compound.md) o [MakerDAO](../../token_guides/es/makerdao.md), Aave permite pedir prestado sin garantía.
- **Tasas de interés**: Generalmente más altas que las de otras plataformas.
- **Seguridad**: los contratos inteligentes de Aave no tienen custodia y están descentralizados, lo que significa que el equipo de Aave no puede acceder a los fondos de los usuarios.

## Activos admitidos

A partir de septiembre de 2020, Aave admite préstamos y tomas en préstamo de 20 tokens de criptomonedas diferentes basados ​​en Ethereum:

- [Moneda USD (USDC)](https://app.aave.com/reserve-overview/USDC?pool=Aave)
- [Tether (USDT)](https://app.aave.com/reserve-overview/USDT?pool=Aave)
- [USD verdadero (TUSD)](https://app.aave.com/reserve-overview/TUSD?pool=Aave)
- [Dai (DAI)](https://app.aave.com/reserve-overview/DAI?pool=Aave)
- [sUSD](https://app.aave.com/reserve-overview/SUSD?pool=Aave)
- [Binance (BUSD)](https://app.aave.com/reserve-overview/BUSD?pool=Aave)
- [Ethereum (ETH)](https://app.aave.com/reserve-overview/ETH?pool=Aave)
- [ETHLend (PRESTAR)](https://app.aave.com/reserve-overview/LEND?pool=Aave)
- [YFI](https://app.aave.com/reserve-overview/YFI?pool=Aave)
- [Token de atención básica (BAT)](https://app.aave.com/reserve-overview/BAT?pool=Aave)
- [EnjinCoin (ENJ)](https://app.aave.com/reserve-overview/ENJ?pool=Aave)
- [REN](https://app.aave.com/reserve-overview/REN?pool=Aave)
- [Red Kyber (KNC)](https://app.aave.com/reserve-overview/KNC?pool=Aave)
- [ChainLink (ENLACE)](https://app.aave.com/reserve-overview/LINK?pool=Aave)
- [Decentraland (MANA)](https://app.aave.com/reserve-overview/MANA?pool=Aave)
- [Creador (MKR)](https://app.aave.com/reserve-overview/MKR?pool=Aave)
- [Augur (REP)](https://app.aave.com/reserve-overview/REP?pool=Aave)
- [Synthetix (SNX)](https://app.aave.com/reserve-overview/SNX?pool=Aave)
- [Moneda WBTC (wBTC)](https://app.aave.com/reserve-overview/WBTC?pool=Aave)
- [0x (ZRX)](https://app.aave.com/reserve-overview/ZRX?pool=Aave)

Cada activo tiene requisitos específicos de endeudamiento y préstamo. El control sobre las criptomonedas admitidas eventualmente se transferirá a los poseedores de tokens Aave.

## Préstamos en Aave

- **Generación de intereses**: los prestamistas ganan intereses sobre los activos depositados.
- **Seguridad**: Los depósitos están garantizados por la garantía proporcionada por los prestatarios.
- **aTokens**: los prestamistas reciben aTokens, que generan intereses y pueden usarse para retirar depósitos junto con las ganancias. Los aTokens están vinculados 1:1 al activo subyacente.

## Préstamo en Aave

- **Requisitos de garantía**: el préstamo requiere una garantía en forma de otra criptomoneda.
- **Relación préstamo-valor (LTV)**: representa el poder de endeudamiento máximo (por ejemplo, 75% LTV significa pedir prestado hasta el 75% del valor de la garantía).
- **Tasas de interés**: los prestatarios pueden elegir entre tasas fijas o variables.
- **Mantenimiento de la garantía**: los prestatarios deben asegurarse de que el valor de la garantía se mantenga por encima del mínimo requerido para evitar la liquidación.

## Préstamos rápidos

Los préstamos flash son exclusivos de Aave y permiten a los usuarios pedir prestado sin garantía:

- **Mecanismo**: pedir prestados activos dentro de una transacción y devolverlos antes de que finalice la transacción.
- **Tarifa**: Se cobra una tarifa del 0,09% sobre los préstamos flash.

Los programadores utilizan principalmente los préstamos flash para actividades como arbitraje y refinanciación.

## Gobernanza de Aave

Aave aspira a convertirse en una organización autónoma descentralizada (DAO) totalmente gobernada por la comunidad:

- **Token AAVE**: Se utiliza para votar sobre mejoras de protocolo y decisiones de gobernanza.
- **Incentivos**: los poseedores de tokens AAVE reciben recompensas y pueden participar en la gobernanza.
- **Fondo de Emergencia**: Protege los activos de los prestamistas en caso de eventos inesperados.
- **Token deflacionario**: una parte de las tarifas se utiliza para recomprar y quemar tokens AAVE.

## Presentamos Aave 2.0

Aave 2.0, anunciado el 14 de agosto de 2020, presenta varias características nuevas:

- **Pago con Garantía**: Simplifica las transacciones de pago de préstamos.
- **Tasas fijas**: proporciona previsibilidad en las tasas de interés y de endeudamiento.
- **Menores costos de transacción**: Reduce los costos de las interacciones de la plataforma.
- **Funciones comerciales**: permite a los usuarios negociar posiciones de deuda y activos depositados en criptomonedas admitidas.

## Riesgos

Como ocurre con cualquier servicio DeFi, existen riesgos asociados con errores de contratos inteligentes. Aave ha auditado sus contratos y ofrece un programa de recompensas por errores para que los miembros de la comunidad informen vulnerabilidades.

## Enlaces útiles

- [Portal oficial de Aave] (https://app.aave.com/)
- [Blog oficial de Aave](https://medium.com/aave)
- [Documentos Portal de información](https://docs.aave.com/portal/)
- [Portal de Gobernanza](https://governance.aave.com)