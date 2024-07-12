# Synthetix explicado de forma sencilla

[Synthetix](https://synthetix.io/) es una plataforma descentralizada en Ethereum para el comercio de activos sintéticos, conocida como Synths.

> Los sintetizadores son tokens ERC-20 que representan criptomonedas, acciones, monedas fiduciarias, metales preciosos y otros activos negociables.

Estos sintetizadores están diseñados para reflejar el precio del activo que representan, pero sin ninguna de sus otras características.

Por ejemplo, sBTC es un token de Bitcoin sintético que se puede negociar en Synthetix al precio actual de Bitcoin.

De manera similar, un token sMKR tiene el mismo precio que un token [MKR](../../token_guides/es/makerdao.md) real, pero no incluye derechos de voto.

- Poseer tokens de sintetizador ofrece la misma exposición al precio que poseer los tokens reales que representan.
- Los usuarios pueden especular sobre los movimientos de precios de varios instrumentos financieros sin tener el activo real.
- Los activos de sintetizador se pueden transferir entre usuarios y comercializar en intercambios descentralizados.

En resumen, Synthetix permite la creación de tokens ERC-20 basados ​​en Ethereum que representan activos del mundo real.

> Cualquier activo con un feed de precios se puede agregar potencialmente a Synthetix como un activo de sintetizador.

Actualmente, los activos de sintetizador disponibles incluyen criptomonedas, acciones y metales preciosos. Synthetix pretende ampliar su oferta para incluir más activos que se encuentran habitualmente en los mercados tradicionales, como las acciones.

## Sintetizadores compatibles

La plataforma Synthetix actualmente admite alrededor de dos docenas de sintetizadores diferentes, con potencial para muchos más.

> Cualquier activo con un precio de mercado se puede agregar a Synthetix, siempre que exista un feed de precios y la aprobación de la comunidad.

Actualmente, existen dos tipos de recursos de sintetizador:

1. **Sintetizadores estándar**

 Estos rastrean el precio del activo que representan, adecuados para aquellos que buscan invertir en largo en los activos.
 - sUSD: USD sintético
 - sEUR: EUR sintético
 - saud: dólar australiano sintético
 - sBTC: Bitcoin sintético
 - sETH: éter sintético
 - sMKR: fabricante sintético
 - sBNB: BNB sintético
 - sXTZ: Tezos sintéticos
 - sADA: Cardano sintético
 - sXRP: ondulación sintética
 - sLTC: Litecoin sintético
 - sBCH: Bitcoin Cash sintético
 - sXAU: Onza de oro sintética
 - sXAG: onza de plata sintética
 - sDEFI: índice DEFI sintético
 - sLINK: eslabón de cadena sintético

2. **Sintetizadores inversos**

 Estos permiten a los usuarios vender en corto el precio de un activo, beneficiándose inversamente de la depreciación del precio.
 - iBTC: Bitcoin inverso
 - iETH: Ethereum inverso
 - iBNB: Binance inverso
 - iXTZ: Tezos inversos
 - iADA: Cardano inverso
 - iXRP: ondulación inversa
 - iLTC: Litecoin inverso
 - iBCH: Bitcoin Cash inverso
 - iDEFI: índice DEFI inverso
 - iLINK: eslabón de cadena inverso

Los sintetizadores se comercializan las 24 horas del día, los 7 días de la semana en [Synthetix.Exchange](https://synthetix.exchange) sin custodia, lo que permite a cualquier persona en el [ecosistema Ethereum](../../token_guides/es/ethereum.md) tomar posiciones largas o cortas en varios activos.

## Cómo se crean los sintetizadores

Para comprender Synthetix, es importante saber cómo se crean y retiran de circulación los nuevos sintetizadores.

1. Synthetix permite a los usuarios crear tokens sUSD (USD sintéticos) [bloqueando](https://mintr.synthetix.io/) sus tokens SNX en un contrato inteligente con un índice de garantía del 600%.
2. Para crear tokens de 1000 sUSD, un usuario debe bloquear al menos $6000 en tokens SNX. Estos tokens se devuelven cuando el usuario paga el monto prestado.
3. Una vez creados, los tokens sUSD se pueden intercambiar en el intercambio Synthetix por otros activos de sintetizador a los precios actuales del mercado.
4. Las órdenes en el intercambio Synthetix son instantáneas y se ejecutan a precios de mercado.
5. Los comerciantes siempre operan contra el intercambio, que destruye el activo recibido del usuario y crea el activo comprado por el usuario.
6. Por ejemplo, comprar sBTC cuando Bitcoin vale $10,000 implica destruir 10,000 sUSD y crear 1 sBTC.

Este proceso garantiza que cada activo de sintetizador esté respaldado por tokens SNX.

Los especuladores también pueden comprar sUSD o sETH existentes en un [intercambio descentralizado](../../defi/es/3-decentralized-exchanges.md) como [Uniswap](../../token_guides/es/uniswap. md) usando ETH.

## Cómo se comercializan los sintetizadores

El ecosistema Synthetix incluye su propio intercambio descentralizado, [Synthetix.Exchange](https://synthetix.exchange), para intercambiar sintetizadores.

- A diferencia de otros intercambios descentralizados, Synthetix.Exchange no requiere mecanismos de igualación de liquidez como libros de pedidos o [grupos de liquidez] (../../defi/es/3-decentralized-exchanges.md).
- Se garantiza que todas las órdenes se ejecutarán a precios de mercado en segundos.
- Las tarifas comerciales oscilan entre el 0,1 % y el 1 % (normalmente, el 0,3 %) y van a quienes crean tokens sUSD bloqueando sus tokens SNX como garantía.

Operar en Synthetix.Exchange suele ser más barato, especialmente para pedidos grandes, lo que proporciona un incentivo económico para usarlo en comparación con otros intercambios descentralizados como [Uniswap](../../token_guides/es/uniswap.md) o [Curve](. ./../token_guides/es/curve-finance.md).

## ¿Por qué crear sintetizadores?

Operar con sintetizadores es más barato y brinda exposición a cualquier activo negociable en el mundo, todo en la cadena de bloques Ethereum. Esto crea fuerte 	g incentivos para que los especuladores intercambien sintetizadores en lugar de los activos reales.

El índice de garantía del 600% protege la estabilidad de los activos de sintetizador contra las fluctuaciones de precios de SNX.

Aquellos que bloquean su SNX en la plataforma para crear nuevos sintetizadores reciben dos tipos de recompensas:
1. **Recompensas por participación de SNX**: creadas a través de la política monetaria inflacionaria de SNX. Entre marzo de 2019 y agosto de 2023, el suministro total de SNX aumentará de 100 millones a 260,3 millones, con una tasa de caída semanal del 1,25%.
2. **Tarifas de intercambio**: Las tarifas por operar con sintetizadores en [Synthetix.Exchange](https://synthetix.exchange/#/) van a un grupo de tarifas, disponible para que los participantes de SNX las reclamen semanalmente.

Los participantes de SNX crean una posición de deuda cuando bloquean sus tokens. Esta deuda comienza con la cantidad de sUSD acuñados y cambia según los movimientos de precios de todos los demás activos de sintetizador.

- Si todos los sintetizadores tuvieran sBTC y BTC reducidos a la mitad, la deuda total se reduciría a la mitad y la deuda de cada participante también se reduciría a la mitad.
- Por el contrario, si solo el 50% de sBTC y BTC duplicaran su precio, la deuda de cada participante aumentaría en una cuarta parte.

De esta manera, los participantes de SNX actúan como una contraparte conjunta para todos los intercambios de sintetizadores, asumiendo el riesgo de la deuda general del sistema.

## Estadísticas de Synthetix

Para obtener estadísticas actuales sobre la plataforma Synthetix, incluida la cantidad de fondos bloqueados y la cantidad de sintetizadores en circulación, visite la descripción general de Synthetix en [DeFi Pulse](https://dashboard.synthetix.io).

Al 9 de septiembre de 2020:
- Total bloqueado (en USD): 650,2 millones de dólares
- Total bloqueado (en ETH): 1,9 millones de ETH
- Total bloqueado (en BTC): 63,3K BTC
- Total bloqueado (en SNX): 141 millones de SNX
- % de suministro de SNX bloqueado: 70,36%