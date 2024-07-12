# Grupos de préstamos

Los grupos de préstamos son servicios DeFi que facilitan los préstamos y empréstitos de criptomonedas sin custodia.

## Préstamo

Los servicios de préstamo permiten a los usuarios tomar prestadas criptomonedas de un contrato inteligente proporcionando una garantía en otra criptomoneda. Esto permite a los prestatarios acceder a liquidez sin vender sus criptomonedas. Los prestatarios pueden pagar el préstamo en cualquier momento para recuperar su garantía.

## Préstamos

Los servicios de préstamo permiten a los poseedores de criptomonedas prestar activos a un contrato inteligente y ganar intereses. Los prestamistas pueden retirar sus depósitos junto con los intereses acumulados en cualquier momento.

Normalmente, los participantes del mercado toman prestados activos de un contrato inteligente para utilizar estos fondos en actividades que generan rendimientos más altos que el costo del préstamo. Por ejemplo, alguien podría pedir prestada una criptomoneda de un servicio DeFi y prestarla a otro servicio que ofrezca mayores rendimientos.

## Préstamos garantizados

- Los prestatarios deben ofrecer otra criptomoneda como garantía, a menudo una cantidad significativamente mayor que la cantidad prestada.
- Es necesaria una garantía elevada para proteger a los prestamistas si el valor de la garantía cae bruscamente.
- Si el valor de la garantía cae por debajo del nivel requerido, el contrato inteligente intentará liquidar la garantía para recomprar los activos prestados.

Se incentiva a los prestatarios a reembolsar el préstamo y evitar la liquidación de la garantía para evitar perder parte de su garantía.

## Préstamos rápidos

Los préstamos flash son una forma de préstamo de criptomonedas que no implica garantía.

> Un préstamo flash permite al prestatario obtener fondos sin garantía alguna, siempre que pague el préstamo en la misma transacción.

Actualmente, los préstamos flash están limitados a aquellos con un conocimiento profundo del ecosistema. El siguiente es un ejemplo de cómo se pueden utilizar los préstamos rápidos:

1. Obtenga un préstamo rápido (en tokenX) de un contrato inteligente.
2. Cambie el tokenX prestado por el tokenB en DEX1.
3. Convierta tokenB a tokenC en DEX2.
4. Convierta tokenC en tokenA en DEX3.
5. Pague el préstamo flash al contrato inteligente.

Si falla algún paso en la cadena de transacciones, los pasos anteriores se revierten y la transacción falla como si nunca hubiera sucedido.

> Cualquiera puede utilizar préstamos flash para pedir prestado todo lo que necesite sin garantía, siempre que el préstamo se devuelva en la misma transacción.

Los préstamos flash permiten transacciones financieras simultáneas: pedir prestados fondos, realizar varias operaciones de arbitraje en múltiples plataformas DeFi y pagar al prestamista original, todo de una sola vez.

## 1. Compuesto

Compound es un popular servicio descentralizado para pedir prestado y prestar criptomonedas.

Los préstamos de [Financiamiento compuesto](https://compound.finance/markets) generalmente requieren garantía, que puede oscilar entre el 0% y el 90% del activo prestado. Cada activo en Compound tiene un requisito de garantía diferente.

Leer: [Compuesto en términos simples](../../token_guides/es/compound.md)

## 2. Aave

[Aave](https://app.aave.com/home) brinda acceso a préstamos flash con y sin garantía.

Los préstamos flash provienen de un fondo de liquidez financiado por otros usuarios. Aave cobra una tarifa del 0,09% por los préstamos rápidos. Para préstamos con garantía, se cobra una tarifa del 0,01% del monto del préstamo en el momento de su originación.

Leer: [Aave en términos simples](../../token_guides/es/aave.md)

## 3. Oasis

[Oasis](https://oasis.app/) es un DEX desarrollado por MakerDAO que facilita el préstamo y el préstamo de la moneda estable DAI.

- Los usuarios pueden pedir prestado DAI de los contratos inteligentes de MakerDAO, que crean nuevos DAI a cambio de una garantía en criptomonedas (normalmente el 150 % del valor del préstamo).
- Cuando se devuelven los tokens DAI, la garantía se devuelve al prestatario y el contrato inteligente destruye los tokens DAI devueltos.

Leer: [MakerDAO en términos simples](../../token_guides/es/makerdao.md)

## Riesgos

Al igual que con otros servicios DeFi, siempre existe el riesgo de que se produzca un pirateo o un exploit que pueda agotar el fondo de liquidez del servicio de préstamos y provocar que los prestamistas pierdan sus activos. Por lo tanto, los prestamistas sólo deben comprometer fondos que puedan permitirse perder.