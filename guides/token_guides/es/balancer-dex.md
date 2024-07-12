# Equilibrador en términos simples

[Balancer](https://balancer.exchange/) es un intercambio descentralizado (DEX) que se lanzó en marzo de 2020. Comenzó como un proyecto de investigación de [BlockScience](https://block.science/) a principios de 2018. El equipo de Balancer desarrolló un marco matemático que permite que cualquier cartera se reequilibre continuamente mientras genera tarifas, conocido como protocolo Balancer. El token Ethereum que impulsa este protocolo es BAL.

## Negociar en Balancer

Desde la perspectiva de un comerciante, Balancer es una plataforma para intercambiar tokens Ethereum y ERC20 de forma descentralizada.

- **Comercio eficiente**: Balancer escanea todos los grupos disponibles en busca de los tokens solicitados y distribuye las órdenes entre los grupos más eficientes para ofrecer los mejores precios.
- **Tarifas variables**: las tarifas de negociación difieren entre los grupos y dependen de los tokens y los grupos de liquidez involucrados.
- **Deslizamiento**: las órdenes más grandes en relación con la liquidez disponible dan como resultado un mayor deslizamiento.
- **Incentivos**: Balancer fomenta tarifas bajas mediante la distribución de tokens BAL a proveedores de liquidez.

## Proporcionar liquidez

Al igual que Uniswap y Curve, Balancer permite a los usuarios ganar tarifas por sus activos inactivos basados ​​en Ethereum. Ofrece oportunidades más flexibles a través de diferentes tipos de fondos de liquidez.

- **Fondos de liquidez**: los usuarios pueden crear un nuevo fondo o agregar activos a los existentes.
- **Composición del pool**: Cada pool puede contener de 2 a 8 activos, manteniendo una proporción específica entre ellos.
- **Autoequilibrio**: Los grupos se autoequilibran para mantener las proporciones requeridas.
- **Depósitos flexibles**: a diferencia de Uniswap, Balancer permite depósitos en cualquier activo respaldado por el grupo.
- **Tokens de propiedad del grupo**: los proveedores reciben tokens ERC-20 que representan su parte del grupo, que pueden usarse para retirar liquidez.
- **Tarifas de transacción**: cada grupo establece sus propias tarifas, y con tarifas más bajas se obtienen más tokens BAL.

## Tipos de piscinas

1. **Piscinas compartidas**:
 - Fichas, pesos y tarifas fijos establecidos en el momento de la creación.
 - No hay privilegios especiales para el creador.
 - Cualquiera puede agregar liquidez y la propiedad se rastrea con Balancer Pool Tokens (BPT).

2. **Piscinas privadas**:
 - Control total sobre los parámetros para el creador (por ejemplo, tokens aceptados, pesos, tarifas).
 - Sólo el creador puede aportar liquidez.
 - Útil para fondos indexados administrados.

3. **Piscinas inteligentes**:
 - Propiedad de un contrato inteligente, no de una persona.
 - Acepte liquidez de cualquier persona con cambios de parámetros flexibles.
 - Propiedad rastreada por tokens ERC-20.

## Fondos indexados

Balancer permite a los usuarios configurar fondos indexados personales sin un reequilibrio complejo.

- **Fondos de autoequilibrio**: los inversores pueden agrupar activos para inversiones a largo plazo en fondos de autoequilibrio, ganando comisiones cuando otros negocian con su cartera.
- **Fondos indexados personalizados**: los usuarios pueden crear o invertir en fondos indexados autoequilibrados.
- **Grupos anidados**: los grupos pueden estar formados por otros grupos de Balancer.
- **Sin permiso**: los grupos no se pueden censurar ni modificar una vez activados.

## Ficha equilibradora

El token BAL, distribuido a proveedores de liquidez desde el 1 de junio de 2020, también sirve como token de gobernanza para el protocolo.

- **Oferta total**: 100 millones de tokens BAL.
- **Distribución**: 25 millones para fundadores, desarrolladores, asesores e inversores; 75 millones a proveedores de liquidez.

Los detalles sobre el modelo de gobernanza y la distribución de tokens se pueden encontrar [aquí](https://balancer.finance/2020/05/15/proposing-balancer-liquidity-mining/).

## Enlaces útiles

- [Documento técnico del proyecto](https://balancer.finance/whitepaper/)
- [Blog oficial](https://balancer.finance/blog-feed/)
- [Gestión del grupo de balanceadores](https://pools.balancer.exchange/#/)